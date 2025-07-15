# 🎵 Music Store SQL Data Analysis Project

## 📌 Objective
The goal of this project is to perform comprehensive data analysis on a digital music store's relational database using SQL. By analyzing customer behavior, sales data, and musical trends, we extract business insights that can inform strategy, marketing, and operations.

---

## 🧱 Database Schema Overview

This relational database consists of the following key entities:

- **Customer**: Personal and contact information of each customer.
- **Invoice**: Each purchase made by customers.
- **InvoiceLine**: Line-by-line details of tracks purchased in each invoice.
- **Track**: Information about each music track.
- **Album**: The album associated with each track.
- **Artist**: The artist or band who performed the album.
- **Genre**: The genre of the track.
- **MediaType**: Type of media (e.g., MPEG audio, AAC audio).
- **Employee**: Music store employees (used for reporting structure).
- **Playlist / PlaylistTrack**: Information about playlists and their included tracks.

---

## 📂 Dataset Source

- The project is based on a cleaned and normalized SQL database schema commonly used for music store demos.
- The dataset is publicly available and consists of CSV and relational tables.

---

## 🧠 Skills Applied

- Advanced SQL Joins (INNER JOIN, LEFT JOIN)
- Aggregation with `GROUP BY` and filtering using `HAVING`
- Window functions and subqueries
- Conditional logic with `CASE`
- Data ranking using `RANK()` and `ROW_NUMBER()`
- Analytical problem-solving using relational modeling

---

## 📊 Question Sets and Analysis Performed

### 🔹 Easy Level

1. Identify the **senior-most employee** by job title.
2. Determine **which countries have the most invoices**.
3. Find the **top 3 invoices by total value**.
4. Locate the **city with the highest revenue** – the best place for a promotional event.
5. Discover the **best customer** based on total spend.

---

### 🔸 Moderate Level

1. List all **Rock music listeners** with their emails and genres.
2. Find the **top 10 rock artists** based on number of rock tracks produced.
3. Return songs **longer than the average duration** and order by descending length.

---

### 🔺 Advanced Level

1. Calculate the **amount each customer spent on each artist**.
2. Identify the **most popular music genre per country** (based on purchases).
3. Determine the **top-spending customer in each country**, handling ties properly.

---

## 📈 Insights & Impact

- Identified top-performing **cities, countries, and customers**.
- Discovered **genre popularity by region**, guiding future licensing decisions.
- Tracked **customer preferences** to optimize marketing.
- Enabled targeting **premium customers and regions** with upsell opportunities.
- Helped the store identify artists and albums with the **highest monetization**.

---

## 💻 Tech Stack

- **SQL (PostgreSQL / MySQL compatible)**
- **DB Tools**: pgAdmin, MySQL Workbench, or SQLite Browser
- **Data Visualization (Optional)**: Power BI, Tableau, or Python (Matplotlib/Seaborn)

---

## 📦 Deliverables

- 📘 SQL Scripts for each question set (`easy.sql`, `moderate.sql`, `advanced.sql`)
- 📂 Raw datasets (CSV or .db formats)
- 📊 Screenshots or dashboards (if visualized)
- 📝 Summary report (this README + .pdf optional)

---

## 🔗 Reference

- Project Guide: [Rishabh Mishra YouTube Channel](https://www.youtube.com/@RishabhMishraOfficial)
- Dataset used from the music store database in `.db`/`.csv` format

---

## 🚀 How to Use

1. Clone this repo or download files manually.
2. Import the SQL schema and CSV data into your preferred DBMS.
3. Open and run the SQL scripts inside your SQL editor.
4. Review results in table format or export for visualization.

---

## 🙌 Acknowledgements

Special thanks to the creators of the sample music store database schema and [Rishabh Mishra](https://www.youtube.com/@RishabhMishraOfficial) for the guided problem set.

---
