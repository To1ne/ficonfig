ficonfig
========
ifconfig beautified

Usage
-----
Run `ficonfig` just like you would run `[ifconfig](http://linux.die.net/man/8/ifconfig)`.

About
-----
`ficonfig` converts this:

    lo0: flags=8049<UP,LOOPBACK,RUNNING,MULTICAST> mtu 16384
    	inet6 ::1 prefixlen 128
    	inet6 fe80::1%lo0 prefixlen 64 scopeid 0x1
    	inet 127.0.0.1 netmask 0xff000000
    gif0: flags=8010<POINTOPOINT,MULTICAST> mtu 1280
    stf0: flags=0<> mtu 1280
    en0: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
    	ether 00:23:df:9f:b7:02
    	media: autoselect
    	status: inactive
    en1: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
    	ether 00:24:36:b0:b7:4f
    	inet6 fe80::224:36ff:feb0:b74f%en1 prefixlen 64 scopeid 0x5
    	inet 192.168.2.101 netmask 0xffffff00 broadcast 192.168.2.255
    	inet6 2002:d576:1d5a:1234:224:36ff:feb0:b74f prefixlen 64 autoconf
    	media: autoselect
    	status: active
    fw0: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 4078
    	lladdr 00:23:df:ff:fe:9f:b7:02
    	media: autoselect <full-duplex>
    	status: inactive
    vmnet8: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
    	ether 00:50:56:c0:00:08
    	inet 192.168.207.1 netmask 0xffffff00 broadcast 192.168.207.255
    vmnet1: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
    	ether 00:50:56:c0:00:01
    	inet 192.168.58.1 netmask 0xffffff00 broadcast 192.168.58.255

to this:
    TODO

How
---
`ficonfig` is just a simple Ruby scripts that runs `ifconfig` and
reformats its output.
