# AtliQo Bank Credit Card Launch Simulation

## 📌 Project Overview
This project simulates the launch of a credit card for a fictional bank, **AtliQo Bank**, as part of my learning journey in the "Math and Statistics for Data Science" course by Codebasics. It mimics real-world workflows, including data acquisition, exploratory data analysis (EDA), and hypothesis testing, to identify a target market and validate the product's performance.

---

## 🛠️ Problem Statement
AtliQo Bank is a new entrant in India's competitive banking market. The goal is to:
1. Identify the ideal target market for the credit card based on factors like age group, income, and spending behavior.
2. Validate the credit card's performance through a trial campaign using A/B testing.

---

## 🚀 Project Workflow

### **Phase 1: Target Market Identification**
1. **Data Acquisition**:  
   - Sourced customer demographics, credit profiles, and transactional data from a fictional provider ("Data Lelo").  
   - Data size:  
     - Customers: **1,000 records**  
     - Transactions: **500,000 records**  
     - Credit Profiles: **1,004 records**

2. **Data Cleaning & Preprocessing**:
   - Handled missing values in `annual_income` (**50 nulls**) using occupation-wise median imputation.
   - Treated outliers in `age` (20 records) and `annual_income` (< ₹100 replaced with occupation-wise medians).

3. **Exploratory Data Analysis (EDA)**:
   - Age Group Distribution:
     - **18–25**: 26% | Avg. Income: ₹37k | Low credit history.
     - **26–48**: 57% | Avg. Income: ₹145k.
     - **49–65**: 19% | Avg. Income: ₹260k.
   - Top Purchasing Categories for 18–25:
     - Electronics (32%), Fashion & Apparel (28%), Beauty & Personal Care (18%).

4. **Outcome**:
   Finalized the **18–25 age group** as the target market due to their untapped potential in credit card adoption.

---

### **Phase 2: Hypothesis Testing & Campaign Validation**
1. **A/B Testing Setup**:
   - Sample size determination using statistical power analysis:
     - Effect size = 0.4 → Sample size = 40 clients per group.
   - Created control and test groups with 40 participants each.

2. **Campaign Execution**:
   - Ran a two-month trial campaign targeting the test group with the new credit card.
   - Key Metric: Average transaction amount.

3. **Results Analysis**:
   - Control Group Avg. Transaction Amount: ₹221.18 (Std Dev = ₹21.36).  
   - Test Group Avg. Transaction Amount: ₹235.98 (Std Dev = ₹36.66).  
   - Z-test Results:
     - Z-score = 2.75 | p-value = 0.003 → Statistically significant improvement.

4. **Outcome**:
   The campaign demonstrated success in increasing transaction amounts among the target audience.

---

## 📊 Key Concepts Applied
- **Exploratory Data Analysis (EDA)**: Pandas, Seaborn, Matplotlib.
- **Statistical Methods**:
  - Central Limit Theorem
  - Hypothesis Testing (Z-tests)
  - Confidence Intervals
- **Agile Development**: Managed tasks using Kanban methodology in Jira.

---

## 📈 Results Summary
- Identified an untapped target market (**18–25 age group**) with high growth potential.
- Achieved a statistically significant improvement in transaction amounts during the trial campaign.
- Demonstrated proficiency in handling large datasets (~500k transactions) and applying statistical techniques to solve business problems.

---

## 💡 Takeaways
This project enhanced my skills in:
1. Cleaning and preprocessing real-world datasets.
2. Applying statistical techniques for decision-making.
3. Communicating actionable insights effectively to stakeholders.

---

## ⚠️ Note
This is a fictional project designed to simulate real-world scenarios in data science workflows.

---

## 🔗 Let's Connect!
Feel free to reach out if you'd like to discuss this project or collaborate on data-driven initiatives! 😊
