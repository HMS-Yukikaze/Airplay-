# Airplay-
1.Airplay 接受端（windows）
  1.1 基于mdns的设备发现
      1.1.1 安装Bonjour SDk用作设备发现协议处理。（Bonjour SDk for win）
      1.1.2 注册服务：_airplay._tcp(视频),_raop._tcp(音频) 相关函数:DNSServiceRegister() DNSServiceUpdateRecord()
