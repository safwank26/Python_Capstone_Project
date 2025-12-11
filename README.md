# Python_Capstone_Project
🎬 Netflix Streaming Platform Users – Exploratory Data Analysis (EDA)

📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on a streaming platform user dataset to uncover insights related to user behavior, subscription patterns, activity levels, device preferences, and spending trends.
The analysis is entirely done using Python and focuses on extracting business-relevant insights through visualization and statistical summaries.

🗂 Dataset Features: user_id, email, first_name, last_name,	age,	gender,	country,	state_province,	city,	subscription_plansubscription_start_date, is_active,	monthly_spend,	primary_device,	household_size,	created_at

🛠️ Tools & Libraries Used
Python
Pandas – data manipulation
NumPy – numerical operations
Matplotlib – data visualization
Seaborn (if applicable) – enhanced visuals
Jupyter Notebook

🔍 Key Analyses Performed

1️⃣ Data Cleaning & Preparation
> Handled missing values
> Converted date columns into datetime format
> Created derived features such as:
* Subscription duration in months
* active days
* Age groups
* Signup month

2️⃣ Univariate Analysis
* Subscribers Age Group Distribution
* Most Common Subscription Plan
* Device Type Usage Frequency
* House Hold Distribution
* Top 5 States by User Count
* User Growth Over time

3️⃣ Bivariate Analysis
* Age Group vs Monthly Spend
* Average Monthly Spend by State
* Revenue per Subscription Plans
* Subscription PLan by Gender
* User Status by Subscription Plan
* Age Group vs Subscription Plan Preference
* User Activity Trend Over Time

4️⃣ Multivariate Analysis
* User Count by Age Group and Subscription plan
* Average Monthly Spend by Age Group and Subscription Plan
* Average Monthly Spend by Country and Subscription Plan
* Correlation Between Age, Monthly Spend and House Hold Size

5️⃣ Key EDA Findings & Recommendations
