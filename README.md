# Data_camp_projects

#  1. Walmart eCommerce Analytics

![Walmart eCommerce](images/walmartecomm.jpg)

##  Project Overview

This project focuses on analyzing Walmart’s eCommerce data to uncover patterns, improve operational efficiency, and enhance customer experience through data-driven insights.

Using Python and tools like Pandas, Seaborn, and Matplotlib, I explored trends in product demand, pricing, and customer behavior to support strategic decision-making.

---

##  Key Objectives

- Analyze product performance and identify high-demand categories  
- Examine seasonal trends and pricing patterns  
- Detect anomalies or outliers in sales data  
- Provide actionable insights for marketing and inventory strategies

---

##  Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook  
- Parquet Dataset Format  
- Git for version control

---

##  Outcomes

- Cleaned and processed Walmart eCommerce data from `.parquet` format  
- Visualized sales trends and customer activity over time  
- Delivered insights on category performance and pricing strategy  
- Created a reproducible Jupyter notebook for future analysis

---

##  How to Run

1. Clone the repository  
2. Install dependencies from `requirements.txt`  
3. Run `notebook.ipynb` in Jupyter  
4. Review visualizations and summaries

---

##  Future Scope

- Incorporate promotional campaign analysis  
- Apply predictive models for demand forecasting  
- Build a dashboard for real-time category tracking


## 2. Hypothesis Testing in Healthcare: Drug Safety

A pharmaceutical company, GlobalXYZ, conducted a randomized controlled drug trial to study the safety of a new medication. This project investigates whether the drug causes statistically significant adverse effects.

###  Dataset Overview

The dataset (`drug_safety.csv`) includes the following fields:

| Column           | Description                                           |
|------------------|-------------------------------------------------------|
| `sex`            | Gender of the individual                              |
| `age`            | Age of the individual                                 |
| `week`           | Week of the drug testing                              |
| `trx`            | Treatment group: Drug or Placebo                      |
| `wbc`            | White blood cell count                                |
| `rbc`            | Red blood cell count                                  |
| `adverse_effects`| Presence of at least one adverse effect               |
| `num_effects`    | Number of adverse effects experienced per individual  |

Sourced and modified from [Hbiostat](https://hbiostat.org), the dataset enables exploration of drug safety based on demographic and clinical features.

---

###  Objective

To test whether adverse effects differ significantly between the treatment and control groups using statistical hypothesis testing methods.

---

###  Tools Used

- Python (Pandas, SciPy, Statsmodels)
- Jupyter Notebook
- Matplotlib & Seaborn for visualization

---

###  Key Analyses

- Proportion test for comparing adverse effect rates between groups  
- T-tests for evaluating differences in blood cell counts  
- Visualizations of effects across age, sex, and treatment week  

---

###  Outcomes

The analysis helps determine if the observed adverse effects are statistically significant, guiding decisions on drug safety and further clinical trials.



