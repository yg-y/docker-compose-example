## 启动说明

>启动成功后，会出现 RabbitMQ Management 无法访问的情况，解决方法如下：
访问此rabbitmq主页时会出现无法访问，这是因为没有开启插件  
开启插件：首先使用命令进入容器  docker exec -it rabbit /bin/bash  
开启插件命令：rabbitmq-plugins enable rabbitmq_management