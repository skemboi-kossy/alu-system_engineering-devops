# Load balancer

Adding redundancy to the web stack with a second web server and an HAProxy load balancer.

| File | Description |
| --- | --- |
| `0-custom_http_response_header` | Configures Nginx with the X-Served-By header set to the server's hostname |
| `1-install_load_balancer` | Installs HAProxy on lb-01, round-robin between web-01 and web-02 |
