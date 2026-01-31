# Food Delivery Data Integration and Analysis

## Project Overview
This project focuses on integrating and analyzing food delivery data from multiple sources to create a single, unified dataset for business analysis.

The objective is to combine transactional order data, user information, and restaurant details into one clean dataset that can be used to answer key business questions related to revenue, customer behavior, cuisine trends, and time-based performance.

---

## Datasets Used
The project uses three different data sources:

1. **orders.csv**
   - Contains transactional order-level data such as order ID, user ID, restaurant ID, order date, and order amount.

2. **users.json**
   - Contains user-related information including membership type and other customer details.

3. **restaurants.sql**
   - Contains restaurant master data such as restaurant ID, name, city, cuisine type, and ratings.

---

## Tools & Technologies
- **Python**
- **Pandas** for data manipulation
- **SQLite (sqlite3)** for processing SQL data
- **Google Colab / Jupyter Notebook**
- **GitHub** for version control and submission

---

## Project Workflow
1. Load data from CSV, JSON, and SQL formats.
2. Validate primary and foreign key relationships.
3. Merge datasets using left joins to preserve all transactional records.
4. Perform data analysis to answer business-related questions.
5. Export the final merged dataset as a CSV file.

---

## Output
- **final_food_delivery_dataset.csv**  
  A clean, merged dataset combining orders, users, and restaurants data.  
  This dataset serves as a single source of truth for analysis and reporting.

---

## Repository Structure
