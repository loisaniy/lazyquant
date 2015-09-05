# 程序化策略编写平台 QuantTrader

## 一. 模块组成 ##
1. client-客户端管理
2. oms-订单管理
3. strategymanager-策略管理
4. strategy-策略进程
5. account-资金账户管理
6. marketdata-行情
7. futurestrader-交易

## 二. 内存及协议 ##
1. json

		模块内部间使用 Json格式数据传输
		定义消息头格式如下：
		to				目的地
		from			  来源
		params			参数集
		action			行为方式
		
		同步场景：
		id				同步编号
		result			结果集

2. redis

		内部存储使用redis

## 三. 相关交互 ##