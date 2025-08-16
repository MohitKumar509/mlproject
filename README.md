## Student Performance Prediction
This repository contains an end-to-end implementation of a machine learning workflow, packaged as a Flask web application. It covers the complete cycle — from data preprocessing and model training to deployment through a simple web interface.

🔍 Overview

Data Processing: Handled with pandas, numpy, and scikit-learn.

Model Training: Includes tree-based models like XGBoost and CatBoost, along with evaluation pipelines.

Pipeline Structure: Modular code for data ingestion, transformation, and prediction.

Web Application: Flask interface for user input and real-time predictions.

Deployment Ready: Packaged with setup.py and dependency management.

📂 Project Structure
├── app.py                # Flask application entry point
├── requirements.txt      # Python dependencies
├── setup.py              # Package setup script
├── .gitignore            # Ignored files for version control
├── src/                  # Source code for ML pipelines and components
│   ├── pipeline/
│   │   ├── predict_pipeline.py
│   │   └── train_pipeline.py
│   ├── components/       # Data ingestion, transformation, and training
│   └── ...
├── templates/            # HTML templates (index.html, home.html)
└── README.md             # Project documentation

⚙️ Installation

Follow the steps below to set up the project locally:

Clone the repository

git clone https://github.com/your-username/mlproject.git
cd mlproject


Create a virtual environment (recommended)

python -m venv venv


Activate it:

Linux/MacOS:

source venv/bin/activate


Windows:

venv\Scripts\activate


Install dependencies

pip install -r requirements.txt


Install the package in editable mode

pip install -e .

▶️ Running the Application

Start the Flask app:

python app.py


The application will be available at:

http://127.0.0.1:5000/


From here, you can:

Access the home page (/)

Enter input values in the form (/predictdata)

View the predicted result on the page

📦 Requirements

Core libraries used in this project:

Flask – Web framework

pandas, numpy – Data handling

scikit-learn – Preprocessing and ML utilities

xgboost, catboost – ML models

matplotlib, seaborn – Visualization (for training & EDA)

dill – Object serialization

Full list is available in requirements.txt.

👨‍💻 Author

Mohit Kumar
📧mohitrajput27780@gmail.com
