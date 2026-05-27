# SubnettingLab2
These lab represents subnets and mask addresses of the same CIDR and how it pings with sh ARP and clear ARP
These Topology is the a subnetting lab;

It teaches how to ensure your IP and Mask of both subnets can send packets to each other;
an IP of 10.1.255.1 /17 gives a subnet of 255.255.128.0; 
R2 IP of 10.1.128.2 /17 gives a subnet of 255.255.128.0;

Both routers would receive packets, both routers can ping each other

sh arp and clear arp, both shows the packets ping in each router being delivered. 

Each ping is cleared with clear ARP, after the ping command is initiated,
each ping, moves packets through both routers, as shown with sh ARP;

for a network address, an IP 10.1.128.2 / cidr 17 = 255(8bits).255(8bits).128(1bit).zero; = 17;


