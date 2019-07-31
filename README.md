# security-memcached
分布式缓存memcached链接IP白名单版本
添加-E参数：实现客户端IP白名单的校验
如 -E 192.168.1.1,10.131.*
note：如果不添加-E参数时表示不作白名单，如果添加-E标示需要IP地址校验
