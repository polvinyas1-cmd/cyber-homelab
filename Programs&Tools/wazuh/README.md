# Wazuh deployment

Wazuh is used as the central SIEM/XDR platform in this homelab.

## Current setup

- Wazuh manager installed on Ubuntu server
- Debian node connected as agent
- Log collection enabled
- Basic intrusion detection active
- SSH monitoring enabled

## Skills learned
- Linux administration
- SIEM deployment
- Network monitoring
- Agent management
- SSH remote administration
- Log analysis
- Security event investigation

## Additional tools
Extra security and networking tools used in the homelab enviornment.
- Fail2Ban for SSH brute-force protection
- Nmap for network scanning and host discovery

## Screenshots

### Dashboard
![dashboard](01-wazuh-dashboard.jpg)

### Agent installation
![agent](02-wazuh-install-edit1.jpg)
![agent](03-wazuh-install-too-edit.jpg)
![agent](04-comand-4-agent.jpg)
![agent](05-agent-enable.jpg)

### Active agents
![agents](06-show-agent-on-dashboard.jpg)

### Example alert
![alert](07-wazuh-example-alert.png)

### Fail2Ban and Nmap tools as an extra
![alert](09-fail2ban-installed.jpg)
![alert](08-Nmap-example.jpg)
