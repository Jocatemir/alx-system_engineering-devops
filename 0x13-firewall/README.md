# 0x13. Firewall
An introductory project on:
- what is a firewall

## File Descriptions
### Mandatory
[0-block_all_incoming_traffic_but](./0-block_all_incoming_traffic_but) - installs the `ufw` firewall and setup a few rules on `web-01`
Requirements:
- Configure `ufw` so that it blocks all incoming traffic, except the following TCP ports:
	- `22` (SSH)
	- `443` (HTTPS SSL)
	- `80` (HTTP)

### Advanced
[100-port_forwarding](./100-port_forwarding) - a copy of the modified `ufw` configuration file
Requirements:
- Configure `web-01` so that its firewall redirects port `8080/TCP` to port `80/TCP`
