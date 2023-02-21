# Sales-Demand-Forecasting

**Goal**: Produce the 28 days ahead point forecasts for 30490 items in 42,840 time series that represent the hierarchical unit sales of Walmart, starting at the item level and aggregating to that of departments, product categories and stores in three geographical areas in US

**Data**: [Kaggle M5 Competition](https://www.kaggle.com/c/m5-forecasting-accuracy)

**Tool**: Python(pandas, numpy, scikit-learn, pytorch, kera, tensorflow, prophet, statsmodels, Optuna) 

**Model**:
- Boosting Model(LightBGM)
- Time Series Statistical Models(SARIMAX, Prophet)
- Deep Learning Models(Transformer, Seq2Seq)

**Techniques**: Multistep-Ahead Time Series Forecasting, Hyperparameters Optimization, Tweedie Loss Function

**Deliverables**: [Write Up](https://github.com/yiyutao22/Sales-Demand-Forecasting/blob/main/m5/Writeup.pdf)

**Result**: 0.5454 private score, ranked 7th in leaderboard
