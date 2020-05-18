# Security Assessment and Audits

### Security Audit Tools
* Protocol Analyzer
  * See what type of network traffic is being transmitted on the network
  * Can be referred to as packer sniffer though it can have other meanings
  * Tools
    * tcpdump
* Vulnerability Scanner
  * Scan computers for known security violations and weakness
  * Determine which machines are secure and which are not
  * Tools
    * nessus
* Port Scanner
  * Identifies open ports on hosts
  * Tools
    * nmap
* Network mapper
  * Maps out a network's layout and identify operating systems running on hosts
  

### Security Audits
* Vulnerability Assessment
  * identifies and priotizes potential threats
* Risk Analysis
  * Does vulnerability assessment and determines how to minimize their effect on businss operations
  * Identifies assets, threats, and risks
  * Determines methods to minimize impact of identified threats
* Baseline Analysis
  * Define what is normal on a given network
* Penetration Testing
  * Simulates various network attacks against a coporate network
  * Can degrade network performance (very risky)
  * Banner grab
    * Used to probe the listening port of a network service with the intent of learning more, such as what version of software is running
    * `telnet smtp1.acme.com 25`
* Honeypot
  * Used to log zero-day activity
* Honeynet
  * A group of honeypots
  * A collection of purposely vulnerable hosts to track malicious activity
* Design Review
  * A process whereby the original project objectives are compared against current progress to ensure that the objectives are being met

### Passive Security Testing
  * Capturing  network traffic

### Protocols
* WPA2
  * WPA2 PSK (Wi-Fi Protected Access Pre-shared Key)
  * WPA2 Enterprise
    * Requires a central authentication server
* 801.2x
  * Requires that connecting hosts or users first authenticate with a central authentication server before even gaining access to the network
  * More secure than WEP and WPA PSK
* RADIUS (Remote Authentication Dial-In User Service)
  * A central server that authenticates users connecting to a network
  
### Ports
* Windows File and Print Sharing
  * TCP ports 135 - 139
* RDP
  * TCP port 3389
* Web server
  * TCP port 80
* SSL
  * TCP port 443
* SMTP (Simple Mail Transfer Protocol)
  * TCP port 25
  
### Misc.
* A Window Service (and Unix and Linux Daemons) must run under the context of a standard user account
  * Service accounts should have only the rights and permissions required to function
* Default administrative accounts must be renamed or disabled
  * Malicious users will try default admin accounts before moving on
* DNS Servers must replicate only with other known DNS servers to prevent replicating DNS records to rogue DNS hosts
* CMOS passwords prevent unauthorized persons from bootring from USB or CD to bypass operating system security
* Third-party source code escrow
  * In case the vendor later goes out of business, it would assist with granting you the source code. So you can maintain the source code yourself
