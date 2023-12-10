# Status

### get cert: work
- 安装cert-manager，然后运行issuer-production，再修改一下网站对应的ingress即可
- 之后任何新网站都可以直接找这个issuer签发证书，巨方便

### mysql: work
- to do: mysql主从模式，一主一从

### wordpress + mysql: work
- wordpress 加了TLS
- mysql 不对外暴露
- to do: 
    - 尝试用StatefulSet部署数据库mysql，而不是hostPath
    - wordpress 持久化储存（在预先设定连接数据库的情况下好像没必要了）

### prometheus + grafana: work
- grafana 加了TLS
- prometheus 没加TLS (有兴趣的可以加上)
- to do: 
    - 数据持久化储存
    - prometheus 加TLS, 再加上basic auth