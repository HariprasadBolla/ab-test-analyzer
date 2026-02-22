# A/B Test Results Analyzer — E-Commerce

## Project Overview
A data analysis project that evaluates whether a new e-commerce webpage 
outperforms the existing one using real-world A/B testing data.

## Dataset
[E-Commerce A/B Testing Dataset](https://www.kaggle.com/datasets/ahmedmohameddawoud/ecommerce-ab-testing) 
— 294,478 users across control and treatment groups.

## Key Findings
| Metric | Control (Old Page) | Treatment (New Page) |
|---|---|---|
| Users | 147,202 | 147,276 |
| Conversion Rate | 12.04% | 11.89% |
| Projected Revenue | $1,772,745 | $1,750,960 |

**Statistical Result:** NOT significant (p = 0.2161 > 0.05)  
**Recommendation:** Do not roll out the new page — projected revenue loss of $21,785.

## Tools Used
- Python (pandas, scipy, statsmodels, openpyxl, matplotlib)
- Jupyter Notebook
- Microsoft Excel

## Skills Demonstrated
- A/B testing & hypothesis testing (two-proportion z-test)
- Statistical significance analysis
- Business impact & revenue modeling
- Automated Excel report generation
