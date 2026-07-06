# Consumer Financial Complaints Analysis
### Analyzing 16.5 Million Banking Complaints to Surface Policy-Relevant Insights


<img width="476" height="269" alt="image" src="https://github.com/user-attachments/assets/f8a47027-86dc-4e0d-8a8b-025fd249a4d0" />


---

##  Project Overview

This project analyzes **16,504,424 consumer financial complaints** filed with the 
Consumer Financial Protection Bureau (CFPB) between December 2011 and July 2026 — 
the complete 15-year dataset from inception to present day.

The objective is to identify structural patterns in complaint volume, resolution 
quality, company-level concentration, and issue type distribution — the kind of 
analysis directly applicable to any consumer protection regulator monitoring 
financial sector conduct at scale.

> This analytical framework mirrors the work of RBI's Consumer Education and 
> Protection Department (CEPD), which monitors complaints against regulated 
> entities in India's banking and financial sector.

---

## 📊 Key Findings

| Metric | Value |
|---|---|
| Total Complaints Analyzed | 16,504,424 |
| Date Range | December 2011 – July 2026 |
| Years Covered | 15 years |
| Total Unique Companies | 8,032 |
| Total Product Categories | 23 |
| Most Complained Product | Credit Reporting |
| Most Complained Company | TransUnion Intermediate Holdings |
| Timely Resolution Rate | 99.4% |
| Untimely Responses (Absolute) | 102,753 |
| Top Consumer Issue | Incorrect Information on Report |

---

## 🔍 Analysis Performed

### 1. Complaint Volume Trend (2011–2026)
Complaint volumes show a broadly upward trajectory over 15 years, with a sharp 
spike observed post-2020. This spike coincides with pandemic-era financial stress, 
loan forbearance disputes, and the rapid digitization of financial services — 
underlining the importance of real-time complaint monitoring systems.

### 2. Complaints by Product Type
Credit reporting dominates complaint volumes, followed by debt collection and 
mortgage products. The concentration of complaints in credit reporting reflects 
growing consumer awareness of credit scores and their impact on financial access.

### 3. Top 10 Companies by Complaint Volume
TransUnion, Equifax, and Experian — the three major credit bureaus — account for 
a disproportionately large share of total complaints, consistent with the 
dominance of credit reporting issues. Large banks (JPMorgan, Wells Fargo, 
Citibank) follow.

### 4. Timely Resolution Rate
99.4% of complaints received a timely response from companies — indicating broad 
compliance with regulatory response timelines. However, 102,753 untimely responses 
in absolute terms represents a significant number of consumers left waiting beyond 
acceptable timeframes.

### 5. Top Consumer Issues
"Incorrect information on report" is the single most common issue, followed by 
"Improper use of your report" and "Problem with a credit reporting company's 
investigation." These three issues together account for the majority of all 
complaints — pointing to systemic problems in credit reporting accuracy.

### 6. Average Resolution Time by Product
Resolution times vary significantly by product. Non-financial and payday loan 
products show longer average resolution times — suggesting these categories may 
warrant closer supervisory attention on resolution quality, not just timeliness.

---

## 💡 Policy Implications

**1.	 Complaint data should be used to spot problems early, not just to check compliance after the fact: -** Complaints grew almost 20 times over from 2019 to 2025, but this pattern only became clear after looking back at years of data. A live dashboard that alerts regulators when complaints for a company or product category cross a certain threshold would catch this kind of surge much sooner.
**2.	"Resolved on time" should not be the only measure of good service:- ** Right now, over 99% of complaints get a timely response, but fewer than 2% actually result in the consumer getting money back or a real fix. This means a company can score well on speed while barely solving the customer's actual problem. Regulators should also track what kind of outcome each complaint gets a real remedy, a partial fix, or just an explanation not just how fast the company replied
**3.	Complaint categories need to be updated regularly so they don't become outdated or messy: -** In this dataset, the same type of complaint (like credit reporting issues) was labelled under three different category names over the years, which makes it harder to track real trends. As new financial products emerge in India, like UPI, Buy-Now-Pay-Later, and digital loans, complaint categories need to keep up. Otherwise, important patterns could be missed or underestimated.


---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| DuckDB | Querying 16.5M row dataset directly from CSV |
| Python (Pandas) | Data cleaning, transformation, analysis |
| Matplotlib / Seaborn | Data visualization |
| Power BI | Interactive monitoring dashboard |
| Jupyter Notebook | Analysis environment |
| GitHub | Version control and project hosting |

---
---

## Dataset Note

The raw dataset (complaints.csv — 8.3GB, 16.5M rows) is not uploaded to this 
repository due to file size constraints. It is publicly available at:

🔗 [CFPB Consumer Complaints Database](https://www.consumerfinance.gov/data-research/consumer-complaints/)

---

## 🔗 About This Project

This project was built as part of a data analytics portfolio demonstrating 
proficiency in large-scale data handling, SQL-equivalent querying, Python-based 
analysis, and interactive dashboard development — skills directly applicable to 
consumer protection analytics, regulatory monitoring, and evidence-based policy 
research.

---
