# 一个简易MQ实现
> 设计思想和部分实现参考rocketmq来做

## 功能列表

1、实现基本的消息存储，需要考虑消息的物理存储与消息的检索
2、消息的简单发送
3、消息的简单消费（技术参考长连接+长轮训）