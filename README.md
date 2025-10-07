Car Price Prediction Web App

🚗 Predict the selling price of used cars with ease!

This is a Car Price Prediction Web App built using Python, XGBoost, and Streamlit. Users can input car details like year, mileage, fuel type, and more to get an instant prediction of the selling price.

🔹 Features

Predict selling price of used cars based on multiple features.

User-friendly web interface built with Streamlit.

Machine learning model powered by XGBoost.

Real-time predictions with minimal input.

🔹 Demo

Check out the live app here: https://car-price-prediction-project-haritha.streamlit.app/

🔹 Installation & Setup

Clone the repository

git clone https://github.com/<your-username>/car-price-prediction-project.git
cd car-price-prediction-project


Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


Install dependencies

pip install -r requirements.txt


Run the app

streamlit run app.py

🔹 Project Structure
Car-Price-Prediction-Project/
│
├── app.py            # Main Streamlit app
├── model.pkl         # Trained XGBoost model
├── requirements.txt  # Project dependencies
├── README.md         # Project documentation
└── data/             # (Optional) dataset folder

🔹 Technologies Used

Python – Core programming language

XGBoost – Machine learning model for regression

Streamlit – Web app framework

Pandas & NumPy – Data processing

🔹 How it Works

User enters car features (year, mileage, fuel type, etc.) in the app.

The app processes the input and passes it to the trained XGBoost model.

The model predicts the selling price and displays it instantly.

🔹 Future Improvements

Add visualization of car price trends.

Include more features like brand, location, or engine type for higher accuracy.

Deploy using Docker for consistent environment.

🔹 Feedback

I’d love your feedback on this project! Try it here: Car Price Prediction Web App

🔹 License

This project is open source and free to use.
