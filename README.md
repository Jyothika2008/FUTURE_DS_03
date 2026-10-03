# FUTURE_DS_03 — Marketing Campaign Analysis

## 📊 Project Overview

This project focuses on analyzing a marketing campaign dataset to understand customer conversion patterns, evaluate campaign performance, and identify factors associated with successful customer conversions.

The analysis was completed as part of **Future Interns — Data Science & Analytics Task 3**.

The project includes data preparation, exploratory data analysis, conversion analysis, campaign comparisons, funnel analysis, correlation analysis, visualizations, and a professional marketing campaign dashboard created using Python.

---

## 🎯 Objective

The main objectives of this analysis are to:

- Analyze overall customer conversion and campaign performance.
- Identify patterns in successful customer conversions.
- Compare conversion rates across different contact methods.
- Analyze the impact of campaign contact frequency on conversion.
- Examine conversion trends across different months.
- Analyze conversion rates across different age groups.
- Compare conversion rates across job categories.
- Analyze conversion based on education level.
- Examine the relationship between housing loans and conversion.
- Analyze the relationship between personal loans and conversion.
- Compare conversion across marital and default statuses.
- Analyze the influence of previous campaign outcomes on conversion.
- Examine relationships between numerical campaign variables using correlation analysis.
- Perform funnel analysis to understand customer conversion and drop-off.
- Present the findings through a professional dashboard.

---

## 📁 Dataset

The project uses a **Bank Marketing Campaign dataset** containing customer and campaign-related information.

The dataset contains **45,211 customer records** and **17 columns**.

The dataset includes:

- Age
- Job
- Marital Status
- Education
- Default Status
- Account Balance
- Housing Loan
- Personal Loan
- Contact Method
- Contact Day
- Contact Month
- Call Duration
- Campaign Contacts
- Days Since Previous Contact
- Previous Campaign Contacts
- Previous Campaign Outcome
- Campaign Outcome

---

## 🧹 Data Preparation

The following data preparation and analysis steps were performed:

- Loaded the marketing campaign dataset.
- Examined the dataset structure and attributes.
- Checked for missing values.
- Checked for duplicate records.
- Examined categorical and numerical variables.
- Created customer age groups.
- Created campaign contact groups.
- Prepared variables for conversion analysis.
- Calculated conversion rates across different customer and campaign segments.

---

## 📈 Key Performance Indicators

| KPI | Value |
| --- | ---: |
| Total Customers Contacted | 45,211 |
| Successful Conversions | 5,289 |
| Overall Conversion Rate | 11.70% |
| Customers Who Did Not Convert | 39,922 |
| Lead-to-Customer Drop-off Rate | 88.30% |

---

## 🔍 Analysis Performed

### 1. Overall Conversion Analysis

The overall campaign conversion performance was analyzed to understand the proportion of customers who successfully converted.

- Total customers contacted: **45,211**
- Successful conversions: **5,289**
- Overall conversion rate: **11.70%**

The analysis shows that 5,289 customers successfully converted after being contacted during the campaign.

---

### 2. Conversion by Contact Method

Conversion rates were compared across different contact methods.

| Contact Method | Conversion Rate |
| --- | ---: |
| Cellular | 14.92% |
| Telephone | 13.42% |
| Unknown | 4.07% |

The **cellular** contact method recorded the highest observed conversion rate among the available contact methods.

---

### 3. Conversion by Campaign Contact Frequency

Customers were grouped according to the number of times they were contacted during the campaign.

| Campaign Contact Group | Customers | Successful Conversions | Conversion Rate |
| --- | ---: | ---: | ---: |
| 1 contact | 17,544 | 2,561 | 14.60% |
| 2–3 contacts | 18,026 | 2,019 | 11.20% |
| 4–5 contacts | 5,286 | 456 | 8.63% |
| 6–10 contacts | 3,159 | 206 | 6.52% |
| 11+ contacts | 1,196 | 47 | 3.93% |

The observed conversion rate generally decreased as the number of campaign contacts increased.

---

### 4. Conversion by Month

Monthly conversion rates were analyzed to identify changes in campaign response throughout the year.

| Month | Conversion Rate |
| --- | ---: |
| January | 10.12% |
| February | 16.65% |
| March | 51.99% |
| April | 19.68% |
| May | 6.72% |
| June | 10.22% |
| July | 9.09% |
| August | 11.01% |
| September | 46.46% |
| October | 43.77% |
| November | 10.15% |
| December | 46.73% |

The analysis shows considerable variation in observed conversion rates across different months.

---

### 5. Conversion by Age Group

Customers were grouped into different age ranges to compare conversion performance.

| Age Group | Customers | Successful Conversions | Conversion Rate |
| --- | ---: | ---: | ---: |
| 18–25 | 1,336 | 320 | 23.95% |
| 26–35 | 15,571 | 1,869 | 12.00% |
| 36–45 | 13,856 | 1,301 | 9.39% |
| 46–55 | 9,548 | 893 | 9.35% |
| 56–65 | 4,149 | 586 | 14.12% |
| 66+ | 751 | 320 | 42.61% |

The **66+ age group** recorded the highest observed conversion rate, while the 46–55 group recorded the lowest among the defined age groups.

---

### 6. Conversion by Job Category

Conversion rates were compared across different job categories.

