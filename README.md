# 📊 Retail Sales and Customer Analytics

## 📌 Project Overview

This project analyzes retail transaction data using Python to identify sales trends, top-performing products, customer purchasing behavior, and geographical revenue distribution.

The project uses data analysis and visualization techniques to generate insights that can support business decision-making.

## 🎯 Objectives

- Analyze monthly revenue trends.
- Identify top-performing products.
- Determine the most valuable customers.
- Compare revenue across countries.
- Perform RFM customer segmentation.
- Calculate average order value.
- Visualize customer and sales patterns.
- Generate actionable business insights.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📈 Project Analysis

### 1. Monthly Revenue Analysis
Examines revenue trends over time and identifies the months with the highest and lowest recorded revenue.

### 2. Product Analysis
Identifies products generating the highest recorded revenue and products sold in the greatest quantities.

### 3. Customer Analysis
Examines customer purchasing activity and identifies customers contributing the most recorded revenue.

### 4. Country-Wise Analysis
Compares revenue across countries to identify the strongest markets.

### 5. RFM Customer Segmentation
Uses three metrics:

- **Recency:** How recently a customer purchased.
- **Frequency:** Number of distinct invoices associated with a customer.
- **Monetary:** Total recorded revenue associated with a customer.

Customers are classified into four preliminary segments:

- High Value
- Loyal Customers
- At Risk
- Others

### 6. Business Metrics
Calculates total recorded revenue, unique invoice count, and average recorded revenue per invoice.

### 7. Data Quality Checks
Examines missing values, duplicate records, and unusual quantity or price values.

## 🔍 Key Findings

Based on the current analysis:

| Metric | Result |
|---|---:|
| Total recorded revenue | 10,642,110.80 |
| Unique invoices | 19,960 |
| Average recorded revenue per invoice | 533.17 |
| Highest revenue month | November 2011 |
| Highest revenue country | United Kingdom |
| Top product by recorded revenue | DOTCOM POSTAGE |
| Largest revenue-contributing customer segment | High Value |

### Customer Segment Revenue Contribution

| Segment | Revenue Contribution |
|---|---:|
| High Value | 49.32% |
| Others | 22.53% |
| Loyal Customers | 20.91% |
| At Risk | 7.24% |

These percentages represent revenue attributed to identified customers under the current segmentation rules.

## 📊 Visualizations

The notebook includes visualizations for:

- Monthly revenue trends
- Top products by revenue
- Top products by quantity sold
- Top customers by revenue
- Revenue by country
- Customer segmentation
- Revenue by customer segment
- Revenue contribution by customer segment

## 💡 Business Recommendations

- Investigate seasonal revenue patterns and November's strong performance.
- Develop retention strategies for high-value customers.
- Investigate opportunities to re-engage customers who have not purchased recently.
- Examine product performance to identify opportunities for cross-selling.
- Investigate revenue patterns across international markets.
- Improve customer identification to support more complete customer-level analysis.

## ⚙️ How to Run the Project

1. Clone or download this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Open the Jupyter Notebook.
5. Ensure the required dataset is available at the file path specified in the notebook.
6. Run the notebook cells sequentially.

## 📁 Project Files

- `README.md` — Project documentation.
- `retail_sales_cleaned.csv` — Processed transaction dataset, if included.
- `customer_rfm_analysis.csv` — Customer RFM metrics and segments, if included.
- `retail_sales_analysis.ipynb` — Analysis notebook; replace this example filename with the actual notebook filename.

## ⚠️ Limitations

- Some transaction records have missing CustomerIDs.
- Customer-level analysis excludes transactions without identifiable customers.
- Customer segments use preliminary rule-based definitions.
- Revenue calculations depend on the transaction filtering and cleaning rules used in the notebook.
- The dataset requires additional validation of cancellations, returns, and unusual transactions before the results can be treated as definitive business metrics.

## 👨‍💻 Author

**Vinit Ramesh Gunagi**

Information Science & Engineering Student

Interested in Python, Data Analytics, and Software Development.
