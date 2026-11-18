# Web stack debugging #2

Running software as a user other than root, and running nginx as the
`nginx` user on port 8080.

## Files

| File | Description |
|------|-------------|
| `0-iamsomeoneelse` | Runs `whoami` as the user passed as an argument |
| `1-run_nginx_as_nginx` | Configures nginx to run as the `nginx` user and listen on port 8080 |
