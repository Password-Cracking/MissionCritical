# MissionMaster

## Description

MissionMaster is an application designed to analyze the complexity of passwords and provide insights into their strength. It utilizes machine learning models to predict the complexity of passwords based on various factors such as length, character types, entropy, and common patterns.

## Prerequisites

Before running the application, ensure you have the following installed:

- [Python](https://www.python.org/downloads/)
- [Flask](https://flask.palletsprojects.com/en/2.0.x/installation/)

## Usage

1. Navigate to the project directory.
2. Install required Python packages: `pip install -r requirements.txt`
3. Run the application using the following command: `gunicorn app:app`
4. Access the application through the browser at `http://localhost:8000`.
5. Enter a password in the input field and click on the "Predict Complexity" button to analyze its complexity.
6. Upload a CSV file containing passwords to analyze multiple passwords at once.
7. View detailed analysis and suggestions for password improvement on the dashboard.

## Authors

- **Qasem Abu Al-Haija**
- **Rand Abu-Ghazaleh**
- **Ayat Hafez**
- **Sara Mansour**
- **Yara Al-Jammal**
