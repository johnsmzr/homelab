# Status

### get cert: work
- 安装cert-manager，然后运行production，再修改一下网站对应的ingress即可

### mysql: work
- to do: mysql主从模式，一主一从

### wordpress + mysql: work
- to do: 
    - 尝试用StatefulSet部署数据库mysql，而不是hostPath
    - wordpress 持久化储存（在预先设定连接数据库的情况下好像没必要了）

### prometheus + grafana: work
- to do: 
    - 数据持久化储存