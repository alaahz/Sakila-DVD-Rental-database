# Sakila-DVD-Rental-database
The Sakila Database holds information about a company that rents movie DVDs.

# _Introduction:_
 In this project, you will query the Sakila DVD Rental database. The Sakila Database holds information about a company that rents movie DVDs. For this project, you will be querying the database to gain an understanding of the customer base, such as what the patterns in movie watching are across different customer groups, how they compare on payment earnings, and how the stores compare in their performance. To assist you in the queries ahead, the schema for the DVD Rental database is provided in the dvd-rental-erd.pdf.

# _Local Environment_
**Step 1. Downloading PostgreSQL:**

PostgreSQL is an object-relational database management system. Object-relational databases use a hybrid approach to databases:
[PostgreSQL](https://www.postgresqltutorial.com/postgresql-getting-started/)

**Step 2. Downloading Sakila database:**

Once PostgreSQL server is installed, you will need to download the Movie database from this page:
[Database](https://www.postgresqltutorial.com/postgresql-sample-database/)

**Step 3. Loading database & Connecting :**

The next step is to load the DVD Rental database into your PostgreSQL server on your machine: [How to load database](https://www.postgresqltutorial.com/load-postgresql-sample-database/)

**Step 4. Connecting back to the PostgreSQL server:**

Relaunch PgAdmin III and click on the PostgreSQL server within the Object browser:
[Connect To a PostgreSQL](https://www.postgresqltutorial.com/connect-to-postgresql-database/)

# _Questions_

**Question 1:**

We want to understand more about the movies that families are watching. The following categories are considered family movies: Animation, Children, Classics, Comedy, Family and Music.

**Create a query that lists each movie, the film category it is classified in, and the number of times it has been rented out.**

**Question 2:**

Now we need to know how the length of rental duration of these family-friendly movies compares to the duration that all movies are rented for.
 **Can you provide a table with the movie titles and divide them into 4 levels (first_quarter, second_quarter, third_quarter, and final_quarter) based on the quartiles (25%, 50%, 75%) of the rental duration for movies across all categories?**
Make sure to also indicate the category that these family-friendly movies fall into.

**Questions 3:**

 Provide a table with the family-friendly film category, each of the quartiles, and the corresponding count of movies within each combination of film category for each corresponding rental duration category. The resulting table should have three columns:

- _Category_
- _Rental length category_
- _Count_



**Question 4:**

We want to find out how the two stores compare in their count of rental orders during every month for all the years we have data for.

**Write a query that returns the store ID for the store, the year and month and the number of rental orders each store has fulfilled for that month. Your table should include a column for each of the following: year, month, store ID and count of rental orders fulfilled during that month.**
