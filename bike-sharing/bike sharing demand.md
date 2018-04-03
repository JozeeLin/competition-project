# bike sharing demand

kaggle:https://www.kaggle.com/c/bike-sharing-demand

EDA notebook是通过可视化进行数据探索分析

## Boosting

GBM是使用利用EDA分析结果对数据进行特征工程和处理，然后使用**GBRT**对数据进行学习和预测,通过超参数调优，在处理casual离群点时设置阈值为0.8时，score从0.41(0.7)时，提升到0.37.另外当阈值为0.5的时候，count和registered的分布变得非常均匀。

##Bagging

RandomForest是使用**随机森林**进行拟合。发现对特征进行独热编码可以有效提升RF的性能，RF对离群点的鲁棒性很好。