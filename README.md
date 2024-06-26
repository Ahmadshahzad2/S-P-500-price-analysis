
# S&P 500 Price Prediction Using Various Models

---

## Introduction
This repository contains the implementation of several statistical, machine learning, and deep learning models to predict the S&P 500 stock prices as detailed in the paper "Comparative Analysis of Statistical, Machine Learning, and Deep Learning Approaches for Predicting S&P 500 Prices". The study spans data from 2014 to 2022 and compares models such as ARIMA, XGBoost, SVM, LSTM, and GRU based on their predictive accuracy and efficiency.

## Repository Contents
- `comparisons.ipynb`: Notebook containing comparative analysis and visualization.
- `DL_models.ipynb`: Implementation of deep learning models including LSTM and GRU.
- `ML_models.ipynb`: Implementation of machine learning models such as XGBoost and SVM.
- `statistical_models.ipynb`: Statistical models like ARIMA used for baseline predictions.
- `requirements.txt`: List of libraries required to run the notebooks.
- `Paper.pdf`: The accompanying research paper detailing the study's findings.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Navigate to the repository directory:
   ```
   cd your-repo-name
   ```
3. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```

## Usage
Each notebook is self-contained and can be run in a Jupyter environment to reproduce the results and visualizations presented in the paper:
```
jupyter notebook <notebook_name>.ipynb
```
Replace `<notebook_name>` with the name of the notebook you wish to run.

## Models Overview
- **Statistical Models**: Explore traditional time series forecasting techniques.
- **Machine Learning Models**: Includes models like Bayesian Ridge and Support Vector Regression which handle non-linear data patterns.
- **Deep Learning Models**: Utilize networks such as LSTM and GRU for their ability to capture long-term dependencies in time-series data.

## Results
The findings indicate that deep learning models, particularly the GRU, perform best in terms of RMSE and R² metrics, suggesting these models are most suitable for handling the complexities of stock price data. For detailed performance metrics, please refer to the `results` section in each notebook.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License
Specify the license under which the project is released, e.g., MIT, GPL, etc.

## Citation
If you use this code or the findings from the accompanying paper in your research, please cite:
```
Khawaja, A. (2024). Comparative Analysis of Statistical, Machine Learning, and Deep Learning Approaches for Predicting S&P 500 Prices. Thompson Rivers University.
```

## Contact
For any queries, please reach out to [a.shahzad2000july@gmail.com](mailto:a.shahzad2000july@gmail.com).

---
