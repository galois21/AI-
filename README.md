# AI 安装接入指南
<img width="343" alt="image" src="https://github.com/user-attachments/assets/46dad1f3-2850-4ee4-90a7-1b02b7339852">


## 1. 梯子（VPN）

### 1.1 iPhone/iPad（iOS）

1. **安装软件**：下载并安装“小火箭”（Shadowrocket），这是 App Store 内的付费软件。
2. **软件下载安装步骤**：
   - 先退出当前的 App Store 账号（打开“App Store”，滑动到底部）。
   - 使用美区账号登录（**注意**：不要在“设置”里登录 iCloud，只在 App Store 内登录）。
   - 登录后，选择“其他选项”并选“不升级账号”，**不要绑定手机号**。
   - 在“已购项目”中找到 Shadowrocket 并下载到手机本地。
3. **添加订阅地址**：点击“➕”添加订阅地址，可以看到多条 VPN 线路。
4. **启动服务**：选择一个延时低的线路（可以通过连通性测试查看延迟），打开最上方的开关。如果能正常打开 YouTube，则说明翻墙成功。
5. **更新订阅**：点击订阅地址右上角的更新按钮。
6. **自定义规则**：进入“配置”->`default.conf`->“规则”，设置直连（direct）和代理（proxy）规则。
   ![image](https://github.com/user-attachments/assets/e890b40a-01c7-4be8-b72a-f83751f4665e)


### 1.2 苹果电脑（macOS）

1. **软件下载安装**：下载 [V2rayU-64.dmg](https://github.com/yanue/V2rayU/releases)并安装。
2. **添加订阅**：在“订阅设置”中点击“添加”。
3. **更新订阅**：在“订阅设置”中选中地址并点击“更新”。如需修改订阅地址，先移除旧的地址再添加新的（不支持直接修改）。
4. **启动服务**：添加订阅后选择一个服务地址，选择 PAC 模式并打开。
5. **自定义规则**：在“PAC 设置”中进行配置。
   ![image](https://github.com/user-attachments/assets/ab2f5b73-e2fa-4b43-ad89-3c1144d35933)


**备用软件**（部分订阅链接需要 ClashX，V2Ray 不支持）：下载 [ClashX.dmg](https://clashxhub.com/clash-backup-download/)。

### 1.3 Windows 电脑

1. **软件下载安装**：下载 [v2rayN-With-Core.zip](https://github.com/2dust/v2rayN/releases)，解压后运行 `v2rayN.exe`。
2. **添加订阅**：在“订阅分组”中点击“订阅分组设置”->“添加”。
3. **更新订阅**：在“订阅分组”中点击“更新全部订阅”。
4. **启动服务**：在系统托盘中选择“自动”+“黑名单”+任一服务器。
5. **自定义规则**：可为特定应用增加自定义规则。
   ![image](https://github.com/user-attachments/assets/2a18c5cd-9fd4-438b-b039-43a02aa5e90a)


**备用软件**：下载 [Clash.for.Windows.Setup.0.20.35.exe](https://clashxhub.com/clash-backup-download/)。。

### 1.4 安卓手机/平板

1. **软件下载安装**：从 [GitHub](https://github.com/2dust/v2rayNG) 下载v2rayNGd的apk 并安装。
2. **添加订阅**：在菜单中选择“订阅分组设置”->“+”添加，输入订阅地址。
3. **更新订阅**：在主界面右上角点击“三个点”->“更新订阅”。
4. **启动服务**：在左上角菜单中选择“设置”->“路由设置”->“预定义规则”->“绕过大陆”，选择任一服务器并启动。
5. **自定义规则**：在“设置”->“路由设置”->“自定义规则”中进行设置。
   ![image](https://github.com/user-attachments/assets/e8ec23f5-8f5e-4839-a06d-396629dfdb84)


**备用软件**：下载 [shadowsocks-universal-5.3.3.apk] 和 [com.github.shadowsocks-4.7.4.apk]。

### 1.5 订阅地址

- **更新日期**：2023-7-10
- **订阅地址**：提供多个 VPN 线路的订阅地址。

## 2. ChatGPT 使用指南

### 2.1 PC 端 ChatGPT

#### 2.1.1 注册

1. 访问 [ChatGPT 注册页面](https://chat.openai.com/auth/login)。
2. 点击 “Sign Up”，输入 Email（推荐使用 Gmail）并设置密码。
3. 收取验证邮件并点击 “Verify Email Address” 完成验证。
4. 注册成功后即可登录使用。

#### 2.1.2 客户端

OpenAI 已推出官方客户端，可直接在官网下载并安装。

### 2.2 移动端 ChatGPT

#### 2.2.1 苹果设备

1. 注册美区 Apple ID（ [参考指南](https://shadowsockshelp.github.io/Shadowsocks/apple-id.html)）。
2. 在 iPhone 的 App Store 中搜索并下载 ChatGPT。

#### 2.2.2 安卓设备

1. 墙外注册 Gmail 账号（建议选择非中国地区）。
2. 安卓手机下载安装 HiGoPlay 或 go 安装器，安装好 Google 服务三件套。
3. 登录 Google 商店，搜索并下载安装 ChatGPT。

# 【其他参考】
## 1 账号获取
### 1.1 虚拟手机号购买注册chatGPT

- 访问 [虚拟手机号购买网站](https://sms-activate.org/cn/freePrice#activation)，输入关键字 “openai” 选择合适的虚拟手机号进行购买。
- 选择任一国家，点击购物车按钮购买虚拟手机号（不要买美国的，无法通过验证！！！），购买成功后回到openai页面选择你购买虚拟号的国家，输入下图虚拟手机号，点击验证（**vpn一定要切全局代理，不然发不了验证码**）。输入验证码注册成功

### 1.2 GPT4 共享账号购买

- [【租用】ChatGPT4.0共享账号 | Plus订阅会员 | 长期稳定使用](https://store.sorryios.com/buy/3) 提供共享账号的租用和购买信息，推荐购买 ChatGPT Plus 订阅会员以获得更稳定的使用体验。

### 1.3 美区账号免费注册

- 参考[注册美区 Apple ID 帐号的终极指南](https://shadowsockshelp.github.io/Shadowsocks/apple-id.html)

### 1.4 美区账号购买

- 访问 [数卡杂货铺](https://www.ididhub.com) 进行购买。
- 其他购买：https://www.ididhub.com

## 2 VPS 运营商推荐连接工具下载

### Windows：

1. **选项 1（推荐）**：**Jamjams**（支持 v2ray 和 shadowsocks 协议）
   - [Jamjams-0.1.8 安装程序](https://justmysocks3.net/members/dist/jamjams-0.1.8-installer.exe) 或 [Jamjams-0.1.8 便携式](https://justmysocks3.net/members/dist/jamjams-0.1.8.exe)

2. **选项 2**：**v2rayN-Core**（支持 v2ray 和 shadowsocks 协议）
   - [v2rayN-Core-5.18](https://justmysocks3.net/members/dist/v2rayn-core-5.18.zip) 
   - 旧版本：[v2rayN-Core-3.18](https://justmysocks3.net/members/dist/v2rayn-core-3.18.zip)

3. **选项 3**：**香草 Shadowsocks-4**（仅支持 shadowsocks 协议）
   - [shadowsocks-4.1.6.zip](https://justmysocks3.net/members/dist/windows-shadowsocks-4.1.6.zip)
   - Windows 版 Shadowsocks-4.1.6 的 OBFS 插件：[obfs-local.zip](https://justmysocks3.net/members/dist/obfs-local.zip)（从存档中提取两个文件并将其放入与 Shadowsocks 相同的文件夹中）

### macOS：

1. **选项 1（推荐）**：**Jamjams**（支持 v2ray 和 shadowsocks 协议）
   - [Jamjams-0.1.8 安装程序](https://justmysocks3.net/members/dist/jamjams-0.1.8.dmg)

2. **选项 2**：**V2rayX**
   - [V2RayX.app](https://justmysocks3.net/members/dist/V2RayX.app.zip)

3. **选项 3**：**暗影袜**（ShadowsocksX-NG）
   - 适用于 OS X v10.12+：[shadowsocksx-ng.app.1.9.4.zip](https://justmysocks3.net/members/dist/osx-shadowsocksx-ng.app.1.9.4.zip)
   - OS X 旧版本：[ShadowsocksX-NG GitHub Releases](https://github.com/shadowsocks/ShadowsocksX-NG/releases)

### iOS：

- **Potatso**: [Potatso Lite](https://apps.apple.com/us/app/potatso-lite/id1239860606)

### 安卓：

- **Shadowsocks**: [shadowsocks-4.7.4.apk](https://justmysocks3.net/members/dist/com.github.shadowsocks-4.7.4.apk)


## 3 特别配置（Viber）

某些 C/S 客户端工具只支持 **ss** 类型的 VPN 服务，因此需要手动配置 **ss** 服务。以下是以 **Viber** 为例的配置步骤：

1. **唤出 Viber 代理配置窗口**  
   启动 Viber 后，若无法成功登录，请耐心等待 1～2 分钟，直至出现配置窗口。

2. **通过订阅获取 ss 服务配置**  
   通过订阅地址获取服务信息，其中编号 1 和 2 是 **ss** 服务，3、4、5 和 801 为 **v2ray** 服务（不容易被封）。

3. **填入 ss 服务信息到 Viber 的代理配置窗口**  
   将获取的 **ss** 服务信息填入 Viber 的代理配置窗口中。

<img width="703" alt="image" src="https://github.com/user-attachments/assets/83ff492d-78b3-4fa0-8949-00ee723e398a">


## 4 教你科学上网

更多科学上网的教程和资源请参考 [链接](https://lienjack.github.io/Blog/knowledge/learn/ssh.html)。

## 5 公司内网科学上网配置
为在公司内网环境中科学上网，您可以通过配置浏览器扩展 **SwitchyOmega** 来实现代理设置。以下是详细步骤：

1. **安装 SwitchyOmega 扩展**
   - 打开 Google Chrome 浏览器。
   - 点击右上角的“三个点”图标，选择“更多工具” -> “扩展程序”，打开扩展程序页面。
   - 在扩展程序页面的右上角开启“开发者模式”。
   - 下载 `SwitchyOmega.crx` 离线文件，将其拖放到扩展程序页面，然后在弹出的对话框中点击“添加扩展程序”。
   - 配置 SwitchyOmega 并将其添加到扩展程序快捷栏。

2. **配置 SwitchyOmega**
   - 左键点击 SwitchyOmega 扩展图标，在弹出的菜单中选择“选项”以打开配置页面。
   - 在配置页面左侧选择“新增情景模式”，在弹出的框中填写名称，并选择类型为“代理服务器”。
   - 选择刚才创建的情景模式，并根据下图配置代理服务器信息（点击右边的锁按钮填写账号和密码）：
     - **地址**：`192.168.0.1`
     - **端口**：`88`
     - **代理协议**：`HTTP`
     - **账号**：`XXX`
     - **密码**：`XXX`

3. **配置自动切换模式**
   - 在左侧菜单中选择默认的“auto switch”情景模式。
   - 在配置页面中按照以下步骤配置：
     - 在“导入规则列表”部分选择“添加列表”。
     - 选择规则列表格式为“AutoProxy”，在规则列表网址中填写 `*.openai.com`，然后点击“立即更新情景模式”。

4. **完成配置并测试**
   - 左键点击 SwitchyOmega 扩展图标，在弹出的菜单中选择“auto switch”。
   - 访问 Google 进行测试，确保配置生效。

