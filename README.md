# Flight-Metrics-Visualization-and-Strategy

# 🛫 Airline Flight Data Analysis

## 📘 Project Overview

The **Airlines Flight Data Analysis** project explores flight pricing patterns, airline performance, and route trends using **Python (Pandas, Seaborn, Matplotlib)** and **SQL (via pandasql)**.
This analysis provides insights into:

* Flight pricing across airlines and classes
* The busiest routes and cities
* Factors affecting ticket prices (days left, duration, stops, etc.)
* SQL-based exploration for business intelligence

---

## 🧰 Tools & Libraries Used

* **Python**
* **Pandas** – Data manipulation and cleaning
* **NumPy** – Numerical computations
* **Matplotlib & Seaborn** – Data visualization
* **pandasql** – Running SQL queries on Pandas DataFrames

---

## 📂 Dataset Description

File: `airlines_flights_data.csv`
**Rows:** 300,153
**Columns:** 11

| Column             | Description                                         |
| ------------------ | --------------------------------------------------- |
| `airline`          | Airline name (e.g., Indigo, Vistara, Air India)     |
| `flight`           | Flight number                                       |
| `source_city`      | Departure city                                      |
| `departure_time`   | Time of day flight departs (Morning, Evening, etc.) |
| `stops`            | Number of stops (zero, one, two+)                   |
| `arrival_time`     | Time of day flight arrives                          |
| `destination_city` | Destination city                                    |
| `class`            | Ticket class (Economy / Business)                   |
| `duration`         | Flight duration in hours                            |
| `days_left`        | Days left before departure                          |
| `price`            | Ticket price in INR                                 |

---

## 🧹 Data Preprocessing

* Removed unnecessary columns (like index)
* Checked for and removed duplicate values
* Verified no missing (`NaN`) values
* Renamed and standardized column names

---

## 📊 Exploratory Data Analysis (EDA)

Key visualizations include:

1. **Price Distribution Across Airlines** – Boxplots to compare ticket prices per airline
2. **Economy vs. Business Class Prices** – Pie chart of average price difference
3. **Busiest Source & Destination Cities** – Bar charts showing city-wise flight density
4. **Days Left vs. Ticket Price** – Scatter plot showing price trend before departure
5. **Stops vs. Ticket Price** – Boxplot comparing prices for non-stop vs. connecting flights
6. **Duration vs. Ticket Price** – Regression plot showing effect of flight time on price

---

## 🧮 SQL Analysis (via `pandasql`)

1. **Average ticket price per airline**
2. **Top 5 most expensive routes**
3. **Cheapest airline for Business class**
4. **Routes with >50 flights & their avg prices**
5. **Price gap between Economy and Business classes**
6. **Most incoming and outgoing flights by city**
7. **Busiest route overall**
8. **Top 3 cheapest airlines per route**
9. **Flights with duration >5 hrs and below average price**
10. **Which class has highest price variation (std deviation)**
11. **Ticket price trends vs. days left before departure**
12. **Highest-priced departure time (Morning, Evening, etc.)**
13. **Price trends by airline and class**
14. **Comparison: non-stop vs. 1-stop vs. 2+ stops**

---

## 💡 Key Insights

* **Vistara and Air India** dominate Business class with the highest average prices.
* **AirAsia** consistently offers the **cheapest flights** across most routes.
* **Delhi–Mumbai** is the **busiest flight route** in India.
* Prices **drop** as the number of days before departure **increases**.
* **Longer duration flights** and **1-stop flights** generally have higher average prices.

---

## 🧾 How to Run

1. Upload the notebook to **Google Colab**.
2. Mount or upload `airlines_flights_data.csv` into `/content/`.
3. Run all cells sequentially.
4. Visualizations and SQL results will be displayed inline.

---

## 📈 Future Improvements

* Build a **machine learning model** to predict ticket prices.
* Add **interactive dashboards** using Streamlit or Power BI.
* Perform **time-series analysis** for seasonal price trends.

---

## 👨‍💻 Author

**Jyothishwar CSM-B**
Software Engineer | AI/ML Enthusiast | Data Analyst
🚀 Focused on building data-driven solutions and insights

---
