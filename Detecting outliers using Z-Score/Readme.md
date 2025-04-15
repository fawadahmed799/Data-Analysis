# Outlier Detection Using Z-Score

This notebook demonstrates how to detect outliers using the Z-score technique on a synthetic sales dataset. It outlines a proactive data quality step implemented after initial data loads during a bi-annual report generation cycle.

## Business Context

Our reporting process is executed twice a year (Spring and Fall) and involves:

- Loading raw data from SQL Server.
- Applying complex, often evolving transformations.
- Storing processed data in a Data Warehouse.
- Generating SSRS reports based on the final datasets.

Historically, errors were often discovered late in the testing cycle, resulting in costly re-runs and bug fixes.

### Solution

To mitigate this, a Z-score based outlier detection was implemented to flag potential anomalies early in the ETL pipeline. This allows for:

- Early investigation of data irregularities.
- Identifying and fixing data issues before they propagate.

## Dataset

We simulate monthly sales data for several salespersons over a 14-year period (2010–2024). The dataset includes:

- `Salesman_Name`
- `Month_Year`
- `Total_Sales`

## Methodology

1. **Calculate Mean & Standard Deviation** for each salesperson.
2. **Compute Z-score** for each sales record.
3. **Classify as Outlier** if the absolute Z-score exceeds a defined threshold (commonly 3).

## Output

The result is a dataframe with additional fields:
- `Z_score`
- `Outlier` (Boolean)

Outliers can be visualized or further analyzed for verification and correction.

## Sample Output

