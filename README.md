# 魔法上网
鉴于用过的好几个梯子体验都比较差（不能chatGPT，谷歌学术打不开，youtube卡顿，谷歌搜索慢，翻墙了还显示我本地ip），因此自己弄了一个梯子，准备挂几个人养活服务器。
- 付费提供流量节点，可用于多个代理软件，25￥/月，需要的Q我1225085028。
- 节点类型包含vmess trojan shadowsocks vless，不提供不加密的类型。
- 网络不好时先打开 软件 连接上节点，再断开，关闭软件 网络即可恢复正常。
- 建议需要翻墙时使用，开启后网络速度会受影响，特别是手机上。

接下来以windows和Android为例，说明用法。
[Android系统](#android%E7%B3%BB%E7%BB%9F)
[Windwos系统](#windows%E7%B3%BB%E7%BB%9F)
[ios系统](#ios%E7%B3%BB%E7%BB%9F)

## Android系统
使用v2rayNG软件，导入节点，设置跳过证书验证，然后点击连接即可上网。

软件下载地址：[开源下载](https://github.com/2dust/v2rayNG/releases/download/1.8.5/v2rayNG_1.8.5.apk)、[备用下载](https://pc.domainsname.win:2080/download/Android.apk)

### 设置
图中最后一步如果没有毫秒值，则节点不可用需要更换。

![image](https://github.com/578meng/v2/assets/33978206/5873da1e-ae0e-4090-8d90-f5a9ac09c06c)

__开启之后屏幕顶部会有VPN提示！！！__




## Windows系统
windows使用的是v2rayN软件，已经有的不用再下载。

下载地址：[开源下载](https://github.com/2dust/v2rayN/releases/download/6.23/v2rayN-With-Core.zip)、[备用下载](https://pc.domainsname.win:2080/download/Windwos.zip)

#### 使用
下载之后解压压缩包，运行里面的v2rayN.exe文件，然后如图点桌面右下角图标打开软件界面

![image](https://github.com/578meng/v2/assets/33978206/77735f92-36a4-4eee-8d4f-ac4337fbb255)

- 复制粘贴节点导入到软件中

![image](https://github.com/578meng/v2/assets/33978206/b40d5f91-a97b-47b4-b004-d42bcf59d092)

- 选中节点测试速度，如果不是正常数值，则该节点不可上网，需要更换。

![image](https://github.com/578meng/v2/assets/33978206/84c1d4c3-30ce-4928-833d-eeffb8bb7f14)


- 设置系统代理，右下角图标变为红色即可上网。

![image](https://github.com/578meng/v2/assets/33978206/14d2adef-08f8-4ba2-9e3a-6f37f8bd59ef)


## ios系统
软件使用Shadowrocket，在app store中下载，国内一般搜不到，需要在已购账号中下载。
- 退出你的app store账号，登录我的，软件下载好之后再切换回去就行。登录时遇到安全验证选择 __其他选项->不升级__
![93e3213c9411a092efc22fa1b3fbe36](https://github.com/578meng/v2/assets/33978206/3c06bc24-1cf4-467b-b8cc-ad7d39bde0d0)

- 登上之后再已购项目中划到最底下找到Shadowrocket下载安装
![image](https://github.com/578meng/v2/assets/33978206/f723a092-1142-419a-a91e-d6dfabe7d52c)


复制节点信息，打开Shadowrocket，稍等片刻会自动弹出窗口，如图，点击“添加”，即可添加所有v2ray节点。

也可使用左上角扫描二维码导入节点。


之后，设置“全局路由”为“配置”，选择节点，进行连接即可。



