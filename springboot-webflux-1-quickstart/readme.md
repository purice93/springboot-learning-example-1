springboot的两种服务架构：
    * MVC架构：阻塞型架构
    * webflux: 异步订阅模式
即webflux通过消息监控来对请求业务进行逻辑处理

表现形式上，webflux使用代码编写。mvc请求方式是通过注解来显示