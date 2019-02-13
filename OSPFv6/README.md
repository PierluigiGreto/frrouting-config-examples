# OSPFv2
You need obviously for each peer the ipv6 address configured and they need to ping at lest in one area. As router-id it seems that an ipv6 format cannot be used.
If you have just two peer you need to specify on the router interface:
```
ip ospf network point-to-point
```
States by examples: [link](https://www.computernetworkingnotes.com/ccna-study-guide/ospf-neighbor-states-explained-with-example.html).  
In fedora you need to stop firewalld (or add a rule for ospf).
To exchange a route the interface need to be up and it has to have assigned the one ip in the network.
