tayra.com
=========

Comercio Eletrônico com Magento

    cd ~
    alias wget='curl -O '
    sudo chmod a+rw /private/etc/hosts
    sudo echo "127.0.0.1       tayra.com " >>  /etc/hosts
    ping -c 3 tayra.com

PING tayra.com (127.0.0.1): 56 data bytes
64 bytes from 127.0.0.1: icmp_seq=0 ttl=64 time=0.069 ms
64 bytes from 127.0.0.1: icmp_seq=1 ttl=64 time=0.043 ms
64 bytes from 127.0.0.1: icmp_seq=2 ttl=64 time=0.107 ms

--- tayra.com ping statistics ---
3 packets transmitted, 3 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 0.043/0.073/0.107/0.026 ms

    sudo chmod a+rw  /Library/WebServer/Documents/
    sudo chmod a+rw  /Library/WebServer/Documents/*
    git clone https://github.com/joao-parana/tayra.com.git

Cloning into 'tayra.com'...
remote: Counting objects: 4, done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 0), reused 0 (delta 0)
Unpacking objects: 100% (4/4), done.

