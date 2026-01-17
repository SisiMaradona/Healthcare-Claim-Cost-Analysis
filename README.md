# Healthcare-Claim-
This project analyzes healthcare claims to uncover the most expensive claim types, top-cost procedures (CPT codes) and diagnoses (ICD codes), high-cost members, and gaps between billed and paid amounts. The insights help drive cost control, optimize resource allocation, and support data-driven decision-making in healthcare.

# 🏥 Healthcare Claims Cost & Utilization Analysis

🔗 **Live Dashboard:** [View Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYmE2NTk2N2ItMzIyMC00NGEzLWE0N2EtZmQ0YzYwMWVjM2UyIiwidCI6ImFlMjc5MjI1LWVhMGMtNDFjMy1iODYyLTk2NWI0MzgwZjYwOCJ9&pageName=6c31389323d90981ee83)

---

## 📌 Project Overview

This project analyzes healthcare claims data to identify:

- The most expensive claim types  
- The CPT procedures and ICD diagnoses driving the highest costs  
- The members responsible for the largest share of total spending  
- The gap between billed and paid amounts  

**Dataset Summary / Key KPIs:**

- **Total Billed Amount:** $2.1M  
- **Total Paid Amount:** $1.6M  
- **Number of Claims:** 449  
- **Number of Members:** 100  
- **Number of Providers:** 103  
- **Number of Plan Types:** 4  

---

## 🎯 Business Questions

1. Which claim types are the most expensive?  
2. Which CPT and ICD codes drive the highest spending?  
3. Which members account for the largest share of total costs?  
4. How do billed amounts compare to paid amounts?

---

## 📊 Key Insights

### 1️⃣ Claim Types
- **Inpatient claims = $1.09M paid (70.45% of total spend)**, average **$11K per claim**.  
- **Emergency claims = $294K paid (18.99%)**, average **$3.3K per claim**.  
- **Outpatient claims = $130k paid**, average **$1.2k per claim**.
- **Lab claims = $30k paid**, average **$308 per claim**.
- **Pharmacy claims =$11k paid**, average **141 per claim**.
- **Outpatient, Lab, Pharmacy combined = ~11% of total spend**.  
➡️ Inpatient + Emergency ≈ **89% of total spending**.

### 2️⃣ CPT Codes (Top 10 by Paid Amount)
| CPT Code | Paid Amount |
|----------|------------|
| 67890    | $243K      |
| 23456    | $204K      |
| 00123    | $122K      |
| 12345    | $115K      |
| 99223    | $57K       |
| 34567    | $54K       |
| 45678    | $52K       |
| 00567    | $39K       |
| 54321    | $37K       |
| 56789    | $33K       |

**Top 5 CPT codes = $741K (~46% of total spend).**

### 3️⃣ ICD Codes (Top 10 by Paid Amount)
| ICD Code | Paid Amount |
|----------|------------|
| I10      | $260K      |
| A12.3    | $152K      |
| B20      | $141K      |
| B20.1    | $105K      |
| C34.91   | $63K       |
| B99.4    | $51K       |
| E11.65   | $51K       |
| J45.909  | $44K       |
| E11.9    | $35K       |
| A01.1    | $34K       |

**Top 5 ICD codes = $721K (~45% of total spend).**

### 4️⃣ Top 10 CPT by Average Paid (High-Severity Procedures)
| CPT Code | Avg Paid |
|----------|----------|
| 36512    | $26K     |
| 10101    | $17K     |
| 89012    | $15K     |
| 00512    | $14K     |
| 50255    | $13K     |
| 20610    | $12K     |
| 61234    | $11K     |
| 43752    | $10K     |
| 99217    | $10K     |
| 00123    | $10K     |

### 5️⃣ Members
**Top 5 Members by Paid Amount:**

| Member ID | Total Paid |
|-----------|------------|
| 6         | $43K       |
| 32        | $40K       |
| 58        | $36K       |
| 36        | $31K       |
| 8         | $31K       |

- **Total paid by top 5 members = $181K (~11.3% of total spend)**.  
- High costs driven by **Inpatient + Emergency claims**.

### 6️⃣ Billed vs Paid
- **Total billed = $2.1M vs Total paid = $1.6M (~76% reimbursement rate)**  

Paid ratio by claim type:
- Inpatient = 0.74  
- Emergency = 0.77  
- Outpatient = 0.80  
- Lab = 0.91  
- Pharmacy = 0.89  

➡️ **Inpatient and Emergency have the largest payment gaps**. Lab and Pharmacy show stronger cost control.

---

## 🛠 Tool Used

- Power BI
