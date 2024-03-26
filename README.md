# Ansible Configuration Playbooks

This repository contains Ansible playbooks for configuring certain security settings on Linux systems. The playbooks are designed to be run on a Debian and RedHat based distro.

## Prerequisites

- SSH access to the target Linux server(s).


### Run All Playbooks

You can run all playbooks together using the following command:

```bash
./run -l <host> -t all
```
<br>
Or you can run the playbooks individually by using these tags:
<br>

### Linux Server:
- motd <br>
- ssh <br>
- banner <br>
- lynis <br>
- fail2ban <br>
<br>
