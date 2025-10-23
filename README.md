Description: multi company OHLCV over ~5 years with ticker column, enabling selection of liquid names and consistent daily forecasting windows suitable for LSTM training density and cross sectional comparison.
Applicability: canonical next day close regression with optional per ticker models or shared architectures; supports indicator engineering and panel style slices by sector or liquidity.
Attributes: date, open, high, low, close, volume, Name/ticker; per ticker instances typically ~1,250 trading days over 5 years; suitable for per ticker modeling or pooled setups.
Algorithms used: LSTM regression baseline; ARIMA baseline; Gradient Boosting/Random Forest on engineered indicators as tabular baselines; BiLSTM classification for directional analysis.
