Student API (Flask)

Simple Flask API for managing student data and predicting the 6th test score.
Provides two endpoints:

GET /Students → returns student data from students.json

GET /Predict?Scores=10 20 30 40 50 → returns predicted 6th score

✅ CORS enabled for development
✅ Ready to deploy on Azure

Tech Stack

Python 3

Flask + Flask-CORS

NumPy

Run
pip install flask flask-cors numpy
python app.py

API will run at http://127.0.0.1:5000

Author

Tomáš Klein
