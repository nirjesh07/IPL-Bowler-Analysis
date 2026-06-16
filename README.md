# IPL T20 Performance Analytics Pipeline

An end-to-end data engineering pipeline using **Python, Pandas, and SQLite** to analyze multi-GB IPL datasets and rank the top 10 death-overs (Overs 16-20) bowlers.

## 🚀 Key Features
* **Data Cleaning:** Pandas used for data formatting and handling missing values.
* **Database Layer:** Built an in-memory infrastructure using **`sqlite3`** for SQL queries.
* **Filter:** Applied `HAVING total_balls >= 120` to eliminate outliers.
* **Charts:** Programmatically generated visualizations using **Matplotlib**.

## 🛠️ Tech Stack
* Python, Pandas, Matplotlib, SQL (SQLite), VS Code

## 📊 Key Insights
* **Death-Overs (16-20):** Most volatile phase where standard metrics fail.
* **Threshold (>= 120 Balls):** Ensures only seasoned death specialists are evaluated.
* **Dual-Metric:** Combined low Economy with high Dot-Ball % to measure real pressure.

## 🏃‍♂️ How to Run
1. **Clone:**
```bash
   git clone https://github.com/nirjesh07/ipl-performance-pipeline.git
```
2. ​Install: pip install pandas matplotlib

3. ​Run: Execute the Jupyter notebook to spin up the DB and generate charts.
