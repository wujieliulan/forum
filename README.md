# 无界浏览(UltraSurf)最新版本下载

## [Windows版： 无界浏览 17.02a](https://raw.githubusercontent.com/wujieliulan/download/master/u.zip)

#### 校验码： 
SHA1: c6cf189a3b3c12028955b67d9fa234bf06aa5562

#### 安装与使用:
不需要安装，下载后将里面的u1702a.exe存到桌面或其他地方，双击即可使用。

## [安卓版(支持4.1以上）: 无界安卓手机版 1.0.7](https://raw.githubusercontent.com/wujieliulan/download/master/ultrasurf.apk)

#### 校验码： 
SHA1: 028df9edf5576d46b423025f7b5668176df51685

#### 安装：

将下载的apk文件拷贝到手机上, 在手机上点击此文件便可安装。如出现“禁止安装”警告，点“设置”，钩选“未知源”，继续安装。

#### 功能与使用：

1. 只支持安卓4.1以上。
2. 只支持整机VPN模式， 不支持代理模式。
3. 开启后，轻触或滑动开关，显示“正在连接 ..."，同时时上面会出现一个小钥匙和闪动的无界图标，表示正在连接。
4. 连接成功后无界图标停止闪动，显示“连接成功“。此时您可以使用任何浏览器或app，都在无界加密保护下。
5. 使用时，只要无界图标和小钥匙都在，就在在无界加密保护下。
6. 如果要停止使用，轻触或滑动开关即可。关闭后，无界图标和小钥匙会消失，这时手机直接联网，不在无界加密保护下。
7. 如果问题，可重启手机再运行无界。

#### 注意事项：
1. 建议使用浏览器的“隐私模式”浏览敏感网站，这样不会留下历史纪录。
2. 如果浏览器不支持“隐私模式”，请手动清除所有历史纪录，或使用清除所有历史纪录的工具。
3. 为安全起见，建议关闭所有浏览器和其他app，再关闭无界，以免直连敏感网站。也可以直接重启手机， 这样最安全。

请大家测试并反馈， 谢谢

  
## [无界火狐扩展 17.02a （支持Windows，Mac，Linux）](https://raw.githubusercontent.com/wujieliulan/download/master/ultrasurf.apk)

#### 校验码： SHA1: bfb67a0b3e53271d7b29191d3a3df78ed93faca3

#### 安装：

可以用火狐直接下载安装，点击“允许”。如火狐禁止下载，可用其他浏览器下载后用鼠标拉到火狐浏览器，点击“安装”。

#### 功能与使用：

1. 支持Windows, Mac, Linux, 32/64位。
2. 点击火狐右上角的无界图标，点击开关即可开启或关闭。 连接成功后，无界图标变成彩色。

## [无界Linux VPN 17.02a （支持Windows，Mac，Linux）](https://raw.githubusercontent.com/wujieliulan/download/master/ul)

#### 校验码： SHA1: 66a10e91f07e48b71046b94471d2fca3e21ca41c

#### 功能与使用：

下载后在下载的文件夹右键打开一个终端，在终端执行：chmod +x ul，然后执行：./ul， 终端出现以下信息：
LISTENING 127.0.0.1:9666 （监听 127.0.0.1:9666 ）
0.650 Connecting ... （正在连接）
1.569 Connecting ... （正在连接）
2.178 CONNECTED （连接成功）
需要手动设置浏览器代理。

./ul -help 显示使用方法：
Usage of ./ul:
-ConnMode string
Connect mode, 0: Auto, 1: T, 2: U, 3: P
-L string
listen address (default "127.0.0.1:9666")
-M string
"vpn": turn on VPN mode
-P string
http or sock proxy, example: 1.2.3.4:8080 或 http://1.2.3.4:8080 或 socks://1.2.4.4:1080 或 socks5://1.2.3.4:1080 或 socks=1.2.3.4:1080
-S string
"safe": turn on VPN safe mode, when exit, do not restore routing until reboot

./ul -ConnMode 1 （1：“T模式” ， 2 ：“U模式” 3：“P模式”）

如需要监听 0.0.0.0，在终端执行： ./ul -L :9666
如需要通过代理， 执行： ./ul -P 1.2.3.4：8080 或 .ul -P socks://1.2.3.4:1080

运行VPN模式，需要root或sudo， 执行：sudo ./ul -M vpn， 输入密码， 终端出现以下信息 （顺序可能不同）：
LISTENING 127.0.0.1:9666 （监听 127.0.0.1:9666 ）
VPN MODE （VPN模式）
0.650 Connecting ... （正在连接）
1.569 Connecting ... （正在连接）
2.178 CONNECTED （连接成功）

如需要在VPN下分享：sudo ./ul -M vpn -L :9666
LISTENING 0.0.0.0:9666 （监听 0.0.0.0:9666 ）
VPN MODE （VPN模式）
0.650 Connecting ... （正在连接）
1.569 Connecting ... （正在连接）
2.178 CONNECTED （连接成功）

在VPN模式下不需要设置代理，整机都通过无界加密翻墙，不会出现直连。我们还是建议设置代理以避免退出无界后直连，这样更安全。建议使用浏览器的“隐私模式”，这样不会留下历史纪录。退出无界前，最好关闭所有浏览器，以免退出后直连敏感网站。

VPN 安全模式：
为了确保安全，新增了VPN 安全模式: sudo ./ul -M vpn -S safe
终端出现以下信息 （顺序可能不同）：
LISTENING 127.0.0.1:9666 （监听 127.0.0.1:9666 ）
VPN SAFE MODE （VPN 安全模式）
0.650 Connecting ... （正在连接）
1.569 Connecting ... （正在连接）
2.178 CONNECTED （连接成功）

一旦运行了 VPN 安全模式，电脑一直处于网络隔离状态，即使关闭了无界，也无法联网。这样消除了所有泄露IP的隐患，以确保安全。不过还是建议设置无界代理，进一步增加安全性，即使恢复到非网络隔离状态也不会泄露IP。也建议使用浏览器的“隐私模式”，最好使用定制版的浏览器，以避免留下历史纪录。

请大家收藏本页面，方便日后下载新版。
