# Firewall

Configures the ufw firewall on web-01.

## Tasks

### 0. Block all incoming traffic but

0-block_all_incoming_traffic_but installs ufw, blocks all incoming traffic, and allows only TCP ports 22 (SSH), 80 (HTTP) and 443 (HTTPS).
