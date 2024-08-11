# Project Overview

This repository contains two distinct projects developed during the **Virtual Internship in AI and Cloud** offered by **Edunet Foundation** in collaboration with **IBM SkillsBuild** and **AICTE**. The projects are as follows:

1. **Machine Learning Project on Loan Dataset**
2. **Chatbot Development using IBM Watsonx Assistant**

## 1. Machine Learning Project on Loan Dataset

### Project Description

This project focuses on predicting loan approval status based on various attributes of the applicants. The dataset used is a publicly available loan dataset that includes information such as gender, marital status, education, applicant income, loan amount, credit history, and more.

### Key Steps

1. **Data Preprocessing**:
    - Conversion of categorical variables using `LabelEncoder`.
    - Handling missing values by filling them with mean or median values.
    - Dropping irrelevant columns such as `Loan_ID`.
    - Feature scaling using `MinMaxScaler`.
2. **Exploratory Data Analysis (EDA)**:
    - Visualization of the distribution of loan status across various attributes such as gender, marital status, education, etc.
    - Correlation analysis using a heatmap to identify relationships between different features.
3. **Model Building and Training**:
    - Several machine learning models were trained, including Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and XGBoost.
    - Hyperparameter tuning was performed using `GridSearchCV` for models like Random Forest and XGBoost to identify the best model configurations.
    - Addressed class imbalance using `SMOTE` (Synthetic Minority Over-sampling Technique).
4. **Model Evaluation**:
    - The performance of each model was evaluated using metrics like accuracy, AUC-ROC score, and confusion matrices.
    - ROC curves were plotted for a visual representation of model performance.

### Dependencies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn (for SMOTE)

### Instructions

1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook or Python script to view the analysis and model training steps.

Note- If setting up the python environment with the necessary dependencies is cumbersome then you can also view and execute the full code which is available on Google Colab at the following link:

[Loan Dataset Analysis on Google Colab](https://colab.research.google.com/drive/18VV0DSwpSBA2SrK7peF-Z9Sdt-PrOGDX?usp=sharing)

Make sure to upload the csv file of loan dataset which is shared in this repository, on google colab before executing the code present on colab notebook.

## 2. Chatbot Development using IBM Watsonx Assistant

### Project Description

The second project involves creating a chatbot named **Vedant Roy** using IBM's **Watsonx Assistant**. The chatbot is designed for a fictitious college named **XYZ** and interacts with users to provide information about the college's engineering departments.

### Key Features

- **Greeting Users**: The chatbot greets users upon receiving a greeting.
- **Providing Department Information**: When asked about the available departments, the chatbot offers five options: Electrical and Electronics Engineering (EEE), Information Technology (IT), Artificial Intelligence (AI), Electronics and Communication Engineering (ECE), and Computer Science Engineering (CSE).
- **Detailed Department Information**: Upon selecting a department, the chatbot provides detailed information about that particular branch.

### IBM Watsonx Assistant Features and Capabilities

- **Free Lite Plan**: The chatbot was developed using IBM's Watsonx Assistant free lite plan, which offers:
    - Up to 1,000 unique monthly active users (MAUs).
    - Up to 10,000 messages per month.
    - The ability to create up to 3 assistants per instance and up to 100 actions per assistant.
    - An analytics dashboard for analyzing user interactions and improving the chatbot's performance.
- **Customizability**: The chatbot was made customizable with the ability to deploy webchat in minutes or extend functionality using IBM's API endpoints. The Watsonx Assistant can integrate with existing webpages and documents, making it a versatile tool for developing conversational AI.

### Video Demonstration

The development and functionality of the chatbot have been documented in a screen-recorded video. This video showcases the entire process, from the chatbot's creation to its interaction with users. The video is hosted on Mega Cloud and can be accessed via the following link:

[View and Download the Chatbot Demo Video](https://mega.nz/file/Coc3wByY#g7mxSfv0PMax1NSMPKDgKoeQIWWW94LZHhovx2qh0T8)

### Instructions

1. Click the link above to view or download the demo video of the chatbot.
2. The video demonstrates how the chatbot interacts with users and provides information based on user queries.

## Files in this Repository

### 1. `Vedant Roy Edunet Internship Project Report.pdf`

This PDF document is the final project report submitted as part of the virtual internship. It includes detailed explanations of the ML project, methodologies used, results obtained, and reflections on the learning experience.

### 2. `Edunet_Internship_Project_Python_Notebook_by_Vedant_Roy.ipynb`

This Jupyter Notebook contains the Python code for the Machine Learning project on the loan dataset. It includes the complete workflow from data preprocessing, exploratory data analysis, model building, and evaluation. The notebook is well-documented with markdown cells explaining each step.

### 3. `Vedant Roy Getting Started with Enterprise Grade AI Badge IBM SkillsBuild.pdf`

This PDF certificate is awarded by IBM SkillsBuild, recognizing the completion of the "Getting Started with Enterprise Grade AI" course. It reflects the skills and knowledge gained in using IBM's AI tools, which were applied in the chatbot development project.

### 4. `loan_data_set.csv`

This CSV file contains the loan dataset used in the Machine Learning project. It includes various attributes related to loan applicants, such as gender, marital status, education, applicant income, loan amount, and credit history. The dataset is used to train and evaluate machine learning models for predicting loan approval status.

## Virtual Internship Details

- **Internship**: AI and Cloud
- **Organization**: Edunet Foundation
- **Collaboration**: IBM SkillsBuild and AICTE
- **Internship Mode**: Virtual

---

This `README.md` file provides a comprehensive overview of the two projects, the associated files in this repository, and instructions on how to utilize the resources provided.
