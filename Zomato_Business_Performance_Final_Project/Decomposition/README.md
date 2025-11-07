# 🍽️ Zomato Business Performance Analysis

### 🔍 Project Plan Decomposition

After I chose my research focus, I designed a decomposition plan defining the **key metrics**, **parameters**, and **dashboard components** for analysis. I studied the data upfront to understand its structure and define clear objectives for the project.  

**Goal:** Analyze which restaurants are most popular, generate the highest revenue, and determine why.  
**Hypothesis:** Restaurants offering popular cuisines and maintaining high customer ratings tend to achieve the highest revenue.

---

### ❓ Research Questions
- What is the most popular cuisine based on the data?  
- Which restaurants have the highest total ratings?  
- How do cuisine popularity and ratings influence business performance?  
- Are the most popular restaurants large chains or local favorites?

---

### 🧩 Before the Visualizations

**Layout Plan:**  
Most popular restaurants → most popular cuisines → ratings overview → final dashboard with consolidated insights.

**Data Preparation:**
- Utilized **restaurant** and **orders** tables from provided spreadsheets.
- Converted `.csv` files into `.xlsx` format for Tableau compatibility.  
- Cleaned and standardized data using `TRIM()`, `UPPER()`, and `LOWER()` functions.  
- Identified and managed `NULL` or missing values for critical fields (e.g., restaurant name).  
- Applied **inner joins** in Tableau to remove broken or irrelevant data.

---

### 📊 Visualizations
- **Bar chart:** Restaurants ranked by revenue (highest → lowest).  
- **Bar chart:** Cuisines ranked by revenue (highest → lowest).  
- **Bar chart:** Restaurants ranked by average ratings.  
  - Filtered to display **Top 5** restaurants in each chart.  
  - Adjusted to weight ratings by number of reviews for fairness.  
- **Scatter plot:** Correlation between **ratings (Y‑axis)** and **revenue (X‑axis)**.  
  - Each point represents a restaurant, showing trends between performance metrics.  

**Tool Used:** Tableau (chosen for ease of use and shareability).  

---

### 🧠 Dashboard Overview
Four interactive panels presenting summarized insights:
- **Top Left:** 5 most popular restaurants  
- **Top Right:** 5 most popular cuisines  
- **Bottom Left:** 5 highest‑rated restaurants  
- **Bottom Right:** Scatterplot showing correlation between ratings and revenue  

Each visualization includes annotations and Tableau slides describing how cuisine type and ratings influence restaurant performance.

---

### 🪄 Project Workflow Outline

**Before Importing Data:**  
1. Convert spreadsheets to `.xlsx`.  
2. Clean data using `TRIM()`, `UPPER()`, `LOWER()` functions.  
3. Import datasets into Tableau.  
4. Create inner join between **Orders** and **Restaurants** tables.

**Visualization Order:**  
Cuisine Revenue → Popular Restaurants → Cuisine Type → Restaurant Ratings → Scatter Plot (Ratings vs Revenue).

**Dashboard Assembly:**  
Add top 5 restaurant and cuisine charts, scatterplot visual, and interactive filters/sliders. Finalize with a clear Tableau presentation summarizing findings.

---

### 🧾 Summary
This project showcases my ability to perform **data cleaning, joining, visualization design, and insight storytelling** using Tableau—all while analyzing real‑world business performance metrics in the restaurant industry.


