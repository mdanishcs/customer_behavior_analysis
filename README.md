🧠 Customer Behavior Analysis & Dashboard Project
📌 Overview

This project explores customer purchasing behavior using Python, SQL, and Power BI. The workflow includes data loading, cleaning, exploratory data analysis (EDA), SQL-based insights extraction, and dashboard creation. The goal is to uncover business insights such as revenue trends, customer segmentation, and purchase patterns — ultimately visualized through an interactive Power BI dashboard and summarized in a report and presentation.

🧾 Dataset

Source: Provided customer transaction dataset (CSV file).

Description: Includes customer demographics, purchase details, subscription status, discounts, ratings, and shipping types.

Key Fields:

customer_id, age, gender, purchase_amount,

discount_applied, subscription_status,

shipping_type, item_purchased, category, review_rating, previous_purchases.

🛠 Tools & Technologies
Category	Tools Used
Programming	Python (Pandas, NumPy, Matplotlib, Seaborn)
Database	PostgreSQL
Visualization	Power BI
Reporting	Gamma App (for presentation)
Environment	Jupyter Notebook / VS Code
📊 Project Workflow

Data Loading & Cleaning (Python)

Imported dataset using pandas.

Handled missing values, data type conversions, and duplicates.

Generated descriptive statistics and distribution summaries.

Exploratory Data Analysis (EDA)

Visualized spending patterns, age distribution, and category-wise sales.

Correlated discounts, subscription status, and review ratings with revenue.

Identified high-value customers and purchasing trends.

SQL Analysis (PostgreSQL)

Created a customer table and ran business queries using SQL scripts.

Example insights:

Total revenue by gender.

Average purchase by shipping type.

Top products by review rating.

Customer segmentation (New, Returning, Loyal).

Age-wise revenue contribution.

📄 SQL File: customer_behavior_analysis_query.sql

Dashboard Creation (Power BI)

Built an interactive Customer Behavior Dashboard to visualize:

Sales by demographic segments

Revenue trends and product performance

Customer loyalty and subscription impact
📊 Power BI File: customer_behavior_dashboard.pbix

Reporting & Presentation

Created a concise report summarizing insights and key findings.

Built a Gamma presentation for stakeholder communication.

📈 Key Results & Insights

Male customers generated higher total revenue, but female customers showed higher average purchase per transaction.

Subscribers spent more on average and contributed significantly to total revenue.

Express shipping orders had a slightly higher average spend than standard ones.

Returning customers formed the largest segment, showing strong repeat purchase behavior.

Young adults (18–30) accounted for the largest revenue share.

⚙️ How to Run

Clone the Repository

git clone https://github.com/yourusername/customer-behavior-analysis.git
cd customer-behavior-analysis


Set Up Python Environment

pip install -r requirements.txt


Run the Notebook
Open the Jupyter Notebook and execute step by step:

C_S_B_Analysis.ipynb


Run SQL Queries (PostgreSQL)

Create a database (e.g., customer_db)

Import your dataset as a customer table

Execute the queries from customer_behavior_analysis_query.sql

View Dashboard

Open the .pbix file in Power BI Desktop to explore visuals.

Present Findings

Access the Gamma presentation for storytelling and final insights.

📚 Project Files
File	Description
C_S_B_Analysis.ipynb	Python code for data cleaning and EDA
customer_behavior_analysis_query.sql	SQL queries for business insights
customer_behavior_dashboard.pbix	Power BI dashboard
project_report.pdf (optional)	Final report summarizing insights
presentation.gamma (optional)	Gamma presentation slides
🚀 Future Improvements

Automate data updates using Power BI refresh or ETL scripts.

Expand dashboard with customer retention and churn prediction models.

Integrate with live databases for real-time analytics.

👤 Author

Md Danish
Data Analyst | Business Intelligence Enthusiast
📧 your.email@example.com
 | 🌐 LinkedIn
