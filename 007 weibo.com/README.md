# weibo.qrcode.py

## 利用手机微博客户端扫描二维码完成登录操作

这种方式的登录更加简便。同时在成功登录之后会将cookie保存在文件中。如果后续需要，可以直接用requests读取cookie文件即可对微博爬虫