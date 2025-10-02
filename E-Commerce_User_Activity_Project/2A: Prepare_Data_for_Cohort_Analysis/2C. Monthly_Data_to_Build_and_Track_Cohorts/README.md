📊 I needed to group users and transactions by month to prepare my data for the cohort analysis.
- Even though I already had both the event_date and first_purchase_date in the “purchase_activity” sheet, I created three new columns to build the cohorts:
  - Event_month
  - First_purchase_month
  - Cohort_age
- 🗓️ In column H, I used the TEXT() function to format the event_date into event_month.  
- 📆 In column I, I repeated the process to create first_purchase_month, making sure to use the YYYY-MM format since the dataset covered multiple years.  
- 🔢 Finally, in column J, I used the DATEDIF() function to calculate cohort_age, measuring the number of months between the first purchase date and the event date.
- ✅ I checked my results and confirmed that the cohort ages ranged properly from 0 to 4 months.

<img width="1238" height="184" alt="image" src="https://github.com/user-attachments/assets/aa833e7c-d81d-4257-8edc-811999f082b9" />
