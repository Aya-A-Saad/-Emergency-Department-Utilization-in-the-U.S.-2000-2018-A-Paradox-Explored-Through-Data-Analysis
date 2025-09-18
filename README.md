# Emergency Department Utilization in the U.S. (2000–2018): A Paradox Explored Through Data Analysis

**Author:** Aya A. Saad  
**Date:** September 18, 2025

---

## Table of Contents
- [Executive Summary](#executive-summary)
- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
  - [ED Utilization Trends](#1-ed-utilization-trends)
  - [Racial Disparities](#2-racial-disparities)
  - [Age-Stratified Patterns](#3-age-stratified-patterns)
  - [Gender-Based Trends](#4-gender-based-trends)
  - [Public Health Implications](#5-public-health-implications)
  - [Emergency Care Dependence](#6-emergency-care-dependence)
  - [Long-Term Implications](#7-long-term-implications)
- [Conclusion & Recommendations](#conclusion--recommendations)
- [Limitations](#limitations)
- [Disclaimer](#disclaimer)
- [Resources](#resources)

---

## Executive Summary

Adults aged **18–44**, who make up **36% of the U.S. population**, consistently show **the highest ED utilization rates**. This is paradoxical, as they are typically considered the healthiest age group. Findings call for policy-level intervention and preventive care promotion to reduce reliance on emergency services.

---

## Introduction

This report analyzes trends in U.S. emergency department (ED) utilization from **2000–2018**, with a focus on the **18–44 age group**. It examines demographic disparities and the impact of economic and policy changes, particularly around **2011–2012**.

---

## Dataset Description

- **Source:** Centers for Disease Control and Prevention (CDC) via HealthData.gov  
- **Years Covered:** 2000–2018  
- **Settings:** Physician offices, hospital outpatient departments, emergency departments  
- **Key Variables:**  
  - Age, Sex, Race  
  - Visit estimates (crude and adjusted)  
  - Settings of care  

- **Final dataset:** 3,110 cleaned rows  
- **Excluded columns:** SE (Standard Error), FLAG (mostly empty)

---

## Methodology

- **Tools:** Python (Google Colab) for cleaning, Power BI for visualization  
- **Data Cleaning:** Removed rows with missing estimate values  
- **Validation:**
  - Excluded incomplete 2017 data
  - Stratified analysis by age, race, gender
  - Timeline cross-referenced with ACA policy rollout

---

## Key Findings

### 1. ED Utilization Trends

- **Sharp decline in hospital visits:** From **6.3M (2011)** to **2.7M (2012)** — a 57% drop
- **ED visits, however, remained high** and even **increased post-2012**
- **Causes of 2011–2012 decline:**
  - Economic fallout from 2008 recession
  - Early Affordable Care Act (ACA) implementations
  - State-level Medicaid cutbacks

---

### 2. Racial Disparities

- **Black or African American patients** use EDs nearly **twice as often** as White patients.
- **White patients** use outpatient and physician office visits more often.
- Persistent disparities reflect systemic inequality in access and quality of care.

---

### 3. Age-Stratified Patterns

- **Adults aged 18–44** account for **26.6% of all ED visits**
- Contradicts expectation that older adults dominate ED usage
- **Elderly (65–74)** account for only **4.8%**

---

### 4. Gender-Based Trends

**Females:**
- Highest ED use: 75+ years (24.54%)  
- Second highest: 18–44 years (19.92%)

**Males:**
- Highest: 75+ years (24.69%)  
- Third highest: 18–44 years (15.88%)

Consistently, **18–44 appears in the top 3 ED-using age groups**, across genders.

---

### 5. Public Health Implications

- **High ED use among 18–44** implies:
  - Poor engagement with preventive care
  - Avoidance of routine screenings
  - Structural barriers: time, cost, insurance gaps

- **Males aged 18–44** have lowest rates of routine visits among adult males — even lower than boys aged 0–18.

---

### 6. Emergency Care Dependence

> “Reactive, not proactive care.”

- Routine care avoidance leads to late detection of:
  - Hypertension
  - Diabetes
  - Cancer

**Early screening impact:**
- Reduces mortality by **15–20%**
- 87.8% of CV disease screening strategies are cost-effective
- Cost per QALY saved (Hypertension): **$48,500**

---

### 7. Long-Term Implications

- Increased ED use today → **higher chronic disease burden tomorrow**
- Rising costs, reduced workforce productivity, overburdened healthcare systems
- Over **100 million adults** in early adulthood under-engage in preventive care

---

## Conclusion & Recommendations

###  Summary

The **18–44 age group**, while theoretically at peak health, shows **concerning reliance** on EDs. This represents a **misalignment** between care availability and actual behavior.

###  Recommendations

1. **Employers & Insurers**
   - Integrate preventive checkups into work benefits
   - Offer time off and HSA incentives for screenings

2. **Workplace Health Integration**
   - Provide on-site/telehealth preventive services
   - Schedule health maintenance around work hours

3. **Public Awareness**
   - Reframe routine checkups as responsible behavior
   - Campaigns targeting young adults

4. **Policy-Level Interventions**
   - Mandate annual physicals
   - Cover screenings with zero out-of-pocket cost
   - Support flexible care models

5. **Target High-Risk Groups**
   - Tailored outreach to Black communities and men
   - Focus on 35–45 age group for early detection programs

---

## Limitations

- No statistical significance tests (e.g., CI, SD) included
- Dataset ends in 2018 — excludes effects of COVID-19 and post-ACA changes
- Limited racial scope (only White and Black groups analyzed)

---

## Disclaimer

- All data are estimates derived from CDC sample datasets (not full-population counts)
- Findings reflect associations, not causality
- Race/ethnicity categories are presented as provided by CDC

---

## Resources

1. Vogenberg, F. R., & Cutts, S. (2009). *Economic instability and its impact on decision making in health care*. NIH  
2. Palosky, C. (2011). *States Focus on Cost Containment...*. KFF  
3. Wood, S. M., et al. (2022). *Preventable Hospitalization Trends...*. NIH  
4. National Academies of Sciences. (2018). *Changing Patterns of Health Insurance...*. NCBI  
5. Institute of Medicine. (2010). *Missed Prevention Opportunities*. NIH  
6. Oude Wolcherink, M.J., et al. (2023). *Value of Early Detection...*. PharmacoEconomics  
7. Dehmer, S. P., et al. (2017). *Cost-Effectiveness of Screening*. Annals of Family Medicine  
8. Schaufler, T. M., & Wolff, M. (2010). *Diabetes Screening Programs*. PubMed  
9. U.S. Census Bureau (2020). *Population Data*
10. [Download Full Report (PDF)](P1003-Report.pdf)
11. [Download Figures and Visualizations (pbix)](P1003.pbix)
12. [Download Figures and Visualizations (jpg)](P1003to-jpg.zip)
13. [Download Article version](P1003Article.pdf)

---

> **Preventive care matters.**  
> In a world focused on productivity, don’t forget that your health is your most valuable asset.

