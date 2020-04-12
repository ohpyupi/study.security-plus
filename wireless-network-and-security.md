# Wireless Networking and Security
### Wireless Standard
* 802.11g
  * 54 Mbps
* 802.11b
  * 11 Mbps

### Wired Ethernet Standard
* 802.3

### Wi-Fi
* Wi-Fi 2.4 GHz
  * Divided into smaller bands (channels) that slightly overlap
  * Any device that uses the same range can interfere the network, e.g. microwave oven
  
### WEP (Wired Equivalent Privacy)
* IV attack
  * Extracts 24-bit IV and a WEP key from packets
  
### WPA (Wi-Fi Protected Access)
* Encrypts packet - Confidentiality
* Verify tampering - Integrity

### WPA2 (Wi-Fi Protected Access version 2)
* WPA2 PSK (Pre-shared Key)
  * WPA and WPA2 PSK are for home use, and uses passphrase
* WPA2 Personal
  * Simply uses passphrase
* WPA2 Enterprise
  * Uses authentication server to contol network access
  
### WPA2 Standard
* CCMP (Counter Mode CBC Message Authentication Protocol)
  * Uses an AES block cipher with counter mode
  * Counter mode makes pattern detection difficult
  
### TKIP (Temporal Key Integrity Protocol)
* Used by WPA standard
* Changes encryption key per packet

### Wireless Modes
* Isolation mode
  * Prevents wireless clients on the same WLAN from seeing one another

### War driving
Searches for wireless networks, often from within a moving vehicle

### EAP (Extensible Authentication Protocol)
Connects device network authentication framework supporting methods such as PIK certificates, smartcards, and passwords
* Variants
  * EAP-FAST
  * EAP-TLS
    * EAP with TLS standard
  * EAP-TTLS
  * PEAP (Protected EAP)
    * Encapsulates the EAP connection in an encrypted and authenticated tunnel
    * Creates secure channel for user authentication using a server-side PKI certificates initially. Then a symmetric session key is used for the remainder of the session
    
### Bluetooth Attacks
* Bluejacking
  * Sends anonymous message to another Bluetooth devices
* Bluesnarfing
  * Access unauthorized devices over Bluetooth communication
  
### MAC Address Filtering
Prevents connections from unauthorized wireless clients

### Security Policy Terms
* MIMO (Multiple input, multiple output)
  * Use multiple antennae to achieve greater wireless transmission throughput
* Captive Portal
  * Presents a user with an authentication web page before allowing Internet access
* Channel Bonding
  * Transmits data over multiple channels simultaneously to achieve greater wireless transmission throughput
  
### RADIUS Federation
* Centralizes authentication
* Each devices such as VPN appliances forward user authentication requests to the central RADIUS server
* Clients
  * Switches
  * Wireless routers
  * VPN concentrators
