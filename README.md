# IPL Win Predictor

This is a machine learning project that predicts the probability of an IPL team winning a match during the second innings. It is built with a Logistic Regression model and deployed as an interactive web application using **Streamlit**.

## Features
- Real-time probability prediction for both batting and bowling teams.
- Uses `scikit-learn` to process historical IPL data.
- User-friendly web interface.

## How to Run Locally

1. Make sure Python is installed on your computer.
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
4. A browser window will open automatically with the web app running at `http://localhost:8501`.

## Deployment
This project is configured perfectly to be deployed on **Streamlit Community Cloud** (`share.streamlit.io`). 

## Files Included
- `app.py`: The Streamlit web application script.
- `IPL_Prediction_Model.ipynb`: The Jupyter Notebook used for data exploration, preprocessing, and model training.
- `pipe.pkl`: The trained machine learning pipeline exported via Pickle.
- `matches.csv` & `deliveries.csv`: The raw dataset used for model training.
- `requirements.txt`: List of dependencies needed to run the project.
