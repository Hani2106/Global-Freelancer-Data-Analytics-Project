Global Freelancers Workforce Analytics – End-to-End Data Analysis Project
🔍 Project Overview

This project focuses on analyzing the global freelancing workforce across multiple countries, skills, and experience levels.
The objective was to understand trends in freelancer earnings, experience, ratings, client satisfaction, and skill market demand.

The complete pipeline follows:
➡ Raw data → Data Cleaning (Python) → SQL Analysis → EDA & Visualization (Python) → Power BI Dashboard

🗂️ Tech Stack Used
-> Python (Pandas, NumPy, Matplotlib)	Data cleaning and exploratory data analysis
-> SQL	Data querying and business insights
-> Power BI	Interactive dashboard & business reporting
-> Jupyter Notebook	Analysis workflow
-> CSV / JSON	Data sources & storage formats

🧹 Data Cleaning Steps (Python)
The raw dataset contained:
=>Missing values (age, hourly rate, rating, satisfaction)
=>Inconsistent currency formats ($30, USD 50, 40)
=>Mixed data types stored as text
=>Categorical inconsistencies in gender (Male, M, F, Female)

Key transformations:
->Converted hourly_rate_usd to numeric after currency extraction
->Standardized gender values
->Handled missing values using:
->Median (numeric)
->Mode (categorical)
=>Created derived columns:
earnings_category (Low / Medium / High)
experience_level (Beginner / Intermediate / Expert)

🧠 SQL Analysis Performed
=>Queries included:
->Top earning freelance skills globally
->Most in-demand countries and programming skills
->Correlation between experience & rating
->Comparison of active vs inactive freelancers
->Country-wise average hourly earning

The project includes multiple insights queries and view creation inside:
📄 global_freelancers.sql 

📊 Python EDA Highlights
Visualizations were generated using:
Bar charts
Pie charts
Box plots
Distribution plots

Some insights observed:
AI, Web Development & Blockchain are the highest-paying skills
Client satisfaction does not always align with hourly rate
Freelancers with 10+ years of experience dominate high-earning category
USA, Germany & Australia contribute the highest number of freelancers

📌 Power BI Dashboard
The dashboard provides:

🌍 Country-wise freelancer insights

💰 Hourly rate comparison across skills

📈 Relationship between experience, rating & earnings

⭐ Top 15 freelancers by rating

🟢 Active vs inactive workforce distribution

File: Freelancer's.pbix

📎 Key Business Insights

✔ AI & Blockchain freelancers charge the highest average hourly rates
✔ Countries with highest client satisfaction score: Canada, Brazil, Italy
✔ Years of experience is the strongest factor influencing earnings
✔ Inactive freelancers mostly belong to low-earning and low-experience category
✔ UI/UX & Graphic Design have the highest number of entry-level freelancers

🚀 What I Learned

📌 End-to-end data analytics workflow
📌 Working with both SQL and NoSQL formats
📌 Feature engineering and handling inconsistent messy real-world data
📌 Building business-ready dashboards for non-technical stakeholders

🏁 Conclusion

This project helped uncover market dynamics of the global freelance ecosystem and can support:
Hiring platforms
Freelance marketplaces
Career roadmap planning for freelancers

⭐ If you like this project

Don’t forget to star the repository on GitHub and connect with me on LinkedIn 😊

❤️Author: Hani Patel
⭐Linkedin: http://linkedin.com/in/hani-patel-6a9370265
🔗Email: hanipatel0621@gmail.com
