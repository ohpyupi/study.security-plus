# Network Basics and Terminologiges
### OSI Model
* Layer 7: Application
* Layer 6: Presentation
* Layer 5: Session
* Layer 4: Transport
  * TCP/UDP (TCP/IP Transport Protocol)
* Layer 3: Network
  * IP Address
* Layer 2: Data Link
  * MAC Address
* Layer 1: Physical

### Broadcast Domain
* A logical division of a computer network
* Any computer connected to a switch is in the same broadcast domain.

### ACL (Access Control List)
* Top-down - A first rule to be executed. If the first rule does not match, a subsequent rule to be executed in the top-down order
* Last rule is all-deny - If no rule matched, the request to be rejected.

### IP Addresses
* Calculating subnets and hosts
  * Class A 10.1.1.0/24
    * network bits = 8
    * subnet bits = 24 - 8 = 16
    * host bits = 32 - 24 = 8
    * number of subnets = 2 ^ 16 = 65,536
    * number of hosts per subnet = 2^8 - 2 = 254
  * Class B 172.15.55.0/21
    * network bits = 16
    * subnet bits = 21 - 16 = 5
    * host bits = 32 - 21 = 11
    * number of subnets = 2^5 = 32
    * number of hosts per subnet = 2^11 - 2 = 2046
  * Class C 192.168.11.0/26
    * network bits = 24
    * subnet bits = 26 - 24 = 2
    * host bits = 32 - 26 = 8
    * number of subnets = 2^2 = 4
    * number of hosts per subnet = 2^6 - 2 =  62

### Load Balancer
* Algorithms
  * Round Robin - Distribute requests in a circular manner.
  * Weighted Round Robin
    * Distributes requests in a way that a server with higher weight receives more requests.
    * Each consecutive is handled in a rotational fasion, but servers with higher specs are designated to process more workload
  * Random - Distribute requests randomly
  * Least Connection - Distrubte requests to the least busiest server.
  * Session affinity - Pass requests consistently from a given client to the same server
* Active-active - Both load balancers are active
* Active-passive - Only one load balancer is active while another is on standby mode.
* Distributive Allocation

### Virtual IP Address
* An IP address that does not correspond to any actual physical network interface

### NIC (Network Interface Card)
* Allow a system communicate on a network

### Switch (Layer 2)
* All traffic copied to the port 24 - normally used to for monitoring
* Typically includes a flood guard to protect against MAC flood attacks
* Switching loop or bridge loop
  * Occurs when there is more than one Layer 2 path between two endpoints
  * Can be protected via STP (Spanning Tree Protocols) and RSTP (Rapid STP)  protocols
* Port mirroring
  * Allows an admin to inspect traffic passing through a network switch

### VLAN (Virtual Local Lan)
* Improves network throughput

### SDN (Software-degined Network)
* A technology designed to simplify network infrastructure management
* Provides scalability

### Network Protocols
* SSH/SCP
  * TCP port 22
* RDP (Remote Desktop Protocol)
  * TCP port 3389
* NTP (Network Time Protocol)
  * UDP port 123
* DNS (Domain Name System)
  * Queries on UDP port 53
  * DNSSEC
* RTP (Real-time Trasnport Protocol)
  * Delivers audio and video over IP networks
  * Used in communication and entertainment systems that involve streaming media such as telephony, video teleconference
  * SRTP
* TFTP (Trivial FTP)
  * UDP port 59
  * Store files without authentication
* FTP (File Transfer Protocol)
  * TCP port 21
  * SFTP and FTPS
* Telnet
  * TCP port 23
  * Gives admins a remote command prompt
  * Transmits message in the clear-text
* POP3
  * TCP port 110
  * POP3S (POP3 over SSL/TLS)
    * TCP port 995
* IMAP
  * An Internet standard protocol used by email clients to retrieve email messages from a mail server over a TCP/IP connection
  * TCP port 143
  * IMAPS (IMAP over SSL)
    * TCP port 993
* SNMP (Simple Network Management Protocol)
  * Allows devices to communicate even if the devices are different hardware and run different software
  * TCP port 161
  * In ealier versions, traffic was sent all in clear text, but from v3, all data sent is encrypted
* LDAP (Lightweight Directory Access Protocol)
  * TCP port 389
* LDAPS (LDAP Secure)
  * TCP port 636
  * Uses TLS alongside LDAP to mitigate the risk of an attacker gathering network resources information
* DHCP (Dynamic Host Configuration Protocol)
  * To obtain a valid TCP/IP configuration, `ifconfig /renew`
* ICMP (Internet Control Message Protocol)
  * Used by network devices to dianose network communication issues
  * Used to determine if or not data is reaching its inended destination in a timely manner
  
### NAT (Network Address Translation)
* Used to hide the internal IP addresses by modifying IP address information in IP packet headers while in trasit across a traffic routing device
* Alleviates the problem of depleting IPv4 address space by allowing multiple hosts on the same private LAN to share a single public IP address

### Router
* A device designed to filter and transfer IP packets between dissimilar types of computer networks

### Industry-standard Frameworks
* Regulatory frameworks
  * SOX
    * Designed to oversee the financial reporting landscape for finance professionals
  * HIPAA
* Non-regulatory frameowkrs
  * ITIL (IT Infrastructure Library)
    * Describes a framework of best practices for delivering IT services
  * COBIT (Control Objectives for Information and Related Technology)
    * Designed to be a supportive tool for managers and allows brining the crucial gap between technical issues, business risks, and control requirements
    
### X.500
A series of computer networking standards used for implemeting directory services

### Terms.
* Extranet
  * A type of private network that allows partial access to trusted third parties
* Intranet
  * A type of privae network for a corporation or organization accessible only to the employees or authorized members
* Tap
  * A monitoring port on a network device
