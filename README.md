# spring-boot-test  微服务

springboot maven项目

一、spring-boot-server

1. servlet、listener、interceptor、filter配置
2. mybatis配置集成，多数据源
3. jmx监控MBean
4. 定时任务配置
5. aop配置
6. ftp服务
7. 测试
8. Metrics监控
9. 参数验证
    测试：/hellox?name=
10. 跨域处理
11. 添加shiro权限控制

    测试用户：userName: admin passwd: admin
             
    验证码：/login/checkcode
    
    登录：/login?userName=&passwd=&code=
    
    测试：/hellox?name=
12. 导出Excel

    测试：/export

13. 服务启动注册到consul；并测试获取redis服务，初始化redis资源；consul 监控redis服务 ；reids分布式锁；注意consul客户端和consul程序版本问题

14. SPI机制: org/windwant/spring/core/spi

    运行时配置：META-INF/services/org.windwant.spring.core.spi.Calc

15. static资源， “/” 映射

16. 使用druid数据源连接池；配置druid数据源监控：http://localhost:8081/druid/index.html

17. dubbo server


二、spring-boot-test

测试dubbo rpc服务

测试websocket protobuf

三、spring-dubbo-common

api 接口

四、spring-dubbo-proxy

netty rpc 服务代理，处理业务消息解析 分发

五、spring-dubbo-wsproxy

netty rpc websocket 服务代理

六、spring-dubbo-protobuf

protobuf 资源

七、spring-dubbo-client

proxy websocketproxy 测试工程

八、spring-dubbo-elasticjob

测试spring-boot-server druid监控定时任务

