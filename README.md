# Heart Health Predictor

Heart Health Predictor is a web application built using Streamlit that helps users assess their risk of developing a heart disease. Users can input various health parameters, and the application uses a machine learning model to provide a prediction.

## Project Structure
- **Development:** Contains Jupyter Notebook (`heart-health-development.ipynb`) for initial development and dataset (`heart.csv`) used for training the model.
- **final_model.p:** Pickle file containing the trained machine learning model.
- **heart.py:** Python script for the Streamlit web application.
- **requirements.txt:** List of Python dependencies required to run the project.

## Data Source: [Kaggle - Heart Health Data](https://www.kaggle.com/datasets/hardikjp7/heart-health-data)
The dataset used in this project is sourced from Kaggle. It includes various health parameters such as age, sex, cholesterol levels, and more, along with a target variable indicating the presence of heart disease.

## How to Clone and Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/hardikjp7/Heart-Health-Predictor.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Heart-Health-Predictor
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit web application:
   ```bash
   streamlit run heart.py
   ```

## About the Project
The Heart Health Predictor app allows users to input their age, gender, cholesterol levels, and other relevant information. Based on this input, the app predicts the user's risk of developing heart disease. The predictions are displayed in a user-friendly interface, with high-risk predictions shown in red and low-risk predictions in green. The app also provides information about how to interpret the results and encourages users to seek medical advice if they have concerns about their heart health.
