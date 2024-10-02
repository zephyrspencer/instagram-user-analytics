# instagram-user-analytics

Project Description: 
This project focuses on analyzing user engagement, marketing metrics, and detecting 
abnormal activity on a simulated Instagram platform using SQL. The goal is to 
provide actionable insights to both the marketing team and investors by answering 
specific business-related questions. These include identifying the most loyal and 
inactive users, finding the most popular hashtags, determining the contest winners, 
analyzing user engagement metrics, and detecting potential fake or bot accounts. The 
analysis will help guide marketing efforts, ensure healthy user activity, and highlight 
any issues with platform integrity. 

Approach: 
To tackle the tasks and derive insights, I followed a structured approach: 
1. Data Understanding: I reviewed the database schema and familiarized myself 
with key tables, such as users, photos, likes, comments, tags, and follows. 
2. Task Execution:
o For user engagement, I calculated average posts per user and compared 
total photos to total users. 
o For bot detection, I identified users who liked every single photo. 
o For marketing insights, I analyzed the most loyal users, inactive users, 
contest winners, and popular hashtags. 
o I also analyzed the best day for launching ad campaigns by checking 
registration trends. 
3. SQL Queries: I wrote targeted SQL queries to extract the relevant data for 
each task. I used aggregation functions like COUNT(), AVG(), and GROUP 
BY to perform calculations and identify trends in user behavior. 
4. Data Analysis: After retrieving the data from SQL, I analyzed the results, 
focusing on patterns in user behavior, engagement, and suspicious activity. 

Tech-Stack Used: 
 MySQL Workbench (Version 8.0): I chose MySQL Workbench as it is a 
robust and user-friendly tool for SQL database management and allows easy 
execution of complex queries and database design. 
 SQL (Structured Query Language): SQL was used to query the data, 
leveraging its powerful aggregation, joining, and filtering capabilities to derive 
meaningful insights. 
 Data Modeling: The database schema was designed using a relational model 
with foreign key constraints to maintain referential integrity between entities 
(users, photos, comments, etc.). 

Insights: 
From the data analysis, several important insights were derived: 
1. Loyal Users: The platform's five oldest users have been consistently active 
since its inception, indicating strong user loyalty. 
2. Inactive Users: A significant number of users have not posted any photos, 
which suggests an opportunity for re-engagement through targeted campaigns. 
3. Contest Winner: The top 3 users with the most-liked photos were identified, 
with one standing out as the clear contest winner. 
4. Popular Hashtags: The top five most frequently used hashtags were identified, 
providing valuable insights for brand partners to optimize their content 
strategy. 
5. Ad Campaign Timing: Most user registrations occur on weekends, suggesting 
that weekend ad campaigns might reach the largest number of new users. 
6. Bot Detection: Several users were flagged for having liked every single photo 
on the platform, indicating potential bot activity.

Result: 
This project provided valuable insights into user behavior on the platform. By 
identifying loyal and inactive users, I helped the marketing team shape their 
engagement strategies. The detection of bot-like activity also helped the team 
consider future security measures to maintain platform integrity. The analysis 
of popular hashtags and registration trends allowed the marketing and product 
teams to make data-driven decisions about future campaigns and feature 
prioritization. This project has enhanced my understanding of user data analysis 
and has demonstrated how SQL can drive business strategy and improve 
platform health.
