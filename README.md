# 🎓 Student Performance Prediction

An End-to-End Machine Learning project that predicts a student's **Mathematics Score** based on demographic and academic features. The project follows a modular ML pipeline including data ingestion, data transformation, model training, hyperparameter tuning, prediction pipeline, and deployment using Flask.

---

## 📌 Project Overview

Educational institutions often need to identify students who may require additional academic support. This project uses Machine Learning to predict a student's mathematics performance using attributes such as gender, parental education, lunch type, race/ethnicity, reading score, and writing score.

The application allows users to enter student information through a web interface and instantly receive a predicted mathematics score.

---

## 🚀 Features

- End-to-End Machine Learning Pipeline
- Modular Project Structure
- Data Ingestion Pipeline
- Data Validation
- Data Transformation & Preprocessing
- Feature Engineering
- Model Training
- Hyperparameter Tuning
- Best Model Selection
- Prediction Pipeline
- Flask Web Application
- Logging & Exception Handling
- Deployment Ready
- Clean and Scalable Code Structure

---

## 🛠️ Tech Stack

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Scikit-learn
- CatBoost
- XGBoost
- Matplotlib
- Seaborn
- Dill

### Framework

- Flask

### Version Control

- Git
- GitHub

### Deployment

- AWS Elastic Beanstalk

---

# 📂 Project Structure

```text
Student-Performance-Prediction/
│
├── .ebextensions/
│
├── artifacts/
│   ├── model.pkl
│   ├── preprocessor.pkl
│   └── train.csv
│
├── catboost_info/
│
├── notebook/
│   ├── EDA.ipynb
│   ├── Model Training.ipynb
│   └── data/
│
├── src/
│   ├── components/
│   │      ├── data_ingestion.py
│   │      ├── data_transformation.py
│   │      └── model_trainer.py
│   │
│   ├── pipeline/
│   │      ├── predict_pipeline.py
│   │      └── train_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
│   ├── home.html
│   └── index.html
│
├── app.py
├── application.py
├── requirements.txt
├── setup.py
└── README.md
```

---

# 📊 Dataset Information

The dataset contains demographic and academic information of students.

### Input Features

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

### Target Variable

- Mathematics Score

---

# ⚙️ Machine Learning Workflow

```
Data Collection
        │
        ▼
Data Ingestion
        │
        ▼
Data Validation
        │
        ▼
Data Transformation
        │
        ▼
Feature Engineering
        │
        ▼
Model Training
        │
        ▼
Hyperparameter Tuning
        │
        ▼
Model Evaluation
        │
        ▼
Best Model Selection
        │
        ▼
Prediction Pipeline
        │
        ▼
Flask Web Application
```

---

# 🤖 Machine Learning Models Used

The following regression algorithms were trained and compared:

- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- AdaBoost Regressor
- XGBoost Regressor
- CatBoost Regressor

The best-performing model is automatically selected based on evaluation metrics.

---

# 📈 Model Evaluation

The models were evaluated using regression metrics such as:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

Hyperparameter tuning was performed to improve model performance.

---

# 🌐 Web Application

The Flask application provides an interactive interface where users can:

- Enter student information
- Predict mathematics score instantly
- Receive real-time predictions using the trained model

---

# 🖥️ Installation

Clone the repository

```bash
git clone https://github.com/amrritt18/student-performance-prediction.git
```

Move to project directory

```bash
cd student-performance-prediction
```

Create virtual environment

### Windows

```bash
python -m venv venv
```

Activate environment

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

Run the Flask application

```bash
python app.py
```

or

```bash
python application.py
```

The application will start locally.

---

# 📸 Project Screenshots

## Home Page

> screenshots

```
images/home.png
```

## Prediction Page

> screenshots

```
images/predict.png
```

---

# 📚 Learning Objectives

This project demonstrates:

- End-to-End Machine Learning Pipeline
- Object-Oriented Programming
- Modular Python Project Structure
- Data Preprocessing
- Feature Engineering
- Model Training
- Hyperparameter Tuning
- Model Serialization
- Exception Handling
- Logging
- Flask Deployment
- AWS Deployment Basics
- Git & GitHub Workflow

---

# 🔮 Future Improvements

- Docker Containerization
- CI/CD Pipeline using GitHub Actions
- MLflow Integration
- Model Monitoring
- Unit Testing
- Kubernetes Deployment
- REST API Development
- Cloud Deployment using AWS EC2
- Streamlit Dashboard
- Database Integration

---

# 📦 Requirements

Major dependencies:

```
Python 3.10+
Flask
Pandas
NumPy
Scikit-learn
CatBoost
XGBoost
Matplotlib
Seaborn
Dill
```

Install all dependencies using

```bash
pip install -r requirements.txt
```

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

## Amrit Raj

**Aspiring Data Scientist | Machine Learning Engineer | MLOps Enthusiast**

GitHub: https://github.com/amrritt18

LinkedIn: www.linkedin.com/in/amrritt18/

---
---

# 🙏 Acknowledgements

This project is based on the **End-to-End Machine Learning Project** taught by **Krish Naik**.

The original project and tutorials provided the foundation for understanding how to build a production-ready Machine Learning application.

As part of my learning journey, I implemented the project on my own, practiced each component, explored the codebase in depth, and gained hands-on experience with:

- End-to-End Machine Learning Pipelines
- Data Ingestion
- Data Transformation
- Model Training
- Hyperparameter Tuning
- Flask Deployment
- Logging & Exception Handling
- Project Structure
- AWS Elastic Beanstalk Deployment

Special thanks to **Krish Naik** for creating such high-quality educational content that helped me understand practical Machine Learning Engineering.

> **Note:** This repository is intended for educational and learning purposes. All credits for the original project idea and teaching methodology belong to Krish Naik.
## ⭐ If you found this project helpful, please consider giving it a Star on GitHub!
