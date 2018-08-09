# _springBoot 高级实战_ 

参考书籍：
    springboot实战 完整版 链接：https://pan.baidu.com/s/1mplnrtdXT-jdYtgR0yxI_Q 密码：kem5

**应用监控** 

1.	http
2.	JMX
3.	SSH

**分布式系统开发**

1.	微服务原生云应用
2.	Spring Cloud 快速入门
3.	实战
4.	基于Docker的部署



## 应用监控


### Http


1.  测试端点

请求地址：http://localhost:8888/actuator
请求结果：

```
{
    "_links": {
        "health": {
            "href": "http://localhost:8888/actuator/health",
            "templated": false
        },
        "info": {
            "href": "http://localhost:8888/actuator/info",
            "templated": false
        },
        "self": {
            "href": "http://localhost:8888/actuator",
            "templated": false
        }
    }
}
```

**注意** 
从springboot2.0开始Actuator有很大的变化：具体可以参考： [Actuator的改变](https://blog.csdn.net/liagn/article/details/81382423 "Actuator的改变") 

2.	定制端点
3.	自定义端点
4.	自定义HealthIndicator


### JMX

jconsole


### ssh


## 分布式服务开发（springcloud）


### 主要内容

1.  配置服务
2.  服务发现
3.	路由网关
4.	负载均衡
5.	断路器


### 实战














