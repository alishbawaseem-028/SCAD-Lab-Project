# SCAD Lab Project – AI Spam Detection Web Application

## 👥 Group Members

* Alishba Waseem (FA23-BSE-028)
* Aima Jahangir (FA23-BSE-043)

**Course:** Software Construction and Development (SCAD) Lab
**University:** COMSATS University Islamabad – Attock Campus

---

## 📌 Project Description

This project is a **lightweight AI-based web application** that classifies SMS messages as **Spam or Ham (Not Spam)**.
The system is built by modifying an existing open-source project and enhancing it with software development practices learned in the course.

---

## 🤖 Model Details

* **Type of Model:** Naive Bayes (Machine Learning – Text Classification)
* **Technique Used:** Bag of Words / Count Vectorization
* **Dataset:** SMS Spam Collection Dataset (`sms.tsv`)

### 📥 Input

* User enters a text message in the web interface

### 📤 Output

* Prediction: **Spam / Ham**
* Confidence Score (probability of prediction)

---

## ⚙️ Features Implemented (Course Requirements)

### 🔹 Web Application

* Single-page web interface using Flask
* Accepts user input and displays prediction results
* Proper error handling for empty/invalid input

### 🔹 Software Construction Concepts

* **Threading:**
  Implemented to handle predictions without blocking the main application

* **Unit Testing:**
  Created `testing.py` using Python `unittest` to test core functions

* **API Testing:**
  Tested Flask API endpoints using Postman

* **Project Management:**
  Trello board created to manage tasks and workflow

* **Diagrams:**
  Use-case diagram and flowchart included in report

---

## 🛠 Technologies Used

* **Backend:** Python, Flask
* **Machine Learning:** scikit-learn, pandas, NumPy
* **Frontend:** HTML, CSS, JavaScript
* **Testing:** unittest, Postman

---

## 🚀 Deployment

* **GitHub Repository:** (Add your link here)
* **Hugging Face Deployment:** (Add your link here)

✔ Deployed using CPU (no GPU required)
✔ Lightweight model for free hosting compatibility

---

## 📸 Screenshots

All screenshots (UI, Postman testing, results) are included in the project report document.

---

## ⚠️ Limitations

* Uses a simple Naive Bayes model (limited accuracy)
* Works only on SMS-style text data
* Not suitable for complex or multilingual spam detection

---

## 🔮 Future Work

* Improve accuracy using advanced models (e.g., LSTM, Transformers)
* Add support for multiple languages
* Deploy with database for storing user inputs
* Enhance UI/UX design

---

## 🙏 Acknowledgment / Original Project Credit

This project is based on the open-source tutorial:
**"Machine Learning with Text in scikit-learn" by Kevin Markham**

We have modified and extended the original implementation by adding:

* Web interface (Flask)
* Threading
* Unit testing
* API testing
* Deployment

---

## ▶️ How to Run Locally

```bash
pip install -r requirements.txt
python app.py
```

Then open: http://127.0.0.1:5000/
