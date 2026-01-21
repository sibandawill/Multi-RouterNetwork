# IP Addressing Scheme
-LAN IP Configuration 
Central Router: 192.168.0.0/24 G0/0
Branch 1 Router: 192.168.1.0/24 G0/0
Branch 2 Router: 192.168.2.0/24 G0/0

-WAN Links
Central Router 10.0.0.1 to Branch 1 Router 10.0.0.2   (10.0.0.0/30 network)
Central Router 10.0.0.5 to Branch 2 Router 10.0.0.6   (10.0.0.4/30 network)


## Router Configuration (Cisco IOS CLI)


## Switch Configuration (Cisco IOS CLI)
None

## PC Configuration
PC1 (Connects to Central Router on SW0 )
Default Gateway: 192.168.0.1
IP Address: DHCP enabled
PC2 (Connects to Branch 2 Router on SW1)
Default Gateway: 192.168.2.1
IP Address: DHCP enabled
PC3 (Connects to Branch 1 Router on SW2)
Default Gateway: 192.168.1.1
IP Address: DHCP enabled
