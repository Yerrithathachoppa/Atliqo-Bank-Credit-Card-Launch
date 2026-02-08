# 🏦 Atliqo Bank Credit Card Launch - Data Analysis Project

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

## 📋 Project Overview

This project analyzes customer transaction and credit profile data for **Atliqo Bank** to identify the optimal target demographic for a new credit card launch. Through comprehensive exploratory data analysis (EDA) and statistical methods, the project identifies the **18-25 age group** as an untapped market with significant growth potential.

## 🎯 Business Objective

- Analyze customer demographics, credit scores, and transaction patterns
- Identify underserved market segments for credit card adoption
- Develop data-driven recommendations for targeted marketing
- Propose A/B testing framework for launch validation

## 🛠️ Technologies & Tools

| Technology | Purpose |
|------------|---------|
| **Python 3.x** | Programming Language |
| **Pandas** | Data Manipulation & Analysis |
| **NumPy** | Numerical Computations |
| **Matplotlib** | Data Visualization |
| **Seaborn** | Statistical Visualization |
| **Jupyter Notebook** | Interactive Development |

## 📊 Project Structure

```
Atliqo Bank Project/
├── data/                          # Raw data files
├── datasets/                      # Processed datasets
├── phase_1_atliqo_bank.ipynb     # Phase 1: Data Cleaning & EDA
├── phase_2_atliqo_bank.ipynb     # Phase 2: A/B Testing Strategy
├── Atliqo_Bank_Credit_Card_Launch_Documentation.pdf
├── Atliqo_Bank_Credit_Card_Launch_Documentation.md
└── README.md
```

## 🔬 Methodology

### Phase 1: Data Analysis & Customer Profiling

**Data Cleaning:**
- Duplicate detection and removal using `drop_duplicates()`
- Null value handling with mode-based imputation
- Outlier detection using IQR (Interquartile Range) method
- Age outliers replaced with occupation-specific median values

**Statistical Methods:**
- **Central Tendency:** Mean, Median, Mode for data summarization
- **Data Binning:** `pd.cut()` for age group segmentation (18-25, 26-48, 49-65)
- **Correlation Analysis:** Credit score vs. credit limit relationship

**Key Visualizations:**
- Age distribution histograms with outlier markers
- Pie charts for demographic proportions
- Scatter plots for correlation analysis
- Stacked bar charts for cross-segment analysis

### Phase 2: A/B Testing & Business Strategy

**Target Identification:**
- 18-25 age group represents ~25% of customers
- This segment shows **lower credit card exposure** compared to other groups
- Identified as primary target for new credit card launch

**A/B Testing Framework:**
- Hypothesis testing (H₀ vs H₁)
- Sample size determination with 80% power
- Key metrics: Conversion rate, transaction value, platform preference

## 📈 Key Findings

| Insight | Details |
|---------|---------|
| **Primary Target** | 18-25 age group (untapped market) |
| **Dominant Segment** | 26-48 age group (~50% of customer base) |
| **Credit Score Correlation** | Positive correlation with credit limit |
| **Platform Preference** | Digital platforms (Amazon, Flipkart, Meesho) |

## 🚀 Business Recommendations

1. **Target Demographic:** Focus on 18-25 age group for credit card launch
2. **Marketing Channels:** Leverage digital e-commerce platforms
3. **Product Features:** Design youth-friendly credit card benefits
4. **Validation:** Implement A/B testing before full-scale rollout

## 📁 Datasets

The project uses three primary datasets:
- **Customer Data:** Demographics (age, gender, location, occupation, income)
- **Credit Score Data:** Credit scores, credit limits, payment history
- **Transaction Data:** Transaction amounts, platforms, payment methods

## 🔧 Installation & Usage

```bash
# Clone the repository
git clone https://github.com/Yerrithathachoppa/Atliqo-Bank-Credit-Card-Launch.git

# Navigate to project directory
cd Atliqo-Bank-Credit-Card-Launch

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch Jupyter Notebook
jupyter notebook
```

## 👤 Author

**Yerri Thatha Choppa**
- GitHub: [@Yerrithathachoppa](https://github.com/Yerrithathachoppa)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*This project demonstrates proficiency in Python, Pandas, data cleaning, exploratory data analysis, statistical methods, and data-driven decision making.*
