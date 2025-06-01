# 🛵 Courier Performance Analysis – Data Analyst Case Study (Bolt-Inspired)

This project was completed as part of a Junior Data Analyst application process. The task involved analyzing a courier dataset to identify underperforming employees and uncover key performance risks across a delivery fleet.

---

## 📋 Task Overview

> **Goal**: Identify couriers whose performance falls below expectations and explain why.
>
> **Dataset Provided**: Delivery-level records including:
> - Courier ID
> - Online time
> - Orders assigned
> - Orders delivered
> - Deliveries per hour

---

## 🔍 Key Metrics Calculated

- **Delivery Efficiency** = Deliveries / Online Hours
- **Fulfillment Rate** = Delivered Orders / Received Orders
- **Drop Rate** = Received Orders - Delivered Orders

---

## 📊 Key Findings

### 🚩 Bottom 5 Performers (by Efficiency)

| Courier ID | Deliveries/Hour | Online Time (hrs) | Delivered Orders    | Notes |
|------------|------------------|------------------|---------------------|-------|
| #2         | 0.34             | 74               | 25                  | Very low efficiency |
| #135       | 0.36             | N/A              | 2/14 orders         | Extremely low fulfillment |
| #30        | 0.74             | Moderate         | Dropped many orders |
| #88        | 0.84             | High             | Underutilized       |
| #112       | 1.10             | Moderate         | Low fulfillment rate|

---

### ⚠️ Additional Risk: Drop Rate Concerns

Some couriers showed **high efficiency** but dropped a large number of orders. For example:

- **Courier #39**: 1.52 deliveries/hour, but dropped 44% of orders
- **Courier #3**: 1.95 deliveries/hour, dropped 51 of 194 orders
- **Courier #34**: 1.99 deliveries/hour, dropped 41% of orders

These individuals may be selectively rejecting orders, overwhelmed, or affected by operational issues. This insight wouldn't be caught by speed-based metrics alone.

---

## ✅ Recommendations

- 📢 **Warn** bottom 5 low-efficiency couriers
- 🎯 Set a **minimum threshold** (e.g., 1.5 deliveries/hour)
- 🔁 Track **drop-off rates** weekly, not just deliveries/hour
- 🔬 **Investigate** high-efficiency couriers with high drop rates

---

## 📈 Tools & Techniques Used

- Microsoft Excel
- Conditional formatting to highlight performance bands
- Derived metrics to uncover hidden risks
- Business-focused summary report

---

## 🧠 What I Learned

- The importance of blending **efficiency** and **reliability**
- How operational data can hide deeper issues if only surface metrics are used
- How to create actionable business recommendations from raw data

---

## 📂 File Structure

- `Juniour Analyst Home task completed.xlsx` — Main analysis with calculated metrics, visuals, and conditional formatting
- `Juniour Analyst Home task.xlsx` — raw file with no analysis done, the task itself
- `README.md` — Project documentation (you’re reading it!)
- `Courier_Performance_Analysis_Levan.txt` — polished text version of the case study presentation summary

---

## 🙋‍♂️ About Me

I'm Levan, a second-year Computer Science student passionate about turning data into decisions. I'm currently pursuing Microsoft’s PL-300T00-A certification in Power BI and building a strong portfolio of real-world analytics work.

Let’s connect on [LinkedIn](www.linkedin.com/in/levan-petrosiani) or feel free to check out my other [projects](https://github.com/levan-petrosiani?tab=repositories)!

