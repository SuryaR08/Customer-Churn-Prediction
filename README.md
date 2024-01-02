# Customer Churn Prediction Project 🚀

Welcome to the Customer Churn Prediction project repository! This project is a journey through the realms of data exploration, insightful model building, and the thrill of deploying a machine learning model. Let's delve into the fascinating world of data science!

## Project Overview 🌐

The primary objective of this project is to predict customer churn, empowering businesses to identify and retain customers at risk of leaving. The journey comprises an enchanting Exploratory Data Analysis (EDA), an ingenious model-building phase, and the magic of deployment using Flask and HTML.

## Project Structure 🏗️

### 1. EDA Phase 📊

- **Notebook:** [Cust_Churn_EDA.ipynb](Cust_Churn_EDA.ipynb)

  - **Tasks:**
    - Removed redundant columns 🧹
    - Handled missing values 🕵️‍♂️
    - Conducted univariate and bivariate analyses 📈
    - Utilized Seaborn and Matplotlib for various plots (bar chart, heatmap, barh, pointplot, countplot) 🎨

- **Original Dataset:** [WA_Fn-UseC_-Telco-Customer-Churn.csv](WA_Fn-UseC_-Telco-Customer-Churn.csv)
- **Refined Dataset:** [tel_churn.csv](tel_churn.csv)

### 2. Model Building Phase 🤖

- **Notebook:** [Model_Building.ipynb](Model_Building.ipynb)

  - **Highlights:**
    - Trained a machine learning model to predict customer churn 🤯
    - Used the refined dataset for training 🛠️
    - Employed Scikit-Learn for model selection 🧠

### 3. Flask API Deployment 🚀

- **Deployment Script:** [app.py](app.py)

  - **Methods:**
    - `loadPage`: Loads the home.html page 🏡
    - `predict`: Handles POST requests for prediction ⚡

## Running the Application 🏃‍♂️

1. Ensure you have Flask installed. If not, install it using `pip install Flask`.
2. Run the application script using `python app.py` in the Anaconda Prompt.
3. Open your browser and visit [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

## Insights and Efficiency 💡

- **Exploratory Data Analysis:**
  - Unleashed the beauty of EDA with interactive plots and insightful analysis 🎨📊
  - Skillfully handled missing data and dropped redundant features 🧰

- **Machine Learning Model:**
  - Crafted an awe-inspiring customer churn prediction model 🤖
  - Demonstrated prowess in using Scikit-Learn for model selection 🛠️

- **Flask Deployment:**
  - Embarked on an exciting journey of deploying machine learning models using Flask and HTML 🌐

## Conclusion 🌟

This project offers a delightful blend of creativity, analytics, and deployment skills. Dive into the notebooks, explore the datasets, and feel the thrill of deploying a real-world machine learning model. For any questions or suggestions, feel free to reach out. Happy coding! 🚀👩‍💻
