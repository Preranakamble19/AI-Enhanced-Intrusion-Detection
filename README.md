# AI-Enhanced-Intrusion-Detection
# AI-Enhanced Intrusion Detection System (IDS)

## Overview

The AI-Enhanced Intrusion Detection System (IDS) is a cybersecurity solution that uses Machine Learning to detect, classify, and respond to network intrusions. The system analyzes network traffic, identifies suspicious activities, and classifies attacks into categories such as DoS, Probe, R2L, and U2R.

## Features

* Real-time intrusion detection
* Machine Learning-based threat analysis
* Detection of unknown and evolving attacks
* Attack classification (DoS, Probe, R2L, U2R)
* Automated alert generation
* Interactive monitoring dashboard
* Continuous model improvement through retraining

## Technologies Used

* Python
* Flask
* Pandas
* NumPy
* Scikit-learn
* HTML, CSS, JavaScript

## System Architecture

1. **Data Input Layer** – Collects network traffic data.
2. **Data Processing Layer** – Cleans and preprocesses data.
3. **Machine Learning Layer** – Trains and predicts network behavior.
4. **Classification Layer** – Categorizes detected attacks.
5. **Alert System** – Generates security alerts.
6. **Dashboard** – Displays results and system status.

## Machine Learning Models

* Random Forest (Primary Model)
* Decision Tree
* Logistic Regression

Random Forest was selected due to its high accuracy, scalability, and resistance to overfitting.

## Dataset

The project uses network traffic datasets containing:

* Protocol Type
* Connection Duration
* Source Bytes
* Destination Bytes
* Service Type
* Connection Flags
* Attack Labels

## Project Structure

```text
AI_IDS/
│
├── backend/
│   └── main.py
│
├── dashboard/
│   ├── app.py
│   ├── templates/
│   │   └── index.html
│
├── data/
│   └── UNSW_NB15_training-set.csv
│
├── ml/
│   ├── train.py
│   ├── model.pkl
│   └── requirements.txt
```

## Workflow

1. Load dataset.
2. Preprocess network traffic data.
3. Train machine learning model.
4. Save trained model.
5. Load model into Flask backend.
6. Receive network traffic input.
7. Predict normal or malicious activity.
8. Generate alerts and display results on the dashboard.

## Performance Metrics

* Accuracy
* Precision
* Recall
* F1 Score

## Advantages

* Detects both known and unknown attacks
* High detection accuracy
* Automated alerting mechanism
* Scalable and flexible architecture
* Supports continuous learning

## Future Enhancements

* Live network traffic integration
* Deep Learning-based detection
* Cloud deployment
* Advanced data visualization
* Automated threat response

## Conclusion

This project demonstrates how Artificial Intelligence and Machine Learning can enhance traditional Intrusion Detection Systems by providing accurate, scalable, and adaptive cybersecurity protection against modern network threats.
