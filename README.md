<h1 align="center">Network Protocols</h1>

| Sr/ No. | Protocol | Full form | Default Port | Transport layer | Description |
|---|---|---|---|---|---|
| 1 | HTTP | HyperText Transfer Protocol | 80 | TCP | Transfers web pages and APIs over the web. |
| 2 | HTTPS | HyperText Transfer Protocol Secure | 443 | TCP | Secure web communication using TLS/SSL. |
| 3 | FTP | File Transfer Protocol | 21 | TCP | Transfers files between client and server. |
| 4 | FTPS | File Transfer Protocol Secure | 990 | TCP | FTP secured with TLS/SSL. |
| 5 | SFTP | SSH File Transfer Protocol | 22 | TCP | Secure file transfer over SSH. |
| 6 | SSH | Secure Shell | 22 | TCP | Secure remote login and command execution. |
| 7 | Telnet | Teletype Network | 23 | TCP | Remote terminal access without encryption. |
| 8 | SMTP | Simple Mail Transfer Protocol | 25 | TCP | Sends email between mail servers. |
| 9 | SMTPS | SMTP Secure | 465 | TCP | Sends email securely over TLS/SSL. |
| 10 | Submission | Message Submission (SMTP) | 587 | TCP | Standard authenticated email submission. |
| 11 | POP3 | Post Office Protocol version 3 | 110 | TCP | Retrieves emails from a mail server. |
| 12 | POP3S | POP3 Secure | 995 | TCP | Secure retrieval of email messages. |
| 13 | IMAP | Internet Message Access Protocol | 143 | TCP | Accesses and manages emails on server. |
| 14 | IMAPS | IMAP Secure | 993 | TCP | Secure email access and synchronization. |
| 15 | DNS | Domain Name System | 53 | UDP/TCP | Resolves domain names to IP addresses. |
| 16 | DHCP | Dynamic Host Configuration Protocol | 67/68 | UDP | Assigns IP addresses and network settings. |
| 17 | TFTP | Trivial File Transfer Protocol | 69 | UDP | Lightweight file transfer, often for booting. |
| 18 | SNMP | Simple Network Management Protocol | 161/162 | UDP | Monitors and manages network devices. |
| 19 | NTP | Network Time Protocol | 123 | UDP | Synchronizes clocks over networks. |
| 20 | LDAP | Lightweight Directory Access Protocol | 389 | TCP/UDP | Accesses directory services and identities. |
| 21 | LDAPS | LDAP over SSL/TLS | 636 | TCP | Secure LDAP directory communication. |
| 22 | RDP | Remote Desktop Protocol | 3389 | TCP/UDP | Remote graphical desktop access. |
| 23 | SMB | Server Message Block | 445 | TCP | File and printer sharing on networks. |
| 24 | CIFS | Common Internet File System | 445 | TCP | SMB-based network file sharing protocol. |
| 25 | NFS | Network File System | 2049 | TCP/UDP | Shares files between Unix/Linux systems. |
| 26 | SIP | Session Initiation Protocol | 5060 | UDP/TCP | Initiates and manages VoIP sessions. |
| 27 | SIPS | SIP Secure | 5061 | TCP | Secure SIP signaling over TLS. |
| 28 | RTP | Real-time Transport Protocol | Dynamic | UDP | Carries real-time audio/video streams. |
| 29 | RTSP | Real Time Streaming Protocol | 554 | TCP/UDP | Controls streaming media sessions. |
| 30 | BGP | Border Gateway Protocol | 179 | TCP | Exchanges routing information between ASes. |
| 31 | OSPF | Open Shortest Path First | 89 | IP | Link-state interior gateway routing protocol. |
| 32 | RIP | Routing Information Protocol | 520 | UDP | Distance-vector interior gateway routing protocol. |
| 33 | IS-IS | Intermediate System to Intermediate System | N/A | L2 | Link-state routing protocol used by service providers. |
| 34 | EIGRP | Enhanced Interior Gateway Routing Protocol | 88 | IP | Cisco advanced distance-vector routing protocol. |
| 35 | ICMP | Internet Control Message Protocol | N/A | IP | Carries error reporting and diagnostic messages. |
| 36 | IGMP | Internet Group Management Protocol | N/A | IP | Manages IPv4 multicast group membership. |
| 37 | ARP | Address Resolution Protocol | N/A | L2 | Maps IPv4 addresses to MAC addresses on LANs. |
| 38 | RARP | Reverse Address Resolution Protocol | N/A | L2 | Maps MAC addresses back to IPv4 addresses. |
| 39 | VRRP | Virtual Router Redundancy Protocol | 112 | IP | Provides gateway redundancy using virtual routers. |
| 40 | HSRP | Hot Standby Router Protocol | 1985 | UDP | Cisco first-hop redundancy protocol. |
| 41 | GRE | Generic Routing Encapsulation | N/A | IP | Tunnels network layer protocols over IP. |
| 42 | IPsec AH | IPsec Authentication Header | N/A | IP | Provides packet authentication and integrity. |
| 43 | IPsec ESP | IPsec Encapsulating Security Payload | N/A | IP | Provides confidentiality, integrity, and authentication. |
| 44 | IKE | Internet Key Exchange | 500/4500 | UDP | Negotiates security associations for IPsec. |
| 45 | L2TP | Layer 2 Tunneling Protocol | 1701 | UDP | Tunnels PPP sessions over IP networks. |
| 46 | PPTP | Point-to-Point Tunneling Protocol | 1723 | TCP | Legacy VPN tunneling protocol. |
| 47 | OpenVPN | OpenVPN Protocol | 1194 | UDP/TCP | VPN protocol using TLS for secure tunnels. |
| 48 | WireGuard | WireGuard VPN Protocol | 51820 | UDP | Modern lightweight VPN tunneling protocol. |
| 49 | STUN | Session Traversal Utilities for NAT | 3478 | UDP/TCP | Helps endpoints discover NAT mappings. |
| 50 | TURN | Traversal Using Relays around NAT | 3478/5349 | UDP/TCP/TLS | Relays media traffic when peer-to-peer fails. |
| 51 | XMPP | Extensible Messaging and Presence Protocol | 5222/5269 | TCP | Open standard for messaging and presence. |
| 52 | MQTT | Message Queuing Telemetry Transport | 1883/8883 | TCP | Lightweight publish-subscribe protocol for IoT. |
| 53 | AMQP | Advanced Message Queuing Protocol | 5672/5671 | TCP | Message-oriented middleware protocol. |
| 54 | CoAP | Constrained Application Protocol | 5683/5684 | UDP | REST-like protocol for constrained IoT devices. |
| 55 | WebSocket | WebSocket Protocol | 80/443 | TCP | Full-duplex communication over a single socket. |
| 56 | gRPC | gRPC Remote Procedure Calls | 443 (common) | TCP/HTTP2 | High-performance RPC framework over HTTP/2. |
| 57 | NNTP | Network News Transfer Protocol | 119/563 | TCP | Distributes, queries, and retrieves Usenet articles. |
| 58 | IRC | Internet Relay Chat | 194/6667/6697 | TCP | Real-time text messaging and chat protocol. |
| 59 | Syslog | System Logging Protocol | 514/6514 | UDP/TCP/TLS | Standard for transmitting log messages. |
| 60 | RADIUS | Remote Authentication Dial-In User Service | 1812/1813 | UDP | AAA protocol for network access control. |
| 61 | TACACS+ | Terminal Access Controller Access-Control System Plus | 49 | TCP | Centralized AAA protocol for device administration. |
| 62 | Kerberos | Kerberos Authentication Protocol | 88 | UDP/TCP | Ticket-based mutual authentication protocol. |
| 63 | NTS | Network Time Security | 4460 | TCP | Adds authentication to NTP time sync. |
| 64 | mDNS | Multicast DNS | 5353 | UDP | Local-link hostname resolution without DNS server. |
| 65 | LLMNR | Link-Local Multicast Name Resolution | 5355 | UDP/TCP | Name resolution on local networks. |
| 66 | SSDP | Simple Service Discovery Protocol | 1900 | UDP | Discovers UPnP devices on local networks. |
| 67 | UPnP | Universal Plug and Play | 1900/5000 | UDP/TCP | Automatic device discovery and control. |
| 68 | NETCONF | Network Configuration Protocol | 830 | TCP/SSH | Manages network device configuration. |
| 69 | RESTCONF | RESTful Network Configuration Protocol | 443 | TCP/HTTPS | REST API for network configuration and state. |
| 70 | BFD | Bidirectional Forwarding Detection | 3784/3785 | UDP | Fast failure detection for forwarding paths. |
| 71 | LDP | Label Distribution Protocol | 646 | TCP/UDP | Distributes MPLS labels between routers. |
| 72 | PIM | Protocol Independent Multicast | 103 | IP | Builds multicast routing trees. |
| 73 | GTP-C | GPRS Tunneling Protocol Control Plane | 2123 | UDP | Mobile core signaling for session control. |
| 74 | GTP-U | GPRS Tunneling Protocol User Plane | 2152 | UDP | Carries user traffic in mobile core networks. |
| 75 | SMPP | Short Message Peer-to-Peer | 2775 | TCP | Exchanges SMS messages between systems. |
| 76 | Diameter | Diameter Protocol | 3868 | TCP/SCTP | AAA protocol successor to RADIUS. |
| 77 | SCTP | Stream Control Transmission Protocol | 9899 (assigned) | IP | Reliable message-oriented transport protocol. |
| 78 | QUIC | Quick UDP Internet Connections | 443 | UDP | Secure multiplexed transport used by HTTP/3. |
| 79 | HTTP/3 | HyperText Transfer Protocol v3 | 443 | UDP/QUIC | Modern web protocol over QUIC transport. |
| 80 | SIP-TLS | SIP over TLS | 5061 | TCP | Encrypted SIP signaling for VoIP. |
| 81 | H.323 | ITU H.323 Multimedia Protocol Suite | 1720 | TCP | Voice and video call signaling suite. |
| 82 | MGCP | Media Gateway Control Protocol | 2427/2727 | UDP | Controls telephony media gateways. |
| 83 | RTP-MIDI | RTP MIDI | 5004 | UDP | Real-time MIDI data transport. |
| 84 | AFP | Apple Filing Protocol | 548 | TCP | File sharing protocol for Apple devices. |
| 85 | SMB Direct | SMB over RDMA | 5445 | TCP | High-performance SMB transport over RDMA. |
| 86 | iSCSI | Internet Small Computer Systems Interface | 3260 | TCP | Encapsulates SCSI storage commands over IP. |
| 87 | FCoE | Fibre Channel over Ethernet | N/A | L2 | Encapsulates Fibre Channel frames in Ethernet. |
| 88 | NBD | Network Block Device | 10809 | TCP | Exposes block devices over a network. |
| 89 | Rsync | Rsync Remote Sync Protocol | 873 | TCP | Efficient differential file synchronization. |
| 90 | SCP | Secure Copy Protocol | 22 | TCP | Secure file transfer using SSH transport. |
| 91 | Modbus TCP | Modbus over TCP/IP | 502 | TCP | Industrial control and automation protocol. |
| 92 | DNP3 | Distributed Network Protocol 3 | 20000 | TCP/UDP | SCADA communication protocol for utilities. |
| 93 | OPC UA | Open Platform Communications Unified Architecture | 4840 | TCP | Industrial interoperability and telemetry protocol. |
| 94 | BACnet/IP | Building Automation and Control Network | 47808 | UDP | Building automation communication protocol. |
| 95 | EtherNet/IP | Ethernet Industrial Protocol | 44818 | TCP/UDP | Industrial automation protocol over Ethernet. |
| 96 | PROFINET | Process Field Net | 34962/34963/34964 | UDP/TCP | Industrial Ethernet for real-time automation. |
| 97 | KNXnet/IP | KNX over IP | 3671 | UDP | Building automation control protocol. |
| 98 | IEC 60870-5-104 | Telecontrol Protocol 104 | 2404 | TCP | Power system telecontrol over TCP/IP. |
| 99 | IEC 61850 MMS | Manufacturing Message Specification (IEC 61850) | 102 | TCP | Substation automation communication protocol. |
| 100 | S7comm | Siemens S7 Communication Protocol | 102 | TCP | PLC programming and diagnostics protocol. |
