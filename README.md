# Machete.Job
Task scheduling platform

解耦方式：
1.	通过回调的形式调度接口
别的系统把要定时调度的功能封装成一个接口，任务调度系统去定时调用这个接口
2.	通过消息队形的形式调度任务
定时调度系统定时往消息队列里面写要调度的任务，别的系统去消息队列里面取，在进行相关的业务代码

技术栈：
1. Spring Boot
2.  Quartz
3.  RabbitMQ
4.  Mysql
5.  Mybatis
