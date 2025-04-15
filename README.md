# Data-Analysis
Portfolio of Data Analysis projects, using Python, SQL & Jupyter Notebook.
# Certifications:
Microsoft Azure Enterprize Data Analyst: https://www.credly.com/earner/earned/badge/19201c4c-1209-4b4c-9b29-191e7fadd448

Microsoft Data Analyst Associate:https://www.credly.com/badges/a84fa95c-c60f-4c5d-9a98-644824726d9a/public_url

Microsoft Azure AI Fundamentals: https://www.credly.com/badges/45ac1ba1-916e-44b9-afbf-8650549b46fb/public_url


# Data Analysis Portfolio Projects

This repository serves as a portfolio showcasing various data analysis projects undertaken by Fawad Ahmed. It demonstrates practical application of data cleaning, exploration, and analysis techniques primarily using SQL.

## Projects Included

This repository currently contains the following projects:

### 1. COVID-19 Data Exploration

*   **Goal:** To explore and analyze global COVID-19 data to uncover trends and insights.
*   **Description:** This project utilizes SQL queries to explore a dataset containing COVID-19 cases, deaths, and potentially vaccination data. The analysis includes calculating metrics like death percentages, infection rates relative to population, continental summaries, and potentially exploring relationships between vaccinations and outcomes.
*   **Files:**
    *   `PortfolioProject.CovidDeaths.xlsx`: The raw data file containing COVID-19 statistics.
    *   `Data Analyst Portfolio Project SQL Data Exploration.sql`: The SQL script containing queries for data exploration and analysis.

### 2. Nashville Housing Data Cleaning

*   **Goal:** To demonstrate data cleaning techniques using SQL on a real-world dataset.
*   **Description:** This project focuses on cleaning a dataset of Nashville housing sales records. Common data cleaning tasks addressed using SQL include:
    *   Standardizing date formats.
    *   Populating missing property address data.
    *   Breaking down addresses into individual columns (Address, City, State).
    *   Changing binary values (Y/N) to more descriptive ones (Yes/No).
    *   Identifying and removing duplicate rows.
    *   Deleting unused or irrelevant columns.
*   **Files:**
    *   `Nashville Housing Data for Data Cleaning.xlsx`: The raw data file containing Nashville housing records.
    *   `PortfolioProject - Data Cleaning.sql`: The SQL script containing queries used for cleaning the data.

## Technologies Used

*   **SQL:** The primary language used for data cleaning, exploration, and analysis. (The specific dialect, e.g., T-SQL for SQL Server, might be inferred but SQL is the core skill).
*   **Microsoft Excel:** Used as the format for the source data files.

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/fawadahmed799/Data-Analysis.git
    cd Data-Analysis
    ```
2.  **Set up a Database:**
    *   You will need a SQL database environment (e.g., Microsoft SQL Server, PostgreSQL, MySQL).
    *   Import the data from the `.xlsx` files (`PortfolioProject.CovidDeaths.xlsx`, `Nashville Housing Data for Data Cleaning.xlsx`) into tables within your database.
    *   **Note:** The SQL scripts likely assume specific table names (e.g., `CovidDeaths`, `NashvilleHousing`) and potentially a specific database/schema structure. You may need to adjust the `CREATE TABLE` statements or the SQL queries (`FROM`/`JOIN` clauses) to match your setup.
3.  **Run the SQL Scripts:**
    *   Open the `.sql` files (`Data Analyst Portfolio Project SQL Data Exploration.sql`, `PortfolioProject - Data Cleaning.sql`) in your preferred SQL client (like SSMS, Azure Data Studio, DBeaver, etc.).
    *   Execute the queries against the database where you imported the data.

## Data Sources

The datasets used in these projects are included within this repository in `.xlsx` format. These files represent snapshots used for these specific analyses.

## Author

*   **Fawad Ahmed**
*   GitHub: [@fawadahmed799](https://github.com/fawadahmed799)
    *   *(You might want to add LinkedIn or other relevant links here)*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


