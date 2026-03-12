# 🔐 Phishing URL Detection System

## 📌 Project Overview

The **Phishing URL Detection System** is a machine learning–based application designed to identify and classify URLs as **legitimate or phishing**. Phishing attacks are one of the most common cybersecurity threats, where attackers create malicious websites that appear legitimate to steal sensitive information such as passwords, credit card details, and personal data.

This project uses **machine learning algorithms and URL feature extraction techniques** to analyze URLs and detect suspicious patterns. The system helps users quickly determine whether a given URL is safe to access or potentially harmful.

---

## 🎯 Objectives

* Detect phishing websites using machine learning techniques.
* Analyze URL structures and extract meaningful features.
* Classify URLs into **phishing** or **legitimate** categories.
* Provide an easy-to-use interface for users to check URLs.

---

## ⚙️ Technologies Used

* **Python**
* **Machine Learning**
* **Scikit-learn**
* **Pandas & NumPy**
* **Streamlit (for web interface)**
* **Matplotlib**
* **Joblib**

---

## 🧠 Machine Learning Model

The system uses the **Random Forest Classifier**, which is an ensemble learning algorithm known for high accuracy and reliability in classification tasks. The model is trained on a dataset containing phishing and legitimate URLs with multiple extracted features.

---

## 🔍 Features

* URL feature extraction
* Phishing vs Legitimate URL classification
* User-friendly **Streamlit web interface**
* Visualization of results
* Fast and reliable prediction

---

## 📂 Project Structure

```
Phishing-URL-Detection/
│
├── phishing.py          # Main application file
├── dataset.csv          # Dataset used for training
├── model.pkl            # Saved trained model
├── README.md            # Project documentation
```

---

## ▶️ How to Run the Project

1️⃣ Clone the repository

```
git clone https://github.com/your-username/your-repository-name.git
```

2️⃣ Navigate to the project folder

```
cd your-repository-name
```

3️⃣ Install required libraries

```
pip install -r requirements.txt
```

4️⃣ Run the Streamlit application

```
streamlit run phishing.py
```

---

## 📊 Output

The system analyzes the given URL and displays whether the URL is **Safe (Legitimate)** or **Phishing (Malicious)** along with prediction insights.

---

## 🚀 Future Enhancements

* Improve accuracy with deep learning models
* Add real-time URL scanning
* Integrate browser extension support
* Expand dataset for better training

---

## 👩‍💻 Author

Developed as a cybersecurity and machine learning project to detect phishing websites and improve online safety.

---

⭐ If you like this project, consider giving it a **star** on GitHub!
