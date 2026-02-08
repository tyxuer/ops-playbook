# Ansible 自动化运维（Demo）

目标：通过 playbook 将一台新机器配置为“可运行服务的标准业务机”：
- 安装基础工具
- 安装 Docker/Compose
- （可选）部署 demo 服务
- 安装 Zabbix Agent

## 使用方式
1) 修改 inventory.example.ini 为你的目标主机信息
2) 执行 playbook（示例）：
- base.yml
- docker.yml
- zabbix-agent.yml

## 截图/输出
- 执行成功截图放在：00-Portfolio/Screenshots/
