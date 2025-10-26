# HR Analytics Dashboard

## General Info
This project contains the analysis of employee attrition data and creates an interactive dashboard using **Power BI**. The dataset was prepared and cleaned using **Python**.

**Aim:**  
The project aims to analyze employee attrition in an example company to identify key factors responsible for attrition. The dashboard helps HR teams interpret data and make decisions to reduce attrition rates.

---

## Dataset
The dataset contains employee attrition details including:  

- Department  
- Age  
- Education Field  
- Job Role  
- Years at Company  
- Monthly Income  
- Job Satisfaction, Environment Satisfaction, Work-Life Balance  
- Gender, Marital Status, OverTime, Business Travel  

The dataset comes from **Kaggle**.

---

## Project Includes
- **HR Dashboard with Power BI** – `HR_analytics.pbix`  
- **Dashboard View** 
- **Python Script to Clean Data** – `HR_Analytics.ipynb`  

---

## Visualizations
The dashboard contains the following visualizations:

| Visual | Description |
|--------|------------|
| **Cards** | Total employees, total attrition, attrition rate (%) |
| **Attrition by Years** | Line chart showing attrition by years at company |
| **Attrition by Gender** | Donut chart of attrition rate by gender |
| **Attrition by Department** | Bar chart showing attrition per department |
| **Attrition by Job Role** | Bar chart showing job roles with highest attrition |
| **Attrition Trend by Age and Salary Level** | Scatter plot: Age vs Monthly Income with attrition highlighted |
| **Attrition by Job Satisfaction** | Column chart showing attrition rate by job satisfaction level |
| **Attrition by Work-Life Balance** | Column chart showing attrition by work-life balance score |
| **Attrition by Environment Satisfaction** | Column chart showing attrition by environment satisfaction |
| **Attrition by Age** | Column chart showing attrition by age group (20–30, 31–40, 41–50, 51–60) |
| **Attrition by Education** | Donut chart showing attrition by education field |
| **Attrition by Marital Status** | Donut chart showing attrition by marital status |
| **Attrition by Business Travel** | Column chart showing attrition by frequency of business travel |

---


## Dataset
- **Total Employees:** 1,470  
- **Employees Left:** 237  
- **Attrition Rate:** 16.12%  

---

## Gender Distribution & Attrition
- Male: 882  
- Female: 588  

**Insight:** Meskipun jumlah karyawan laki-laki lebih banyak, data menunjukkan **lebih banyak laki-laki yang resign dibanding perempuan**.  

---

## Korelasi dengan Attrition

### Positive Correlation (Meningkatkan kemungkinan resign)
| Faktor | Korelasi | Insight |
|--------|----------|---------|
| DistanceFromHome | 0.078 | Semakin jauh jarak rumah ke kantor, risiko resign sedikit lebih tinggi |
| NumCompaniesWorked | 0.043 | Karyawan yang pernah bekerja di banyak perusahaan lebih cenderung resign |
| MonthlyRate | 0.015 | Korelasi sangat kecil, hampir tidak signifikan |
| PerformanceRating | 0.003 | Korelasi sangat kecil |
| HourlyRate | -0.007 | Korelasi negatif kecil, bisa diabaikan |

### Negative Correlation (Menurunkan kemungkinan resign)
| Faktor | Korelasi | Insight |
|--------|----------|---------|
| Age | -0.159 | Karyawan lebih tua cenderung lebih stabil dan jarang resign |
| MonthlyIncome | -0.160 | Gaji lebih tinggi menurunkan risiko resign |
| YearsInCurrentRole | -0.161 | Lama di posisi saat ini membuat karyawan lebih loyal |
| JobLevel | -0.169 | Posisi lebih tinggi mengurangi kemungkinan resign |
| TotalWorkingYears | -0.171 | Pengalaman kerja total lebih banyak menurunkan risiko attrition |

---

## Categorical Insights
- **Department:** Sales department memiliki attrition tertinggi.  
- **Marital Status:** Single employees lebih cenderung resign dibanding married/divorced.  
- **OverTime:** Karyawan yang sering bekerja lembur memiliki risiko attrition lebih tinggi.  
- **JobRole & EducationField:** Beberapa peran, seperti Sales Executive, dan bidang studi tertentu (Life Sciences) memiliki risiko resign lebih tinggi.

---

**Key Findings:**  
- Most attrition occurs within the first few years of employment.  
- Job roles with highest attrition: Sales Representatives, Laboratory Technicians, Research Scientists, Sales Executives.  
- Employees with salary below 5,000 show the highest attrition.  
- Higher attrition is observed among employees with educational backgrounds in Life Sciences and Medical fields.  
- Age group 26–35 has the highest attrition; attrition decreases as age increases.  
- Male employees have higher attrition across all age groups.  
- Frequent business travel and low job satisfaction or work-life balance are also associated with higher attrition.

---

## Technologies
- **Power BI**  
- **Python**  

---

## Running the Project
To use the dashboard:  
1. Clone the repository or download the `.pbix` file.  
2. Open the file in **Power BI Desktop**.  
3. Use slicers to filter data by Gender, OverTime, Marital Status, Department, or other indicators.  

---

## Dashboard Preview
<img width="937" height="528" alt="image" src="https://github.com/user-attachments/assets/b8637ace-2ec6-4fd8-9f1c-6f7e446bcaee" />
<img width="921" height="531" alt="image" src="https://github.com/user-attachments/assets/56518d1d-af28-4920-acec-1035abc0b89d" />
<img width="923" height="522" alt="image" src="https://github.com/user-attachments/assets/89b14406-f178-466f-90a2-36f2e4453ed2" />

