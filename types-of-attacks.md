# Types of Attacks
### ARP (Address Resolution Protocol) Poisoning
* Man in the middle attack
* Occurs when the hacker alters the ARP cache to redirect communication to a particular IP address to the wrong MAC address
* Preventions:
  * Add static ARP entries
  * Implement physical security to avoid malicious users from gaining access to the network and poisoning everyone's ARP cache.

### Buffer Overflow
* Preventions:
  * Patches periodically

### Integer Overflow
* A programming error where an application tries to store a numeric value in a variable that is too small to hold it

### Point Dereference
* Describes an attempt to read a variable that stores a null value
  
### Domain Kiting
* Register and delete a domain name repeatedly to avoid paying for the domain name

### Smurf Attack
* DDOS

### Hybrid Attack
* The combination of dictionary attack, brute-force attack, and modification of passwords

### Vishing
* Voice + Phishing

### Bluejacking
* Sends unsolicited text messages to a Bluetooth device such as phone

### Hoaxes
* Email messages received giving a false story and asking the user to take some form of action usch as forwarding the message on to others

### Xmas Attack
* Creates a TCP packet that turns on flags to scan systems

### Social Engineering
* Authority, Urgency, and Trust

### SYN flood
* Half-open connections
* A form of DoS attack

### RAT (Remote Access Trojan)
* Typically ports 135 and 445
* Different than worm since its installed by users

### Refactoring Attack
* Refactors an internal code while maintaining the external behavior so that it appears to be behaving normally

### Downgrade Attack
* Forces a connection to abandon a high-quality encryption method of a lower quality, more easily broken method.
* Examples
  * POODLE (Padding Oracle On Downgraded Legacy Encryption)
    * A MITM exploit which takes advantage of Internet and security software clients' fallback to SSL 3.0

### Logic Bombs
* Triggers when certain conditions are met such as date

### Pivot
* Occurs when you successfully exploit one machine and use that to exploit another
* Can be internal or external

### Typosquatting
* a URL named very simlar so when users mistype the site name, it goes to a fake site
* For example googlr.com

### Phishing
* Spear phising
  * Targets a small group
* Whaling
  * Targets a specific individual, for example CEO
  
### Banner Grabbing
* A process where someone connects to a web server and gathers information.
* Can be done through netcat easily

### Hacking Attack Stages
* Passive Reconnaissance
  * There is no engagement with the target
  * For example, gathering information from sources such as archive.og, netcraft.com, or social media
* Active Reconnaissance
  * Has a target communication

### Shimming
* An attacker places malware between an application and other files which intercepts the communication of the file

### APT (Advanced Persistent Threat)
* Takes a while to complete

### Pharming
* A fradulent practice of directing Internet users to a bogus website that mimics the appearance of a legitimate one in order to obtain personal information such as user passwords, account numbers, and other confidential data

### Multipartite
* Viruses that combine infections with boot sector viruses

### Sparse Infector Virus
* Performs activity sporadically

### Rainbow tables
* A precomputed table for reversing cryptographic hash functions, usually for cracking password hashes
* Can be mitigated by password length

### DLL Injection
* A malware that attempts to inject code into the process library
* A type of attack that relies on executing a library of code

### Spim
* A type of spam targeting users of IM (instant messaging) services, SMS, or private message within websites and social media

### KPA (Known-plaintext Attack)
* An attack model for cryptanalysis where the attacker has access to both the plaintext, and its encrypted version
* These can be used to reveal further secret information such as secert keys and code books

### MAC flood attack
* Attempts to overload a switch with different MAC addresses associated with each physical port

### Misc
* Two popular methods of driver manipulation are: shimming and refactoring
  * In malware, these are often doen to look for opportunities to take advantage of weak code and look for holes that can be exploited
* IPSec, Kerberos, and CHAP offer countermeasures against replay attacks
