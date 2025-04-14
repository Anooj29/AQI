
🌀 Air Quality Index (AQI) Prediction
This project predicts the Air Quality Index (AQI) using machine learning, and provides a simple interactive interface with Streamlit. It leverages pollution data from Indian cities to train a regression model and predict AQI values.

📁 Repository Structure
bash
Copy
Edit
ShubhamSPawde/
├── AQI.ipynb          # Jupyter notebook for EDA and model training
├── app.py             # Streamlit web app
├── aqi.pkl            # Trained machine learning model
├── city_day.csv       # Dataset (pollution data from Indian cities)
├── requirements.txt   # List of dependencies
└── README.md          # Project documentation
🚀 How to Run the Project
Clone the repository

bash
Copy
Edit
git clone https://github.com/ShubhamSPawde/AQI-Prediction.git
cd AQI-Prediction
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app

bash
Copy
Edit
streamlit run app.py
📊 Dataset
File: city_day.csv

Source: Central Pollution Control Board (via Kaggle or MOEFCC)

Features: PM2.5, PM10, NO2, CO, SO2, O3, Benzene, Toluene, etc.

Target: AQI

🔍 Model
Trained in AQI.ipynb using regression

Model is saved as aqi.pkl

Built using Scikit-learn

🧪 Example
PM2.5	PM10	NO2	CO	Predicted AQI
134	205	42	0.9	182
🛠 Built With
Python 3.12

Pandas, NumPy

Scikit-learn

Streamlit

Matplotlib / Seaborn (for EDA)

📌 To Do
 Improve model accuracy

 Add classification of AQI category

 Display city-wise AQI trends

📃 License
This project is open-source and available under the MIT License.
