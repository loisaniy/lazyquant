# 策略管理 #	

> **实现如下功能**
> 
> 管理策略进程的创建，执行，停止及心跳维护
1. 策略进程的创建
2. 发送策略执行/停止信号到策略进程
3. 维护策略心跳
4. 实时查询各个策略进程的状态
5. 将相关策略信息写入到Redis，以便监控模块能实时监控


> **关联模块：**
- strategy进程
- client进程
- oms
- Redis

## 注意事项 ##
1. 若策略正常创建及执行超时或者停止失败，需要提供强停接口，直接kill掉策略进程