# Authentication
### TACACS+ (Terminal Access Controller Access Control System)
* Cisco proprietary network access protocol that uses the reliable TCP transport mechanism
* Can be used instead of RADIUS (But it didn't succeed RADIUS)
* Encrypts the entire packet payload instead of only password, as well as separates authentication, authorization, and accounting duties
* Not compatible with TACACS (Old network access standard used primarily in UNIX network environments)

### LDAP (Lightweight Directory Access Protocol)
A central database that can securely authenticate users or computers
* Ports
  * TCP 389 - clear text transmission
  * TCP 636 - encrypted transmission (Secured LDAP)
* Compliant protocols to LDAP
  * Microsoft Active Directory Services
  * Novell eDirectory
  
### Diameter Protocol
* Succeeds RADIUS protocol
* Adds capabilities to RADIUS protocol such as using TCP instead of UDP (more reliability) and being more scalable and flexible

### CHAP (Challenge Handshake Authentication Protocol)
* Involves three-way handshake to establish session
* After session establishment, peers must periodically prove their identity by way of a changing value based on a shared secret
* A shared secret (for example, password) is known by both parties but never sent over the network
* Designed to stop a session hijack

### Authentication/Authorization Frameworks
* OpenID Connect
* OAUTH
* Shibboleth
  * Popular in UNIX and Linux environments
  
### Kerberos
* A key distribution center and provides keys with certain time limits
* Can be affected by NTP (Network Time Protocol)

### Authentication devices
* Key fob
  * Displays an authentication passcode that a user enters in addition to other data such as username/password to gain access to a system or network resource
* Smartcards
  * Contains an embedded chip that has personal identification data such as encryption keys or PKI digital certificates
  
### Misc.
* A computer PKI certificate can grant access to an 802.1x-configured wireless network
* Common access card is used to gain access to more than one type of secured resource
* Transitive trusts are created where one party trusts a remote party through a middle party
