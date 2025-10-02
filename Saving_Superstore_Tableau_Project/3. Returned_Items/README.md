## In the last part of my analysis, I used the Returns table to check for products with abnormal return rates. 🔄

- I made sure to LEFT JOIN the Returns table onto the Orders table so I could see both “Yes” and “null” values in the Returned column. 🧩
- Next, I created a calculated field where null values became 0 and “Yes” values became 1, making it easier to quantify returns. ➕
- Using this field, I built visualizations to answer key questions:
  - 1️⃣ Which products have the highest return rates?
  - 2️⃣ Which customers have the highest return rates?
- Finally, I created a separate visualization comparing average profit against average return rate by a dimension of my choice. 📊
<img width="658" height="350" alt="image" src="https://github.com/user-attachments/assets/3037a522-309d-4b48-8dcf-2afb426ffce9" />
