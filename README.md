# IPL T20 Performance Analytics Pipeline

An end-to-end data engineering and analytics pipeline built using **Python, Pandas, and SQLite** to analyze multi-GB ball-by-ball IPL cricket datasets. The project specifically focuses on identifying and ranking the top 10 most efficient death-overs (Overs 16-20) specialist bowlers.

## 🚀 Key Features & Pipeline Workflow
* **Data Cleaning & Preprocessing:** Leveraged **Pandas** to clean, format dates, and handle missing values within the extensive ball-by-ball delivery and match-level tracking data.
* **In-Memory Database Layer:** Built a temporary, high-performance database infrastructure using Python's inbuilt **`sqlite3`** library to execute complex analytical SQL queries.
* **Consistency Threshold Filter:** Implemented strict query optimization filters (`HAVING total_balls >= 120`) to filter out anomalies and ensure only highly consistent death-overs bowlers are evaluated.
* **Dual-Metric Visualizations:** Programmatically generated insights using **Matplotlib/Pandas** to plot and contrast performance across two key data dimensions:
  1. Lowest Economy Rates in Death Overs
  2. Highest Dot-Ball Percentages (Utility & Pressure Optimization)

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, Matplotlib, sqlite3
* **Database Language:** SQL (SQLite)
* **Environment:** VS Code / Jupyter Notebook
*
