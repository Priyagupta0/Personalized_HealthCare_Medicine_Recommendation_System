# 🏥 Personalized Healthcare & Medicine Recommendation System

An AI-powered healthcare assistant that allows users to input symptoms and receive **disease predictions**, **dietary advice**, and **personalized workout plans** using machine learning models.

🔐 Features user **login and signup** functionality for secure access, built using **Flask**, and stores data using **Flask-SQLAlchemy**.

---

## 🚀 Key Features

✅ **User Authentication**  
- Secure login/signup using `bcrypt` password hashing

✅ **Symptom-based Disease Prediction**  
- Users enter symptoms, and the ML model predicts the most probable disease

✅ **Diet Recommendations**  
- Based on predicted illness, suitable food and nutrition tips are provided

✅ **Workout Suggestions**  
- Light, moderate, or intense workouts based on user health condition

✅ **Clean Dashboard Interface**  
- Built using Flask templates and styled with Bootstrap for responsiveness

✅ **Data Visualization**  
- Insightful health-related plots using `matplotlib` and `seaborn`

---

## 🧠 Tech Stack

**Frontend:**
- HTML, CSS

**Backend:**
- Python
- Flask
- Flask-SQLAlchemy
- Flask-Bcrypt

**Machine Learning:**
- scikit-learn
- pandas
- numpy

**Visualization:**
- matplotlib
- seaborn

---

## 📦 Requirements

Create a `requirements.txt` with the following content:

```

bcrypt==4.3.0
Flask==3.1.0
Flask-Bcrypt==1.0.1
Flask-SQLAlchemy==3.1.1
matplotlib==3.10.0
numpy==2.0.2
pandas==2.2.3
scikit-learn==1.6.0
seaborn==0.13.2
SQLAlchemy==2.0.39

````

Install with:
```bash
pip install -r requirements.txt
````

---

## 🗂️ Project Structure

```
personalized-healthcare-system/
├── app.py                           # Flask application entry point
├── templates/                       # HTML templates
├── static/                          # CSS and images
├── model/                           # ML model files and pickle files
├── dataset/                         # CSV dataset(s) for training
├── instance/                        # Local DB (SQLite)
├── __pycache__/                     # Python cache
├── Medicine_Recommendation_System.ipynb  # Training notebook
├── requirements.txt
└── README.md
```

---

## 💻 Running the App Locally

1. Clone the repo:

```bash
git clone https://github.com/Priyagupta0/Personalized_HealthCare_Medicine_Recommendation_System
cd personalized-healthcare-system
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the app:

```bash
python app.py
```

4. Open in browser:

```
http://127.0.0.1:5000
```

---

## 🧪 ML Workflow Summary

* Input: Symptom list from the user like ( headache , cough)
* Processing: Symptom encoding + prediction using trained model
* Output:
  * Predicted Disease
  * Recommended Exercises
  * Suggested Diet Plan

---

## 🔒 Security Notes

* User credentials are hashed using `bcrypt` for secure storage
* Uses Flask's built-in session management for user sessions

---

## 👨‍⚕️ Author

Developed by Priya Gupta
For educational purposes — AI for social impact in healthcare.
