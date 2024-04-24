# investment_portfolio

## 关于
1. 代码主要参考Fábio Neves的文章，你可以在他的文章中找到一些细节性的解释：https://towardsdatascience.com/python-markowitz-optimization-b5e1623060f5
2. 灵感来自于科普视频博主--柴知道的有关科学投资的相关视频，并对代码计算速度进行优化，具体可以多关注柴知道呀
 
## 使用说明
1. 修改起始时间`start_date`和`end_date`。需要注意有些公司上市时间可能比较迟，例如B站是在2018年上市，如果你的开始时间是从2015年开始，那么结果可能会不准确，取你需要进行组合分析成分的最新上市时间为佳。
2. 修改和添加`data_array`中的资产代号，数量没有限制，这里使用的是雅虎财经的API，你可以在搜索引擎中以「公司名+雅虎财经（Yahoo Finance）」搜索对应公司代号。例如茅台是「600519.SS」，苹果是「AAPL」，腾讯是「0700.HK」。
3. 如果运算时间过长，你可以尝试降低`sample_num`的数值。
4. 由于yfinance被墙，需要使用科学上网方式连接其API，当然也可以改为国内其他接口（如tushare，baostock等）。
5. 计算结果仅供参考。投资有风险，入市需谨慎。

# stock_daily_k_visualization

## 基本内容
基于国内免费财经数据平台baotock进行编程，使用mplfinance进行K线等绘图,进行资金回测
需要的库：baostock  mplfinance

# stock_prediction_using_RNN_and_relative_banch

## 基本内容
使用RNN和其他相关网络（LSTM, GRU）对股票走势进行预测
需要的特殊库：tensorflow 1.12

# stock_strategy_analysis_using_DQN

## 基本内容
使用深度强化学习方法（DQN）,实现对股票买卖策略的自适应调整
需要的特殊库：chainer

# data_download
链接：https://pan.baidu.com/s/1OnBsM281KMy96AdopM5ofg?pwd=2023 
提取码：2023 
--来自百度网盘超级会员V6的分享