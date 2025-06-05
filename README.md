 📊 Task 3 – Amazon Sales Dashboard | Data Analytics Internship

 🔍 Objective
To build an interactive and insightful business intelligence dashboard using Power BI. The aim was to analyze an Amazon product sales dataset, derive key business metrics (KPIs), and design a dashboard that helps stakeholders make informed decisions.

---
 📁 Dataset Details
- Source: Kaggle – Amazon Product Sales and Review Dataset
- Rows: 1,465 entries
- Original Issues:
  - Currency symbols (₹), commas in numeric fields
  - Percentage signs (%) in discount columns
  - Text in numeric fields like `rating` and `rating_count`
- Solution:
  - Cleaned entirely using **Power BI Power Query (Transform Data)**
  - Removed invalid characters and converted data types
  - Handled errors using `IFERROR` logic and replaced with zeros
  - Removed unnecessary columns (like review text, URLs, etc.)

---

 🧰 Tools Used
- Power BI:  
  - Power Query for data cleaning and transformation  
  - DAX for calculations (e.g., Profit Estimation)  
  - Visualizations and KPI design
- GitHub: For task documentation and submission

---

📊 KPIs Tracked
- ✅ Total Sales (`discounted_price`)
- ✅ Total Profit Estimate (`actual_price - discounted_price`)
- ✅ Top 5 Products by Sales
- ✅ Average Product Rating
- ✅ Total Rating Count
- ✅ Sales by Category
- ✅ Sales vs Rating correlation

---

📈 Visuals Used in Power BI
- Card visuals for Total Sales, Profit, Ratings
- Bar Chart for Top 5 Products
- **Donut Chart for Category-wise Sales
- Scatter Plot for Sales vs Rating
- Slicers for filtering: Category, Rating, Discount %
- Calculated Column:
  DAX
  Profit_Estimate = [actual_price] - [discounted_price]
