# FWI Prediction using Flask

This project is deployed on **AWS Elastic Beanstalk** for easy access and scalability.

## Features

- User-friendly web interface for inputting data
- Predicts FWI based on environmental parameters
- Built using Flask and Bootstrap for a modern UI
- Simple setup and execution
- Deployed on AWS Elastic Beanstalk

## Dataset

The model is trained using the Algerian Forest Fire dataset, which contains various meteorological parameters affecting fire weather conditions.

## How to Run the Flask App Locally

Follow these steps to set up and run the application locally:

1. **Clone the Repository**

   ```bash
   git clone <repository_link>
   cd <repository_folder>
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**

   ```bash
   python application.py
   ```

4. **Access the Web App**
   Open your browser and go to the homepage URL (usually `http://127.0.0.1:5000`).

5. **Make a Prediction**
   Navigate to the prediction page by appending `/predictdata` to the URL:

   ```
   http://127.0.0.1:5000/predictdata
   ```

   Enter the required data and get the FWI prediction.

## Deployment on AWS Elastic Beanstalk

The application is deployed on AWS Elastic Beanstalk, which provides scalability and easy maintenance.

### Steps to Deploy:
1. Install the AWS Elastic Beanstalk CLI:
   ```bash
   pip install awsebcli --upgrade --user
   ```
2. Initialize Elastic Beanstalk in your project directory:
   ```bash
   eb init -p python-3.x fwi-prediction-app --region <your-aws-region>
   ```
3. Create an environment and deploy the app:
   ```bash
   eb create fwi-env
   ```
4. Access the deployed application using the provided AWS Elastic Beanstalk URL.

## Technologies Used

- Python
- Flask
- HTML/CSS (Bootstrap)
- AWS Elastic Beanstalk
- Machine Learning (Scikit-Learn, Pandas, NumPy)



