# Wireless Networking and Security
### Wireless Standard
* 802.11g
  * 54 Mbps
  * Backward compatible with 802.11b hardware
    * Slows down the network speed
  * Has an option to accept only 802.11g devices
* 802.11b
  * 11 Mbps
  
### IEEE 802.11 Networks
* Includes 2.4 Ghz and 5.0 Ghz

### Wired Ethernet Standard
* 802.3

### Wi-Fi
* Wi-Fi 2.4 GHz
  * Divided into smaller bands (channels) that slightly overlap
  * Any device that uses the same range can interfere the network, e.g. microwave oven
  
### WPS (Wi-Fi Protected Setup)
* A network security standard to create a secure wireless home network
* A pin on the back of a router
  
### WEP (Wired Equivalent Privacy)
* Uses RC4
* IV attack
  * Extracts 24-bit IV and a WEP key from packets
  
### WPA (Wi-Fi Protected Access)
* Encrypts packet - Confidentiality
* Uses TKIP (Temporal key Integrity Protocol), verifying tampering

### WPA2 (Wi-Fi Protected Access version 2)
* Capable of using TKIP or the more advanced AES algorithm and CCMP
* Developed by WiFi Alliance and implemented the requirement of IEEE 802.11i
* WPA2 PSK (Pre-shared Key)
  * WPA and WPA2 PSK are for home use, and uses passphrase
* WPA2 CCMP (Counter Mode CBC-MAC Protocol)
  * Must be used by default in WAP2-CCMP (not necessarily in WPA-CCMP)
  * the least susceptible to wireless replay attacks
  * Replaces TKIP option
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

### WAP (Wireless Access Point)
* Fat WAP
  * Independent to be separated from other network devices
  * Has everything
  * Not ideal in large enterprise or college campus
* Thin WAP
  * All the functions controlled in a central device, like a wireless switch or wireless LAN controller
  * All the settings can be configured automatically by central device in a remote location
* Controller-based WAP
  * Has minimal functionality as most are centrally-controlled
* WAP power level controls
  * Helps troubleshooting signal loss and low wireless network signal coverage
* Antenna Types
  * Dipole Antenna
    * A comment antenna type used as a standard equipment on most AP for indoor WLAN deployments
    * Provides a 360-degree horizontal signal coverage
  * Omnidirectional Antenna
    * Provides a 360-degree horizontal signal coverage
  * Unidirectional Antenna
    * Highly directional antenna type for long-range point-to-point bridging links
  * Dish Antenna
    * Highly directional antenna type for long-range point-to-point bridging links
 * An optimal WAP antenna placement provides a countermeasure against war driving attack
 
### Wireless Bridge
* A type of device that is used for interconnecting two or more physically separated network segments
  
### WLAN
* Disabling SSID broadcast will make a WLAN harder to discover

### Wireless Modes
* Isolation mode
  * Prevents wireless clients on the same WLAN from seeing one another
  
### ANT (Adaptive Network Topology)
* A proprietary technology that works with low-power mode devices
* Primarily used for sports and fitness sensors

### War driving
Searches for wireless networks, often from within a moving vehicle

### EAP (Extensible Authentication Protocol)
* An authentication framework frequently used in wireless networks and point-to-point connections
* It provides an authentication framework, not a specific authentication mechanism
* Connects device network authentication framework supporting methods such as PIK certificates, smartcards, and passwords
* Variants
  * EAP-FAST
    * Exists where password policy cannot be enforced
    * Consists of 3 phases which are provisioning, establishment of a tunnel, and authentication
  * EAP-TLS
    * Offers the highest level of security
    * EAP with TLS standard
    * Requires both client and server certificates
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
* Prevents connections from unauthorized wireless clients
* A security access control method whereby the MAC address assigned to each network card is used to determine access to the network

### Security Policy Terms
* MIMO (Multiple input, multiple output)
  * Use multiple antennae to achieve greater wireless transmission throughput
* Captive Portal
  * Presents a user with an authentication web page before allowing Internet access
* Channel Bonding
  * Transmits data over multiple channels simultaneously to achieve greater wireless transmission throughput
  
### RFID (Radio-frequency Identification)
* Uses electromagnetic fields to automatically identify and track tags attached to objects
* Examples
  * Implanting RFID microchips in livestock and pets enables psotivie identification of animals
* Privacy concerns
  * RFID tags can be attached to cash, clothing, and possesions.
  * The possibility of reading personally-linked information without consent has raised serious pricacy concerns

### Wi-Fi Direct
* Enables establishing direct communication links between two wireless devices without an itermediary WAP

### OTA (Over-the-air)
* Mobile device updates delivered over a wireless connection
