## Part 3: App Reviews 📊🔗  
- I created a new sheet in my .pbix file for this section and named it App Reviews. 🗂️✨  

- In the data model, I created a new relationship between the Reviews table and the Apps table. 🔄  
- I used the app_id column from the Reviews table and the id column from the Apps table, making the relationship many-to-one, where many corresponds to the Reviews table and one corresponds to the Apps table. 🔢➡️1  

- Using this new relationship, I created a Bar Chart with the developer on the X-axis and the sum of rating on the Y-axis. 📉👨‍💻⭐  

- Since that chart could be misleading—because an app may have a high sum of ratings simply due to many one-star reviews ⚠️⭐, I made another Bar Chart with the developer on the X-axis and the helpful_review average on the Y-axis. 📊💡  

- Finally, I built a Bar Chart to show which developers are the most responsive 🙋‍♂️🙋‍♀️, using the developer field from the Apps table and the developer_answered column I created earlier.  
- I applied a Filter to this chart only, so it includes only rows where reviews_count is greater than 500. 🎯📈

<img width="497" height="406" alt="Updated_App_Reviews_FullScreen" src="https://github.com/user-attachments/assets/43eed4dd-c41b-4326-9244-38c6234f640a" />
