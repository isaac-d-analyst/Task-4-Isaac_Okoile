# Task-4-Isaac_Okoile
# Project 4: E-Commerce Revenue Performance and Revenue Leakage Analysis (2023–2025)
### DecodeLabs Data Analytics Internship

---

## 📌 What This Project Is About

This project transforms raw e-commerce transaction data into meaningful business
insights through data visualization and storytelling using Power BI.

The dashboard focuses on two critical business questions:
1. **What factors are driving revenue?**
2. **How much revenue is being lost and why?**

The goal was not simply to visualize data — but to communicate insights that
support better business decisions.

---

## 🎯 Objectives

- Identify key revenue drivers
- Measure customer acquisition performance
- Analyze product performance
- Quantify revenue leakage sources
- Provide actionable business improvement recommendations

---

## 📊 Dataset Overview

| Property | Detail |
|----------|--------|
| Total Orders | 1,200 |
| Total Customers | 1,189 |
| Total Products | 7 |
| Analysis Period | 2023 – 2025 |
| Tool Used | Microsoft Power BI |

### Key Fields:
OrderID, CustomerID, Product, Quantity, TotalPrice, PaymentMethod,
ReferralSource, CouponCode, OrderStatus, Date

---

## 🛠️ Tools Used

- Microsoft Power BI (Dashboard & Visualizations)
- Power Query (Data Cleaning & Transformation)
- DAX (Measures & Calculations)

---

## 🎨 Dashboard Design Principles

| Principle | Description |
|-----------|-------------|
| **One Page, One Message** | Each page focuses on a single business question |
| **Reduce Visual Clutter** | Only visuals that directly support the objective were included |
| **Tell a Story** | Every visual answers: What happened? Why does it matter? What should management do? |

---

## 📋 Dashboard Pages

---

### Page 1 — Revenue Driver Analysis

**Business Question:** What factors are driving revenue growth?

#### Key Metrics:
| Metric | Value |
|--------|-------|
| Total Revenue | $1,264,762 |
| Total Orders | 1,200 |
| Total Customers | 1,189 |
| Total Products | 7 |
| Avg Items in Cart | 5.49 |

#### Revenue by Referral Source:
| Referral Source | Revenue |
|----------------|---------|
| Instagram | $275,285 |
| Email | $261,809 |
| Google | $250,441 |
| Facebook | $250,411 |
| Referral | $226,816 |

#### Revenue by Product:
| Product | Revenue |
|---------|---------|
| Chair | $195,620 |
| Printer | $195,613 |
| Laptop | $192,127 |
| Tablet | $186,569 |
| Monitor | $175,651 |
| Desk | $167,460 |
| Phone | $151,722 |

#### Key Insights:
- Instagram is the most effective customer acquisition channel
- Revenue is concentrated among a small number of top products
- Overall revenue trendline shows a gradual decline requiring strategic attention

#### Recommendations:
1. Increase marketing investment in Instagram and high-performing digital channels
2. Maintain adequate inventory for top-performing products
3. Introduce cross-selling and upselling strategies
4. Monitor revenue trends and implement growth initiatives proactively

---

### Page 2 — Revenue Leakage Analysis

**Business Question:** How much revenue is being lost and what is causing it?

#### Key Metrics:
| Metric | Value |
|--------|-------|
| Total Revenue Lost | $519,674 |
| Lost to Cancellations | $276,396 |
| Lost to Returns | $243,278 |

#### Revenue by Order Status:
| Status | Revenue | Orders |
|--------|---------|--------|
| Cancelled | $276,396 | 250 |
| Pending | $256,328 | 237 |
| Shipped | $246,160 | 235 |
| Returned | $243,278 | 247 |
| Delivered | $242,600 | 231 |

#### Key Insights:
- Cancellations generate more financial loss than returns
- Revenue leakage occurs after customer acquisition costs have already been incurred
- Potential causes: payment issues, checkout abandonment, shipping delays, product dissatisfaction

#### Recommendations:
1. Investigate root causes of order cancellations — focus on checkout and payment experience
2. Analyze return reasons and identify recurring product or service issues
3. Implement proactive customer communication throughout order fulfillment
4. Develop a revenue recovery strategy targeting both cancellations and returns

---

## 💡 Overall Business Insights

### Opportunity 1 — Revenue Growth
Revenue is strongly influenced by high-performing referral channels and products.
Instagram and top products (Chair, Printer, Laptop) should receive increased strategic investment.

### Opportunity 2 — Revenue Recovery
Over **$519,000** in potential revenue was lost through cancellations and returns.
Reducing revenue leakage may generate substantial financial gains without additional acquisition spending.

---

## ✅ Final Recommendations

1. Increase investment in high-performing marketing channels — particularly Instagram
2. Prioritize inventory management for top-performing products
3. Develop strategies to reverse the declining revenue trend
4. Investigate causes of order cancellations
5. Reduce product return rates through quality and service improvements
6. Implement customer retention and engagement initiatives
7. Monitor key business metrics through regular dashboard reviews

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `project_4_dashboard.pbix` | Power BI dashboard file |
| `project_4_dataset.xlsx` | Cleaned dataset used for the dashboard |
| `project_4_report.pdf` | Full written report with findings |
| `screenshots/page1_revenue_drivers.png` | Dashboard Page 1 screenshot |
| `screenshots/page2_revenue_leakage.png` | Dashboard Page 2 screenshot |
| `README.md` | This documentation file |

---

## 👤 Author
**Isaac Okolie**
DecodeLabs Data Analytics Intern
*Powered by SkillAhead Solutions Ltd*
