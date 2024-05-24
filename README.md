# Quantitative Trading & Machine Learning Techniques
* Fama-French Factors and Rolling Factor Betas.
* K-Means Clustering Algorithm
* Portfolio Optimization based on Efficient Frontier max Sharpe ratio optimization

![image](https://github.com/Inquisitive-Learner/Unsupervised-Machine-Learning-Quantitative-Trading-Strategy/assets/80440978/6cdab35d-c4dc-49c9-989d-17eae95ee67f)

# Process
* Download/Load SP500 stocks prices data.
* Calculate different features and indicators on each stock.
* Aggregate monthly and filter the top 150 most liquid stocks.
* Calculate Monthly Returns for different time horizons.
* Download Fama-French Factors and Calculate Rolling Factor Betas.
* For each month fit a K-Means Clustering Algorithm to group similar assets based on their features.
* For each month select assets based on the cluster and form a portfolio based on Efficient Frontier max Sharpe ratio optimization.
* Visualize Portfolio returns and compare them to SP500 returns.
