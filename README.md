# Candy-ServerStatus 糖果服务器云探针
2020 07 14

![image](http://icland.xyz/picture/Candy-ServerStatus-github-examples.png)

# 在线展示 https://icland.xyz/status/

# 基于修改&优化&去杂
```bash
/client/*
/server/src/main.h
/server/src/main.cpp
/web/index.html
/web/css/hotaru_fix.css
/web/js/serverstatus.js
/web/img/*
```
# 食用方法:
```bash
git clone https://github.com/skyxingcheng/Candy-ServerStatus.git
cd /Candy-ServerStatus/server
make
./sergate -c config -d /usr/share/wwwroot/ -p 35601
```

客户端使用linux或跨平台的python文件直接启动即可 注意配置服务器和用户名密码

支持ipv4和ipv6支持检测双线

需在客户端设置自定义ipv4&ipv6检测地址

# 相关开源项目:
前端来自:		https://github.com/CokeMine/ServerStatus-Hotaru

服务端来自:		https://github.com/BotoX/ServerStatus

客户端来自:		https://github.com/cppla/ServerStatus
