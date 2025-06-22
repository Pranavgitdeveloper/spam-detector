# spam-detector
A Flask web app for detecting spam emails using Machine Learning.
# Spam Detector 📨

A **Flask web application** that predicts whether an email is **Spam** or **Not Spam** using Machine Learning (Naive Bayes + TF-IDF).

## Features
- ✅ Predicts Spam or Not Spam
- ✅ Shows confidence score (%)
- ✅ Clean web interface (Bootstrap + CSS)
- ✅ Deployed on Render

## Technologies Used
- Python
- Flask
- Scikit-learn
- TF-IDF Vectorizer
- Gunicorn
- HTML + CSS (Bootstrap 5)

## Project Structure
spam-detector/
├── app.py
├── model.pkl
├── vectorizer.pkl
├── templates/index.html
├── static/style.css
├── requirements.txt
├── Procfile



## Run Locally
```bash
git clone https://github.com/YOUR_USERNAME/spam-detector.git
cd spam-detector
pip install -r requirements.txt
python app.py

Open → http://127.0.0.1:5000/
