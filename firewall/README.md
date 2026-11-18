# Firewall

This project configures the `ufw` firewall on web-01 to block all incoming
traffic except TCP ports 22 (SSH), 80 (HTTP) and 443 (HTTPS).

## Files

| File | Description |
|------|-------------|
| `0-block_all_incoming_traffic_but` | ufw commands that deny all incoming traffic except ports 22, 80 and 443 |
