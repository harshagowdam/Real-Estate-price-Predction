# Real-Estate-price-Predction
Overview
This project predicts the selling price of residential properties based on various features such as location, size, number of bedrooms, and more. The model is trained on historical housing data and deployed via a web app.

🚀 Features
📊 Data preprocessing & cleaning

🧠 Model training using regression algorithms

📈 Evaluation using metrics like RMSE and R²

🌐 Frontend (HTML/CSS) + Flask backend

🧮 Live price prediction based on user input

🛠️ Tech Stack
Layer	Tools Used
Language	Python
ML	Scikit-learn, Pandas, NumPy
Web App	Flask, HTML, CSS, Bootstrap
Visualization	Matplotlib, Seaborn
Deployment (Optional)	Streamlit / Render / Heroku

📂 Project Structure
php
Copy
Edit
real-estate-price-predictor/
│
├── data/                 # Raw dataset (CSV)
├── notebooks/            # EDA and model training notebooks
├── static/               # CSS files
├── templates/            # HTML files for Flask app
├── app.py                # Flask backend
├── model.pkl             # Saved ML model
├── requirements.txt      # Python dependencies
└── README.md             # You're here!
📈 Algorithms Used
Linear Regression ✅

Lasso Regression

Decision Tree (optional)

Random Forest (optional)

🧪 Model Evaluation
R² Score: 0.85 (example)

RMSE: ₹2.1 Lakhs (example)

🔮 How to Use
🚧 Local Setup
Clone the repo:

bash
Copy
Edit
git clone https://github.com/yourusername/real-estate-price-prediction.git
cd real-estate-price-prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask app:

bash
Copy
Edit
python app.py
Open your browser and visit:

arduino
Copy
Edit
http://localhost:5000
📈 Predict Price:
Select location

Enter size, number of bedrooms, bathrooms

Click Predict

See estimated price! 💰

📊 Sample Input/Output
Input	Output (Price ₹)
3 BHK, 1200 sqft, Bangalore	₹ 85,00,000
2 BHK, 950 sqft, Chennai	₹ 42,00,000

👨‍💻 Author
Harsha Gowda M
B.Tech CSE @ DSATM
📫 LinkedIn • GitHub

🌟 Acknowledgements
Kaggle / Housing dataset

Scikit-learn docs

Flask community

Stack Overflow (as always 😎)

📌 Future Improvements
Add more ML models (XGBoost, GradientBoosting)

Enable location autocomplete via Google Maps API

Deploy on Render/Streamlit/Heroku

Add feature importance graphs
