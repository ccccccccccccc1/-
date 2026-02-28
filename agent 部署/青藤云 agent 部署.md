Linux 系统安装
1. 确保以 root 权限登录系统。

2. 运行以下命令进行安装：

curl -s -1 -L -k 'https://143.64.38.34:8443/client/com-qt-os-agent/service-agent2/agent/v2/host_agent/linux/install_script?arch='$(uname -m)'&config_hash=9962b72cd979f6e53182a7f2a5a4fafbdb622bc5a36f55f668b1d1f61857af2b&tenant_id=627acf9b5f96e8b0decc&token=e%3Ad5op54fohfsvouivdjg0' | bash



