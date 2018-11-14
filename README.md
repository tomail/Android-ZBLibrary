## 部署
1. 点击 [![](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/onplus/shadowsocks-heroku/tree/re)，[一键部署到heroku](https://heroku.com/deploy?template=https://github.com/onplus/shadowsocks-heroku/tree/re)
  
    也可以选择另一个版本的服务端[shadowsocks-websocket-python](https://github.com/onplus/shadowsocks-websocket-python/blob/deploy/README.md)

1. 设置 加密算法和app 密码

![deploy](https://user-images.githubusercontent.com/31188782/31343896-ab0a868a-ad43-11e7-8a83-369cf5e385b0.jpg)

[](https://user-images.githubusercontent.com/31188782/31310674-e783c9e4-abce-11e7-87d2-48f328e74169.JPG)

支持的加密算法类型如下https://github.com/mrluanma/shadowsocks-heroku#supported-ciphers

## 启动本地 Client
1. 下载release https://github.com/onplus/shadowsocks-heroku/releases （[备份](https://github.com/onplus/archive/tree/master/tool)）

2. 修改config.json参数，运行ss-h.exe 或 start.vbs (或 [win托盘工具taskbar.exe](https://github.com/onplus/shadowsocks-heroku/issues/39))

5. 启动成功，命令行显示：`server listening at { address: '127.0.0.1', family: 'IPv4', port: 1080 }`
