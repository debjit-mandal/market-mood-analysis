
# Market Mood Index vs NIFTY Index Analysis

This project analyzes the relationship between the Market Mood Index (MMI) and the NIFTY Index using various statistical and machine learning techniques. The dataset includes data from 2012 to 2024.

## Dataset

The dataset is sourced from TickerTape and includes the following columns:

- **Date**: The date of the data entry.
- **Market Mood Index**: A numerical value representing the market sentiment.
- **Nifty Index**: The closing value of the NIFTY Index on the given date.

## Project Structure

The project consists of several Jupyter notebooks, each focusing on different aspects of the analysis:

1. **Descriptive Analysis**: Summary statistics and trend analysis.
2. **Correlation Analysis**: Correlation between MMI and NIFTY, including lagged correlation.
3. **Time Series Analysis**: Seasonality, decomposition, moving averages, and autocorrelation analysis.
4. **Predictive Modeling**: Linear regression, ARIMA modeling for forecasting.
5. **Comparative Analysis**: Event analysis, volatility comparison.
6. **Visualization**: Scatter plots, heatmaps.
7. **Advanced Visualization**: Pair plot, joint plot.
8. **Moving Average Analysis**: Calculation and visualization of moving averages.
9. **Statistical Tests**: Pearson correlation, T-test, ANOVA.
10. **Clustering Analysis**: K-Means clustering.
11. **Trend Analysis**: Linear and exponential trend analysis.
12. **Forecasting**: Exponential smoothing for forecasting.
13. **Sentiment Analysis**: Sentiment analysis using TextBlob.
14. **Anomaly Detection**: Anomaly detection using Isolation Forest.

## Notebooks

- `Descriptive_Analysis_MMI_vs_NIFTY.ipynb`
- `Correlation_Analysis_MMI_vs_NIFTY.ipynb`
- `Time_Series_Analysis_MMI_vs_NIFTY.ipynb`
- `Predictive_Modeling_MMI_vs_NIFTY.ipynb`
- `Comparative_Analysis_MMI_vs_NIFTY.ipynb`
- `Visualization_MMI_vs_NIFTY.ipynb`
- `Advanced_Visualization_MMI_vs_NIFTY_Corrected.ipynb`
- `Moving_Average_Analysis_MMI_vs_NIFTY.ipynb`
- `Statistical_Tests_MMI_vs_NIFTY.ipynb`
- `Clustering_Analysis_MMI_vs_NIFTY.ipynb`
- `Trend_Analysis_MMI_vs_NIFTY.ipynb`
- `Forecasting_MMI_vs_NIFTY.ipynb`
- `Sentiment_Analysis_MMI_Corrected_v2.ipynb`
- `Anomaly_Detection_MMI_vs_NIFTY.ipynb`

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - pandas
  - matplotlib
  - seaborn
  - numpy
  - statsmodels
  - scikit-learn
  - textblob

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/debjit-mandal/market-mood-analysis.git
   ```
2. Navigate to the project directory:
   ```sh
   cd market-mood-analysis
   ```
3. Install the required libraries:
   ```sh
   pip install pandas matplotlib seaborn numpy statsmodels scikit-learn textblob
   ```

### Usage

Open the desired Jupyter notebook using Jupyter Notebook or Jupyter Lab:
```sh
jupyter notebook
```
or
```sh
jupyter lab
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgments

- TickerTape for providing the data.
- All the Python libraries and tools that made this project possible.

----------------------------------------------------------------

**Feel free to suggest any kind of improvements.**