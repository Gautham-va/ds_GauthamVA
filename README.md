# ds_GauthamVA
Explore and analyze the relationship between trader behavior and market sentiment, using two key datasets. 

# Market Sentiment & Trader Data Analysis

This notebook combines market sentiment data (Fear/Greed Index) with historical trading data from Hyperliquid.  
The aim is to explore relationships between sentiment and trader performance, identify trends, and generate actionable insights.

---

## 1. Data Import & Merging

In this section, we load:
- **Bitcoin Market Sentiment Dataset** (Fear/Greed Index over time)
- **Trader Data** (execution price, size, side, closed PnL, etc.)

After cleaning and formatting dates, we merge both datasets on the **date** field.  
This creates a unified dataset containing **market sentiment + trading metrics**, which will be used for all further analysis.

---

## 2. Exploratory Data Analysis (EDA)

Here we explore:
- Basic dataset info (shape, columns, datatypes)
- Null/missing values
- Summary statistics of key metrics (execution price, trade size, PnL)

The goal is to understand data quality and the distributions of both sentiment and trading metrics.

---

## 3. Aggregated Analyses

We compute **daily aggregated metrics** such as:
- Total trades per day  
- Total closed PnL per day  
- Average trade size per day  
- Daily sentiment classification (Fear vs Greed)  

This helps in studying trader performance and activity at a **daily level**.

---

## 4. Trend Analysis Over Time

In this part, we analyze:
- **Daily number of trades** over time  
- **Daily PnL trends** (profits/losses)  
- **Market sentiment movement** (Fear/Greed changes)  

This provides an overview of how trading activity and profitability vary with shifts in market sentiment.

---

## 5. Relationship Between Sentiment & Trader Metrics

We examine:
- Distribution of **PnL across Fear vs Greed days**  
- Average **trade size vs sentiment**  
- Correlation between **sentiment score and daily PnL**  

This reveals how trader behavior and profitability align with market psychology.

---

## 6. Interactive Visualizations & Insights

Using **Plotly**, we create interactive charts for:
- Sentiment trends over time  
- Daily trade counts and PnL trends  
- Comparison of sentiment categories (Fear vs Greed)  

These visualizations allow dynamic exploration of trading performance under different sentiment conditions.

---

## 7. Key Insights

- Trading volume and activity tend to **increase during high sentiment swings**.  
- Daily PnL shows visible fluctuations aligned with Fear/Greed cycles.  
- In some cases, **PnL is higher during Greed phases**, suggesting traders may take advantage of bullish conditions.  
- Average trade sizes differ slightly between Fear and Greed, reflecting changes in risk appetite.

---

## 8. Conclusion

This assessment successfully:  
✔ Merged two heterogeneous datasets (sentiment + trading)  
✔ Performed **trend analysis** of trades and PnL over time  
✔ Analyzed **relationships between sentiment and trader performance**  
✔ Built **interactive dashboards** for deeper insights  

**Takeaway:**  
Market sentiment plays a significant role in trading outcomes.  
Greed often drives higher profits but also larger risks, while Fear periods see reduced activity and cautious trading.  
These findings can help improve strategy design and risk management for traders and analysts alike.
