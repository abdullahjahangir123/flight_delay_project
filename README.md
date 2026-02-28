# flight_delay_project
End-to-End Machine Learning project that predicts flight delays using Random Forest and Streamlit web application.
✈️ Flight Delay Prediction System




📌 Project Overview
This is an End-to-End Machine Learning Project that predicts whether a flight will be delayed by more than 15 minutes.

The project demonstrates the complete ML workflow:

📊 Data preprocessing

🧠 Model training

📈 Model evaluation

💾 Model serialization

🌐 Web application development

🚀 Deployment-ready structure

🎯 Objective
The goal of this system is to predict:

Will a flight be delayed by more than 15 minutes?

📥 Input Features:
Distance (miles)

Day of Week

📤 Output:
Flight Delayed 🚨

Flight On Time ✅

Delay Probability (%)

🛠️ Tech Stack
Category	Tools Used
Programming	Python
Data Processing	Pandas, NumPy
Machine Learning	Scikit-learn
Model Saving	Joblib
Web App	Streamlit
🧠 Machine Learning Model
Algorithm: Random Forest Classifier

Target Variable: is_delayed

Train/Test Split: 80/20

Evaluation Metrics:

Accuracy

Classification Report

Model saved as: model.pkl

📂 Project Structure
flight_delay_project/
│
├── train_model.py        # Model training script
├── model.pkl             # Trained ML model
├── app.py                # Streamlit web application
├── requirements.txt
└── README.md
⚙️ Installation Guide
1️⃣ Clone Repository
git clone https://github.com/your-username/flight_delay_project.git
cd flight_delay_project
2️⃣ Install Dependencies
pip install -r requirements.txt
Or manually:

pip install pandas numpy scikit-learn streamlit joblib
3️⃣ Train Model (Optional)
python train_model.py
4️⃣ Run Web Application
streamlit run app.py
The app will open automatically in your browser.

🌐 Web Application Features
Clean and interactive UI

Real-time prediction

Probability score display

Lightweight & fast performance

📊 Sample Prediction
Distance	Day	Prediction
800	Monday	Delayed 🚨
300	Sunday	On Time ✅
🚀 Future Improvements
Add Airline feature encoding

Hyperparameter tuning

Add more flight features

Add model performance dashboard

Deploy on AWS / Streamlit Cloud

Add Docker support

💡 Learning Outcomes
This project demonstrates:

Practical Machine Learning implementation

Model serialization & deployment

Web app integration with ML

Real-world dataset handling

👨‍💻 Author
Abdullah Khattanaking
Machine Learning Enthusiast 🚀

⭐ If You Like This Project
Give it a ⭐ on GitHub!
