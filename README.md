# buaaGatewayAutoLogin
北航校园网网关自动登录脚本，挂在实验室服务器上，自动登录，防止断网

## 使用

win10下
```
pip install -r .\requirements.txt
```

ubuntu下
```
pip install -r ./requirements.txt
```

修改`BeihangLogin\login.sh`中的`username`和`pwd`

可以在ubuntu下使用crontab

在win10下使用系统自带定时任务

