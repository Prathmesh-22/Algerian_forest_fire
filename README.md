# FWI Prediction using Flask

This project is a web application for predicting the Fire Weather Index (FWI) based on various environmental factors such as temperature, humidity, wind speed, and more. The app is built using Flask and provides a simple interface for users to input data and get an FWI prediction.

## Features
- User-friendly web interface for inputting data
- Predicts FWI based on environmental parameters
- Built using Flask and Bootstrap for a modern UI
- Simple setup and execution

## Dataset
The model is trained using the Algerian Forest Fire dataset, which contains various meteorological parameters affecting fire weather conditions.

## How to Run the Flask App
Follow these steps to set up and run the application:

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

## Technologies Used
- Python
- Flask
- HTML/CSS (Bootstrap)
- Machine Learning (Scikit-Learn, Pandas, NumPy)


