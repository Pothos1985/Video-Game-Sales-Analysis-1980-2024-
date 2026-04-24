# 🎮 Video Game Sales Analytics (1980 - 2024)

## 📌 Project Overview
This project is an end-to-end data analysis of global video game sales. It follows a complete data lifecycle: from raw data ingestion and cleaning in **Python** to interactive business intelligence reporting in **Power BI**. 

The primary objective was to analyze market dominance across major platforms and evaluate the relationship between critic scores and global revenue.

## 🛠️ Tech Stack
* **Data Processing:** Python (Pandas) via Jupyter Notebooks.
* **Visualization:** Power BI (DAX, Power Query, Custom UI/UX design).
* **Version Control:** Git & GitHub.
* **Dataset:** `vgsales` (Comprehensive list of titles, genres, platforms, publishers, developers , and regional sales).

## 📂 Project Structure
* **`/data`**: Includes `vgsales_raw.csv` and the optimized `vgsales_cleaned.csv`.
* **`/notebooks`**: Jupyter Notebook containing the Python scripts for data cleaning and feature engineering.
* **`/dashboard`**: The `.pbix` file featuring the interactive Power BI report.

## 🧹 Data Sanitization & Feature Engineering
* **Column Optimization:** Removed redundant attributes (e.g., image URLs) to reduce file size and improve dashboard performance.
* **Feature Engineering:** Created a custom "Company" grouping to aggregate platforms (Sony, Nintendo, Microsoft) for high-level market comparison.
* **Handling Nulls:** Cleaned missing values in Year and Genre columns to ensure visualization accuracy.

## 🚀 Key Features
* **Custom UI/UX:** Developed an interface with localized page navigation giving feeling like a professional software.
* **Sales Analysis:** Correlation mapping between Critic Scores and Global Sales.
* **Trend Visualization:** Tracking the evolution of genres over almost four decades.

## 📖 How to Access
1.  **Code:** Explore the transformation logic in the `/notebooks` folder.
2.  **Report:** Download the `.pbix` file from the `/dashboard` folder to interact with the live data.
