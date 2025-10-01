## I calculated the first purchase dates for each user so I could later assign them into cohorts. 
- 📊 Since I had already isolated purchase activity into its own table, I started by creating a pivot table on a new sheet called “first_purchase.”  
- 🗂️ I configured the pivot table to return the minimum event_date for every user, which gave me the earliest purchase date tied to each user ID.  
- 📥 Next, I needed to bring those first purchase dates back into my “purchase_activity” sheet.  
- 📝 I added a new column header in cell G1 called “first_purchase_date.”  
- 🔍 Then, in cell G2, I wrote a formula using VLOOKUP() to pull in the first purchase date from the “first_purchase” sheet, matching it against the user ID in cell A2.  
- ✅ Once I confirmed the ranges in my formula were correct, I copied it all the way down column G.  
- 🔎 To validate the data, I checked that none of the first_purchase_date values were later than their corresponding purchase_date values.  
