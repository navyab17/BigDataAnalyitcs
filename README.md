# 🎓 College Placement Analytics using PySpark

This repository contains a PySpark-based analytics project exploring patterns and insights from a **College Placement Dataset**. It demonstrates data cleaning, descriptive analysis, and insight extraction using Spark DataFrames, along with recommendations for students and institutions.

---

## 📁 Contents

1. **Data Cleaning & Exploration**  
   - Load and inspect CSV files using PySpark  
   - Join student and placement datasets  
   - Handle missing and inconsistent values  

2. **Descriptive Analytics**  
   - Total students, placed students, and recruiting companies  
   - Department-wise placement counts  
   - Package and year-wise placement trends  

3. **Relationship Analysis**  
   - Correlation between academic performance and placement outcomes  
   - Department-wise and company-wise comparisons  
   - Package distribution and recruiter preferences  

4. **Insights & Recommendations**  
   - Top-performing departments  
   - Salary trends and company patterns  
   - Strategic recommendations for students and colleges  

5. **Predictive Analytics (Future Work)**  
   - Model placement likelihood using MLlib  
   - Clustering to identify high-offer student profiles  

---

## 🧩 Dataset Description

**Source:** College Placement Dataset (CSV format)

**Columns include:**
- `studentId` — unique student identifier  
- `name`, `department`, `gender` — student attributes  
- `company`, `package`, `placementStatus` — placement details  
- `year`, `college`, `location` — metadata  

**Data Quality:**
- Schema correctly inferred  
- Consistent datatypes (`ID` categorical, `package` numeric, etc.)  
- Some missing values for unplaced students  

---

## 💡 Key Insights

| Category | Summary |
|-----------|----------|
| **Department Performance** | Computer Science leads with ~96% placement rate; ECE shows solid performance; Mechanical/Civil moderate. |
| **Company Trends** | Infosys, TCS, and Wipro recruit in bulk; Amazon, Google, and Microsoft offer top packages. |
| **Package Distribution** | Most offers fall in ₹3.5–₹6 LPA; top packages exceed ₹18 LPA, mainly in tech roles. |

---

## 🧠 Recommendations

### For Students:
- Earn technical certifications & gain internship experience  
- Build soft skills and interview readiness  
- Target high-growth domains — AI, Data Science, Cloud  

### For Colleges:
- Strengthen alumni and industry ties  
- Conduct placement and resume workshops  
- Monitor analytics to optimize placement efforts  

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- Apache Spark 3.x with PySpark
- Jupyter Notebook or JupyterLab

### Setup
```bash
pip install pyspark jupyter
