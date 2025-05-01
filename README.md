# 🛒 Task 7: Basic Sales Summary from SQLite using Python

This project connects to a small SQLite database, performs a sales summary query using SQL, and visualizes the results with a bar chart.

---

## ✅ Objective

- Connect to `sales_data.db` using `sqlite3`
- Run a SQL query to summarize sales by product
- Load the results into a `pandas` DataFrame
- Print the summary table
- Plot a bar chart of revenue by product using `matplotlib`

---

## 🛠️ Tools Used

- Python
- SQLite (via `sqlite3`)
- pandas
- matplotlib

---

## 📦 Sample Data Inserted

```python
[
    ('Apples', 10, 0.5),
    ('Apples', 5, 0.5),
    ('Bananas', 8, 0.3),
    ('Oranges', 12, 0.7),
    ('Bananas', 6, 0.3),
    ('Oranges', 4, 0.7)
]
```
---

## 📈 Output

- Console: Prints total quantity and revenue per product
  
![Records](https://github.com/user-attachments/assets/f4a5f4ce-05b2-4d2e-bc7e-d6a0a05c2899)

- Chart: A bar chart (sales_summary_chart.png) shows revenue per product
  
![Revenue by product](https://github.com/user-attachments/assets/6b01192b-9ca3-4e72-a206-3f7226740378)

---

## 🎓 What I Learned
- How to create and query an SQLite database using Python
- Use SQL to compute simple aggregates
- Load SQL results into pandas
- Visualize data using matplotlib
- Integrate Python data workflows with SQL queries
This task improved my understanding of SQL integration in Python-based data workflows and basic reporting visualizations.
