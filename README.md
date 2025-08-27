-Financial Sentiment Analysis Tool-
Automated insights from financial news to support smarter investment decisions

-About the Project-
This tool was designed to address a common challenge in finance: the overwhelming volume of daily news and the difficulty of extracting actionable insights quickly. By automating sentiment analysis and quality scoring, it helps analysts focus on what matters—making informed decisions faster.

-Why It Matters-
Financial analysts often spend 3–4 hours a day reviewing hundreds of articles. This manual process is:

-Slow and hard to scale-
Subjective, leading to inconsistent interpretations
Risk-prone, with critical signals buried in noise
This project reduces that time to under 30 minutes while improving consistency and surfacing high-priority risks.

-What It Does-
Collects financial news via APIs
Classifies sentiment (positive, negative, neutral) using finance-specific models
Scores article quality to highlight actionable insights
Flags risks such as lawsuits, downgrades, and regulatory issues
Generates daily reports tailored for analysts and decision-makers
Technologies Used
R for data processing and modeling
tidyverse, tm, textclean for text cleaning and transformation
httr2, jsonlite for API integration
Custom ML models for sentiment and quality scoring
Results
95% noise reduction: Filters out irrelevant content
37% high-quality articles flagged for review
22 risk alerts surfaced daily
4 hours → 30 minutes: Time saved per analyst per day
Sample Output
HIGH PRIORITY ALERTS:
- Tesla: Negative sentiment (-0.039) – Securities fraud investigation  
- Bank of America: Positive sentiment (+0.082) – Institutional buying activity

COMPANY SENTIMENT OVERVIEW:
- Microsoft: +0.03 sentiment (29 articles) – Stable positive coverage
- JPMorgan: Institutional activity leader (95 articles tracked)

TOP ACTIONABLE ARTICLES:
1. "Brooklyn Investment Group Increases Holdings" – Quality: 75, Bullish signal
2. "UBS Issues Pessimistic Forecast" – Quality: 65, Downgrade risk
Business Applications
Investment Banks

Real-time sentiment for trading desks
Automated screening for research teams
Early warnings for risk management
Insurance Firms

Portfolio sentiment tracking
Legal and regulatory risk alerts
Alternative data for actuarial models
Tech & Fintech Companies

Credit risk assessment
M&A due diligence automation
Customer sentiment analysis
Under the Hood
Sentiment Analysis
Custom financial lexicon (100+ terms)
Context-aware scoring (e.g., “lawsuit” = negative)
Normalized sentiment scale: -1 to +1
Quality Scoring

Future Plans
Integrate FinBERT for deeper NLP
Real-time stream processing
Predictive modeling for price movement
AWS Lambda deployment for scalability
How to Run
Install Dependencies

Set Up API
Get a free NewsAPI key: newsapi.org/register
Add your key to scripts/01_data_collection_v2.R
Run the Tool

About Me
I'm Gabriel Paulino, a data analyst passionate about transforming complex data into clear, actionable insights.
