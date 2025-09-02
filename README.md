AI-powered web app that predicts late vs. on-time payments from Accounts Receivable (AR) data and recommends dynamic collection strategies.

This project uses a Random Forest classifier trained on synthetic invoice data, with a Streamlit web interface for predictions and strategy recommendations.

🚀 Features

📊 Upload AR data (CSV)

🤖 Predict payment status (On-Time or Late)

📌 Get recommended collection strategies:

✅ Low Risk – Regular Cycle

⚠️ Medium Risk – Standard Follow-Up

🚨 High Risk – Send Early Reminder

⬇️ Download results as a CSV

🗂️ Project Structure
AI-Powered-Cash-Flow-Optimization/
│── app.py              # Streamlit app
│── model.pkl           # Trained ML model
│── requirements.txt    # Dependencies
│── sample_data.csv     # Example AR dataset
│── README.md           # Project documentation

🛠️ Installation & Usage
1️⃣ Clone the repository
git clone https://github.com/YOUR-Siva-CT/AI-Powered-Cash-Flow-Optimization.git
cd AI-Powered-Cash-Flow-Optimization

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the app
streamlit run app.py

📂 Example Input (sample_data.csv)
Customer_ID,Invoice_Amount,Invoice_Month,Due_Month,Days_Past_Due
CUST0001,5000,3,4,0
CUST0002,12000,5,6,10
CUST0003,7500,7,8,25

🌐 Deployment

This app can be deployed on:

Streamlit Cloud

Hugging Face Spaces

📌 Future Improvements

Add industry/region features for better predictions

Integrate with real AR datasets

Add dashboard visualizations
