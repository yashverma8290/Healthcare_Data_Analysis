# 🚀 Healthcare Data Analysis (EDA) 🏥

📌 Overview
🔹 This project focuses on Exploratory Data Analysis (EDA) of a healthcare dataset, aiming to derive meaningful insights through data cleaning, exploration, and visualization.
🔹 The dataset contains crucial information about patient demographics, hospital admissions, medical conditions, and healthcare service costs.
🔹 By analyzing this dataset, we aim to uncover patterns, trends, and potential anomalies that could assist in healthcare decision-making.

# 📊 Dataset Description
📝 The dataset includes multiple attributes that define patient profiles, admission details, medical histories, and associated healthcare costs. Below are some key characteristics of the dataset:

📌 Key Attributes:

✅ Patient Age: Ranges from 13 to 85 years.
✅ Billing Amount: The maximum recorded billing amount is ₹52,764, while the minimum is ₹-2008.49 (likely due to insurance adjustments, refunds, or claim reversals).
✅ Medical Conditions: Various diseases, diagnoses, and treatments are recorded, allowing for detailed medical analysis.
✅ Admission Details: Information regarding hospital admissions, discharge statuses, and duration of stay.
✅ Insurance & Payment: Coverage details that may impact overall patient billing and financial burden.


# ------------🔍 Steps Performed in This Project --------------


# 📌 1️⃣ Data Cleaning & Preprocessing

✨ Before any meaningful analysis, it is critical to clean the dataset:
🛠 Checking for missing values: Identified columns with missing data and handled them using appropriate imputation techniques (e.g., mean, median, or mode imputation).
🗑 Removing duplicate records: Detected duplicate entries and eliminated them to maintain dataset integrity.
⚠ Handling incorrect values: Negative billing amounts were investigated, and erroneous entries were either corrected or removed.
🔄 Data type conversions: Ensured that numerical and categorical columns were properly formatted for seamless analysis.



# 📌 2️⃣ Exploratory Data Analysis (EDA)

📊 Once the dataset was cleaned, we performed an in-depth exploration:
📌 Descriptive statistics: Used .describe() to summarize numerical features, including mean, standard deviation, and percentiles.
📌 Categorical data analysis: Examined the distribution of non-numerical attributes such as disease types, admission sources, and payment modes.
📌 Correlation analysis: Measured the relationships between different medical and financial factors to uncover hidden patterns.



# 📌 3️⃣ Data Visualization

📉 We used Matplotlib and Seaborn to create insightful visualizations:
📊 Histograms: Analyzed the distribution of patient ages, billing amounts, and lengths of hospital stay.
📈 Box plots: Identified outliers in medical expenses and length of stay.
📌 Scatter plots: Examined relationships between age, disease severity, and hospital charges.
🔥 Heatmaps: Displayed correlation matrices to identify strongly related variables.
📊 Bar charts: Visualized patient distribution based on disease type, gender, and insurance coverage.



# 📌 4️⃣ Key Findings & Insights

🔎 Through EDA, we uncovered several significant insights:
💰 Billing variations: Higher medical costs were observed in older patients and those with chronic conditions.
🗓 Seasonal trends: Certain diseases showed an increase in hospitalization rates during specific times of the year.
📜 Insurance impact: Patients with insurance had significantly different billing trends compared to uninsured individuals.
💉 Common medical conditions: The most frequent diagnoses were related to cardiovascular and respiratory diseases.
🚑 Hospital readmission rates: Identified trends in patient readmissions, which can help improve hospital efficiency.

# ---------------🛠 Technologies & Tools Used ------------------ 

# 🖥 Python Libraries:

🐼 pandas (for data manipulation and cleaning)
🔢 numpy (for numerical operations)
📊 matplotlib & seaborn (for visualization)


# 🖥 Development Tools:
📝 Jupyter Notebook (for interactive analysis)
🔗 Git & GitHub (for version control and collaboration)


# 📥 How to Use This Project

💻 Follow these steps to explore this project on your local system:
1️⃣ Clone the repository: git clone https://github.com/yashverma8290/Healthcare_Data_Analysis.git
2️⃣ Install the required libraries: pip install pandas numpy matplotlib seaborn
3️⃣ Open the Jupyter Notebook: jupyter notebook Healthcare_data_analysis_Project.ipynb
4️⃣ Run the notebook cells step by step to visualize and analyze the dataset.



# 🚀 Future Enhancements

🔮 Planned future improvements:
🤖 Machine Learning Models: Implement classification and regression models to predict patient outcomes or hospital readmissions.
📊 Advanced Statistical Analysis: Apply hypothesis testing and inferential statistics to validate findings.
📈 Dashboard Creation: Use Power BI or Tableau to create interactive dashboards for real-time healthcare data monitoring.
📂 Larger Dataset Integration: Merge with real-world healthcare datasets to improve generalizability.

# 🏁 Conclusion

✨ This project provides a detailed and structured analysis of a healthcare dataset, focusing on data quality, exploratory insights, and visualization techniques.
✨ By understanding patient demographics, billing patterns, and common medical conditions, we can contribute towards better decision-making in healthcare management.
⭐ Support

💡 If you found this project helpful, please ⭐ star this repository!

✍ Author
- YASH VERMA
