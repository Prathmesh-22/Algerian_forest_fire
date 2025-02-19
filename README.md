FWI Prediction using Flask

This project is deployed on AWS Elastic Beanstalk for easy access and scalability.

Features

User-friendly web interface for inputting data

Predicts FWI based on environmental parameters

Built using Flask and Bootstrap for a modern UI

Simple setup and execution

Deployed on AWS Elastic Beanstalk

Dataset

The model is trained using the Algerian Forest Fire dataset, which contains various meteorological parameters affecting fire weather conditions.

How to Run the Flask App Locally

Follow these steps to set up and run the application locally:

Clone the Repository

git clone <repository_link>
cd <repository_folder>

Install Dependencies

pip install -r requirements.txt

Run the Application

python application.py

Access the Web App
Open your browser and go to the homepage URL (usually http://127.0.0.1:5000).

Make a Prediction
Navigate to the prediction page by appending /predictdata to the URL:

http://127.0.0.1:5000/predictdata

Enter the required data and get the FWI prediction.

Deployment on AWS Elastic Beanstalk

The application is deployed on AWS Elastic Beanstalk, which provides scalability and easy maintenance.

Steps to Deploy:

Install the AWS Elastic Beanstalk CLI:

pip install awsebcli --upgrade --user

Initialize Elastic Beanstalk in your project directory:

eb init -p python-3.x fwi-prediction-app --region <your-aws-region>

Create an environment and deploy the app:

eb create fwi-env

Access the deployed application using the provided AWS Elastic Beanstalk URL.

Technologies Used

Python

Flask

HTML/CSS (Bootstrap)

AWS Elastic Beanstalk

Machine Learning (Scikit-Learn, Pandas, NumPy)




