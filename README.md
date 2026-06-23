 House Price Prediction Web App

Overview

The House Price Prediction Web App is a Machine Learning-based application that predicts the estimated price of a house based on various property features. The project uses a trained machine learning model and a Flask web application to provide real-time house price predictions through a simple and user-friendly interface.

Features

- Predict house prices instantly
- User-friendly web interface
- Machine Learning model integration
- Real-time prediction results
- Dynamic form inputs
- Flask-based backend

Technologies Used

- Python
- Flask
- Pandas
- NumPy
- Scikit-Learn
- HTML
- CSS

Project Structure

House-Price-Prediction-WebApp/

├── app.py

├── model_svc.pkl

├── processed_data.csv

├── requirements.txt

├── templates/

│   └── index.html

├── static/

│   └── style.css

├── prompt.txt

└── steps.txt

Input Features

The model predicts house prices using features such as:

- Number of Bedrooms
- Number of Bathrooms
- Floors
- Waterfront
- View
- Condition
- Year Built
- Year Renovated
- Street
- City
- State ZIP
- Living Area (sq ft)
- Lot Area (sq ft)
- Above Ground Area (sq ft)
- Basement Area (sq ft)

Installation

Clone the Repository

git clone <repository-link>

cd House-Price-Prediction-WebApp

Install Dependencies

pip install -r requirements.txt

Run the Application

python app.py

Machine Learning Model

The application uses a trained Scikit-Learn regression model saved as "model_svc.pkl". The model analyzes housing features and predicts an estimated market price for the property.

Future Improvements

- Improve prediction accuracy
- Add data visualization dashboard
- Deploy on cloud platforms
- Add advanced property analytics
- Support multiple prediction models

Author

Aima Eirj

AI Student | Machine Learning Enthusiast

License

This project is developed for educational and learning purposes.
