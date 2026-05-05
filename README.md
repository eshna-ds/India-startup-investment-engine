India-startup-investment-engine

📌 Overview
This project is an end-to-end data analytics and machine learning system designed to **predict startup success probability** and simulate business decisions such as funding, sector, and location.

It combines:
- 📊 Data Analysis
- 🤖 Machine Learning
- 🔄 Decision Simulation
- 📈 Power BI Dashboard

🎯 Business Problem
Investors and founders often struggle to answer:
- Which startups are likely to succeed?
- How does funding impact success?
- Which sector or location performs better?
This project solves this by building a **decision-support system**.

🧠 Key Features
- Predicts startup success probability using ML
- Simulates different business scenarios
- Provides confidence-based insights (Low / Medium / High)
- Generates outputs for Power BI dashboards
- Handles real-world data issues (missing values, unseen categories)

⚙️ Tech Stack
- Python (Pandas, NumPy, Scikit-learn)
- Machine Learning (Classification Models)
- Power BI (Dashboard & Visualization)
- Pickle (Model Saving)

🔍 Workflow

1. Data Preprocessing
- Cleaned missing values
- Standardized categorical variables
- Removed inconsistent entries

2. Feature Engineering
- Extracted year and month
- Encoded categorical features

3. Model Building
- Trained classification model
- Predicted success probability

4. Decision Simulation
- Generated multiple scenarios
- Evaluated impact of business decisions

5. Output Generation
- Exported predictions to CSV
- Integrated with Power BI

📊 Outputs
- predictions.csv → Model predictions for each startup  
- simulation_results.csv → Simulated scenarios  
- Power BI Dashboard → Interactive decision tool  
