## `【_Jeremy_固件】（6.12内核）`
#### 🚩 源码拉取`coolsnowwolf` `Lienol` `immortalwrt` `x-wrt` `openwrt` 自行选择编译
- _Jeremy_适配OTA自动升级のX86固件
- 默认IP地址：`10.10.10.2`
- 账户：`root`   密码：`空`
 
#### 🚩 点击下表中 [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?style=flat&logo=hack-the-box)](https://github.com/shidahuilang/openwrt/releases) 即可跳转到该设备固件下载页面
| 平台+设备名称 | 固件编译状态 | 配置文件 | 固件下载 |
| :-------------: | :-------------: | :-------------: | :-------------: |
| [![](https://img.shields.io/badge/openwrt-X86_64-32C955.svg?logo=openwrt)](https://github.com/JeremyTnT/JeremyWrt/blob/main/.github/workflows/Lede.yml) | [![](https://github.com/shidahuilang/openwrt/actions/workflows/Lede.yml/badge.svg)](https://github.com/JeremyTnT/JeremyWrt/actions/workflows/compile.yml) | [![](https://img.shields.io/badge/编译-配置-orange.svg?logo=apache-spark)](https://github.com/JeremyTnT/JeremyWrt/blob/main/build/Lede/seed/x86_64) | [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?logo=hack-the-box)](https://github.com/JeremyTnT/JeremyWrt/releases) |


- ================================================================
- 首先需要打开 Openwrt 主页,点击系统-TTYD 命令窗,或者使用```putty```或者```openwrt```后台luci插件在线更新 
- 输入`openwrt`即可进入固件升级菜单                            
- 输入`tools`即可打开工具箱
- 输入`qinglong`即可全自动安装青龙 
- ================================================================

- 自行云编译固件姿势
- ssh-actions改为ssh就可以启动插件选择
- 看到ssh链接会有一个web的链接，打开就是命令行，根据下面命令进入
- 开始 ctrl+c 
- 进ssh选择插件 
``` bash
cd openwrt && make menuconfig
```
- 结束ctrl+d
- REPO_TOKEN密匙制作教程：https://git.io/jm.md
- 云编译需要 [在此](https://github.com/settings/tokens) 创建个```token```,勾选：```repo```, ```workflow```，保存所得的key
- 然后在此仓库```Settings```->```Secrets```中添加个名字为```REPO_TOKEN```的Secret,填入token获得的key

- TG通知```Settings```->```Secrets```中添加个名字为```TELEGRAM_BOT_TOKEN```和```TELEGRAM_CHAT_ID```

## 自动更新固件
![img.png](img/img.png)
![1.png](img/1.png)
![2.png](img/2.png)
![img2.png](img/img2.png)
![img3.png](img/img3.png)

[![Stargazers over time](https://starchart.cc/shidahuilang/openwrt.svg)](https://starchart.cc/shidahuilang/openwrt)
 ### 鸣谢！
 感谢以下各位大佬（排名无分先后）<br />
[`coolsnowwolf`]
[`danshui`]
[`Lienol`]
[`immortalwrt`]
[`P3TERX`]
[`Hyy2001X`]


