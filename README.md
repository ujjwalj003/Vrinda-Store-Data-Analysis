# Vrinda Store — Annual Sales Report (2022)

Vrinda Store’s 2022 data is analyzed to understand customers, channels, and regions—so the team can grow sales in 2023.  
This repo contains the Excel analysis and a summary of key questions, insights, and recommendations.

---

## 🎯 Objective
Create an annual sales report for 2022 that answers core business questions and turns findings into concrete actions for 2023.

---

## 📁 What’s in this repo
**`Vrinda Store Data Analysis.xlsx`** — the main workbook with:

- **Dataset 2022** — cleaned, row-level order data  
- **Order vs Sales** — monthly trend comparison  
- **Order Status** — distribution of Delivered / Returned / Cancelled / Refunded  
- **Sales Men vs Women** — gender breakdown  
- **Sales Top 5 States** — regional contribution  
- **Age 'N' Gender** — age group × gender analysis  
- **Orders Channels** — channel contribution (Amazon, Flipkart, Myntra, etc.)  
- **Report 2022** — a compact dashboard view  

---

## 🔎 Business questions answered
- Compare sales vs orders in a single view  
- Highest month by sales and by orders  
- Who purchased more: men or women?  
- What are the order statuses for 2022?  
- Top 5 states by sales  
- Age × Gender pattern of orders  
- Which channel contributes the most sales?  
- Highest-selling category  

---

## 📊 Headline findings (from the Excel data)
- **Peak month**: March (highest by both orders and sales)  
- **Gender (share by rows)**: Women ~69.4%, Men ~30.6%  
- **Order status mix**: Delivered ~92.3%, Returned ~3.4%, Cancelled ~2.7%, Refunded ~1.7%  
- **Top 5 states by sales**: Maharashtra, Karnataka, Uttar Pradesh, Telangana, Tamil Nadu  
- **Age contribution (by orders)**: Adult (30–49) ~49.5%, Young ~30.5%, Senior ~20.0%  
- **Top channels by sales**: Amazon ~35.5%, Myntra ~23.3%, Flipkart ~21.6% (≈ 80% combined)  
- **Highest-selling category**: *Set*  

*(All percentages are rounded for readability.)*

---

## ✅ Conclusion & 2023 playbook
Focus efforts where the upside is largest:

- **Target segment**: Women, 30–49 years (Adult group)  
- **Regions**: Maharashtra, Karnataka, Uttar Pradesh  
- **Channels**: Amazon, Flipkart, Myntra (optimize placements, coupons, and ad spend)  
- **Offers**: Time promotions and stock to March seasonality; feature *Set* category prominently  

---

## 🧪 How to use the workbook
1. Open `Vrinda Store Data Analysis.xlsx`  
2. Explore pivots: monthly trends, channel split, states, age × gender  
3. Refresh data/hooks if you replace Dataset 2022 with a newer extract  
4. Use **Report 2022** as a one-page dashboard for presentations  

---

## 🔧 Methods & assumptions (quick notes)
- Aggregations are done via Excel pivots on `Dataset 2022`  
- **Sales = sum of Amount; Orders = count of Order_ID (as rows)**  
- Gender, age group, and channel stats use share of rows unless specified as sales share  
- Minor rounding applied; sheet/column names normalized where needed  

---

## 📌 Roadmap (nice-to-haves)
- Add a “Refresh & Rebuild” macro for one-click pivot refresh  
- Create a lightweight Power BI / Tableau version of the dashboard  
- Add cohort retention (repeat buyers) and RFM segmentation  
- Forecast 2023 using simple seasonal baselines (+/− campaign lift)  
