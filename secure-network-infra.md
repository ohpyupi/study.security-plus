# Securing the Network Infrastructure

### Media Gateway
Converts data from a format a network can accept to a format that another network can accept, such as a PBX to the internal Ethernet network.

### NAC (Network Access Control)
* Ensures connecting devices are compliant with configured requirements before allowing network access
* Ensures fire wall and antivirus in place
* Agents
  * Permanent NAC agent
    * Would have impact on visitor devices
  * Agentless NAC agent
    * Less impact
  * Dissolvable NAC agent
    * Minimal impact

### Packer-filtering Firewall
* Filters traffic bIP/Port/Protocol on a packet header

### Command-line Tools
* iptables
  * Configures inbound firewall rules on a Linux host
* netsh
  * Configures inbound firewall rules on a Windows host
  
### Web application firewall
Monitors and blocks HTTP traffic based on configured policy

### Web security gateway
* Provides deep packet inspection
* Detects/deals with malware

### Application Container
* Isolates applications from the host opeating system
* Can mitigate the vulnerabilities of older and legacy applications

### Proxy Server
* Retrieves content for clients
* Authenticate clients (login page for free WiFi network)
* Forward Proxy
  * what most people typicall call 'a proxy'
  * You send a connection request to it, and the forward proxy retrieves data from the internet
* Reverse Proxy
  * Controls access to a server on private networks
  * Can perform authentication tasks, as well as cache or decrypt data

### DHCP (Dynamic Host Configuration Protocol)
* Provides IP/subnet mask/default gateway/DNS to clients
* Does not provide authentication

### Protocol Analyzer
Captures and view network traffic
