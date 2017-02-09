# squid dockerfile
开放的代理服务器，不过限制只能访问指定域名。

## 使用方法
docker run -d --restart always -p 3128:3128 --name squid-domain centosbz/squid-domain

## 测试
curl -x ip:3128 www.centos.bz