# Heart-Failure-Risk-Detection
# 💓 Heart Failure Risk Prediction App



A modern, interactive web app to predict the risk of heart failure using machine learning. Built with Flask, styled with CSS animations, and ready for 1-click deployment on Render.

---

## 🚀 Features
- Predicts heart failure risk based on clinical parameters
- Animated, responsive UI with heart pulse and arrival effects
- Retains user input after prediction for easy re-tries
- Ready for cloud deployment (Render, Heroku, etc.)

---

## 🖥️ Screenshots

<img width="1923" height="1019" alt="image" src="https://github.com/user-attachments/assets/20f92c02-7dcd-438c-94b7-fc2515e0f4d4" />

---

## 🛠️ Setup (Local)

1. **Clone the repo:**
   ```bash
   git clone https://github.com/yourusername/heart-failure-predictor.git
   cd heart-failure-predictor
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Add model files:**
   - Place `heart_failure_model.pkl` and `encoders.pkl` in the project root.
4. **Run the app:**
   ```bash
   python app.py
   ```
5. **Visit:**
   - Open (https://heart-failure-risk-detection.onrender.com/predict) in your browser.

---

## 🌐 Deploy on Render

1. Click the button below to deploy instantly:
   
   [![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

2. Set up the following:
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `gunicorn app:app`
   - **Python Version:** 3.8+
   - Upload your model files (`heart_failure_model.pkl`, `encoders.pkl`) to the root directory.

---

## 📄 Project Structure
```
├── app.py
├── requirements.txt
├── heart_failure_model.pkl
├── encoders.pkl
├── static/
│   └── style.css
├── templates/
│   └── index.html
```

---

## 🤝 ACKNOWLEDGEMENTS
- UI/UX: Inspired by modern medical dashboards
- Model: Your trained ML model
- Built with [Flask](https://flask.palletsprojects.com/)
- Thanks to DevTown

---

## 📬 Contact
For questions or feedback, open an issue or contact [ksvnspavankumar.24@example.com](mailto:ksvnspavankumar.24@gmail.com@example.com) 
