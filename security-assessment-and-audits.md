# Security Assessment and Audits

### Security Audit Tools
* Protocol Analyzer
  * See what type of network traffic is being transmitted on the network
  * Can be referred to as packer sniffer though it can have other meanings
  * Tools
    * tcpdump (CLI)
      * packet capturing utility
    * Wireshark (GUI)
* Vulnerability Scanner
  * Scan computers for known security violations and weakness
  * Determine which machines are secure and which are not
  * Offers the functionality of a configuration compliance scanner
  * Tools
    * nessus
    * OpenVAS (Open Vulnerability Assessment Scanner)
* Pasword Cracking Tools
  * Tools
    * John the Ripper
    * Cain & Abel
* Wireless Scanner
  * Performs a site survey
* Port Scanner
  * Identifies open ports on hosts
  * Tools
    * nmap
    * netcat
* Network mapper
  * Maps out a network's layout and identify operating systems running on hosts
* Exploit Framework
  * A tool to find vulnerabilities and attempting to exploit them

### Tools
* netstat
  * Windows built-in CLI tool that displays network connections for TCP, routing tables, and a number of network interface and network protocol statistics
  * network + statistics
  * parameters
    * -a: displays all connections and listening ports
    * -n: displays addresses and port numbers in numerical form
* Metasploit
  * Metasploitable
    * A Linux distribution commonly used as a target system for pracitcing penetation testing techniques
* tracert
  * Trace + Route
  * Windows built-in CLI tool that tracks and displays the route taken by an IP packet on its way to another host
* traceroute
  * A Linux CLI tool which is a counterpart of the tracert
* nslookup
  * Used to troubleshoot DNS-related problems
* arp 
* ipconfig
  * Windows built-in CLI tool
  * parameters
    * /all: displays the full TCP/IP configuration information for all adapters
    * /renew: resets the DHCP configuration settings for all adapters
* ifconfig
  * A counterpart of ifconfig in Linux distributions
* netcat
  * Can be used for both port scanning and banner grabbing
* nmap
  * Used to discover hosts and services on a computer network by sending packets and analyzing the responses
* SFC (System File Checker)
  * A utility in Microsoft Windows that allows users to scan for and restore corruptions in Windows system files
  * Checks the file integrity and restores corrupted system files
  
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
    * The practice of connecting to an open port on a remote host to gather more information about its configuration
    * `telnet smtp1.acme.com 25`
* Honeypot
  * Used to log zero-day activity
* Honeynet
  * A group of honeypots
  * A collection of purposely vulnerable hosts to track malicious activity
* Design Review
  * A process whereby the original project objectives are compared against current progress to ensure that the objectives are being met
* Usage audit and review
  * Documents how users actually use their account permissions
* Permission auditing and review
* Time-of-day restrictions
  * Nobody needs to access the lab at 3AM

### Passive Security Testing
  * Capturing network traffic

### Protocols
* WPA2
  * Supported by 802.11i
  * WPA2 PSK (Wi-Fi Protected Access Pre-shared Key)
  * WPA2 Enterprise
    * Requires a central authentication server
* 802.1x
  * Requires that connecting hosts or users first authenticate with a central authentication server before even gaining access to the network
  * More secure than WEP and WPA PSK
* RADIUS (Remote Authentication Dial-In User Service)
  * A central server that authenticates users connecting to a network
  * A cross-platform remote access protocol
  * Uses symmetric encryption
  
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
