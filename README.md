# ☕ Coffee Shop Sales Dashboard

A complete data visualization project built using **Google Sheets** to analyze the sales performance of a coffee shop chain across multiple locations. The dashboard gives actionable insights into revenue trends, product popularity, and customer preferences — all derived from transactional data.

##  Project Objective :

To transform raw transactional data into a visually appealing and insightful dashboard that helps coffee shop managers and stakeholders understand:

- Which locations generate the highest revenue
- What product categories and sizes are most popular
- How sales vary by product type, store, and quantity
- How to use Google Sheets to create dynamic business dashboards


##  Dashboard Overview

The dashboard consists of six interactive charts:

1. **Location vs Product Type (Clustered Column)**  
   Visualizes how different products perform across stores (Astoria, Hell's Kitchen, Lower Manhattan).

2. **Highest Revenue by Store (Bar Chart)**  
   Shows total revenue earned by each store and helps identify top-performing branches.

3. **Popular Product Category (Column Chart)**  
   Displays the most sold product categories based on quantity.

4. **Size Share by Category (Pie Chart)**  
   Represents the proportion of each product category based on size type (Small, Regular, Large).

5. **Top Revenue-Generating Product Type (Bar Chart)**  
   Shows which individual products bring in the highest income.

6. **Location-wise Quantity Share (Pie Chart)**  
   Percentage distribution of total quantity sold at each store location.

---

##  Data Cleaning & Transformation

To prepare the data for analysis:

- **Extracted Size** from product names using text functions (`SEARCH`, `REGEXEXTRACT`)
- **Removed Size Tags** (e.g., "Rg", "Sm", "Lg") from product names using `SUBSTITUTE` and `REGEXREPLACE`
- **Split Date and Time** for time-based trends
- **Created Pivot Tables** to summarize data by location, category, product, size, etc.
- **Formatted Columns** for readability (currency, numbers, text)
- **Applied Filters** using slicers to make the dashboard interactive

---

## Tools & Techniques Used

- **Google Sheets** for spreadsheet modeling
- **Pivot Tables** for aggregations
- **Chart Types**: Bar, Column, Pie, Line
- **Formulas Used**:  
  - `REGEXREPLACE`, `SEARCH`, `SPLIT`, `SUBSTITUTE`, `IF`, `ARRAYFORMULA`
- **Data Types Handled**: Date, Time, Text, Currency

---

##  Key Insights

- 💰 **Lower Manhattan** generated the highest total revenue.
- ☕ **Coffee and Tea categories** dominate the transaction quantity.
- 📦 **Barista Espresso** and **Black Tea** are among the top-selling product types.
- 📍 Sales quantity is nearly equally distributed across the three store locations.
- 🧊 **Regular size** dominates over small and large in most categories.

---

##  How to Use

1. Clone or download this repo.
2. Open the Google Sheet linked in the repo.
3. Explore the dashboard using slicers (filters by store location or product).
4. Modify the source data to refresh all charts and tables dynamically.

---




