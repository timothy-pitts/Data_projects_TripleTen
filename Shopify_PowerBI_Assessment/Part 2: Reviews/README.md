## Part 2: Reviews 📝⭐  
- I created a new sheet in my .pbix file for this section and named it Reviews. 🗂️✨  

- I added a new Column in the Reviews table called helpful_reviews using a DAX expression that multiplies the rating by ___1+helpful_count___  to weigh the reviews by how helpful they have been found. ➕💬👍  

- The formula in mathematical form was ___rating × (1+helpful_count)___. 🧮🔢  

- I then created a Card that displays the average value of this new helpful_reviews column. 🎴📊  

- I added another new Column in the Reviews table named developer_answered using a DAX expression, where the value is 1 (TRUE) if the developer_reply column is not blank, and  
0 (FALSE) if that row is blank. ✔️❌👨‍💻  

- Finally, I created a Scatterplot comparing the average rating on the Y-axis against the value of the developer_answered column on the X-axis. 📈⚖️  

<img width="491" height="404" alt="Updated_Reviews_FullScreen" src="https://github.com/user-attachments/assets/6a548791-82c2-44c2-9ef1-3a1730882cd2" />
