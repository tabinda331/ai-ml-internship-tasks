# AI/ML Internship Tasks

This repository contains completed **AI/ML internship tasks** implemented using Python and
Jupyter Notebooks. Each task demonstrates practical understanding of data analysis,
machine learning workflows, and safe AI application development.

---

## Task 1: Iris Dataset Exploration

### Objective
The objective of this task is to explore the classic **Iris dataset** to understand data
distribution, feature relationships, and class separability. This task focuses on
**exploratory data analysis (EDA)** and visualization techniques.

---

### Dataset
- **Dataset Name:** Iris Dataset
- **Source:** Built-in dataset (scikit-learn)

**Description:**  
The dataset contains 150 samples of iris flowers with four numerical features:
sepal length, sepal width, petal length, and petal width.
The target variable represents three iris species.

---

### Methodology
- Loaded the dataset using Pandas and scikit-learn
- Inspected dataset structure and summary statistics
- Visualized feature distributions using plots
- Analyzed relationships between features and classes

---

### Key Insights
- Petal length and petal width are the most discriminative features
- Iris species are clearly separable using petal-related attributes
- The dataset is clean and well-balanced

---

### Skills Demonstrated
- Exploratory Data Analysis (EDA)
- Data visualization
- Understanding of feature relationships

---

### How to Run
- 📘 [Task1_Iris_Exploration.ipynb](Task1_Iris_Exploration.ipynb)


---

## Task 3: Heart Disease Prediction

### Objective
The objective of this task is to build a **binary classification model** that predicts whether
a person is at risk of heart disease based on medical and lifestyle attributes. This task
demonstrates a complete machine learning pipeline from preprocessing to evaluation.

---

### Dataset
- **Dataset Name:** Heart Disease UCI Dataset
- **Source:** Kaggle

**Description:**  
The dataset contains patient health attributes such as age, sex, chest pain type,
cholesterol level, blood pressure, and maximum heart rate.
The target variable indicates the presence or absence of heart disease.

> **Note:** This notebook was originally developed using **Kaggle Notebook** and later
exported as a Jupyter Notebook for submission.

---

### Methodology
1. Data loading and inspection  
2. Data preprocessing and cleaning  
3. Exploratory Data Analysis (EDA)  
4. Model training using classification algorithms  
5. Model evaluation using accuracy, confusion matrix, and ROC curve  
6. Feature importance analysis  

---

### Key Results
- The trained model achieved good predictive performance on unseen data
- Clinical features such as age, chest pain type, cholesterol level, and heart rate
  significantly influenced predictions
- Logistic Regression provided an interpretable baseline model for medical datasets

---

### Limitations & Future Improvements
- Dataset size is limited
- Advanced ensemble models (e.g., Random Forest, XGBoost) could improve performance
- Additional feature engineering and hyperparameter tuning may enhance results

---

### How to Run
Open and execute the notebook:

- 📘 [Task3_Heart_Disease_Prediction.ipynb](Task3_Heart_Disease_Prediction.ipynb)


---

## Task 4: General Health Query Chatbot (Prompt Engineering Based)

### Objective
The objective of this task is to build a chatbot that answers **general health-related questions**
using a Large Language Model (LLM) via API, while ensuring safety, clarity, and user-friendly
responses.

---

### Tools & Technologies
- **LLM API:** DeepSeek
- **Programming Language:** Python
- **Interface:** Jupyter Notebook
- **Techniques Used:**
  - Prompt engineering
  - Safety filtering
  - Emotion-aware responses
  - Conversation memory

---

### Key Features
- Uses a system prompt to behave like a helpful medical assistant
- Avoids diagnosis and medication dosage instructions
- Implements safety filters for harmful or sensitive queries
- Detects emotional tone (anxious / sad / neutral)
- Secure API key handling via environment variables

---

### Safety Handling
- Blocks self-harm or dangerous medical queries
- Adds medical disclaimers to responses
- Encourages professional medical consultation for serious symptoms

---

### API Key Security
For security reasons, the API key is **not stored** in the notebook or repository.
It is loaded securely from a system environment variable named:

---

### How to Run
- 📘 [Task4_Health_Chatbot.ipynb](Task4_Health_Chatbot.ipynb)


