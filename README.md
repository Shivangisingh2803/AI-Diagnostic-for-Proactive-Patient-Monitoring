# AI-Diagnostic-for-Proactive-Patient-Monitoring
A web-based application designed to assist pathologists in making faster and more accurate disease predictions. By integrating machine learning algorithms into an intuitive web interface, the system predicts diseases such as Diabetes, COVID-19, and Migraine. It analyzes patient symptoms and test data to generate instant predictions with confidence scores, thereby supporting pathologists in clinical decision-making.

**Features**
Multi-Disease Prediction: Supports predictions for Diabetes, COVID-19, and Migraine based on patient input.

Real-Time Analysis: Provides immediate risk assessments with associated confidence scores.

User-Friendly Interface: Intuitive web interface for easy data input and result interpretation.

Educational Resources: Offers trimester-specific health recommendations and video resources for enhanced usability.
arXiv

**Technologies Used**
Frontend: HTML, CSS, JavaScript

Backend: Python, Flask

Machine Learning: Scikit-learn (Random Forest, K-Nearest Neighbors)

Data Processing: Pandas, NumPy

Model Deployment: Flask for integrating ML models into the web application

**Project Structure**
|-- Dashboard/
|   |-- diagnosis_dashboard.png         # Screenshot or visual representation of the UI
|
|-- Models/
|   |-- diabetesmodel.py                # Diabetes prediction model using Random Forest
|   |-- covidmodel.py                   # COVID-19 prediction model using KNN
|   |-- migrainemodel.py                # Migraine prediction model using KNN
|   |-- *.pkl                           # Serialized ML models (joblib/pickle)
|
|-- static/
|   |-- style.css                       # CSS for styling the frontend
|
|-- templates/
|   |-- index.html                      # Main HTML page
|
|-- Data and EDA/
|   |-- exploratory_analysis.ipynb      # Data cleaning and EDA notebooks
|   |-- patient_data.csv                # Sample dataset for prediction
|
|-- app.py                              # Main Flask application
|-- requirements.txt                    # Python dependencies
|-- README.md                           # Project overview and instructions

