# Flight Price Prediction

This repository contains a machine learning project that predicts flight prices using various features such as airline, date of journey, source, destination, departure time, arrival time, duration, total stops, and additional information.

## Project Overview

The project involves the following steps:

1. **Data Preprocessing**: Cleaning and preparing the flight data for model training.
2. **Exploratory Data Analysis (EDA)**: Analyzing the data to gain insights and understand the relationships between features and the target variable (flight price).
3. **Feature Engineering**: Creating new features or transforming existing ones to improve model performance.
4. **Model Training and Evaluation**: Training and evaluating different machine learning models (e.g., Linear Regression, Support Vector Regression, XGBoost, Random Forest) using learning curves to select the best-performing model.
5. **Web Application Development**: Building a user-friendly web application using Flask to serve the trained model and allow users to input flight details for price prediction.
6. **Deployment**: Deploying the Flask application on Render, making it accessible online.

## Usage

### Running Locally

To run the project locally, follow these steps:

1. Clone the repository: git clone https://github.com/your_username/flight-price-prediction.git
cd flight-price-prediction
2. Install the required dependencies: pip install -r requirements.txt
3. Run the Flask application: python app.py
4. Open your web browser and navigate to `http://localhost:5000` to access the web application.

### Using the Web Application

1. Input the required flight details in the provided form fields.
2. Click the "Predict" button to get the predicted flight price.

## Project Structure

- `data/`: Contains the dataset files used for training and evaluation.
- `static/`: Contains CSS files for styling the web application.
- `templates/`: Contains HTML templates for the web application.
- `app.py`: The main Flask application file.
- `forms.py`: Contains the form class for handling user input.
- `model.joblib`: The trained machine learning model saved using joblib.
- `model-training.ipynb`: A Jupyter Notebook containing the code for data preprocessing, EDA, feature engineering, model training, and evaluation.
- `requirements.txt`: A list of required Python packages and dependencies.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
