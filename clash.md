Clash Meta 已改名 Mihomo，是一个基于开源项目 Clash 的二次开发版本，并增加了一些独有特性，Meta 核心支持所有原开源核心的全部特性，支持原 Clash Premium 核心部分特性。

## 使用
Windows、mac、Linux桌面版安装Clash Verge，安卓安装Clash Meta for Android，苹果继续小火箭
1. 导入订阅
2. 托盘右键设置为如图
<img width="380" height="644" alt="2b1ab38f6000d49e3e0bc0ca28501b6d" src="https://github.com/user-attachments/assets/7d404189-baac-4756-8e79-c7bf038da16a" />
3. 开启tun模式（可选）
   首页tab下，页面滚动到最下方，切换到服务模式，安装，可以启动tun模式

## Clash Meta 客户端列表

| 客户端              | Windows | macOS | iOS | Android | 维护状态 | 教程 | 下载 |
|-------------------|--------|-------|-----|---------|----------|------|------|
| Clash Meta For Android |        |       |     | &#x2714;       | 更新     | 教程 | 下载 |
| Clash Mi           | &#x2714;      | &#x2714;     | &#x2714;   | &#x2714;       | 更新     | 教程 | 下载 |
| Clash Nyanpasu     | &#x2714;      | &#x2714;     |     |         | 更新     | 教程 | 下载 |
| Clash Party        | &#x2714;      | &#x2714;     |     |         | 更新     | 教程 | 下载 |
| Clash Verge        | &#x2714;      | &#x2714;     |     |         | 更新     | 教程 | 下载 |
| ClashN             | &#x2714;      |       |     |         | ~~停更~~     | 教程 | 下载 |
| ClashX Meta        |        | &#x2714;     |     |         | 更新     | 教程 | 下载 |
| FlClash            | &#x2714;      | &#x2714;     |     | &#x2714;       | 更新     | 教程 | 下载 |
| Mihomo Party       | &#x2714;      | &#x2714;     |     |         | ~~停更~~     | 教程 | 下载 |
| v2rayN             | &#x2714;      | &#x2714;     |     |         | 更新     | 教程 | 下载 |

Clash Meta 只是内核，需搭配客户端使用，目前还在维护更新的 Clash Meta 客户端可直接在下面点击进入下载，包含 Windows、macOS、Android、iOS 及 Linux  操作系统，均支持 Mihomo 内核。

## Clash Meta（Mihomo）客户端下载

### Windows

- [Clash Verge 下载](https://github.com/clash-verge-rev/clash-verge-rev)
- [v2rayN 下载]()
- [Clash Party 下载]()
- [Clash Nyanpasu 下载]()
- [FlClash 下载]()

### macOS

- [ClashX.Meta 下载](https://github.com/MetaCubeX/ClashX.Meta)

### Android

- [Clash Meta for Android 下载](https://github.com/MetaCubeX/ClashMetaForAndroid)

### iOS

- [Clash Mi 下载]()

### Linux

- [v2rayN 下载]()
- [Clash Verge 下载](https://github.com/clash-verge-rev/clash-verge-rev)

下载deb包后，使用apt安装：`sudo apt install -y ./Clash.Verge_x.x.x-_xxx.deb`。
注意：
1. 必须在 Linux 桌面 GUI 下命令启动`clash-verge`，无桌面环境下命令行无法生效
2. 管理后台网页：Safari 打开链接有问题，用 chrome



注：Clash Verge Rev是Windows、macOS、Linux平台下一款网络 代理 软件客户端，基于Mihomo内核开发，是Clash Verge之后的后续版本，支持翻墙协议有Shadowsocks (SS)、ShadowsocksR (SSR)、Trojan、V2Ray等科学上网协议。https://clashverge.net

## 如何拥抱 clashX（Mac）
clashX应该是mac上最好用的终端，主要涉及两部分：无泄露隐私风险部署转换服务+工具选用

<!--more-->

https://www.youtube.com/watch?v=7abmWqCXPR8

### 部署sublink，自己域名下转换

教程 https://sublink.works/guide/quick-start
自己有域名，挂靠cloudflare

1. 通过教程建立 worker 服务（cloudflare 的云服务）。首次建立可能出现失败，构建命令需要按教程改成`npm run deploy`

2. 自定义自己的域名（用workers.dev会被ban），建议子域名加随机前缀做 token，也避免被搜索引擎收录

3. 打开自定义域名自定义自己的域名，看到url 转换页面，可以先按默认生成

### clashX工具选择

旧版 clashX 可能无法兼容sublink 的链接，建议使用ClashX Meta

https://github.com/MetaCubeX/ClashX.Meta
