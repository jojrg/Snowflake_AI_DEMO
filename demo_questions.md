## Notes Misc

What are the top sales reps. whats their tenure and are they still with the company?

What were our top performing products last quarter?

What are our top 5 vendors in the last 5 years? Check our vendor management policy rules, are we following procurement rules for all of the transactions with this vendors?

Wer sind unsere Top-5-Lieferanten der letzten fünf Jahre? Überprüfe unsere Richtlinien für das Lieferantenmanagement: Halten wir bei allen Transaktionen mit diesen Anbietern die Beschaffungsregeln ein?



## Demo Flow

### Historical Sales analysis

*Q1: Show me the monthly sales trends for 2025* 

- Typical what happened question
- Agent utilizes the Sales Semantic Model, Cortex Analyst for structured data Analysis
- Agent delivers key insights


### Reasoning and Causality ("Why it happened")

*Q2: Why was there such a big increase in June?*

- Typical: "why" aquestion
- This requires the system to perform reasoning across multiple domains to identify drivers such as marketing campaigns



### Cross-Domain Chaining (Sales and HR)

*Q3: Who were our top 10 sales reps last year, what is their tenure & are they still with the comany*

- Typical: "why" aquestion
- This prompt forces the AI to identify top performers in the sales data mart and then query the HR data mart to calculate tenure based on hiring dates
- very good.
- this delivery real insights 


### Unstructured Data / poilicy Compliance and structured finance data (Finance and Audit)

*Q4: What are the top five vendors in the last 5 years? Are we following vendor management and procurement rules for the transactions of with these vendors?*

- This unified analysis cross-references structured financial transaction data with unstructured vendor management PDFs

### External Data & Custom Tools (Web Scraping):

*Q5: Get the latest information from the website (https://www.bea.gov/news/2025/us-international-trade-goods-and-services-july-2025) ans analyze its potential impact on our sales forecast for various product categories. Then send me an executive summary email.

- This query combines structured sales analytics with real-time data extracted from an external URL

## Improvements

Add to response instructions:
If suitable also provide recommendations based on the key findings.