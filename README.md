# David Akomolafe

**Data analyst who works on the commercial side of the business.** I take messy operational data and turn it into the decision someone has to make on Monday: which partner to call, which spend to cut, which number is lying.

Senior Data Analyst at **Glovo Nigeria**, working across commercial strategy, partner portfolio analysis and supply-side analytics. Before that, Business Intelligence Analyst at **First Bank of Nigeria**. Trained as a chemical engineer, which is where the habit started: state the method, show the measurement, do not report what you cannot reproduce.

Founder of **Vantage Analytics**, helping Nigerian SMEs find out why revenue is moving using their own data.

[LinkedIn](#) · segunlafe@gmail.com · Lagos, Nigeria · Open to remote and international roles

---

## VenaNow: where the money actually went

Many people in Lagos earn into one account and spend through three. No app sees all of them, but the statements do. [**VenaNow**](https://github.com/TheKingSegun/venanow) reads GTBank, Zenith, UBA, Access, OPay and Kuda statements in PDF, CSV or Excel and returns categorised spending, recurring payments, a health score and a 30 day cash flow forecast.

The part I would point at: the rules are written for Lagos, not borrowed from a foreign budgeting app, and every category carries a confidence score so the interface can ask instead of guess. Re-uploading an overlapping month cannot double count spending, because each transaction is fingerprinted and unique in the database. 

`Python` `pandas` `pdfplumber` `scikit-learn` `FastAPI` `PostgreSQL` `Docker`

---

## Analytics and machine learning

### [Customer churn prediction](https://github.com/TheKingSegun/customer-churn-prediction): who is worth a call this week
A retention team cannot call everyone, so the question is not "will this customer leave" but "who should we call first". An XGBoost model ranks customers by risk, and SHAP shows why each one was flagged so the agent knows what to say. On synthetic data where the true churn drivers are known, SHAP ranked exactly those four drivers above the four noise features, and calling the top 30% of ranked customers reached 91% of churners.
`XGBoost` `SHAP` `Optuna` `scikit-learn`

### [Food demand forecasting](https://github.com/TheKingSegun/food-demand-forecasting): how many riders on Friday night
Delivery volume drives how many riders and how much stock a platform needs. Prophet and ARIMA compared for forecasting delivery volumes.
`Prophet` `statsmodels`

### [Nigeria inflation dashboard](https://github.com/TheKingSegun/nigeria-inflation-dashboard): what the CPI headline hides
NBS publishes one headline number. This takes the underlying CPI data into a Power BI dashboard so you can see what is behind it.
`Python` `Power BI`

### [NGX stock analysis](https://github.com/TheKingSegun/ngx-stock-analysis): a momentum screen for Nigerian equities
A screener for NGX listed stocks, built because most retail tools ignore the Nigerian market.
`Python` `TA-Lib`

### [Financial model toolkit](https://github.com/TheKingSegun/financial-model-toolkit): DCF, unit economics and FX sensitivity
Reusable models for valuing a business in Nigeria, where the exchange rate has to be a sensitivity, not a fixed assumption.
`Python` `Excel`

---

## What I work on professionally

| Domain | What that looked like |
|---|---|
| **Food delivery and logistics** | Partner portfolio analysis, supply-side performance and commercial deal support at Glovo Nigeria |
| **Banking** | Business intelligence reporting at First Bank of Nigeria |
| **SME advisory** | Revenue diagnostics for Nigerian small businesses through Vantage Analytics |

## Tools

**Languages** · Python · SQL · DAX
**Analysis and ML** · pandas · scikit-learn · XGBoost · LightGBM · Prophet · statsmodels · SHAP
**Data platforms** · BigQuery · Snowflake · dbt · PostgreSQL · Supabase
**Reporting** · Power BI · Tableau · Plotly
**Engineering** · FastAPI · Docker · Git

**Domain** · fraud detection · credit risk · A/B testing · customer lifetime value

## How I work

I start from the decision, not the dataset. An analysis that cannot change what somebody does next week is a report, not an answer.

I keep the uncertainty visible. A model score, a forecast range, a category the classifier was not sure about: all of it is shown rather than rounded away, because a confident wrong number does more damage than an honest "we do not know yet".

And I write down where each project stops, so a reader can tell the difference between something hard and something unfinished.
