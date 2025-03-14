# ospfv3

```bash
en
conf t

ipv6 unicast-routing 

ipv6 router ospf 10
router-id 4.4.4.4
ex


int gig0/2
ipv6 address 2031::2/64
no sh
ipv6 ospf 10 area 0
ex


int gig0/3/0
ipv6 address 2042::2/64
no sh
ipv6 ospf 10 area 0
ex

int gig0/0
ipv6 address 2021::2/64
no sh
ipv6 ospf 10 area 0
ex


int gig0/1
ipv6 address 2004::1/64
no sh
ipv6 ospf 10 area 0
ex








```
