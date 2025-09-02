This project uses AI/ML models to predict whether customer invoices will be paid on-time or late and suggests dynamic collection strategies to optimize cash flow.

It is built with:

🐼 Pandas for data handling

🤖 Scikit-learn for model training

🌐 Streamlit for interactive deployment

⚡ Features

Upload Accounts Receivable (AR) CSV data

Predict On-Time vs Late payments

Recommend collection strategies (low, medium, high risk)

Download results as a CSV report

Built on a synthetic dataset for demonstration

🛠️ Installation & Usage
1. Clone this repository
git clone https://github.com/Siva-CT/AI-Powered-Cash-Flow-Optimization.git
cd AI-Powered-Cash-Flow-Optimization

2. Install dependencies
pip install -r requirements.txt

3. Run Streamlit app
streamlit run ai_powered_cash_flow_optimization.py

📂 Repository Structure
├── LICENSE
├── README.md
├── ai_powered_cash_flow_optimization.py   # Streamlit app
├── model.pkl                              # Trained ML model
├── requirements.txt                       # Dependencies
├── synthetic_ar_data.csv                  # Synthetic dataset

📊 Example Input (CSV)
Customer_ID,Industry,Region,Invoice_Amount,Invoice_Month,Due_Month,Days_Past_Due
CUST0001,IT Services,North America,5000,3,4,0
CUST0002,Retail,Europe,12000,5,6,10
CUST0003,Finance,Asia,7500,7,8,25

👨‍💻 Author
https://github.com/Siva-CT

Sivaggami Sundaram CT
🔗 GitHub Profile
