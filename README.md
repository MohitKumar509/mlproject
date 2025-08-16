This repository contains an end-to-end implementation of a machine learning workflow, packaged as a Flask web application. It covers the complete cycle — from data preprocessing and model training to deployment through a simple web interface.
🔍 Overview
•	Data Processing: Handled with pandas, numpy, and scikit-learn.
•	Model Training: Includes tree-based models like XGBoost and CatBoost, along with evaluation pipelines.
•	Pipeline Structure: Modular code for data ingestion, transformation, and prediction.
•	Web Application: Flask interface for user input and real-time predictions.
•	Deployment Ready: Packaged with setup.py and dependency management.
________________________________________
📂 Project Structure
├── app.py                
├── requirements.txt     
├── setup.py              
├── .gitignore          
├── src/                  
│   ├── pipeline/
│   │   ├── predict_pipeline.py
│   │   └── train_pipeline.py
│   ├── components/       
│   └── ...
├── templates/            
└── README.md             
________________________________________
⚙️ Installation
Follow the steps below to set up the project locally:
1.	Clone the repository
2.	git clone https://github.com/your-username/mlproject.git
3.	cd mlproject
4.	Create a virtual environment (recommended)
5.	python -m venv venv
Activate it:
o	Linux/MacOS:
o	source venv/bin/activate
o	Windows:
o	venv\Scripts\activate
6.	Install dependencies
7.	pip install -r requirements.txt
8.	Install the package in editable mode
9.	pip install -e .
________________________________________
▶️ Running the Application
Start the Flask app:
python app.py
The application will be available at:
http://127.0.0.1:5000/
From here, you can:
•	Access the home page (/)
•	Enter input values in the form (/predictdata)
•	View the predicted result on the page
________________________________________
📦 Requirements
Core libraries used in this project:
•	Flask – Web framework
•	pandas, numpy – Data handling
•	scikit-learn – Preprocessing and ML utilities
•	xgboost, catboost – ML models
•	matplotlib, seaborn – Visualization (for training & EDA)
•	dill – Object serialization
Full list is available in requirements.txt.
________________________________________
👨‍💻 Author
Mohit Kumar
📧 mohitrajput27780@gmail.com

