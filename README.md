# E-Commerce Analysis – UCI Online Retail

## Project Objective
Explore and analyze the UCI Online Retail dataset using Python and Pandas to clean real-world transaction data, calculate revenue, and identify the top 10 countries by total revenue.

## Project URL
[View E-Commerce Analysis Project](https://github.com/Harishbroo/ecommerce-sales-analysis)

## Dataset
- **Source:** [UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
- Real-world transaction data from a UK-based online retailer.
- A random 10% sample was used for analysis.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow
1. Loaded the dataset and sampled 10% of the rows.
2. Explored the data and identified missing values and unusual transactions.
3. Handled missing values.
4. Converted `InvoiceDate` to datetime.
5. Removed duplicate records.
6. Filtered out returns and free items.
7. Cleaned text columns.
8. Created a `Revenue` column using `Quantity × UnitPrice`.
9. Identified and visualized the top 10 countries by total revenue.
10. Compared international markets separately, excluding the UK.

## Key Outcome
Identified the highest-revenue countries and visualized their revenue distribution. A separate visualization was created to compare international markets without the UK dominating the results.

## Note
The analysis uses a random 10% sample of the original dataset. Therefore, revenue figures are estimates and may differ from full-dataset results.
