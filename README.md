# [Project 1 - Bank Churn Prediction](https://github.com/KhanMuhammadOvais/Bank-Churn-Management-Project)
 - The main goal of the project is to identify potential reasons behind customer attrition at the bank, and to predict future customers who might leave, that that will allow the bank to be creative and proactive in their engagement with the customers.
 - As a data objective, we would ideally also like to idenfify the machine learning algorithm that has the best accuracy and what are some of the most important factors considered by the algorithm.
 - Performed EDA and identified some indicators and red flags that can be used as signals to highlights customers that might churn. 
 - Data Preprocessing including (Feature Transformation, Feature Scaling, and Addressing imbalanced dataset)
 - Ran linear (Logistic Regression, SVM) and Non Linear models (Decision Trees, Random Forest, Catboost) to select model with best Accuracy and Recall score. 
 - Optimizing and Hyperparameter tuning for the best models, using Grid Search CV to further improve the model performance. 
 - Built a client facing dashboard using Power BI, to track the most important feature and metrics from the modeling and EDA conclusions. 
 
 ![](/images/project1.jpg) 
 
 # [Project 2 - Robo Advisor](https://github.com/KhanMuhammadOvais/Robo-Advisor)
  - The main goal of the project was to build an, automated investment advisory service, that is well diversified across various asset classes and that require little to no user interaction. The other goal is to match or exceed the risk adjusted performance of the market.
 - Utilized Yahoo Finance API to download 10 years data for various ETFs across, different assets classes and different geographies.
 - Categorized investor's risk tolerance level based on the responses to the risk assessment queries.
 - Used Montecarlo simulation technique to generate various portfolios using random weights, and then plotted the efficient frontier, by using Scipy optimization to extract maximum returns for all given possible risk levels.
 - Selected the optimal portfolio for the customer, given their risk score, and backtested the performance of this optimal portfolio, to review historical risk adjusted performance of the portfolio against the market performance.
 - Finally using the Montecarlo simulation to forecast portfolio performance with 95% confidence interval across the next 3 years.
 
 ![](/images/project2.jpg) 
