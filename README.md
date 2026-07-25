# sales-dashboard    
# 📊 Sales Performance Analysis Dashboard

An interactive Excel dashboard analyzing sales performance across regions, products, salespersons, and categories — built from raw transactional data through cleaning, KPI calculation, and visualization.

## 📁 Project Structure
- **Raw Data** — original unprocessed sales records
- **Cleaned** — cleaned dataset (removed unusable rows, standardized blank/missing product entries as "Unspecified")
- **KPI's** — calculated financial, sales, and performance KPIs
- **Dashboard** — interactive visual dashboard with linked slicers

## 📈 Key Metrics
| Metric | Value |
|---|---|
| Total Units Sold | 19,416 |
| Total Revenue | $20,04,04,165.00 |
| Total Profit | $51,43,128.83 |
| Profit Margin | 25.22% |
| Number of Orders | 1,959 |
| Avg. Revenue per Order | $1,050.89 |
| Avg. Profit per Order | $264.89 |

**Best Selling Product:** Laptop | **Most Profitable Product:** Smartwatch
**Best Performing Region:** West | **Top Salesperson:** Grace
**Highest Revenue Month:** August | **Highest Profit Month:** June

## 🔍 Key Business Insights
1. Business generated $20.04Mn revenue at a healthy 25.22% profit margin.
2. Laptop drives volume, but Smartwatch drives profitability — margin per unit is likely higher on smartwatches despite lower ticket size.
3. West region significantly outperforms all other regions.
4. Grace is the top-performing salesperson — a possible benchmark for training others.
5. Revenue peaked in August, but profit peaked in June — signals a possible cost spike or discounting in August.
6. Average order value ($1,050.89) and average profit per order ($264.89) provide a clean baseline for tracking future performance.

## 🛠 Tools & Techniques
Excel — Pivot Tables, Slicers (linked across sheets), XLOOKUP, Conditional Formatting, Charts (Line, Bar, Donut)

## 🧹 Data Cleaning Notes
- Removed rows with unrecoverable/missing critical data (price/quantity).
- Blank product entries were grouped under "Unspecified" instead of being dropped, to preserve revenue/profit data integrity.
