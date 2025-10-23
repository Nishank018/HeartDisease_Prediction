# ❤️ Heart Disease Prediction App

A user-friendly web application built with **Streamlit** and **scikit-learn** to predict the likelihood of heart disease based on user inputs.

🔗 Live Demo: [nishank018-heartdisease-prediction-app-de6vtz.streamlit.app](https://nishank018-heartdisease-prediction-app-de6vtz.streamlit.app)

---

## 📌 Features

- **Interactive User Interface**: Input personal health metrics to receive instant predictions.
- **Machine Learning Model**: Utilizes a trained model (`KNN_heart.pkl`) to assess heart disease risk.
- **Real-time Feedback**: Immediate results displayed upon submission.

---

## 🧠 How It Works

1. **User Input**: Enter health-related details such as age, cholesterol levels, and blood pressure.
2. **Model Prediction**: The app processes the inputs using a pre-trained machine learning model.
3. **Output**: Displays the likelihood of heart disease based on the input data.

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/HeartDisease_Prediction.git
cd HeartDisea
### 2. Create and Activate Virtual Environment
python3 -m venv .venv
source .venv/bin/activate  # On macOS/Linux
.venv\Scripts\activate     # On Windowsse_Prediction

### 3. Install Dependencies
pip install -r requirements.txt
### 4. Run the Application
streamlit run app.py
Visit http://localhost:8501 in your browser to interact with the app.
📁 Project Structure
HeartDisease_Prediction/
│
├── app.py                # Main Streamlit application
├── KNN_heart.pkl         # Trained machine learning model
├── requirements.txt      # Python dependencies
├── .gitignore            # Git ignore file
└── README.md             # Project documentation
🧪 Model Details
The application uses a K-Nearest Neighbors (KNN) classifier trained on a dataset containing various health parameters. The model predicts the likelihood of heart disease based on the input features.
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
📬 Contact
For any inquiries or feedback, please reach out to ginshank@8076gmail.com.
