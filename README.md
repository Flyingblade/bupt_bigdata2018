# bupt_bigdata2018
bupt bigdata rank22 rmse 213.2797

# 数据预处理
  * 缺失值填补

# 特征工程
  * 日期、小时、星期几、当月第几周……
  * 是否 周末、小假期、寒暑假…（from 校历） --> 当天是否上课
  * 是否 上课时段（不放假的周一到周五）
  * 天气情况：污染指数、温度、天气、风力、风向……
 
 # 模型
  * xgboost,random forest
 
 # 模型融合
  * 平均值
