# Ubuntu stuff

## VPN

Bei FW-Problemen mal den Status folgender Dienste ansehen:

```bash
systemctl --user status firewall-identity-agent.service
systemctl status oc-daemon.service
```

### vim
#### Settings
```
set ts=2
set sw=2
set ai
set si
syntax on
colo delek
set bg=dark
```