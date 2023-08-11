
密码：kong

### 🎈 非关系型数据库

非关系型数据库是指采用了非关系模型来组织数据的数据库，其以键值对的形式存储数据。

Redis：
端口：6379

### 📫 消息队列

消息队列是一种应用程序对应用程序的通信方法。应用程序通过读写出入队列的消息（针对应用程序的数据）来通信，而无需专用连接来链接它们。

RocketMQ

### 📝 服务注册中心

服务注册中心是微服务架构中的核心组件，用于实现服务的注册与发现，以及服务的健康检查、故障隔离等功能。

consul
s
### 📋 配置文件中心

配置中心是微服务架构中的核心组件，用于实现配置文件的统一管理。

nacos

### 📂 文件服务器

文件服务器是用于存储文件的服务器，本项目中用于存储用户上传的文件。

aliyun oss

### 🚀 内网穿透工具

内网穿透是一种将局域网或者数据中心内部服务映射到公网上的技术。

- [x] （选用）NATAPP <https://natapp.cn/>

    + 优点：有免费版
    + 缺点：每次本地启动域名会变，需要在 nacos 中每次修改 oss-web.json 的 callback_url

- [ ] 飞鸽 <https://www.fgnwct.com/>

    + 优点：有免费版
    + 缺点：免费隧道需强制访问验证，一些外网服务不方便做回调

### 💰 支付功能

alipay 
沙箱环境：<https://openhome.alipay.com/develop/sandbox/app>

### 🎢 链路追踪

链路追踪是一种记录请求调用链路的技术，用于分析和解决微服务架构中的性能问题。

opentracing-go <github.com/opentracing/opentracing-go>
jaeger-client-go <github.com/uber/jaeger-client-go>

### 🕹 API 网关

API 网关是微服务架构中的核心组件，用于实现请求的路由、限流、熔断、鉴权等功能。

kong/konga

### ⚒ 构建工具

jenkins
