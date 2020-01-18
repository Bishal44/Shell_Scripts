# Shell_Scripts
shell scripts to automate small daily activity

##find service by port

[source](/check_port/check_port.sh)

with this method you can find which process is running on specific port

paste source into your ```.bashrc``` or ```.bash_alias```

then run the below command

```bash
check 5000
```

```bash
COMMAND   PID USER   FD   TYPE             DEVICE SIZE/OFF NODE NAME
Python    95429  Dell  217u  IPv6 0xe5tab40cfb482b67      0t0  TCP *:http-alt (LISTEN)
```
