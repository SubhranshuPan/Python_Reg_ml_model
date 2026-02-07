# 🏎️ Vehicle Price Predictor: Machine Learning Under the Hood

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://vehicleprice.streamlit.app/)
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Machine Learning](https://img.shields.io/badge/Model-Linear%20Regression-green)
![Status](https://img.shields.io/badge/Status-Deployed-success)

> **"Price is what you pay. Value is what you get."** > An interactive Machine Learning project built for car enthusiasts to estimate the fair market value of vehicles based on real specifications.

---

## 🔧 About The Project

For those of us who speak the language of **Boost**, **Drivetrains**, and **Transmissions**, buying a car isn't just a transaction—it's about the specs. 

This project utilizes a **Simple Linear Regression** machine learning model to analyze vehicle prices based on their mechanical configurations. Whether you are looking at a daily driver or a weekend track weapon, this tool helps crunch the numbers to predict the price tag based on the hardware under the chassis.

---

## 🎯 Key Features (Specs)

The model doesn't just look at the make and model; it dives into the specific mechanical attributes that drive value:

* **💨 Aspiration:** * Naturally Aspirated (NA)
    * Turbocharged
    * Supercharged
    * Twin-Turbo
* **⚙️ Drivetrain:** * FWD (Efficiency)
    * RWD (Drift/Sport)
    * AWD / 4WD (Grip/Offroad)
* **🕹️ Transmission:** * Manual (For the purists)
    * Automatic (Cruising)

---

## 🛠️ How It Was Built (The Workflow)

This project follows a complete end-to-end Data Science pipeline, detailed in the included Jupyter Notebook (`Linear Regression ML.ipynb`).

### 1. 🧠 Problem Formulation
Defining the goal: Predict continuous values (Price) based on categorical and numerical vehicle features using Supervised Learning.

### 2. 📂 Raw Data Collection
Sourcing automotive datasets containing varied car specifications and market prices.

### 3. 🧹 Data Preprocessing
* **Cleaning:** Handling missing values and removing outliers.
* **Visualizing:** using plots to understand price distribution.
* **Analyzing:** Correlation matrices to see which parts (like Turbo vs NA) affect price the most.

### 4. ✂️ Splitting the Data
Dividing the dataset into **Training** sets (to teach the model) and **Testing** sets (to verify its accuracy).

### 5. 📉 Running Regression
Implementing the `LinearRegression` algorithm from Scikit-Learn to fit the data points.

### 6. 📊 Evaluation Metrics
Testing the model's performance using metrics like **R-squared** scores to ensure predictions are realistic.

### 7. 💾 Model Storage
Saving the trained model using serialization (Pickle/Joblib) so it can be reused without retraining.

### 8. 🚀 Streamlit App Development
Building the frontend interface (`Regr_model_cars.py`) to allow users to input specs and get instant price predictions.

---

## 🚀 Live Demo

Don't want to run the code? Test drive the model immediately on the deployed Streamlit app:

👉 **[Launch Vehicle Price Predictor](https://vehicleprice.streamlit.app/)**

---

## 💻 Local Installation

Want to tune the model yourself or run it offline? Follow these steps:

### 1. Clone the Repo
```bash
git clone [https://github.com/SubhranshuPan/Python_Reg_ml_model.git](https://github.com/SubhranshuPan/Python_Reg_ml_model.git)
cd Python_Reg_ml_model
```
### 2. Install Dependencies
Make sure you have the required Python libraries installed.
```bash
pip install -r requirements.txt
```
### 3. Run the App
Fire up the engine!
```bash
streamlit run Regr_model_cars.py
```

## 📂 Project Structure
* ```Linear Regression ML.ipynb```: The research lab. Contains all the EDA, data cleaning, and model training code.
* ```Regr_model_cars.py```: The engine. The main Python script that runs the Streamlit application.
* ```requirements.txt```: The parts list. All the libraries needed to run the project.

## 🤝 Contributing
* Got an idea to make the model more accurate? Maybe adding Horsepower or Torque figures?
* Fork the Project
* Create your Feature Branch (```git checkout -b feature/AmazingFeature```)
* Commit your Changes (```git commit -m 'Add some AmazingFeature' ```)
* Push to the Branch (```git push origin feature/AmazingFeature```)
* Open a Pull Request

---

Built with ❤️ for Cars & Code.