| Job Category | Conversion Rate |
| --- | ---: |
| Student | 28.68% |
| Retired | 22.79% |
| Unemployed | 15.50% |
| Management | 13.76% |
| Admin | 12.20% |
| Self-employed | 11.84% |
| Unknown | 11.81% |
| Technician | 11.06% |
| Services | 8.88% |
| Housemaid | 8.79% |
| Entrepreneur | 8.27% |
| Blue-collar | 7.27% |

The analysis shows differences in observed conversion rates across occupational groups.

---

### 7. Conversion by Education Level

Conversion performance was analyzed across education levels.

| Education Level | Customers | Successful Conversions | Conversion Rate |
| --- | ---: | ---: | ---: |
| Primary | 6,851 | 591 | 8.63% |
| Secondary | 23,202 | 2,450 | 10.56% |
| Tertiary | 13,301 | 1,996 | 15.01% |
| Unknown | 1,857 | 252 | 13.57% |

Customers with **tertiary education** recorded the highest observed conversion rate among the defined education categories.

---

### 8. Housing Loan Status vs Conversion

Conversion rates were compared between customers with and without housing loans.

| Housing Loan | Customers | Successful Conversions | Conversion Rate |
| --- | ---: | ---: | ---: |
| No | 20,081 | 3,354 | 16.70% |
| Yes | 25,130 | 1,935 | 7.70% |

Customers without a housing loan had a higher observed conversion rate in this dataset.

---

### 9. Personal Loan Status vs Conversion

Conversion rates were analyzed based on personal loan status.

| Personal Loan | Customers | Successful Conversions | Conversion Rate |
| --- | ---: | ---: | ---: |
| No | 37,967 | 4,805 | 12.66% |
| Yes | 7,244 | 484 | 6.68% |

Customers without a personal loan had a higher observed conversion rate.

---

### 10. Conversion by Marital Status

Conversion rates were compared across marital status categories.

| Marital Status | Conversion Rate |
| --- | ---: |
| Divorced | 11.95% |
| Married | 10.12% |
| Single | 14.95% |

Single customers recorded the highest observed conversion rate among the three marital-status categories.

---

### 11. Conversion by Default Status

Conversion performance was analyzed based on customer default status.

| Default Status | Conversion Rate |
| --- | ---: |
| No | 11.80% |
| Yes | 6.38% |

Customers without a recorded default had a higher observed conversion rate.

---

### 12. Previous Campaign Outcome

The relationship between previous campaign outcomes and current campaign conversion was analyzed.

| Previous Campaign Outcome | Conversion Rate |
| --- | ---: |
| Success | 64.73% |
| Other | 16.68% |
| Failure | 12.61% |
| Unknown | 9.16% |

Customers with a previous successful campaign outcome recorded a substantially higher observed conversion rate in the current campaign.

---

### 13. Correlation Analysis

A correlation matrix was used to examine relationships between numerical campaign variables including:

- Age
- Account Balance
- Contact Day
- Call Duration
- Campaign Contacts
- Days Since Previous Contact
- Previous Contacts

The strongest observed relationship among these variables was between **pdays and previous**, with a correlation of approximately **0.45**.

The correlation analysis also showed a positive relationship of approximately **0.16** between contact day and campaign contacts.

---

### 14. Funnel Analysis

A conversion funnel was created to understand the overall customer journey from contact to successful conversion.

| Funnel Stage | Customers |
| --- | ---: |
| Customers Contacted | 45,211 |
| Successful Conversions | 5,289 |
| Customers Not Converted | 39,922 |

The overall **lead-to-customer conversion rate was 11.70%**, while the observed drop-off rate was **88.30%**.

---

## 💡 Key Business Insights

The analysis identified several notable patterns in campaign conversion:

- The overall conversion rate was **11.70%**.
- **Cellular** recorded the highest observed conversion rate among contact methods at **14.92%**.
- Customers with a previous campaign outcome of **success** had an observed conversion rate of **64.73%**.
- The observed conversion rate generally decreased as campaign contact frequency increased.
- Conversion rates varied considerably across different months.
- The **66+ age group** recorded an observed conversion rate of **42.61%**.
- **Students** recorded the highest observed conversion rate among job categories at **28.68%**.
- Customers without housing loans and personal loans showed higher observed conversion rates than customers with these loans.

These findings provide useful descriptive insights into customer response patterns and campaign performance within the analyzed dataset.

---

## 📊 Dashboard

A professional **Marketing Campaign Performance Dashboard** was created to present the analysis visually.

The dashboard includes:

- Total customers KPI
- Successful conversions KPI
- Overall conversion rate KPI
- Drop-off rate KPI
- Conversion rate by contact method
- Conversion rate by campaign contact group
- Monthly conversion rate
- Conversion rate by age group
- Conversion rate by job category
- Conversion rate by previous campaign outcome
- Key campaign insights

The dashboard is designed to provide a clear overview of campaign performance and allow the analysis to be understood quickly.

---

## 🛠️ Tools Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Google Colab**

---

## 📂 Project Files

The project contains the following main notebooks:

`Task_3_Marketing_Campaign_Analysis.ipynb`

`Task_3_Marketing_Campaign_Dashboard.ipynb`

---

## 🎓 Internship

**Program:** Future Interns  
**Track:** Data Science & Analytics  
**Task:** Task 3 — Marketing Campaign Analysis

---

## 👩‍💻 Author

**Jyothika J**

Currently pursuing B.Tech Computer Science and Engineering with specialization in Data Science
