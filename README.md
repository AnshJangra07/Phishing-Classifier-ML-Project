# Phishing Classifier ML Project

A machine learning project to detect phishing websites based on URL and website features. The model is trained on labeled data and deployed as a Flask web application.

## Features

- Data ingestion, validation, and transformation pipeline
- Model training using XGBoost
- MongoDB integration for data storage
- Flask web app for predictions
- Dockerized deployment with CI/CD via GitHub Actions

## Project Structure

```
├── src/
│   ├── components/          # Data ingestion, validation, transformation, model training
│   ├── configuration/       # MongoDB connection setup
│   ├── pipeline/            # Training and prediction pipelines
│   └── utils/                # Utility functions
├── config/                   # Model and schema configuration files
├── notebook implementation/  # EDA and experimentation notebooks
├── templates/                # HTML templates for the web app
├── static/                   # CSS/static files
├── app.py                    # Flask application entry point
├── requirements.txt          # Python dependencies
└── setup.py                  # Package setup
```

## Installation

1. Clone the repository

```bash
git clone https://github.com/AnshJangra07/Phishing-Classifier-ML-Project.git
cd Phishing-Classifier-ML-Project
```

2. Create and activate a virtual environment

```bash
python -m venv myenv
myenv\Scripts\activate      # Windows
source myenv/bin/activate   # macOS/Linux
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

## Usage

Run the Flask app:

```bash
python app.py
```

## Tech Stack

- Python, Flask
- XGBoost, scikit-learn, pandas, numpy
- MongoDB
- Docker, GitHub Actions

## Author

**Ansh Jangra**
