# 🌱 SmaCro – Smart Crop & Disease Prediction System

SmaCro is a Machine Learning–based web application that helps farmers and agricultural researchers predict the most suitable crop and potential plant diseases using soil and climatic parameters. By analyzing **Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, and pH**, the system suggests the best crops and warns about possible diseases, supporting **data-driven farming decisions**.

---

## 🚀 Features
- Predicts the best crop for given soil parameters.
- Identifies potential crop diseases.
- Built using **Random Forest / Extra Trees classifiers** for high accuracy.
- Web frontend with a simple soil input form.
- Backend powered by **Flask API**.
- Models trained on extended datasets including soil nutrients & disease info.

---

## 🛠️ Tech Stack
- **Python** (pandas, scikit-learn, joblib, matplotlib)
- **Flask** (backend REST API)
- **HTML, CSS, JavaScript** (frontend interface)
- **Joblib** (for saving & loading trained ML models)

---

## 📂 Project Structure
├── app.py # Flask backend

├── sample.py # Training script for crop model

├── train_with_disease.py # Training script for crop + disease model

├── predict_crop_disease.py # Script for testing predictions

├── Updated_Crop_Recommendation.csv

├── Updated_Crop_Recommendation_with_Disease_Info.csv

├── templates/ # HTML frontend

├── static/ # CSS, JS, images

└── README.md

---

## ⚡ How to Run
1. Clone this repository:
   
   git clone https://github.com/your-username/smacro.git
   cd smacro
   
2.Install dependencies:

Flask==2.3.2
flask-cors==4.0.0
pandas==2.1.4
scikit-learn==1.3.2
numpy==1.26.4
matplotlib==3.8.2
joblib==1.3.2

3.Train the models :

python sample.py
python train_with_disease.py
Run the Flask app:
python app.py
Open the frontend:
Go to http://127.0.0.1:5000 in your browser.

📊 Example Predictions
Input: N=70, P=60, K=80, Temp=25°C, Humidity=70%, pH=6.5

Output:
Predicted Crop → Sugarcane
Predicted Disease → Leaf Scorch

📖 References
Brown, K. (2022), Machine Learning Applications in Precision Agriculture
Li, J., & Zhao, Y. (2020), Random Forest for Agricultural Decision-Making
Ministry of Agriculture, Govt. of India (2023), Soil Health Card Data
Das, P. (2020), Role of AI in Predictive Agriculture
Gupta, R. (2021), Impact of pH on Crop Productivity
Open Weather Data APIs (2023)

🏆 Advantages
Provides accurate, reliable crop recommendations.
Helps prevent crop loss by warning about potential diseases.
Bridges the gap between AI research and real-world farming.
Can be extended with real-time weather APIs for dynamic predictions.

