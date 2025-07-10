# 📚 SQL Book Review Analysis – Data-Driven Product Insights

## 📁 Project Summary

This bootcamp project analyzes a SQL database containing information about books, authors, publishers, user ratings, and reviews to uncover key trends that can help shape a compelling value proposition for a new product in the book market.

---

## 🎯 Objectives

Using SQL queries, this project aims to:

- Analyze book publication trends post-2000
- Investigate user engagement through ratings and reviews
- Identify top publishers and authors based on engagement and content volume
- Understand the behavior of highly active users

---

## 🗃️ Dataset Overview

### `books`
- `book_id`: Unique book ID  
- `author_id`: Author’s ID  
- `title`: Title of the book  
- `num_pages`: Number of pages  
- `publication_date`: Publication date  
- `publisher_id`: Publisher ID  

### `authors`
- `author_id`: Unique author ID  
- `author`: Author’s name  

### `publishers`
- `publisher_id`: Unique publisher ID  
- `publisher`: Publisher name  

### `ratings`
- `rating_id`: Unique rating ID  
- `book_id`: Related book ID  
- `username`: Name of the user who rated  
- `rating`: User rating (e.g. 1–5)  

### `reviews`
- `review_id`: Unique review ID  
- `book_id`: Related book ID  
- `username`: Name of the user who reviewed  
- `text`: Text of the review  

---

## 🧠 Analytical Tasks

1. **Books Published Post-2000**  
   - Count how many books were published after January 1, 2000.

2. **User Engagement per Book**  
   - For each book, calculate:  
     - Number of reviews  
     - Average rating  

3. **Top Publisher (Excluding Pamphlets)**  
   - Identify the publisher with the most books having **more than 50 pages**.

4. **Highest-Rated Author**  
   - Among authors with books having **at least 50 ratings**, find the one with the highest average rating.

5. **Power Users – Text Reviews**  
   - Among users who have rated **more than 50 books**, find the **average number of written reviews**.

---

## 🛠️ Tools & Technologies

- SQL (PostgreSQL or SQLite)
- Jupyter Notebook (for query output and markdown documentation)
- Data exploration with `pandas` (optional, if integrated)

---

## 📈 Project Structure

Each step includes:

- SQL query
- Output table
- Brief explanation of insights

All queries are executed directly in the notebook environment and presented clearly with headings and comments.

---

## 🧾 Key Outcomes

This analysis helps answer questions like:

- Are more modern books (post-2000) dominant in the dataset?
- Which publishers are the most active with substantial content?
- Which authors produce highly-rated, widely-reviewed content?
- How engaged are top users, and how often do they write reviews?

