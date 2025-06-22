# 📊 Marketing Analytics Case Study

## 🏢 Client Overview

**ABC Inc.** is a provider of project management software for IT companies. Their marketing strategy includes:

- Multi-channel ad campaigns  
- Social media outreach  
- Client referrals  
- Trade shows  

**Primary Goal:** Drive **free trial registrations** through engagement with decision-makers at target accounts.

---

## 🎯 Your Role: Marketing Analyst

As a marketing analyst, you are tasked with **assembling the marketing budget** for the next quarter. Your responsibilities include:

- Providing **data-driven recommendations** for marketing platform investments  
- Identifying **opportunities** to maximize free trial sign-ups  
- Ensuring **optimum ROI** for every marketing dollar  

Key deliverables:

- Statistical analysis of historical campaign performance  
- Visualizations and insights  
- Budget optimization recommendations  

---

## 📁 Data Overview

**General Notes:**

- 80% of marketing data is available globally  
- Remaining data must be sourced from additional systems  

**Dataset Fields:**

| Field              | Description |
|-------------------|-------------|
| `Campaign ID`     | Unique identifier (date, time, and additional attributes) |
| `Campaign Name`   | Name of the campaign |
| `Prospect Status` | Stages in the marketing funnel: a. Responded, b. No Show, c. Attended, d. Registered |
| `Account ID`      | Unique Salesforce account ID |
| `Account Name`    | Client company name |
| `Country`         | Client’s country of origin |
| `Prospect ID`     | Unique ID representing an individual |
| `Opt-Out Timestamp` | Date of opting out (blank if not opted-in) |
| `Job Title`       | Role classification: a. Practitioner (e.g., Analyst), b. Decision Maker (e.g., Manager), c. Executive |
| `Prospect Source` | How the prospect heard about the product: Advertisement, Social Media, Referral, Trade Show |

---

## 💻 How to Run the Notebook

The notebook `marketing_analysis_complete.ipynb` performs data cleaning, exploratory analysis, and insights visualization based on the dataset described above.

### 🔧 Requirements

Install the necessary packages:

```bash
pip install pip-tools
pip-compile requirements.in
pip install -r requirements.txt
```

### 📊 Data visualization

- Visualization Types:

- Funnel Chart: Overall drop-offs per stage
- Dispersion chart: conversion by country and source
- Stacked Bar Chart: Conversion rates by job role, country and prospect status
- Box Plot: Variability in conversion by Job Role
- Heatmap: Country vs Prospect Status rates

#### Tools:
- Looker
- Export interactive dashboards for stakeholder walkthroughs

#### Dashboard:
[ABC Marketing ROI Dashboard](https://lookerstudio.google.com/reporting/2ca779ec-7392-44d4-b92b-0e8546ff801b)