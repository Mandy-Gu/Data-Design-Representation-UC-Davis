# Data-Design-Representation-UC-Davis
## Introduction:
The followings are three projects about Data Design & Representation done within UC Davis courses

## Project 1: Scrape the website with login account
*Part 1*
1. Scrape and download the content to the local system from the website
2. Leverage regex to do analysis about the content

*Part 2*
1. Create an account on the website
2. Log in my account by Python for further scraping some specific content that is only viewed by **login users**
3. Scrape the website with the current status and print out my account name to verify that I'm truly logged in

## Project 2: Store content scraped from a website to MySQL and conduct analysis upon it
*Part 1*
1. Understand how the API of the website works
2. Scrape information from the website through the use of that API

*Part 2*
1. Scrape the first 10 pages of search result for PS4 (each page contains 100 items)
2. Identify the pattern of sponsored items appearing on the website, extract sponsored items and non-sponsored items to 2 separate files and store them in the local system
3. Retrieve information such as the price of the item and return policy from the page and deal with different exceptional situations 
4. Store all the information to **MySQL database** (each row includes all information for an item)
5. Conduct analysis based on data extracted from MySQL (for instance: how to predict if the item is sponsored)

## Part 3: Leverage MapReduce to aggregate huge amount of data efficiently
1. Connect Python to MongoDB
2. Store json file to MongoDB line by line
3. Utilize **MapReduce** to carry out analysis highly efficiently instead of using aggregation function 
