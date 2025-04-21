# Titanic Survival Predictor 🛳️

This Streamlit app uses a tuned RandomForestClassifier to predict survival chances of passengers on the Titanic dataset. It's a fun, interactive way to explore machine learning and real-time predictions.

## 🚀 Features

- Predict survival with user-input data
- Uses top features: Age, Fare, Adult Male
- Optimized with RandomizedSearchCV
- Displays prediction confidence
- Clean UI built with Streamlit

## 📂 Project Structure

├── app.py
# Streamlit app
├── model.pkl
# Trained RandomForestClassifier
├── scaler.pkl
# StandardScaler for input features
├── requirements.txt
# Dependencies


## 📦 Requirements

- Python 3.x
- scikit-learn
- pandas
- streamlit
- joblib

Install them with:

```bash
pip install -r requirements.txt

▶️ How to Run
Clone the repo and run:
streamlit run app.py

🌐 Live Demo (Optional)
If hosted on Streamlit Cloud, drop your app link here!

👤 Author
EODavis – Machine Learning Enthusiast
