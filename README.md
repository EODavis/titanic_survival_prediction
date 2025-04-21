# titanic_survival_prediction
# 🚢 Titanic Survival Prediction App
This is a simple yet powerful machine learning web app built with Streamlit that predicts whether a passenger would survive the Titanic disaster. It uses a tuned Random Forest Classifier trained on key features like Age, Fare, and Adult Male status.

# 📦 Features
. 🚀 Predicts Titanic survival in real-time
. 🧠 Powered by a trained Random Forest model
. 🧮 Preprocessing with StandardScaler
. 🎯 Clean UI for seamless input
. ⚙️ Easily deployable via Streamlit Cloud

# 📁 Folder Structure:
titanic_app/
│
├── app.py               # Streamlit app script
├── model.pkl            # Trained ML model
├── scaler.pkl           # Fitted scaler for input preprocessing
├── requirements.txt     # App dependencies
└── README.md

# 🛠️ Getting Started
# 1. Clone this repo
_git clone https://github.com/EODavis/titanic_survival_prediction
.git
cd titanic-app_
# 2. Install dependencies
_pip install -r requirements.txt_
# 3. Run the app
_streamlit run app.py_

# 💡 Demo Inputs
. Age: 22
. Fare: 7.25
. Adult Male: Yes / No

# 🧠 Model Info
# . Model: RandomForestClassifier
# . Accuracy: 0.79, F1-score: 0.80
# . Best Params: max_depth=10, min_samples_leaf=2, min_samples_split=5, n_estimators=100

# 📤 Deployment
Ready for deployment on Streamlit Cloud, Render, or HuggingFace Spaces.

# 📬 Feedback
Pull requests welcome. For major changes, please open an issue first.
