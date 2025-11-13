# Amazon Sales Dataset Analysis

## 📊 Overview
This repository provides a complete **Exploratory Data Analysis (EDA)** pipeline for the **Amazon Sales Dataset**, a simulated e-commerce dataset mimicking Amazon's order and returns data. The analysis uncovers key business insights such as sales trends, profit margins, customer segmentation, product performance, and regional return rates.

- **Dataset Size**: ~51,290 orders across global markets (2012–2015).
- **Focus Areas**: Financial KPIs (Sales, Profit, Discounts), Operational Metrics (Shipping Delays), and Customer Behavior (Segments, Returns).
- **Tech Stack**: Python with Pandas for data wrangling, Matplotlib/Seaborn for visualizations, and Jupyter/Colab for reproducibility.

Perfect for data analysts, business intelligence enthusiasts, or students learning EDA on real-world sales data!

## 🔍 Key Insights (From Analysis)
- **Top Performer**: Technology category accounts for ~50% of total sales ($1.2M+), but Furniture has the highest average profit per order ($$45).
- **Profit Margin**: Overall 11.2% – Discounts erode margins in high-volume categories like Office Supplies.
- **Returns**: 2.7% return rate; Oceania leads at 5.1% (potential shipping issues).
- **Trends**: Q4 sales spike (holiday season); Average ship time: 4.2 days.
- **Customer Segments**: Corporate drives 45% of revenue but has lower return rates than Consumers.

Visuals include bar charts for category sales, line plots for monthly trends, and heatmaps for correlations.

## 📁 Dataset Description
The dataset is an Excel file (`Amazon-Dataset.xlsx`) with three sheets:

| Sheet     | Rows | Columns | Description |
|-----------|------|---------|-------------|
| **Orders** | 51,290 | 24 | Core orders: Sales, Profit, Quantity, Discounts, Ship Modes, Regions, Categories (e.g., Technology, Furniture). |
| **Returns** | 1,028 | 3 | Returned orders with Order IDs and Regions for merging return flags. |
| **People** | 25 | 2 | Demographic samples (Persons and Regions) – optional for advanced segmentation. |

**Sample Orders Row**:
| Order Date | Ship Mode | Segment  | Region     | Category   | Sales | Profit | Returned |
|------------|-----------|----------|------------|------------|-------|--------|----------|
| 2014-11-13 | First Class | Consumer | Central US | Technology | 221.98 | 62.15 | No |

Download: [Amazon-Dataset.xlsx](https://github.com/yourusername/amazon-sales-analysis/raw/main/Amazon-Dataset.xlsx)

## 🚀 Quick Start
### Prerequisites
- Python 3.8+
- Jupyter Notebook or Google Colab

### Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/amazon-sales-analysis.git
   cd amazon-sales-analysis
