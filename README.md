# Data Engineer Coding Challenge
This page contains a coding challenge for Data Engineering roles at STAND 8.

# Purpose
The goals of this test are threefold:
- evaluate your coding abilities
- judge your technical experience
- understand how you design a solution

# How you will be judged
You will be scored on:
1. coding standard, comments, and style
2. unit testing strategy
3. overall solution design
4. appropriate use of source control

# Instructions
- You may use any Open Source database (i.e. MySQL, PostgreSQL, MariaDB, MongoDB, etc.) for storing results 
- Candidate should put their test results on a public code repository hosted on Github
- Please include details on how to access the database you create
- Once test is completed, please share the Github repository URL with Rich Lucas (rlucas@stand8.io) so he can review your work
- You are building a backend application and no UI is required, input can be provided using a configuration file or command line

# Challenge – User Accounts and Viewing History
Create a solution that stores the content below in an Open Source database of your choice then makes it available to search via an API.

Table 1: table_video_viewing

Table 2: table_account_info


# Details
- Q1: Write a query that will return the first title watched for each user.
- Q2: Write a query that will give me total viewing time in minutes of each title in September 2021.
- Q3: Write a query that will give me the share of minutes (as a percentage) Ruthless was viewed in September 2021.
- Q4: Write a query that will give me the share of minutes viewed (as a percentage) with a premium account.
- Store the data in a hosted Open Source database for subsequent search and retrieval. 
- Write an API that provides access to the content in the database. 

# Bonus point
Deploy the solution as a public API using a cloud solution (either AWS, GCP, or Azure). The free tier is just fine.


