Construire une route entre deux interfaces DHCP et Fixe

## Autre solution DHCP et NAT
http://www.cisco.com/c/en/us/support/docs/broadband-cable/cable-modems/19268-router-behind-cm-19268.html

##

! En Mode privilege
conf t

! Cheer un pool DHCP Interne
ip dhcp excluded-address 172.16.1.1 172.16.1.30
!
ip dhcp pool DHCPinterne
network 172.16.1.0 255.255.0.0
default-router 172.16.1.1
dns-server 10.10.99.2 10.10.99.3
!
interface FastEthernet0/0
description Vers le FAI (le WAN)
ip address dhcp
ip nat outside
no shutdown
!
interface FastEthernet0/1
description Vers le LAN
ip address 172.16.1.1 255.255.0.0
ip nat inside
no shutdown
!
ip nat inside source list 1 interface FastEthernet0/0 overload
!
access-list 1 permit 172.16.1.0 0.0.255.255



