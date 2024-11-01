# Advanced Online Payment Fraud Detection

## Project Overview
The **Online Payment Fraud Detection** project aims to detect fraudulent transactions in real time, leveraging machine learning models trained on historical transaction data. By distinguishing between genuine and suspicious activities, this system can effectively flag and prevent fraudulent payments, enhancing transaction security.

## Features
- **Real-Time Detection**: Identifies fraud during transactions by processing live data.
- **Machine Learning Models**: Uses both supervised and unsupervised algorithms to classify transactions.
- **Feature Engineering**: Builds complex features like transaction frequency and geolocation consistency to improve model accuracy.
- **Evaluation Metrics**: Evaluates model performance with metrics like Precision, Recall, F1-Score, and ROC-AUC.

## Tech Stack
- **Backend**: Flask
- **Machine Learning**: Scikit-Learn, Pickle
- **Frontend**: HTML (for input form)
- **Deployment**: Local deployment using Flask (Docker/Kubernetes options for scalable production environments)

## Project Structure

├── app.py # Flask app for serving the model and handling HTTP requests ├── templates │ └── index.html # Frontend HTML form for user inputs ├── Online_payment_fraud_detection_randomforest.pkl # Trained model file (Random Forest) ├── online_payment.ipynb # Jupyter notebook for model training and testing └── .gitignore # Lists files/folders ignored by Git (e.g., temporary files)
