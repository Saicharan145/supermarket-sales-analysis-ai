# Supermarket Sales Analysis with AI

## Project
**Supermarket Sales Analysis and AI-Based Transaction Segmentation**

## Internship
IBM SkillsBuild Data Analytics with AI Internship

## Objective
Analyze supermarket transaction data and identify useful sales and purchasing patterns. The project also applies K-Means clustering to group transactions with similar characteristics.

## Dataset
The public supermarket sales dataset contains 1,000 transactions and 17 fields, including branch, city, customer type, gender, product line, unit price, quantity, tax, total, date, time, payment method, cost of goods sold, gross income, and customer rating.

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Analysis Performed
1. Data loading and understanding
2. Data quality checks
3. Exploratory Data Analysis
4. Product-line analysis
5. Branch analysis
6. Payment-method analysis
7. Time-based sales analysis
8. Customer rating analysis
9. K-Means transaction clustering
10. Business insights and recommendations

## Actual Results
- Total sales: **322,966.75**
- Gross income: **15,379.37**
- Average transaction value: **322.97**
- Highest-performing product line: **Food and beverages**
- Highest-performing branch: **C**
- Most-used payment method: **Ewallet**
- Peak sales hour: **19:00**
- Average rating: **6.97/10**
- Selected number of clusters: **2**

## AI Cluster Results

| Cluster | Avg Unit Price | Avg Quantity | Avg Total | Avg Rating |
|---|---:|---:|---:|---:|
| 0 | 73.90 | 7.88 | 597.56 | 6.89 |
| 1 | 45.19 | 4.15 | 165.13 | 7.02 |

Cluster 0 represents higher-value and higher-quantity transactions in this dataset, while Cluster 1 represents lower-value and lower-quantity transactions.

These are **transaction-level segments**, not customer segments, because the dataset does not contain a persistent customer identifier.

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open `SaiCharan_SupermarketSalesAI_Final.ipynb` in Google Colab or Jupyter Notebook and run the cells.

## Project Files
- `SaiCharan_SupermarketSalesAI_Final.ipynb` — analysis code
- `requirements.txt` — Python dependencies
- `SaiCharan_ProjectReport.docx` — project documentation
- `README.md` — project overview and instructions
