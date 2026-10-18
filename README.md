# Bookstore Inventory and Analytics System

**Student Name:** Shrey Shah  
**Institute:** Red & White Skill Education  
**Project:** Data Analysis Course

## Project Overview

The Bookstore Inventory and Analytics System is a Python-based project designed to help a bookstore manage books, record sales, analyze revenue, and visualize sales trends.

## Objectives

- Add, remove, and update books in the inventory.
- Record book sales and automatically update available stock.
- Calculate inventory value, average book price, units sold, and total revenue.
- Identify best-selling books and monthly revenue trends.
- Create charts using Matplotlib and Seaborn.
- Store inventory and sales records in CSV files.

## Technologies Used

- **Python:** program logic, loops, conditions, functions, and exception handling.
- **OOP:** `Bookstore` class and reusable methods.
- **NumPy:** numerical calculations and arrays.
- **Pandas:** CSV data handling, cleaning, grouping, merging, and analysis.
- **Matplotlib:** charts and graphs.
- **Seaborn:** visualizations and correlation heatmaps.
- **CSV file handling:** saving and loading inventory and sales data.

## Project Files

```text
Bookstore_Project/
├── bookstore_system.py
├── inventory.csv
├── sales.csv
└── README.md
```

- `bookstore_system.py`: Main Python program.
- `inventory.csv`: Book title, author, genre, price, and stock quantity.
- `sales.csv`: Sale date, book title, quantity sold, and total revenue.
- `README.md`: Project description and instructions.

The program creates sample CSV files automatically if they do not already exist.

## Installation

Install Python, then open a terminal in the project folder and run:

```bash
python -m pip install numpy pandas matplotlib seaborn
```

## How to Run

1. Open the project folder in Visual Studio Code.
2. Open **Terminal → New Terminal**.
3. Run:

   ```bash
   python bookstore_system.py
   ```

4. Choose an option from the menu and follow the prompts.

## Main Features

1. **Show Inventory** — display all available books.
2. **Add a Book** — add a book or update an existing title's details and stock.
3. **Remove a Book** — remove a title from inventory.
4. **Update Stock** — set a book's available quantity.
5. **Record a Sale** — record units sold, calculate revenue, and reduce stock.
6. **Generate Report** — summarize stock, inventory value, average price, units sold, revenue, and best-selling books.
7. **Create Visualization** — generate:
   - Bar chart: units sold by book.
   - Line graph: monthly sales revenue.
   - Pie chart: revenue share by genre.
   - Heatmap: correlation between price and units sold.
8. **Import Inventory CSV** — load inventory data from another CSV file.
9. **Save All Data** — save inventory and sales records.
10. **Exit** — save data before exiting.

## Dataset Columns

### `inventory.csv`

| Column | Description |
|---|---|
| `Title` | Name of the book |
| `Author` | Book's author |
| `Genre` | Category of the book |
| `Price` | Price per book |
| `Quantity` | Available stock |

### `sales.csv`

| Column | Description |
|---|---|
| `Date` | Sale date in `YYYY-MM-DD` format |
| `Title` | Book sold |
| `Quantity Sold` | Number of copies sold |
| `Total Revenue` | Revenue from the sale |

## Concepts Demonstrated

- Variables, functions, loops, and conditional statements.
- Classes, objects, constructors, and methods.
- NumPy arrays and numerical calculations.
- Pandas DataFrames, data cleaning, grouping, and merging.
- CSV file reading and writing.
- Exception handling and input validation.
- Data visualization and interpretation.

## Notes

- Keep the Python script and CSV files in the same working folder.
- Record at least one sale before creating sales charts.
- Check that imported CSV columns match the required names.
- The heatmap shows correlation; it does not prove that price causes a change in sales.

---

**Prepared by:** Shrey Shah  
**Course:** Data Analysis  
**Institute:** Red & White Skill Education
