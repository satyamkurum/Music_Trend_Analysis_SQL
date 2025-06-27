# 🎵 Music Trend Analysis (SQL Project)

A SQL-based project for analyzing trends in a music store database, including artist popularity, album sales, genre distribution, customer behavior, and more. This project uses raw SQL queries to derive actionable insights from a relational music database.

## 📁 Project Structure

```
📦 Music_Trend_Analysis_SQL/
├── Raw-Music Store Analysis-SQL Project/      # Original/raw analysis file(s)
├── MusicDatabaseSchema.png                    # ER diagram of the music database
├── Music_Store_Query.sql                      # Collection of SQL queries for analysis
├── Music_Store_database.sql                   # SQL schema and data dump for DB creation
├── album2.csv                                 # Supplemental CSV data
├── music store data.zip                       # Archived dataset
└── README.md                                  # Project overview
```

## 📌 Features

- Music database creation using PostgreSQL or MySQL
- SQL queries for trend analysis (artists, albums, genres, etc.)
- Schema diagram for database understanding
- Cleanly structured query file with comments
- Exportable data (CSV format) for visualization or BI tools

## 🔍 Use Cases

- Learning SQL with real-world schema
- Interview preparation (joins, aggregations, grouping, subqueries)
- Data analysis portfolio project

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/satyamkurum/Music_Trend_Analysis_SQL.git
cd Music_Trend_Analysis_SQL
```

### 2. Set Up the Database

Use any SQL RDBMS (recommended: PostgreSQL or MySQL).

```bash
# Example: PostgreSQL
psql -U your_user -d your_db -f Music_Store_database.sql
```

### 3. Explore the Queries

Open and execute queries from `Music_Store_Query.sql` to analyze trends in the music store.

### 4. View Schema

Check `MusicDatabaseSchema.png` to understand the relational schema.

## 🛠 Requirements

- Any SQL-compatible database (MySQL / PostgreSQL / SQLite)
- SQL client or DB management tool (e.g., pgAdmin, MySQL Workbench, DBeaver)
- (Optional) Python or Excel to analyze exported `.csv`

## 📊 Sample Queries

```sql
-- Top 5 selling artists
SELECT artist, COUNT(*) AS total_sales
FROM sales
GROUP BY artist
ORDER BY total_sales DESC
LIMIT 5;
```

## 🧠 Author

**Satyam Kurum**  
[GitHub Profile](https://github.com/satyamkurum)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

🔗 **Feel free to fork, star, or raise issues to contribute!**
