# my-eureka-server

启动后可提供Eureka服务

## 使用

- 本地启动  
下载项目并编译(JRE>=8)后，启动`com.github.io.eureka.server.EurekaServerApplication`的`main`方法

- Docker启动  
``` bash
docker pull ldang264/my-eureka-server:1.0.0

docker run -p 8761:8761 ldang264/my-eureka-server:1.0.0
```
