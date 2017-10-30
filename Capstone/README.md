# Machine Learning Engineer Nanodegree Capstone Project
					 July 2, 2017

## Implementation of a Stock Predictor

### Libraries used

1. sklearn: linear model, neighbors, decomposition, metrics, preprocessing, model selection

2. pandas

3. numpy

4. scipy

5. xgboost

6. matplotlib.pyplot

7. urllib

8. bs4

9. seaborn

### Core Files

The entire solution is located in the Main.ipynb notebook. The remaining notebooks were used exclusively for research.

### Supplementary Files

**Datasets used:** All data was downloaded from Yahoo! Finance website on 06/09/2017. The datasets comprises the period of 01/04/2017 to 06/08/2017.

1. S&P 500: SPY.csv

2. NVIDIA Corporation: NVDA.csv

3. HNI Corporation: HNI.csv

4. Chevron Corporation: CVX.csv	

### Instructions of Use

After running all cells containing functions in the Main.ipynb notebook, follow these steps:

1. Use the function prepare data to get the feature and target sets, for each stock. Ex.:

> NVDA feats, NVDA target = prepare data(’NVDA’)

2. Run the cell with the models

3. Use the main function to get the prediction result. The ﬁrst six arguments are for the three pairs of data (features, target); the seventh argument is the number of days for prediction; the eight, the symbols of the stocks; and the ninth, to choose for printing the scores and plotting the graphics. Example:

>longo(NVDA feats, NVDA target, HNI feats, HNI target, CVX feats, CVX target, 7, [’NVDA’,’HNI’,’CVX’], True)

This will return the prediction of 7 days interval for NVIDIA, HNI and Chevron stocks, and will print/plot results.