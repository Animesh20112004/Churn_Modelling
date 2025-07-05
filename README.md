# 🧠 Customer Churn Prediction App

Welcome to the Customer Churn Prediction App — a sleek, interactive Streamlit web application that uses an Artificial Neural Network (ANN) to predict whether a customer is likely to exit a bank. This tool is designed to help financial institutions proactively identify at-risk customers and take action to improve retention.

---

## 📌 Notes
The app is deployed on the streamlit cloud.
Below is the Link:
Please do have a look:
https://churnmodelling-phsrflxmetrejyknrm5y7x.streamlit.app/

## 🚀 Features

- 🔍 Predicts customer churn using a trained ANN model (Model Accuracy : 0.86)
- 📊 Interactive UI built with Streamlit
- 🧠 Uses TensorFlow for model inference
- 🧮 Preprocessing with Scikit-learn (scaling, encoding)
- 📁 Clean and modular code structure
- 📈 Displays churn probability and decision outcome

---

## 🧬 Model Overview

- Model Type: Sequential Artificial Neural Network (ANN)
- Framework: TensorFlow / Keras
- Input Features:
  - Credit Score
  - Geography (One-Hot Encoded)
  - Gender (Label Encoded)
  - Age
  - Tenure
  - Balance
  - Number of Products
  - Has Credit Card
  - Is Active Member
  - Estimated Salary

---

## 🛠️ Tech Stack

| Tool            | Purpose                          |
|-----------------|----------------------------------|
| Python          | Core programming language        |
| Streamlit       | Web app framework                |
| TensorFlow/Keras| ANN model training & inference   |
| Scikit-learn    | Preprocessing (scaling, encoding)|
| Pandas & NumPy  | Data manipulation                |
| Pickle          | Model and encoder serialization  |

---

## 🧪 How to Run the App

1. 🔁 Clone the repository:
   ```bash
   git clone https://github.com/Animesh20112004/churn-prediction-app.git
   cd churn-prediction-app
   ```

2. 📦 Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. ▶️ Launch the app:
   ```bash
   streamlit run app.py
   ```

---

## 📂 Folder Structure

```
├── app.py                      # Streamlit app
├── ANN_model.h5                # Trained ANN model
├── scaler.pkl                  # StandardScaler object
├── OneHotEncoder_geography.pkl# OneHotEncoder for Geography
├── label_encoder_gender.pkl    # LabelEncoder for Gender
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

---

## 📈 Sample Prediction Output

- ✅ Input: Age = 40, Geography = France, Balance = 60,000, etc.
- 🔮 Output: Churn Probability = 0.73
- ⚠️ Result: The customer is likely to Exit/Churn

---

## 📌 Notes

- This app is for educational/demo purposes.
- For production use, consider integrating model versioning (e.g., DVC), secure deployment, and monitoring.

---

## 🙌 Acknowledgments

Thanks to the open-source community and the creators of TensorFlow, Streamlit, and Scikit-learn for making this project possible.
