## Project Overview
HealthyLife Clinics is a chain of outpatient healthcare facilities dedicated to enhancing patient outcomes through personalized care, efficient treatment plans, and preventive healthcare initiatives. With a growing patient base, the organization generates significant amounts of data on patient demographics, medical conditions, treatment outcomes, service delivery, and patient satisfaction—data that has been previously underutilized.

This project thoroughly analyzes and synthesizes this information to uncover key trends and operational insights that will help HealthyLife Clinics optimize patient care, streamline operations, and improve overall healthcare efficiency. By leveraging data analytics, this study provides actionable recommendations to enhance clinical decision-making and resource management, ultimately supporting HealthyLife Clinics’ mission of delivering high-quality, patient-centered care

## Business Problemm and Key Question
1. What are the most common medical conditions treated?
2. Are there any noticeable trends in patient demographics (age, gender, 
location)?
3. How effective are treatments based on patient outcomes?
4. What is the average duration and cost of treatments for different 
conditions?
5. Are there seasonal patterns in patient visits or conditions?
6. How can clinic operations be optimized to enhance patient experience and 
outcomes?

## Dataset Overview
Size & Scope: 5,000 records, 15 columns.
Key Data Fields:
Patient ID, Age, Gender, Location
Visit Date, Medical Condition, Treatment Type
Treatment Duration (Days), Treatment Cost, Outcome
Follow-up Required, Medication Prescribed, Insurance Coverage
Doctor's Specialty, Patient Satisfaction </br>
![Model](https://github.com/Bolajie/Project_1/blob/main/Screenshot%202025-02-03%20200215.png)

## Tools and Technique Used
**Excel:** Data cleaning, pivot tables, Power Pivot, Data Modeling, Data Classification,<br>trend analysis, Dashboad Creation and Data Visualization visualizations. </br>
- **Description:** In this project, I analyzed healthcare data to uncover patterns in common medical conditions, demographic insights, treatment effectiveness, and seasonal trends in patient visits. 
- **Key Insights:**
  - Anxiety is the most frequently treated condition, followed by Flu and Hypertension.
  - Seniors are more likely to experience chronic conditions, while adults show higher rates of anxiety and diabetes.
  - Therapy is the most effective treatment for Anxiety, whereas Surgery has mixed outcomes for various conditions.
  - Autumn sees the highest patient visits, peaking in September 2024.
- **Demo Overview:**
  I built this project to explore healthcare data trends and identify key insights that could support better decision-making in patient care. Using SQL, I cleaned and structured the dataset, and with Power BI and Tableau, I visualized trends in patient demographics, treatment effectiveness, and cost distribution. My analysis highlights how different age groups experience medical conditions and how treatment methods vary in effectiveness. This project demonstrates my ability to extract meaningful insights from healthcare data and present them in an accessible way.

## 📊 Insight: Medical Condition Analysis Report
### 1️⃣ Most Common Medical Conditions
- **The most common condition treated is Anxiety, followed by Flu and Hypertension.**

### 2️⃣ Demographic Insights
#### 📌 Age Distribution
- Seniors experience the highest prevalence of chronic conditions such as back pain, hypertension, arthritis, and flu.
- Adults are more affected by anxiety, asthma, and diabetes.
- Young adults consistently show the lowest prevalence across conditions.

#### 📌 Gender Distribution
- **Anxiety:** More common in men (37%) with 218 cases, followed by women (32%) with 186 cases, and other genders (31%) with 180 cases.
- **Arthritis:** More common in other genders (35%) with 197 cases, followed by women (33%) with 186 cases, and men (32%) with 175 cases.
- **Asthma:** Most common in women (35%) with 178 cases, followed by other genders (34%) with 176 cases, and men (31%) with 158 cases.
- **Back Pain:** More common in women (37%) with 207 cases, followed by men (33%) with 181 cases, and other genders (30%) with 169 cases.
- **COVID-19:** Highest among women (36%) with 206 cases, followed by men (33%) with 188 cases, and other genders (31%) with 178 cases.
- **Diabetes:** More common in men (35%) with 191 cases, followed by women (34%) with 187 cases, and other genders (31%) with 174 cases.
- **Flu:** Most common in men (35%) with 200 cases, followed by other genders (33%) with 190 cases, and women (32%) with 187 cases.
- **Hypertension:** Equally prevalent in men and women (34%) with 194 and 192 cases, respectively, while other genders account for 32% with 185 cases.

### 3️⃣ Location-Based Trends
- Most conditions have an average of **2 cases per location.**
- **Jamesport** has the highest number of anxiety cases (**3**).
- **West David** has the highest number of back pain cases (**3**).
- **Michaelview** has the highest number of flu cases (**3**).
- **West Michael** has the highest number of asthma cases (**3**).

### 4️⃣ Treatment Effectiveness by Condition
- **Anxiety:** Therapy (40% improvement), Surgery (34.6% improvement but 37% worsened).
- **Arthritis:** Therapy (36.5% improvement), Counseling, Medication, and Surgery have less than 28.3% improvement.
- **Asthma:** Therapy (~40% improvement), followed by Physical Therapy and Lifestyle Changes. Surgery has the worst results (38.5% worsening).
- **Back Pain:** Surgery (38.9% improvement) is most effective, but Therapy and Counseling have the highest worsening rate (37.1%).
- **COVID-19:** Physical Therapy, Medication, Lifestyle Change, and Counseling are most effective, but Therapy has the highest worsening rate (41%).
- **Diabetes:** Medication and Lifestyle Changes (37.2% improvement). Physical Therapy shows a balanced but slightly higher rate of no improvement.
- **Flu:** Surgery (40.2% improvement), followed by Therapy (39.8%). Medication and Counseling are least effective with 40%–43.9% worsening.
- **Hypertension:** Counseling (38.6% improvement), followed by Lifestyle Changes. Therapy and Surgery show the worst outcomes, with over 40% worsening.

### 5️⃣ Treatment Cost Analysis
- The overall average treatment cost is **$2,566**.
- **Hypertension** has the highest average treatment cost (**$2,631**), followed by **Diabetes** (**$2,610**) and **COVID-19** (**$2,609**).
- **Depression** has the lowest average treatment cost at **$2,477**.

### 6️⃣ Seasonal Trends in Patient Visits
- **Autumn:** Peak in **September (471 visits)**, decline in **October (426)** and **November (425)**.
- **Winter:** Highest in **January (436 visits)**, then **February (402)**, and a sharp drop in **December (270)**.
- **Spring:** Fluctuates, with **May (456 visits)** being the busiest.
- **Summer:** **August (434 visits)** leads, while **July (398 visits)** sees the lowest visits.

### 7️⃣ Identification of Bottlenecks in Clinic Operations
- **High Rate of No Improvement & Worsening Cases:** Solution: Personalized treatment plans, regular reassessments, and data-driven adjustments.
- **Cost Barriers:** Solution: Introduce cost-effective alternatives and better insurance support.
- **Seasonal Patient Overload:** Solution: Better staffing, telemedicine, and promoting preventive care.
## ✅ Recommendations
1. **Optimize Treatment Strategies** by prioritizing Therapy-based interventions and reducing ineffective treatments.
2. **Reduce Cost Barriers** through affordable treatment plans, better insurance support, and prioritizing cost-effective solutions.
3. **Improve Clinic Efficiency** by increasing staffing in peak seasons, expanding telemedicine services, and launching preventive care initiatives.
4. **Enhance Data-Driven Decision-Making** with predictive analytics and real-time dashboards to monitor patient trends and outcomes.

## Dashboard and Analysis
![](https://github.com/Bolajie/Project_1/blob/main/Screenshot%202025-02-13%20022854.png) </br>
![](https://github.com/Bolajie/Project_1/blob/main/pivot%201.png)![](https://github.com/Bolajie/Project_1/blob/main/pivot%202.png)
