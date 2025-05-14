# ssh-config-pi

`~/.ssh/config`

```
Include "csb/config"

Host pi
    HostName 172.24.18.82
    User pi
    Port 2222
    RequestTTY force
```
