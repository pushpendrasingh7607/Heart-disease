# ❤️ Heart Disease Prediction App

A Machine Learning web application built with **Python**, **Scikit-learn**, and **Streamlit** that predicts whether a person is at **high risk** or **low risk** of heart disease based on medical parameters.

## 🚀 Features

- Predicts heart disease risk using a trained KNN model.
- Simple and interactive Streamlit interface.
- User-friendly input fields.
- Automatic data preprocessing using a saved scaler.
- Real-time prediction results.

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Joblib

---

## 📂 Project Structure

```
Heart-Disease-Prediction/
│── app.py
│── KNN_heart.pkl
│── scaler.pkl
│── columns.pkl
│── requirements.txt
│── README.md
```

---

## 📊 Dataset Features

The model uses the following medical attributes:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak (ST Depression)
- ST Slope

---

## 🩺 Prediction Output

The application predicts one of the following:

- ✅ Low Risk of Heart Disease
- ⚠️ High Risk of Heart Disease

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git
```

### Navigate to the project

```bash
cd Heart-Disease-Prediction
```

### Create a virtual environment (Optional)

```bash
python -m venv venv
```

### Activate the virtual environment

**Windows**

```bash
venv\Scripts\activate
```

**macOS/Linux**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will be available at:

```
http://localhost:8501
```

---

## 📸 Application Preview

_Add a screenshot of your Streamlit application here._

Example:

```
images/app.png
```

---

## 🧠 Machine Learning Model

- Algorithm: **K-Nearest Neighbors (KNN)**
- Feature Scaling: StandardScaler
- Model Serialization: Joblib

---

## 📌 Future Improvements

- Improve model accuracy using advanced algorithms.
- Add probability scores.
- Deploy on Streamlit Community Cloud.
- Add data visualization dashboard.
- Improve UI/UX.

---

## 👨‍💻 Author

**Pushpendra Singh**

- GitHub: https://github.com/pushpendrasingh7607
- LinkedIn: https://www.linkedin.com/in/pushpendra-singh-730798307/

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
