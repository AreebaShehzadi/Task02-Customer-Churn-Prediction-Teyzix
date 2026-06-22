# Customer Churn Prediction System
**TEYZIX CORE Internship - ML Task 2**

---

## Short Description of the Task
This project is a Machine Learning solution designed to predict whether a customer is likely to stop using a company's service based on their historical behavior and engagement patterns. The project successfully fulfills all the requirements for Task ML-2, which include:

* **Dataset Generation:** Generation of a synthetic and realistic dataset with 1,500 records containing demographics, spending patterns, and a churn status target variable.
* **Data Pipeline:** Comprehensive Data Preparation, Exploratory Data Analysis (EDA), and Feature Engineering.
* **Advanced Modeling:** Training and evaluating advanced classification models (Random Forest and XGBoost) utilizing hyperparameter tuning.
* **Web Deployment:** Deployment of an interactive live Prediction Interface using Gradio for real-time churn risk assessment.

---

## Instructions to Run the Project

### Method A: Running via Google Colab (Recommended)
1. Upload the provided Jupyter Notebook (`.ipynb`) file to your Google Colab environment.
2. Ensure all saved model files (`.pkl`) and the dataset (`.csv`) are uploaded to the Colab session storage.
3. Click on **"Runtime"** > **"Run all"** from the top menu.
4. The notebook will automatically install any missing libraries (like Gradio and Faker), run the ML pipeline, and output the evaluation metrics.
5. Scroll to the last cell of the notebook. A Gradio public URL (e.g., `https://...gradio.live`) will be generated. Click the link to open and test the interactive web interface.

### Method B: Running Locally (Jupyter Notebook / VS Code)
1. Ensure **Python 3.x** is installed on your local system.
2. Open your terminal or command prompt and install the required dependencies by running:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn faker xgboost gradio joblib