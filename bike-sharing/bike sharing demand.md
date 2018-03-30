# bike sharing demand

kaggle:https://www.kaggle.com/c/bike-sharing-demand

EDA notebook是通过可视化进行数据探索分析

gbmANDrf是使用利用EDA分析结果对数据进行特征工程和处理，然后使用GBRT和RandomForestRegression对数据进行学习和预测

算法提升：

在处理casual离群点的时候，把0.7变成0.8可以有效提升gbm的性能，score从0.41提升到0.37