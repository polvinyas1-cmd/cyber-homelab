# Wazuh deployment

Wazuh is used as the central SIEM/XDR platform in this homelab.

## Current setup

- Wazuh manager installed on Ubuntu server
- Debian node connected as agent
- Log collection enabled
- Basic intrusion detection active
- SSH monitoring enabled

## Screenshots

### Dashboard
![dashboard](01-wazuh-dashboard.jpg)

### Agent installation
![agent](02-wazuh-install.jpg)
![agent](03-wazuh-install-too.jpg)
![agent](04-comand-4-agent.jpg)
![agent](05-agent-enable.jpg)

### Active agents
![agents](06-show-agent-on-dashboard.jpg)

### Example alert
![alert](07-wazuh-example-alert.png)
