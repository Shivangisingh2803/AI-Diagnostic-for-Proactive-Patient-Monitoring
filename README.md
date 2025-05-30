# AI-Diagnostic-for-Proactive-Patient-Monitoring

**📂 Project Structure**<br>
**|-- Models/**<br>
|   |-- diabetesmodel.py                 # Diabetes prediction model using Random Forest<br>
|   |-- covidmodel.py                    # COVID-19 prediction model using KNN<br>
|   |-- migrainemodel.py                 # Migraine prediction model using KNN<br>
|   |-- *.pkl                            # Serialized ML models (joblib/pickle)<br>
|
**|-- static/**<br>
|   |-- home.css                         # CSS for styling the home page<br>
|   |-- aboutus.css                      # CSS for styling the about us page<br>
|   |-- vitality monitor.css             # CSS for styling the vitality monitor page<br>
|   |-- diabetes predict.css             # CSS for styling the diabetes prediction page<br>
|   |-- covid predict.css                # CSS for styling the covid prediction page<br>
|   |-- migraine predict.css             # CSS for styling the migraine prediction page<br>

|
**|-- templates/**<br>
|   |-- index.html                       # Home HTML page<br>
|   |-- vitality monitor.html            # vitality monitor HTML page<br>
|   |-- about us.html                    # about us HTML page<br>
|   |-- icons.html                       # icons HTML page<br>

|
**|-- Data and EDA/**<br>
|   |-- diabetes.csv                      # raw diabetes csv file<br>
|   |-- covid.csv                         # raw covid csv file<br>
|   |-- migraine.csv                      # raw migraine csv file<br>
|   |-- diabetes_cleaned.csv              # cleaned diabetes csv file<br>
|   |-- covid_cleaned.csv                 # cleaned covid csv file<br>
|   |-- migraine_cleaned.csv              # cleaned migraine csv file<br>
|   |-- diabetes_eda.py                   # Data cleaning and EDA notebooks for diabetes<br>
|   |-- covid_eda.py                      # Data cleaning and EDA notebooks for covid<br>
|   |-- migraine_eda.py                   # Data cleaning and EDA notebooks for migraine<br>
|
|-- app.py                                      # Main Flask application<br>
|-- covidmodel.py                               # covid ml model file<br>
|-- diabetesmodel.py                               # diabetes ml model file<br>
|-- migrainemoddel.py                               # Migraine ml model file<br>

|-- README.md                            # Project overview and instructions<br>


**Overview**
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
