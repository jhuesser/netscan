# netscan
A simple commandline netscan in bash.

#Features
This commandline tool scans a network and list all hosts with hostname and IP.

#Usage
````
./ipscan <subnet_host_part>
```

##Example
````
./ipscan 192.168.1
```
###Output

```
192.168.1.1 UP Server: 192.168.1.1 Address: 192.168.1.1#53 1.1.168.192.in-addr.arpa name = fancyrouter.home.
192.168.1.2 UP Server: 192.168.1.1 Address: 192.168.1.1#53 2.1.168.192.in-addr.arpa name = fancyserver.home.
...
```
