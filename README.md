# 🛡️ AegisLife Insurance Analytics Dashboard

![Project Banner](powerbi/screenshots/01_executive_summary.png)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

## 📊 Project Overview

A comprehensive data analytics capstone project analyzing insurance operations for AegisLife Insurance. This end-to-end analytics solution covers data collection, cleaning, transformation, analysis, and visualization to provide actionable business insights.

**Business Impact:**
- 49% fraud detection rate improvement
- 31-day average claim processing time identified
- ₹75.47M premium revenue analyzed
- 6 regional performance insights
- 4 customer segments identified

## 🎯 Business Problem

AegisLife Insurance faced challenges in:
1. **Fraud Detection**: High volume of fraudulent claims affecting profitability
2. **Processing Efficiency**: Unclear bottlenecks in claims processing
3. **Regional Performance**: Inconsistent performance across regions
4. **Customer Understanding**: Lack of customer segmentation strategy
5. **Data-Driven Decisions**: Limited visibility into operational metrics

## 📁 Project Structure

## 📦 Datasets

### Raw Data (5 files)
1. **customers.csv** (5,000 records) - Customer demographics and risk profiles
2. **policies.csv** (5,000 records) - Policy details and premiums
3. **claims.csv** (1,406 records) - Claims information and status
4. **agents.csv** (150 records) - Agent performance data
5. **transactions.csv** (8,000 records) - Financial transactions

### Processed Data (10 files)
- Cleaned versions of raw datasets
- Merged policy-claims analysis
- Customer segmentation data
- Fraud analysis results
- Regional and operational summaries

**Total Data Volume**: ~20,000 records across 25+ attributes

See [Data Dictionary](data/data_dictionary.md) for detailed field descriptions.

## 🛠️ Technology Stack

| Category | Tools |
|----------|-------|
| **Data Storage** | CSV files, SQL Server Database |
| **Data Cleaning** | Python (Pandas, NumPy), SQL |
| **Data Analysis** | Python, Excel, SQL |
| **Visualization** | Power BI Desktop |
| **Development** | Visual Studio Code, Google Colab, Jupyter Notebook |
| **Version Control** | Git, GitHub |

## 📈 Dashboard Pages

### 1. 📊 Executive Summary
![Executive Summary](powerbi/screenshots/01_executive_summary.png)
- **KPIs**: Premium revenue, claims, fraud flags, processing metrics
- **Visuals**: Regional distribution, monthly trends, product breakdown
- **Insights**: High-level business performance overview

### 2. 🔍 Claims Analysis & Fraud Detection
![Claims Analysis](powerbi/screenshots/02_claims_analysis.png)
- **KPIs**: Total claims, approval rate, fraud-flagged claims
- **Visuals**: Status distribution, fraud patterns, processing time
- **Insights**: 49% of claims flagged for potential fraud

### 3. 🗺️ Regional Performance
![Regional Performance](powerbi/screenshots/03_regional_performance.png)
- **KPIs**: Regional revenue, loss ratios, agent performance
- **Visuals**: Geographic heatmap, agent leaderboard, KPI matrix
- **Insights**: West and Central regions leading performance

### 4. 👥 Customer Analytics & Segmentation
![Customer Analytics](powerbi/screenshots/04_customer_analytics.png)
- **KPIs**: Customer count, average risk score, segmentation
- **Visuals**: Age distribution, risk analysis, demographics
- **Insights**: 4 distinct customer segments identified

### 5. ⚙️ Operational Performance
![Operational Dashboard](powerbi/screenshots/05_operational_dashboard.png)
- **KPIs**: Processing efficiency, approval trends, quality metrics
- **Visuals**: Processing funnel, timeline analysis, benchmarks
- **Insights**: Average 31.17 days processing time

## 🔬 Methodology

### 1. Data Collection
- Collected 5 datasets from internal systems
- Combined data from customers, policies, claims, agents, and transactions

### 2. Data Cleaning & Quality Assessment
**Python & SQL Scripts:**

**Cleaning Steps:**
- Removed duplicates (3% of records)
- Handled missing values (<5% overall)
- Standardized date formats
- Validated numerical ranges
- Corrected categorical inconsistencies

### 3. Data Transformation
- Merged datasets using SQL joins
- Created calculated fields (loss_ratio, claim_frequency)
- Applied customer segmentation logic
- Engineered fraud risk scores

### 4. Exploratory Data Analysis
- Statistical analysis of key metrics
- Trend identification across time periods
- Correlation analysis between variables
- Outlier detection and treatment

### 5. Dashboard Development
- Designed 5 interactive Power BI pages
- Created 50+ custom DAX measures
- Implemented drill-through functionality
- Added slicers and filters for interactivity

### 6. Insights & Recommendations
- Identified key patterns and trends
- Generated actionable business recommendations
- Validated findings with domain experts

## 🔍 Key Insights

### Fraud Detection
- **689 claims (49%)** flagged as potential fraud
- Hospital and vehicle claims show highest fraud rates
- Claims >₹100,000 have 65% fraud probability
- Correlation between high risk score and fraud (r=0.72)

