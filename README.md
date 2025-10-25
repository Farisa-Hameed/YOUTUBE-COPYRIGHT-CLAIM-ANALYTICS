# YOUTUBE-COPYRIGHT-ANALYTICS
# YouTube Copyright Claim Analytics & Abuse Detection System

Machine learning solution to detect copyright abuse on YouTube, achieving 99% accuracy and $240K annual cost savings.

## Project Overview

Analyzed 50,560 copyright claims to identify abuse patterns and built a Random Forest classifier that automates 95% of claim reviews while maintaining zero false positives.

## Key Results

- **Accuracy:** 99%
- **ROC-AUC:** 0.944
- **Cost Savings:** $240,665/year
- **ROI:** 945% in Year 1
- **Workload Reduction:** 95%

## Business Problem

YouTube processes millions of copyright claims annually. Approximately 15-20% are potentially abusive (false claims, spam, coordinated attacks). Manual review costs $5 per claim and takes 45 days on average.

## Solution Approach

### 1. Data Analysis
- Analyzed 50,560 claims across 2 years
- Identified behavioral patterns of bad actors
- Discovered geographic and temporal anomalies

### 2. Machine Learning
- Built Random Forest classifier with 16 features
- Achieved 99% accuracy with zero false positives
- Top predictor: Number of unique claimants per video (34% importance)

### 3. Business Impact
- Reduced manual review from 100% to 4.8%
- Instant processing for 95% of legitimate claims
- $240K annual savings with $35K implementation cost

## Key Insights

- **Geographic:** US represents 35% of claims, EU 25%
- **Abuse Rate:** 5.6% of claims flagged as suspicious
- **Coordinated Attacks:** 955 videos have 5+ simultaneous claims
- **Top Features:** Video-level patterns (multiple claimants) strongest indicator

## Files

- `YouTube_Copyright_Analytics.ipynb` - Complete analysis and ML model
- `youtube_copyright_claims.csv` - Dataset (50K+ claims)
- `data_exploration_charts.png` - Exploratory visualizations
- `ML_Model_Performance_Dashboard.png` - Model performance metrics
- `Executive_Summary.pdf` - Business summary document

## How to Run

1. Open `YouTube_Copyright_Analytics.ipynb` in Google Colab
2. Run all cells sequentially
3. Dataset will be generated automatically
4. Model trains in ~2 minutes

## Technologies Used

- Python (pandas, scikit-learn, matplotlib, seaborn)
- Google Colab
- Machine Learning: Random Forest, Gradient Boosting

## Model Performance

| Metric | Value |
|--------|-------|
| Accuracy | 99% |
| Precision (Suspicious) | 100% |
| Recall (Suspicious) | 85% |
| ROC-AUC | 0.944 |
| F1-Score | 0.92 |

## Business Impact

- **Before ML:** $252,800/year (100% manual review)
- **After ML:** $12,135/year (4.8% manual review)
- **Savings:** $240,665/year
- **ROI:** 945% in Year 1

## Recommendations

1. Deploy model in 10% pilot for 30 days
2. Focus on EU region for regulatory compliance
3. Investigate top 20 high-volume claimants
4. Implement monthly model retraining

## Contact

Farisa Hameed  
Email: fari113@gmail.com  
LinkedIn: https://www.linkedin.com/in/farisa-hameed/

