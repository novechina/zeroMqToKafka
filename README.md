# zeroMqToKafka
序列化推送到kafka
## 简介
使用probuf工具对传输对象进行序列化
经过zeroMQ传输
反序列化
推送到kafka
### probuf
需要用工具编译出来java的对象文件
### zeroMQ
使用了基于发布订阅模式的配置，开启了一个代理端口
### kafka
高级api
