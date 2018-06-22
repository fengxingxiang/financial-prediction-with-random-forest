## financial-prediction-with-random-forest<br>
##### 主题：使用随机森林分类器去预测金融市场股票未来第K天的涨跌情况<br>
##### 细节：原始股票数据经过指数平滑处理，并计算常用的技术指标，进行最大最小归一化处理，使用随机森林分类器训练预测<br>
##### 1、get_stock_data通过Tushare获取原始股票数据<br>
##### 2、exponential_smoothing、em_stock_data进行股票指数平滑处理<br>
##### 3、calc_technical_indicators进行常用的技术指标<br>
##### 4、normalization进行归一化处理并分割数据集<br>
##### 5、random_forest_model随机森林模型，返回准确率和数据特征对数据标签的影响程度<br>
