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
  * Weighted Round Robin - Distribute requests in a way that a server with higher weight receives more requests.
  * Random - Distribute requests randomly
  * Least Connection - Distrubte requests to the least busiest server.
* Active-active - Both load balancers are active
* Active-passive - Only one load balancer is active while another is on standby mode.

### NIC (Network Interface Card)
* Allow a system communicate on a network

### Switch (Layer 2)
* All traffic copied to the port 24 - normally used to for monitoring

### VLAN (Virtual Local Lan)
* Improves network throughput

### RDP (Remote Desktop Protocol)
* TCP port 3389

### NTP (Network Time Protocol)
* UDP port 123

### DNS (Domain Name System)
* Queries on UDP port 53

### TFTP (Trivial FTP)
* UDP port 59
* Store files without authentication

### Telnet
* TCP port 23
* Gives admins a remote command prompt
* Transmits message in the clear-text

### SCP
* TCP port 22

### POP3
* TCP port 110

### SNMP (Simple Network Management Protocol)
* TCP port 161
* In ealier versions, traffic was sent all in clear text, but from v3, all data sent is encrypted

### LDAP
* TCP port 389
* Secured LDAP -> TCP port 636

### DHCP (Dynamic Host Configuration Protocol)
* To obtain a valid TCP/IP configuration, `ifconfig /renew`

### SDN (Software-degined Network)
* Provides scalability
