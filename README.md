# Sales Data Analysis

## 📊 Overview
A small practice project analyzing a sample sales dataset (15 records, 3 cities, 3 categories, Jan–May) to identify trends by city, month, and category.

*Note: this uses a small synthetic dataset for practicing pandas — built to demonstrate the analysis workflow, not to represent real business data.*

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib

## 🔍 Analysis Performed
- Sales aggregation by city, month, and category using `groupby()`
- Pivot table analysis for multi-dimensional insights
- Feature engineering using `apply()` for sales categorization
- Data visualization using bar charts

## 📈 Key Insights
- **Delhi** had the highest total sales (1,990), followed by Pune (1,580) and Mumbai (1,340) — a ~24% gap between the top and bottom city.
- Monthly sales were **volatile, not steadily increasing** — sales rose from Jan (750) to a March peak (1,180), dipped in April (820), then recovered in May (1,110).
- **Clothing** was the top category by revenue (1,980, ~40% of total sales), narrowly ahead of Electronics (1,850, ~38%), with Furniture well behind (1,080, ~22%).
- High-value transactions (sales > 300) were fairly evenly distributed across all three cities (Pune: 3, Delhi: 3, Mumbai: 2) — no single city dominates large-ticket sales.

## 📌 Conclusion
On this sample, Delhi and Clothing/Electronics drive the most revenue, but monthly performance is inconsistent rather than trending — worth investigating what caused the April dip if this were real operational data. As a practice project, this demonstrates grouping, aggregation, and chart-based reporting in pandas.
