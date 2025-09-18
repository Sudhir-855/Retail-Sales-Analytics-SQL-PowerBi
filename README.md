
# 📚 Bookstore Data Analysis Project

## 🔍 Overview
This project analyzes a Bookstore dataset using **SQL** and **Power BI**.  
It provides insights into sales, customers, revenue, and stock management.

The project uses **3 datasets**:
- `books.csv` → Details of books (title, author, genre, price, stock, etc.)
- `customers.csv` → Customer details (name, city, country, etc.)
- `orders.csv` → Order details (order date, quantity, total amount, etc.)

---

## 📂 Project Structure
bookstore-data-analysis
│── data
│   ├── books.csv             # Dataset containing book details
│   ├── customers.csv         # Dataset containing customer details
│   ├── orders.csv            # Dataset containing order details
│
│── sql
│   ├── bookstore_queries.sql # SQL schema and analytical queries
│
│── reports
│   ├── bookstore_dashboard.pbix  # Power BI dashboard file
│   ├── bookstore_dashboard.pdf   # Exported dashboard (PDF with visuals)
│
│── README.md                 # Project documentation

---

##  Tools & Technologies
- **SQL** (for querying and analysis)
- **Power BI** (for dashboard and visualization)
- **GitHub** (for project hosting)

---

## 📊 Dashboard Insights
The **Power BI dashboard** includes:
- Total Orders, Books Sold, Customers, and Revenue
- Sales Revenue by Genre
- Yearly Sales Trend
- Top 5 Best-Selling Books
- Revenue by Author
- Geographic Distribution of Sales

📄[View Documentation on Google Drive] https://drive.google.com/file/d/1xgV3JsXHn7FgDUbAONnQ2QFXbpoDOPjx/view?usp=drive_link
---

## 🗄 SQL Queries
The `sql/bookstore_queries.sql` file contains:
- Retrieving books by genre
- Customers by country
- Orders by date range
- Revenue, stock, and sales analysis
- Most frequently ordered books
- Top customers and top authors

---[Download zomato_project.sql] https://drive.google.com/file/d/1ivih-QTm87h-uaylCOQDR1zg6btrNxax/view?usp=sharing


## How To Use
**1)Download the Repository:** git clone https://github.com/sudhir-855/bookstore-data-analysis.git
cd Retail-Sales-Analytics-SQL-PowerBi
Explore the Datasets

**2)Go to the data/ folder**. You will find:
books.csv → Book details (title, author, genre, price, stock)
customers.csv → Customer details (name, email, city, country)
orders.csv → Order details (date, book purchased, quantity, total amount)

**3)Run the SQL Queries**
Open the file sql/bookstore_queries.sql.
Import the CSV files into your database.
Run the queries in your SQL editor (MySQL/PostgreSQL/SQLite).

**4)Open the Power BI Dashboard**
Navigate to the reports/ folder.
Open bookstore_dashboard.pbix in Power BI Desktop.
Explore interactive visuals:
=Total Revenue & Orders
=Revenue by Genre and Author
=Top 5 Best-Selling Books
=Yearly & Monthly Sales Trends
=Geographic Distribution of Sales

