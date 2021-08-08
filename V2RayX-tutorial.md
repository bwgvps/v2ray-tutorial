# Mac 客户端 V2RayX 下载方法与使用教程
V2RayX是一个基于V2Ray内核的Mac OS X客户端,用户可以通过界面生成配置文件，并且可以手动更新V2Ray内核,V2RayX还可以配置系统代理。本文介绍V2rayX下载方法和V2rayX使用教程。
## V2RayX 下载

|Mac客户端|本站下载|官网下载|
|----|----|----|
|V2RayX|[点击下载](https://github.com/bwgvps/v2ray-tutorial/tree/master/V2RayX)|[点击下载](https://github.com/Cenmrev/V2RayX/releases)|

## V2RayX 使用教程

点击上方链接，进行下载，成功后直接点击图标即可。当 V2RayX 客户端打开后，可以在顶部状态栏找到 V2rayX 的图标，如图：

![V2RayX下载.png](https://i.loli.net/2021/08/02/kvJKH3RIcgBosx5.png)

点击 V2rayX 图标后会弹出 V2rayX 的菜单栏，我们选中“Confrigure",如下图所示：

![v2rayx.菜单栏png.png](https://i.loli.net/2021/08/02/wIsWZgOGycdLAmu.png)

随后我们就可以进行配置 V2RayX了，主要包括默认配置以及一些需要手动配置的内容：

![v2rayx手动配置.png](https://i.loli.net/2021/08/02/7upoV5gard4IUi1.png)

Address：输入“域名”或者“IP”。

User ID：用户 ID。

alterid：额外 ID。

Security：安全性正常选择“auto”。

Tag：名称

Network：承载网络一般为“tcp

如果 V2Ray 没有使用伪装，那么在以上弹出的对话框中填入相应的上网信息，就基本完成了网络配置。

但是如果你使用了伪装版的 V2Ray ，就需要接着填写以下信息：

点击“transport settings”进入高级设置界面。在 path 处填写伪装路径，headers 处填写伪装域名。

![高级配置.jpg](https://i.loli.net/2021/08/02/EcRra8TKU61dVSh.jpg)

然后点击“TLS”，如图：

![高级配置2.jpg](https://i.loli.net/2021/08/02/qwJ5edngFovI7ma.jpg)

当以上所有配置都完成后，点击右下方”OK“进行保存。

最后点击状态栏图标，V2Ray:on 为灰色的表示启用状态，开启 V2RayX 后系统也就开启了代理，无需再去配置浏览器之类的，就可以开始上网啦。软件代理模式有PAC和全局模式可选，一般选PAC模式。

### [<< 返回首页](README.md)
