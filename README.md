# haproxy

add repo:
```bash
sudo apt install --no-install-recommends software-properties-common
sudo add-apt-repository ppa:vbernat/haproxy-2.4
```

install haproxy:
```bash
sudo apt install haproxy=2.4.\*
```

check config file:
```bash
sudo haproxy -f /etc/haproxy/haproxy.cfg -c
```

restart haproxy:
```bash
sudo systemctl restart haproxy
```

check status:
```bash
sudo systemctl status haproxy
```
