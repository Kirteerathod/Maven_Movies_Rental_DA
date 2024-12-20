
# Maven_Movies_Rental_DA
Data analysis of movies CD/DVD rental (transactions) and inventory

# Maven Movies Data Analysis: Enhancing Insights for a Rental Business

## Project Overview:
This project analyzes a movie rental business's database to provide actionable insights for improving operations, marketing strategies, and inventory management. The dataset is hosted in the MAVENMOVIES database, and SQL was extensively used for exploratory data analysis (EDA), schema understanding, and answering business-critical ad-hoc queries.

## Project Objectives:

### Customer Insights:

Identify customer details (names, emails) for targeted marketing campaigns.
Analyze customer rental patterns to improve customer engagement.

### Movie Inventory Analysis:

Explore the rental inventory and classify movies based on rental rates and availability.
Provide recommendations for expanding the movie collection based on popularity and rental rates.
Revenue Optimization:

Analyze rental rates to identify trends and the profitability of various pricing categories.
Determine the most rented movie categories and ratings to maximize revenue.

### Operational Efficiency:

Help track and manage movie inventory effectively.
Highlight gaps in the inventory and optimize stock levels.


# Tools & Library Used
[<img src="./IMAGES/mysql.png" alt="mysql.png" width="100"/>](https://www.mysql.com/) &nbsp;

# Project Result

[Click here to get full code](https://github.com/Kirteerathod/Maven_Movies_Rental_DA/blob/main/MOVIES_RENTAL_CODE.sql)

# Query Task

1. How can we extract the first name, last name, and email address of all customers to prepare a comprehensive contact list for the marketing team?
 
   [<img src="./IMAGES/email id list.png" alt="email id list.png" width="400"/>] &nbsp;


3. What is the total number of movies in the inventory that are available for rent at the lowest rental rate of $0.99?

    [<img src="./IMAGES/CHEAPEST RENTAL.png" alt="CHEAPEST RENTAL.png" width="400"/>] &nbsp;


5. How can we categorize all movies based on their rental rates and determine the count of movies in each category?

    [<img src="./IMAGES/TOTAL_NUMBER_OF_MOVES.png" alt="TOTAL_NUMBER_OF_MOVES.png" width="400"/>] &nbsp;


7. Which movie rating (e.g., PG, PG-13, R) has the highest number of titles in the inventory, and how can this information help optimize inventory management?

   [<img src="./IMAGES/RATING_WISE_COUNT.png" alt="RATING_WISE_COUNT.png" width="400"/>] &nbsp;


8. What is the total count of PG-rated movies that have been rented, and what does this indicate about customer preferences?

  [<img src="./IMAGES/TOTAL_FILMS.png" alt="TOTAL_FILMS.png" width="400"/>] &nbsp;
  
6. What are the inventory IDs and corresponding film titles for movies that are currently rented out, and how can this data help track rental activity?

   [<img src="./IMAGES/POPULARITY.png" alt="POPULARITY.png" width="400"/>] &nbsp;

7. -- List of films by filmname,category,language.

   [<img src="./IMAGES/CATEGORY_NAME.png" alt="CATEGORY_NAME.png" width="400"/>] &nbsp;

8. -- Revenue Per film (top 10 grosser)

   [<img src="./IMAGES/GROSS REVENUE.png" alt="GROSS REVENUE.png" width="400"/>] &nbsp;

9. -- Which store has historically brought tye most revenue
    
   [<img src="./IMAGES/STORE_REVENUE.png" alt="STORE_REVENUE.png" width="400"/>] &nbsp;

11. -- How Many Rental We Have For Each Month

    [<img src="./IMAGES/RENTAL_PER_MONTH.png" alt="RENTAL_PER_MONTH.png" width="400"/>] &nbsp;

12. -- Reward users who have rented at least 30 times (WITH DETAILS OF CUSTOMER)

   [<img src="./IMAGES/NUMBER_OF_CUSTOMER.png" alt="NUMBER_OF_CUSTOMER.png" width="400"/>] &nbsp;

12. -- Could you pull all payment from our first 100 customer (Based on customer_id)

       [<img src="./IMAGES/first 100 customer.png" alt="first 100 customer.png" width="400"/>] &nbsp;

14. -- Now, could you please write a query to pull all payments from those specific customers, along with payments over $5, from any customer?

      [<img src="./IMAGES/payment_from_specificcustomer.png" alt="payment_from_specificcustomer.png" width="400"/>] &nbsp;
