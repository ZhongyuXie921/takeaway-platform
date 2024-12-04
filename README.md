# takeaway-platform

# Shanghai Takeaway Platform Performance Dataset

## Overview
This dataset contains detailed performance metrics for food delivery operations in Shanghai, covering multiple stores across different platforms (Meituan and Eleme) from January 2020 to August 2020. The data tracks various key performance indicators (KPIs) including GMV, merchant revenue, exposure metrics, and order statistics.

## Sample Weekly Performance Report
Below is a sample weekly performance report for the second week of August 2020 (20200810-20200816):

### Weekly KPI Dashboard
![Weekly Performance Dashboard](sample_weekly_report.png)

Key Metrics:
- Exposure Users (曝光人数): 8,816
- Store Visit Conversion (进店转化率): 7.83%
- Order Conversion (下单转化率): 21.45%
- Platform Target Achievement: 27% (Target: 100,000)

Weekly Performance Breakdown:
| Date | Day | GMV | Revenue | Commission Rate | Valid Orders | Invalid Orders | Order Value |
|------|-----|-----|---------|-----------------|--------------|----------------|-------------|
| 2020-08-10 | Mon | 1538 | 500 | 32.50% | 30 | 0 | 51.28 |
| 2020-08-11 | Tue | 1253 | 420 | 33.51% | 26 | 0 | 48.19 |
| 2020-08-12 | Wed | 912 | 346 | 37.99% | 15 | 1 | 60.79 |
| 2020-08-13 | Thu | 1054 | 348 | 33.00% | 21 | 0 | 50.21 |
| 2020-08-14 | Fri | 1012 | 356 | 35.23% | 18 | 1 | 56.21 |
| 2020-08-15 | Sat | 1139 | 415 | 36.42% | 22 | 0 | 51.79 |
| 2020-08-16 | Sun | 1164 | 436 | 37.49% | 21 | 1 | 55.43 |

## Data Structure

### Time Period
- Start Date: 2020-01-01
- End Date: 2020-08-31

### File Format
- CSV file with daily performance metrics
- Character encoding: UTF-8

### Key Fields
1. **Basic Information**
   - Date (日期)
   - Brand ID (品牌ID)
   - Brand Name (品牌名称)
   - Store ID (门店ID)
   - Store Name (门店名称)
   - City (城市)
   - Platform (平台)
   - Platform Store Name (平台门店名称)

2. **Financial Metrics**
   - GMV
   - Merchant Revenue (商家实收)
   - CPC Total Cost (cpc总费用)
   - Merchant Subsidy (商户补贴)
   - Platform Subsidy (平台补贴)

3. **Performance Metrics**
   - Store Exposure (门店曝光量)
   - Store Visits (门店访问量)
   - Store Orders (门店下单量)
   - Invalid Orders (无效订单)
   - Valid Orders (有效订单)
   - Exposure Users (曝光人数)
   - Visiting Users (进店人数)
   - Ordering Users (下单人数)

4. **Marketing Metrics**
   - CPC Exposure (cpc曝光量)
   - CPC Visits (cpc访问量)

## Data Visualization

### Monthly Performance Trends
The dataset shows clear seasonal patterns and growth trends:
- Strong growth in GMV from January to July 2020
- Peak performance in June-July 2020
- Correlation between GMV and order volumes
- Conversion rate improvements over time

### Platform Comparison
Key differences between platforms:
- Eleme (饿了么) shows higher overall GMV and order volumes
- Meituan (美团) demonstrates strong per-order performance
- Different seasonal patterns between platforms
- Varying marketing efficiency metrics

### Key Insights from Visualizations
1. **Growth Trajectory**: Significant business growth from Q1 to Q2 2020
2. **Platform Dynamics**: Each platform shows distinct performance characteristics
3. **Seasonal Effects**: Clear monthly patterns in order volumes and GMV
4. **Conversion Trends**: Improving conversion rates over the observed period

## Usage
This dataset can be used for:
- Analyzing platform performance trends
- Comparing store performance across different platforms
- Evaluating marketing efficiency
- Understanding customer behavior patterns
- Measuring conversion rates at different stages

## Notes
1. All monetary values are in Chinese Yuan (CNY)
2. The dataset contains both raw numbers and calculated ratios
3. Some stores may have incomplete data for certain dates
4. Platform subsidies and merchant subsidies are tracked separately

## Data Processing Considerations
- Handle missing values appropriately
- Consider seasonal effects in analysis
- Account for platform-specific differences in metrics
- Verify calculations for derived metrics

## Sample Metrics Calculation
- Store Conversion Rate = Store Orders / Store Visits
- User Conversion Rate = Ordering Users / Visiting Users
- Marketing Efficiency = GMV / CPC Total Cost

For questions or additional information about the dataset, please contact the data team.
