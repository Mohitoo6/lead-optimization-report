# 📊 Lead Quality Analysis and Optimization

## 📌 Project Overview  
This project focuses on **analyzing and optimizing lead quality trends** based on real-world marketing data. The dataset contains **about 3,000 leads**, each categorized by lead quality indicators. The goal is to **identify key factors affecting lead conversion rates** and **implement strategies to enhance overall lead quality**.

## 🎯 Key Objectives
1. **Analyze lead quality trends over time** – Identify whether lead performance is improving or declining and test statistical significance.
2. **Determine key drivers of lead quality** – Explore how different **ad creatives, lead sources, and audience segments** impact conversion.
3. **Optimize lead generation strategy** – Suggest methods to improve lead quality by **20%** to align with advertiser goals and justify a CPL increase.

## 📁 Dataset Overview
- **LeadCreated (Date)** – The timestamp when the lead was generated.
- **CallStatus (Target Variable)** – Defines lead success/failure categories:
  - ✅ **Good Leads:** Closed, EP Sent, EP Received, EP Confirmed.
  - ❌ **Bad Leads:** Unable to Contact, Invalid Profile, Doesn’t Qualify.
  - ❓ **Unknown Leads:** Not categorized as good or bad.
- **WidgetName** – The ad creative used for lead capture.
- **PublisherCampaignName** – Source of the lead (Online Forms vs. Call Center).
- **AddressScore & PhoneScore** – Validity of lead contact details.
- **Debt Level** – Consumer's declared debt (if available).
- **Referral Domain, AdGroup, Keywords** – Marketing attributes influencing lead quality.

## 🔍 Analysis & Findings
### 1️⃣ **Lead Quality Trends Over Time**
- A **statistically significant decline** in good leads (**correlation: -0.15, p = 0.040**).
- Bad leads **not significantly increasing** (p = 0.73), indicating issues in conversion rather than lead deterioration.

### 2️⃣ **Key Drivers of Lead Quality**
- **Best performing ad creatives:** `CreditSolutions (78.26%)`, `BlueMeter (77.78%)` generate the highest quality leads.
- **Online forms outperform call center leads** by ~5.26% in good lead quality.
- **Debt level data was inconsistent**, requiring further validation.

### 3️⃣ **Recommendations for Improving Lead Quality**
✅ **Focus on high-performing ad creatives** (`CreditSolutions`, `BlueMeter`).  
✅ **Increase investment in online lead generation** over call center-based leads.  
✅ **Stricter lead verification:** Require **AddressScore ≥ 3 & PhoneScore ≥ 3** for higher accuracy.  
✅ **A/B test ad creatives** and optimize landing page messaging.  
✅ **Refine targeting strategy** by identifying top referral sources & keyword impact.

## 🛠️ Technologies Used
- **Python** (Pandas, Seaborn, Matplotlib, SciPy)
- **SQL** (for exploratory data analysis)
- **Excel** (Initial data formatting)
- **Jupyter Notebook** (Data analysis and visualization)

## 📊 Visualizations & Reports
- 📈 **Time-series analysis of lead trends**
- 📊 **Comparison of lead performance by ad creatives**
- 🔍 **Cohort analysis of lead sources**
- 📑 **Statistical tests & correlation analysis**

## 🚀 Future Improvements
🔹 Perform **feature engineering** on lead quality predictors.  
🔹 Apply **machine learning models** for **lead conversion prediction**.  
🔹 Automate **real-time lead quality monitoring** with dashboards.  

## 🤝 Contributing
If you're interested in improving this analysis, feel free to fork the repository and submit pull requests.

## 📩 Contact  
For any questions or collaborations, reach out via **GitHub Issues**.

---

