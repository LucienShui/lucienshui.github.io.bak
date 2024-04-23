---
title: "中国石油大学（华东）校园网络认证脚本"
date: 2018-04-23 00:21:00 +0800
last_modified_at: 2018-06-05 10:45:48 +0800
math: false
render_with_liquid: false
categories: ["程序人生", "其它"]
tags: ["其它"]
---

## 中国石油大学（华东）校园网络认证脚本

#### 项目地址

&emsp;&emsp;https://github.com/LucienShui/UPCNet

#### 源码依赖
&emsp;&emsp;采用Python3编写，依赖于

```
requests
urllib/urllib.parse
base64
```

#### 使用方法
&emsp;&emsp;第一次启动时会自动要求输入账号密码以及选择运营商，然后会加密后保存在本地的`config.ini`文件中，如需重新配置账号密码删掉脚本根目录下的这个文件即可

&emsp;&emsp;运营商对应编号：

```
1.校园网
2.联通
3.移动
4.电信
5.校园内网
```

#### 目前支持的网络类型：

有线网络（认证IP地址:`121.251.251.207`)

无线网络（认证IP地址:`121.251.251.217`)

#### 版权信息

```
Author：LucienShui

From：EndangeredFish
```

#### 鸣谢

&emsp;&emsp;[EndangeredFish](https://github.com/EndangeredF1sh)
