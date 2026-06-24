对，自用推荐这样配：VLESS + TCP + Reality。不需要域名，不需要额外证书，适合你
这台只有 IP 的服务器。

  入站配置
  在 3x-ui 里点 Inbounds -> Add Inbound：

  备注/Remark: vless-reality
  协议/Protocol: VLESS
  监听 IP/Listen IP: 留空 或 0.0.0.0
  端口/Port: 443
  传输/Network: TCP
  安全/Security: Reality

  Reality 里面填：

  Dest: www.microsoft.com:443
  Server Names: www.microsoft.com
  Short IDs: 点生成，或填 8-16 位十六进制，比如 a1b2c3d4e5f6
  SpiderX: /

  密钥：

  Private Key / Public Key: 点面板里的 Generate / 生成

  其他：

  Flow: xtls-rprx-vision
  Sniffing: 开启

  注意：如果 443 被占用，就改成 8443 或 2083。不要用 2053，那是面板端口。

  客户端配置
  在这个入站下面添加 Client：

  Email/备注: my-phone 或 my-client
  UUID: 点生成
  Flow: xtls-rprx-vision
  Limit IP: 0
  Total GB: 0
  Expiry Time: 不设置 或 0
  Enable: 开启

  保存后，在入站列表里点二维码/复制链接，把 vless://... 导入客户端即可。

  客户端里最终应该看到类似：

  协议: VLESS
  地址: 66.154.103.150
  端口: 443
  UUID: 面板生成的 UUID
  传输: TCP
  安全: Reality
  Flow: xtls-rprx-vision
  SNI: www.microsoft.com
  Public Key: 面板 Reality 生成的 public key
  Short ID: 你填/生成的 short id

  分组、订阅、流量套餐这些你自用可以先不管。


› 你觉得我用订阅链接？还是节点链接？
• 你只有一个节点自用，建议先用节点链接
