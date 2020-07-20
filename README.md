# Sakila DVD Rental database 

## Overview:
n this project, you will use SQL to explore a database related to movie rentals. You will write SQL code to run SQL queries and answer interesting questions about the database. As part of your project submission, you will run SQL queries and build visualizations to showcase the output of your queries.

We will begin by getting familiar with the database. We have included Practice Quizzes that include a series of questions that will assure you have mastered the main concepts taught throughout the SQL lessons. These practice quizzes will not be "graded" by a reviewer, but they will help you self-assess and make sure you are on the right track. The quizzes are there to assist you in understanding the database before developing the questions that you wish to include for the project.



## Introduction

In this project, you will query the Sakila DVD Rental database. The Sakila Database holds information about a company that rents movie DVDs. For this project, you will be querying the database to gain an understanding of the customer base, such as what the patterns in movie watching are across different customer groups, how they compare on payment earnings, and how the stores compare in their performance. To assist you in the queries ahead, the schema for the DVD Rental database is provided below.



## Let's set up your local environment
# What is PostgreSQL?
PostgreSQL is an object-relational database management system. Object-relational databases use a hybrid approach to databases.

In object databases, information is stored as objects, much like object-oriented programming.
In relational databases, information is stored in tables with relationships between tables defined by primary and foreign keys.
Importantly, PostgreSQL allows the use of advanced functions (such as Window Functions), and even development and use of custom functions written in different programming languages. Here is a link to better understand what is meant by an object-relational database, and how it differs from a relational database.
https://en.wikipedia.org/wiki/Object-relational_database

Ready to proceed with PostgreSQL? Follow along!

## Step 1. Downloading PostgreSQL
First, you will need to install PostgreSQL on your local machine. The instructions below provide detailed description of the steps you need to take.

# Installing PostgreSQL for Windows:
http://www.postgresqltutorial.com/install-postgresql/

# Installing PostgreSQL for Mac OS:
https://www.postgresql.org/download/macosx/

Friendly reminder! Please write down the database superuser (postgres) password as you will need it to create the Sakila database once you have installed the PostgreSQL server.

# Step 2. Downloading Sakila database
Once PostgreSQL server is installed, you will need to download the Movie database from this page: PostgreSQL Sample Database

Scroll down and click on the orange "Download DVD Rental Sample Database" button.

This will download a zipped file, and you will need to extract the dvdrental.tar file.

## Step 3. Loading database
The next step is to load the DVD Rental database into your PostgreSQL server on your machine. We recommend using the PgAdmin tool. You will find the instructions to do so on the following link: Load PostgreSQL Sample Database.

## Step 4. Connecting back to the PostgreSQL server:
Relaunch PgAdmin III and click on the PostgreSQL server within the Object browser. The screenshot below shows the red arrow pointing to PostgreSQL server. Click it and enter your superuser (postgres) password.

## Step 5. Connecting to the DVD rental database:
Next click on the plus sign next to Databases to access the DVD rental database. The screenshot below shows the red arrow pointing to Databases.

## Step 6. Choose the DVD Rental database
Choose the dvdrental database under Databases. The red arrow in the screenshot is pointing towards the dvdrental database.

You should now be linked to the DVD rental database.

## Step 7. Running Queries on your dvdrental database
Ready to run some queries?? Click on the SQL icon with a magnifying glass (see the screenshot below with the red square on the icon).












