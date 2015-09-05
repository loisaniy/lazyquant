# 数据库进程 #	

> **实现如下功能**
> 
> 为所有服务提供数据存储
1. 为account提供资金账户及营业部信息存储
2. strategy管理进程提供策略储存
3. strategy进程提供数据储存
4. client账户储存
5. oms订单储存
6. markdata行情储存

> **关联模块：**
- account进程
- client进程
- oms
- strategy管理进程
- strategy数据存储

## 注意事项 ##
1. 以上均为落地，缓存数据均存储在redis中
