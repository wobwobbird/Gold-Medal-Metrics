# Gold Medal Metrics

A SQL learning project that powers an Olympic analytics web application.

This project is part of the **Codecademy skill path: "Create a Back-end App with JavaScript."**

## Task Summary

Implement **14 SQL query functions** in `sql.js` that power the application's backend. Each function returns a SQL query string that the Express server executes against a SQLite database.

**Note:** This project was provided as part of the Codecademy course. I only edited `sql.js` - all other files (frontend components, server setup, test suite, etc.) were provided by the course.

## Key SQL Concepts Learned

- `CREATE TABLE` with constraints (`NOT NULL`, `PRIMARY KEY`)
- `COUNT(*)` and `COUNT(DISTINCT column)` for aggregations
- `GROUP BY` for grouping data
- `ORDER BY` with `ASC`/`DESC` for sorting
- Subqueries for calculating percentages
- Conditional SQL query building in JavaScript

## Running the Project

1. Install dependencies: `npm install`
2. Compile frontend: `npm run webpack`
3. Start server: `node server.js`
4. Open `index.html` in a browser
5. Run tests: `npm test`

## Data

The project uses two CSV files:
- `data/country.csv` - Country information (201 countries)
- `data/goldmedal.csv` - Olympic gold medal records (12,406 medals)

Data is loaded into SQLite on server startup.
