# Candy-ServerStatus 糖果服务器云探针
2021 07 17

# 在线展示 http://kvm.icland.xyz/

![](https://cdn.jsdelivr.net/gh/skyxingcheng/ic-cdn@master/static/pictures/20210717101613.png)

本次更新全面使用了CDN你只需部署服务端和主页即可

# 食用方法:
```bash
git clone https://github.com/skyxingcheng/Candy-ServerStatus.git
cd /Candy-ServerStatus/server
make
./sergate -c config -d /usr/share/wwwroot/ -p 35601
```

客户端使用linux或跨平台的python文件直接启动即可 注意配置服务器和用户名密码

```
python client-linux-main.py
```

# 本项目修改自:

https://github.com/cppla/ServerStatus
