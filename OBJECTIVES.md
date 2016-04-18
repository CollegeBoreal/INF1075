1.0 Operation of IP Data Networks 5%
1.1 Recognize the purpose and functions of various network devices such as routers,
switches, bridges and hubs
1.2 Select the components required to meet a given network specification
1.3 Identify common applications and their impact on the network
1.4 Describe the purpose and basic operation of the protocols in the OSI and TCP/IP models
1.5 Predict the data flow between two hosts across a network
1.6 Identify the appropriate media, cables, ports, and connectors to connect Cisco network
devices to other network devices and hosts in a LAN

2.0 LAN Switching Technologies 20%
2.1 Determine the technology and media access control method for Ethernet networks
2.2 Identify basic switching concepts and the operation of Cisco switches
2.2.a Collision Domains
2.2.b Broadcast Domains
2.2.c Ways to switch
2.2.c (i) Store
2.2.c (ii) Forward
2.2.c (iii) Cut through
2.2.d CAM Table
2.3 Configure and verify initial switch configuration including remote access management
2.3.a hostname
2.3.b mgmt ip address
2.3.c ip default-gateway
2.3.d local user and password
2.3.e enable secret password
2.3.f console and VTY logins
2.3.g exec-timeout
2.3.h service password encryption
2.3.i copy run start
2.4 Verify network status and switch operation using basic utilities such as
2.4.a ping
2.4.b telnet
2.4.c SSH
2.5 Describe how VLANs create logically separate networks and the need for routing
between them
2.5.a Explain network segmentation and basic traffic management concepts
2.6 Configure and verify VLANs
2.7 Configure and verify trunking on Cisco switches
2.7.a dtp (topic)
2.7.b auto-negotiation
2.8 Identify enhanced switching technologies
2.8.a RSTP
2.8.b PVSTP
2.8.c Etherchannels
2.9 Configure and verify PVSTP operation
2.9.a Describe root bridge election
2.9.b Spanning tree mode

3.0 IP Addressing (IPv4/IPv6)  5%
3.1 Describe the operation and necessity of using private and public IP addresses for IPv4
addressing
3.2 Identify the appropriate IPv6 addressing scheme to satisfy addressing requirements in a
LAN/WAN environment
3.3 Identify the appropriate IPv4 addressing scheme using VLSM and summarization to
satisfy addressing requirements in a LAN/WAN environment
3.4 Describe the technological requirements for running IPv6 in conjunction with IPv4
3.4.a dual stack
3.5 Describe IPv6 addresses
3.5.a global unicast
3.5.b multicast
3.5.c link local
3.5.d unique local
3.5.e eui 64
3.5.f auto-configuration
4.0 IP Routing Technologies
4.1 Describe basic routing concepts
4.1.a packet forwarding
4.1.b router lookup process
4.1.c Process Switching/Fast Switching/CEF
4.2 Configure and verify utilizing the CLI to set basic Router configuration
4.2.a hostname
4.2.b local user and password
4.2.c enable secret password
4.2.d console & VTY logins
4.2.e exec-timeout
4.2.f service password encryption
4.2.g interface IP Address
4.2.g (i) loopback
4.2.h banner
4.2.i motd
4.2.j copy run start
4.3 Configure and verify operation status of a device interface
4.3.a Serial
4.3.b Ethernet
4.4 Verify router configuration and network connectivity using
4.4.a ping
4.4.a (i) extended
4.4.b traceroute
4.4.c telnet
4.4.d SSH
4.4.e sh cdp neighbors
4.5 Configure and verify routing configuration for a static or default route given specific
routing requirements
4.6 Differentiate methods of routing and routing protocols
4.6.a Static vs. dynamic
4.6.b Link state vs. distance vector
4.6.c next hop
4.6.d ip routing table
4.6.e Passive Interfaces (how they work) 
4.6.f Admin distance
4.6.g split horizon
4.6.h metric
4.7 Configure and verify OSPF
4.7.a Benefit of single area
4.7.b Configure OSPv2
4.7.c Configure OSPv3
4.7.d Router ID
4.7.e Passive Interface
4.7.f Discuss multi-area OSPF
4.7.g Understand LSA types and purpose
4.8 Configure and verify interVLAN routing (Router on a stick)
4.8.a sub interfaces
4.8.b upstream routing
4.8.c encapsulation
4.9 Configure SVI interfaces
4.10 Manage Cisco IOS Files
4.10.a Boot Preferences
4.10.b Cisco IOS Images (15)
4.10.c Licensing
4.10.c (i) Show license
4.10.c (ii) Change license
4.11 Configure and verify EIGRP (single AS)
4.11.a Feasible Distance/Feasible Successors/Administrative distance
4.11.b Feasibility condition
4.11.c Metric composition
4.11.d Router ID
4.11.e Auto summary
4.11.f Path Selection
4.11.g Load Balancing
4.11.g (i) Unequal
4.11.g (ii) Equal
5.2.c named
5.2.d numbered
5.2.e Log option
5.3 Configure and verify ACLs in a network environment
5.3.a named
5.3.b numbered
5.3.c Log option
5.4 Identify the basic operation of NAT
5.4.a purpose
5.4.b pool
5.4.c static
5.4.d 1 to 1
5.4.e overloading
5.4.f source addressing
5.4.g one way NAT
5.5 Configure and verify NAT for given network requirements
5.6 Configure and verify NTP as a client
5.7 Recognize High availability (FHRP)
5.7.a VRRP
5.7.b HSRP
5.7.c GLBP
5.8 Configure and verify syslog
5.8.a Utilize syslog output
5.9 Describe SNMP v2 and v3.