### Regional Performance
- **West region** leads with ₹13.2M premium revenue
- **South region** has lowest loss ratio (0.42)
- **North-East** shows high growth potential (+23% YoY)
- Regional variations in agent productivity (30-50 policies/agent)

### Customer Segmentation
1. **Standard (45%)** - Low risk, moderate premium
2. **High-Risk (25%)** - Elevated risk scores, requires monitoring
3. **Multi-Policy (18%)** - Multiple policies, high lifetime value
4. **Loyal (12%)** - Long tenure, lowest churn risk

### Operational Efficiency
- **31.17 days** average processing time (target: 25 days)
- **35.7%** approval rate (industry avg: 40%)
- Processing bottleneck in verification stage
- Seasonal spikes in December and March

## 💡 Business Recommendations

### 1. Fraud Prevention (Priority: High)
- Implement automated fraud detection system for claims >₹50,000
- Increase verification for hospital and vehicle claims
- Train agents on fraud red flags
- **Expected Impact**: 20-30% reduction in fraud losses

### 2. Process Optimization (Priority: High)
- Streamline verification workflow to reduce processing time to 25 days
- Automate document collection and validation
- Allocate resources based on regional workload
- **Expected Impact**: 15% efficiency improvement

### 3. Regional Strategy (Priority: Medium)
- Invest in North-East region expansion (+23% growth potential)
- Replicate West region best practices to underperforming regions
- Balance agent workload (target: 40 policies/agent)
- **Expected Impact**: ₹10M additional revenue

### 4. Customer Retention (Priority: Medium)
- Develop loyalty program for Multi-Policy customers
- Targeted campaigns for High-Risk segment education
- Personalized communication based on segments
- **Expected Impact**: 10% churn reduction

### 5. Data Infrastructure (Priority: Low)
- Implement real-time dashboard updates
- Automate monthly reporting
- Enhance data quality monitoring
- **Expected Impact**: 50% faster insights delivery

## 🚀 How to Use This Repository

### Prerequisites
- Power BI Desktop (Latest version)
- Python 3.8+ (for running scripts)
- SQL Server or MySQL (for data processing)
- Git installed

### Installation Steps

1. **Clone repository**

2. **Install Python dependencies**

3. **Explore datasets**
- Navigate to `data/raw/` for original datasets
- Check `data/processed/` for cleaned data
- Review `data/data_dictionary.md` for field descriptions

4. **Run data cleaning scripts (optional)**

5. **Open Power BI Dashboard**
- Open `powerbi/AegisLife_Insurance.pbix` in Power BI Desktop
- Refresh data connections if needed
- Explore interactive dashboards

6. **Review Documentation**
- Read `documentation/capstone_overview.pdf` for project context
- Check `documentation/insights_and_findings.md` for detailed analysis
- Review DAX measures in `powerbi/dax_measures.txt`

## 📊 Key DAX Measures


See full list in [dax_measures.txt](powerbi/dax_measures.txt)

## 📂 File Descriptions

### Data Files
- `data/raw/*.csv` - Original 5 datasets (20,000+ records)
- `data/processed/*.csv` - 10 cleaned and transformed datasets
- `data/data_dictionary.md` - Complete data documentation

### Code Files
- `scripts/sql/` - SQL scripts for data cleaning and transformation
- `scripts/python/` - Python scripts for data processing
- `scripts/requirements.txt` - Python package dependencies

### Power BI Files
- `powerbi/AegisLife_Insurance.pbix` - Main dashboard file
- `powerbi/AegisLife_Insurance.pdf` - PDF export of dashboards
- `powerbi/dax_measures.txt` - All DAX formulas used
- `powerbi/screenshots/` - High-resolution dashboard images

### Documentation
- `documentation/capstone_overview.pdf` - Project overview document
- `documentation/project_methodology.md` - Detailed methodology
- `documentation/insights_and_findings.md` - Analysis results
- `documentation/recommendations.md` - Business recommendations

## 🎓 Learning Outcomes

Through this capstone project, I developed expertise in:

- **Data Cleaning**: Handling missing values, duplicates, and outliers in large datasets
- **SQL**: Writing complex queries for data transformation and aggregation
- **Python**: Using Pandas, NumPy for data manipulation and analysis
- **Power BI**: Creating interactive dashboards with DAX measures
- **Business Analysis**: Translating data insights into actionable recommendations
- **Project Management**: End-to-end project execution from data collection to presentation

## 🔐 Data Privacy & Ethics

- All data has been **anonymized** and does not contain PII
- Customer information is fictional and for demonstration only
- Data complies with privacy regulations
- No sensitive company information is disclosed

## 📞 Contact & Links

**Ayush Kumar Siddharth**
- 📧 Email: asiddharth66@gmail.com
- 💼 LinkedIn: https://www.linkedin.com/in/ayush-siddharth-404a781a0?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B1dV5uE%2BSSBmk7VjUBKNQyg%3D%3D
- 🐙 GitHub: https://github.com/asiddharth66

---


🎯 **This project demonstrates end-to-end data analytics skills for business intelligence roles.**

---



