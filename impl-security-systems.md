# Implementing System Security
### NTFS (New Technology File System)
* Developed by Microsoft
* Provides access control to files/folders
* Does not provide encryption to the file system
* The access control can be easily circumvented in the local

### EFS (Encrypting File System)
* Can be configured only on the NTFS-enabled drives
* Provides encryption for the drive content
* Stores keys in the OS

### DLP (Data Loss Prevention)
* Limits unapproved technologies
  * For example, limit the risk associated with unapproved USB devices to company documents

### TPM (Trusted Platform Module)
* Stores keys in a tamper-resistant chip similar to an internal Smartcard
* Needs to back up the keys after its setup
* Provides encryption for the drive content

### HSM (Hardware Security Module)
* Handle cryptographic duties to reduce a server's workload

### HIDS (Host-based IDS)
* Application-centric IDS
* Monitor an abnormal activities of a host or an application

### NIDS (Network-based IDS)
* Monitors network packets

### All-in-one security appliance
1. URL filter
2. Content inspection
3. Malware inspection

### BYOD, COPE, CYOD
* BYOD (Bring your own devices)
  * Needs a separate network for BYOD devices
* CYOD (Choose your own devices)
* COPE(Corporate-owned, Personally-enabled)
  * Security features enabled
    * Cellular data, remote wipe, location tracking, MDM
  
### Data Policy
* Wiping, Disposing, Retention, Policy, and Storage

### Data Communication
* NFS
* SATCOM (Satelite Coummunication)

### Hypervisor
  * Type 1
    * Runs on a hardware level
  * Type 2
    * Runs on an existing OS level
    
### VoIP
* Applying encryption over VoIP can add delay
* Works with SIP (Session Initiation Protocol) and RTP (Real-time Transport Protocol)

### UTM (Unified Threat management) Firewall
* Includes firewall, IDS, antivirus, and some other devices

### VDE (Virtual Desktop Environment)
* Ensures all workstations have a common configuration, do not contain a rogue software installation, and all patches are ketp up do date

### Immutable Server
* A server that has a configuration for applications and the OS that cannot be changed

### Terminologies
* Sideloading
  * Allows to install an application without using an official app store
* MFD (Multi-functional Devices)
  * For example, a device capable of priting, scanning, and faxing
* EMI (Electromagnetic Interference)
* Degaussing
  * Removes magnetic field generated from a device
