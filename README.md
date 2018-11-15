# dpdk kni 多进程多队列

## 配置文件如下所示
```
[dpdk]
core_list = 2
numa_on = 0
channel = 4
promiscuous = 1
ctrl_core = 3
port_list = 0,1

[port0]
name = eth1
solt = 0000:02:06.0
#pcap = /tmp/kni_eth1.pcap

[port1]
name = eth2
solt = 0000:02:02.0
#pcap = /tmp/kni_eth2.pcap
```

***【注】<br>***
***1、dpdk版本是18.05.1<br>***
