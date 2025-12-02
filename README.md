# Tip Analysis
Tip Analysis Project

## Overview
For this project, we analyzed a restaurant tipping dataset from Kaggle to understand what affects how much people tip. Since restaurants rely heavily on tips to motivate servers and keep staff happy, we approached this like we were giving insights to a restaurant manager. The goal was to figure out when customers tip the most, which types of tables are more profitable, and whether certain customer groups tip differently.

All of the analysis was done using Python, Jupyter Notebook, and basic data science tools.

---

## Dataset Information
**Source:** Kaggle – Tip Prediction Dataset  
**File Used:** `tip.csv`

**Key Columns:**
- `total_bill`: Total bill amount  
- `tip`: Tip amount  
- `sex`: Male/Female  
- `smoker`: Yes/No  
- `day`: Day of the week  
- `time`: Lunch or Dinner  
- `size`: Number of people at the table

I also created a new column called **`tip_pct`**, which calculates the tip percentage using:


---

## Business Questions I Wanted To Answer
1. **What factors influence tip amount and tip percentage the most?**  
2. **Which days and times have the highest tipping behavior?**  
3. **How does party size affect tipping?**  
4. **Do men, women, smokers, or non-smokers tip differently?**  
5. **Can we build a simple model to predict the tip amount based on total bill and group size?**

---

## Summary of Findings
Here’s what I discovered from the data:

- **Best tipping times:**  
  Fridays and Sundays had the highest average tip percentages. Lunch tips were also slightly higher than Dinner tips.

- **Party size:**  
  Smaller groups (especially tables of 1–2) tip a much higher percentage compared to big groups. Larger tables leave bigger total tips, but their percentages drop.

- **Customer groups:**  
  Women tip a little higher than men. Smokers also tip slightly more than non-smokers. The differences aren’t huge, but they're noticeable.

- **Prediction model:**  
  The model showed that the total bill and party size are both positively related to the tip amount. The R-squared was around 0.47, meaning the model explains about half of why tips change. Not perfect, but good for a basic model.

---
