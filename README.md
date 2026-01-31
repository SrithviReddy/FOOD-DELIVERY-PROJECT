# Food Delivery Data Integration & Analysis

## Overview
This project demonstrates a structured approach to integrating and analyzing food delivery data from multiple heterogeneous data sources. The objective is to consolidate transactional, user, and restaurant datasets into a unified, analytics-ready dataset that can be used to derive meaningful business insights.

The project emphasizes real-world data engineering practices such as data ingestion, validation, transformation, and integration.

---

## Data Sources
The following datasets are used in this project:

- **orders.csv**  
  Contains transactional order-level data including order identifiers, user identifiers, restaurant identifiers, order dates, and order amounts.

- **users.json**  
  Contains user master data such as membership type and other customer-related attributes.

- **restaurants.sql**  
  Contains restaurant master data including restaurant identifiers, cuisine type, city, and ratings.

---

## Tools & Technologies
- **Python**
- **Pandas** – Data manipulation and analysis
- **SQLite (sqlite3)** – SQL data processing
- **Jupyter Notebook / Google Colab**
- **GitHub** – Version control and project submission

---

## Methodology
1. Ingested data from CSV, JSON, and SQL formats.
2. Performed structural validation of primary and foreign key relationships.
3. Integrated datasets using left joins to preserve all transactional records.
4. Prepared a consolidated dataset suitable for analysis and reporting.
5. Exported the final merged dataset for reuse and further analytics.

---

## Output
- **final_food_delivery_dataset.csv**  
  A clean, unified dataset combining orders, users, and restaurants data.  
  This dataset serves as a single source of truth for business analysis.

---

## Repository Structure
