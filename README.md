# Data Science Assignment  
## Trader Behavior vs Market Sentiment Analysis

---

##  Project Overview

This project analyzes how **trader behavior** changes under different **market sentiment conditions** such as *Fear* and *Greed*.  
The goal is to understand patterns in trade volume and buy/sell behavior rather than to build predictive models.

Two datasets are used:
1. Historical trader transaction data  
2. Bitcoin Fear & Greed Index (daily market sentiment)

All analysis was performed using **Google Colab**, as required.

---

## 📂 Project Structure

ds_krishna/
├── notebook_1.ipynb # Main analysis notebook (Google Colab)
├── csv_files/ # Input datasets
│ ├── historical_data.csv
│ └── fear_greed_index.csv
├── outputs/ # Generated plots and visual outputs
│ ├── sentiment_distribution.png
│ ├── avg_trade_volume_by_sentiment.png
│ └── buy_sell_by_sentiment.png
├── ds_report.pdf # Final summarized insights
└── README.md # Project documentation


---

##  Analysis Summary

The analysis focuses on the following aspects:

###  Market Sentiment Distribution
Trading activity is highest during **fear-dominated market conditions**, indicating increased participation during periods of uncertainty.

###  Trade Volume vs Sentiment
Average trade size is **highest during fear periods**, suggesting increased risk exposure or forced trading behavior when sentiment is negative.

###  Buy vs Sell Behavior
- **Fear:** Buy and sell trades are almost evenly distributed, indicating uncertainty  
- **Greed:** Sell trades outnumber buy trades, suggesting profit-taking  
- **Neutral:** Lowest overall trading activity  

These patterns align with commonly observed market behavior.

---

##  Timestamp Handling

The trader dataset contained timestamps stored as **Unix epoch values in milliseconds**.  
These were converted to datetime format before extracting daily dates to correctly align with the sentiment dataset.

This step was necessary to ensure accurate analysis.

---

##  Visual Outputs

All charts generated during the analysis are stored in the `outputs/` folder:
- Sentiment distribution
- Average trade volume by sentiment
- Buy vs sell behavior across sentiment categories

These visuals support the numerical insights presented in the report.

---

## 📘 Google Colab Notebook

All work was completed in Google Colab.

🔗 **Colab Link (Anyone with the link can view):**  
https://colab.research.google.com/drive/1IBNHQbmeQFKudA7gRzQA8dixie86jjlC?usp=sharing
---

##  Final Report

A concise summary of findings and explanations is available in: ds_report.pdf 


---

##  Notes

- This repository follows the exact structure specified in the assignment instructions  
- No external or proprietary libraries were used  
- The focus is on **data understanding and interpretation**

---

##  Author

**Candidate Name:** krishna H  
**Assignment:** Data Science Assignment Submission
