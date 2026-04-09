# SQL
# 🎬 Prime Video SQL Database Project

## 📌 Overview

This project is a SQL-based database system that simulates a streaming platform similar to Prime Video. It includes structured data for users, movies, subscriptions, watch history, and ratings.

The project demonstrates database design, data manipulation, and advanced SQL querying techniques.

## 🗂️ Database Structure

The database consists of the following tables:

* **Users** – Stores user details such as name, email, country, and subscription plan
* **Movies** – Contains movie information like title, genre, release year, and duration
* **Subscriptions** – Tracks user subscription periods
* **WatchHistory** – Records movies watched by users and duration
* **Ratings** – Stores user ratings and reviews for movies



## 🛠️ Technologies Used

* SQL (MySQL)
* Database Design
* Data Analysis using Queries



## 📊 Features & Queries

### 🔹 Basic Queries

* View all users, movies, subscriptions, ratings, and watch history

### 🔹 Filtering Queries

* Find premium users
* Movies released after a certain year
* Ratings above a threshold

### 🔹 Aggregation Queries

* Count users by country
* Average movie ratings
* Total watch time per user

### 🔹 Join Queries

* User subscription details
* User ratings with movie names
* Watch history with movie details

### 🔹 Advanced Queries

* Top 5 most watched movies
* Top 5 highest-rated movies
* Users who watched more than 5 movies

---

## 📂 Project File

* `Prime Video Project sql.sql` 



## 🚀 How to Run

1. Open MySQL Workbench or any SQL tool
2. Create a new database:

   ```sql
   CREATE DATABASE PrimeVideo;
   USE PrimeVideo;
   ```
3. Run the SQL script file
4. Execute queries to explore the data



## 💡 Key Learning Outcomes

* Database schema design
* Writing complex SQL queries
* Working with joins and aggregations
* Data analysis using SQL




* Create views for analytics
* Integrate with frontend/dashboard
