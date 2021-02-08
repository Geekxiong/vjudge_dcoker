# vjudge_dcoker

只是将老版本的vjudge做成了可以用docker-compose快速安装部署的项目。

1. 将整个项目clone下来
2. 将 `data/tomcat/webapps/vjudge.tar.gz`解压
3. 最后然后在该项目的根目录下运行下面的指令即可。

```
docker-compose up -d
```

访问地址是 http://127.0.0.1:8080/vjudge

设置宿主OJ的账号需要编辑`data/tomcat/webapps/vjudge/WEB-INF/classes/remote_accounts.json`
