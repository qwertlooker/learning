# Reactor
## 场景
分布式系统里面的server端同时收到多个client的多个event。
## 问题
分布式系统里面，必须要处理多个client的服务请求。在响应服务之前，server要解复用并把每一个请求分发到对应的服务提供者，这个过程需要高效处理，但是面临以下困难：   
* 可用性：处理时候不阻塞   
* 效率：时延小，吞吐量高，避免浪费CPU资源
* 编码简单：系统设计应该尽量简化使用并发的难度
* 适应性：
* 移植性：

## 解决方案


# 参考
深入设计模式 https://refactoringguru.cn/design-patterns/book
