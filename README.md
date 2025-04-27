# Data-Analyst_Day7



---

# MySQL Table Creation and Data Insertion Tutorial

This project demonstrates how to use Python to interact with a MySQL database. It covers the complete workflow starting from connecting to the database, creating tables, inserting records, querying data, and finally dropping the table.

## What You Will Learn

- Establishing a MySQL database connection using `mysql-connector-python`.
- Creating tables with SQL `CREATE TABLE` command.
- Inserting single and multiple records into the table.
- Querying and fetching:
  - All records
  - Single records
  - Particular rows and columns
  - Distinct column values
- Using conditional queries with `WHERE`, `OR`.
- Dropping tables using SQL `DROP TABLE`.

## Project Structure

```
notebook/
│
└── tavily_mysql_tutorial.ipynb    # Complete MySQL operation tutorial in Python
```

## Requirements

- Python 3.x
- MySQL Server installed and running locally
- Python packages:
  - `mysql-connector-python`

Install dependencies with:

```bash
pip install mysql-connector-python
```

## How to Run

1. Ensure your MySQL server is running.
2. Open the notebook `tavily_mysql_tutorial.ipynb`.
3. Update your MySQL credentials if needed (`host`, `user`, `password`, `database`).
4. Run the notebook cells sequentially to create, insert, query, and drop tables.

## Notes

- Make sure the database `student` already exists before running the notebook.
- Data inserted includes sample student names and subjects for testing queries.

## License

This notebook is open for educational and personal learning purposes.

---