6.0 Network Device Security 10%
6.1 Configure and verify network device security features
6.1.a Device password security
6.1.b Enable secret vs. enable
6.1.c Transport
6.1.c.1 disable telnet
6.1.c.2 SSH
6.1.d VTYs
6.1.e physical security
6.1.f service password
6.1.g Describe external authentication methods
6.2 Configure and verify Switch Port Security
6.2.a Sticky MAC
6.2.b MAC address limitation
6.2.c static/dynamic
6.2.d violation modes
6.2.d (i) err disable
6.2.d (ii) shutdown
6.2.d (iii) protect restrict
6.2.e Shutdown unused ports
6.2.f err disable recovery
6.2.g Assign unused ports in unused VLANs
6.2.h Putting Native VLAN to other than VLAN 1
6.3 Configure and verify ACLs to filter network traffic
6.4 Configure and verify ACLs to limit telnet and SSH access to the router

7.0 Troubleshooting  20%
7.1 Troubleshoot and correct common problems associated with IP addressing and host
configurations
7.2 Troubleshoot and resolve VLAN problems
7.2.a Identify that VLANs are configured
7.2.b Verify port membership correct
7.2.c Correct IP address configured
7.3 Troubleshoot and resolve trunking problems on Cisco switches
7.3.a Verify correct trunk states
7.3.b Verify correct encapsulation configured
7.3.c Correct VLANs allowed
7.4 Troubleshoot and resolve ACL issues
7.4.a Verify statistics
7.4.b Verify permitted networks
7.4.c Verify direction
7.4.c (i) Interface
7.5 Troubleshoot and resolve Layer 1 problems
7.5.a Framing
7.5.b CRC
7.5.c Runts
7.5.d Giants
7.5.e Dropped packets
7.5.f Late collisions
7.5.g Input/output errors
7.6 Identify and correct common network problems
7.7 Troubleshoot and resolve spanning tree operation issues
7.7.a Verify root switch
7.7.b Verify priority
7.7.c Verify mode is correct
7.7.d Verify port states
7.8 Troubleshoot and resolve routing issues
7.8.a Verify routing is enabled (sh ip protocols)
7.8.b Verify routing table is correct
7.8.c Verify correct path selection
7.9 Troubleshoot and resolve OSPF problems
7.9.a Verify neighbor adjacencies
7.9.b Verify hello and dead timers
7.9.c Verify OSPF area
7.9.d Verify interface MTU
7.9.e Verify network types
7.9.f Verify neighbor states
7.9.g Review OSPF topology table
7.10 Troubleshoot and resolve EIGRP problems
7.10.a Verify neighbor adjacencies
7.10.b Verify AS number
7.10.c Verify load balancing
7.10.d Split horizon
7.11 Troubleshoot and resolve interVLAN routing problems
7.11.a Verify connectivity
7.11.b Verify encapsulation
7.11.c Verify subnet
7.11.d Verify native VLAN
7.11.e Port mode trunk status
7.12 Troubleshoot and resolve WAN implementation issues
7.12.a Serial interfaces
7.12.b Frame relay
7.12.c PPP
7.13 Monitor NetFlow statistics
7.14 TS EtherChannel problems

8.0 WAN Technologies 10%
8.1 Identify different WAN Technologies
8.1.a Metro ethernet
8.1.b VSAT
8.1.c Cellular 3g/4g
8.1.d MPLS
8.1.e T1/E1
8.1.f ISDN
8.1.g DSL
8.1.h Frame relay
8.1.i Cable
8.1.j VPN
8.2 Configure and verify a basic WAN serial connection
8.3 Configure and verify a PPP connection between Cisco routers
8.4 Configure and verify frame relay on Cisco routers
8.5 Implement and troubleshoot PPPoE
