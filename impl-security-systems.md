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
* An embedded cryptoprocessor that can be found on the motherboard of newer PCs and laptops
* Capabilities
  * Remote Attestation
    * To check a computer system's integrity against a remote trusted third-party service

### HSM (Hardware Security Module)
* Handle cryptographic duties to reduce a server's workload
* A hardware device or a plugin card used for secure management, processing and storage of cryptographic keys

### UEFI (Unified Extensible Firmware Interface)
* A firmware interface designed as a replacement for BIOS.
* Provides a variety of improvements over BIOS, GUI, mouse support, or secure boot functionality to prevent the loading of malware and unauthoirzed operating systems during the computer startup process

### IDS (Intrusion Detection System)
* components
  * Sensor
    * Collects the data from the network segement
  * Manager
    * An intergace that the human uses to interact with the system
  * Analyzer
    * Analyzes the data
* Operation modes
  * Passive
    * Examin a copy of the traffic
    * No way to block the traffic
  * Out-of-band
    * The IDS is not part of the traffic flow
    * Can send TCP reset frame to the source and the destination to close the session between two
  * In-band
    * All traffic passes through the IDS
* Detection of attacks
  * Signature-based
  * Anomaly-based
  * Behavioral
  * Heuristic
  
### HIDS (Host-based IDS)
* Application-centric IDS
* Monitor an abnormal activities of a host or an application

### NIDS (Network-based IDS)
* Monitors network packets

### ICS (Industrial Control System)
* A system providing the capability for remote control, real-time monitoring, and gathering information related to industrial equipment
* Examples
  * SCADA (Supervisory Control and Data Aquisition)
    * A centralized system that control and monitor the entire sites, or it is a complex system that spreads out over large areas
    * No access from the outside (Network isolation)
    * Large-scale, multi-site ICS
    * Distributed control systems
    * PC manages equipment
      * Power generation, refining, manufacturing equipment
      
### HVAC (Heating, Ventilating, and Air Conditioning)
* A complex science
* PC manages equipment
* Trandionally not built with secuirty in mind
  * Difficult to recover from an infrastructure DoS

### All-in-one security appliance
1. URL filter
2. Content inspection
3. Malware inspection

### Mobile Security Solution
* Terms.
  * Screen lock
    * A user interface element controlling access to a mobile device after the device is switched on
  * Sideloading
    * Allows to install an application without using an official app store
  * Jailbreaking
    * Refers to removing software restrictions imposed by Apple on its iOS OS
  * Containerization
    * The isolation of corporate applications and data from other parts of the mobile device
  * Storage segmentation
    * Enables separate controls over the user and enterprise data
* Mobile Device Deployment
  * Policies
    * BYOD (Bring your own devices)
      * Needs a separate network for BYOD devices
    * CYOD (Choose your own devices)
      * Employees can choose and purchase a device from approved choices
    * COPE(Corporate-owned, Personally-enabled)
      * The most secure solution
      * Security features enabled
      * Cellular data, remote wipe, location tracking, MDM
    * VDI (Virtual Desktop Infrastructure)
      * A mobile device can act as a terminal for accessing data and applications hosted on a remote server
      * Virtualize the user's desktop and run it in the data center
      * All of the computing power is in the data center
      * Enhanced security
      * Also referred to VDE (Virtual Desktop Environment)
      * Persistent VDI
        * Each user runs their own copy of virtual desktop
        * At the end of a session, user data and personal settings are saved

### CASB (Cloud Access Security Broker)
* A security policy enforcement software tool or service placed between cloud service users and cloud applications
* Implemented as client softwares or cloud-based security solutions
* Capabilities
  * Visibility
  * Compliance
  * Threat prevention
  * Data security

### Data Policy
* Wiping, Disposing, Retention, Policy, and Storage

### IPSec
* Tunneling mode
  * Encrypts entire packets (the entire contents)
* Transport mode
  * Encrypts only data, not the header
* AH (Authentication header)
  * Only provides integrity
* ESP (Encaptulating security payload)
  * Provides integrity and encryption

### Data Communication
* NFS
* SATCOM (Satelite Coummunication)

### Hypervisor
  * Type 1
    * Runs on a hardware level
    * Bare metal
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
* A DevOps software deployment approach where applications and services are redployed rather than modified whenever a need for introducing change occurs

### Hypervisor
* A software that creates and runs virtual machines
* Type I
  * Bare metal
* Type II
  * Has host OS
  
### Cloud Services
* IaaS
  * network infrastructure
* PaaS
  * infrastructure for hosted applications
* SaaS
  * applications
* IAC (Infrastructure as Code)
  * Replaces manual configuration of hardware with automatic deployment through code
  
### Air Gap Networking
* Ensures that a secure computer network is physically isolated from unsecured networks, such as the public Internet or an unsecured local area network

### TCP Wrapper

### Terms.
* MFD (Multi-functional Devices)
  * For example, a device capable of priting, scanning, and faxing
  * A document stored in the memory of this can pose a risk of an unauthorized data access
* EMI (Electromagnetic Interference)
* Degaussing
  * Removes magnetic field generated from a device
* FDE (Full Disk Encryption)
  * The best way to protect data on any device (often the most important security feature)
* SED (Self-encrypted Drives)
  * A data storage device equipped with a hardware-level encryption functionality
* Secure supply chain
  * Based on the assumption that all hardware/software should originate from reliable sources
* SoC (System on a Chio)
  * Raspberry Pi
  * Multiple components running on a single chip
* RTOS (Real-Time Operating System)
  * An operating system with a determinitic processing schedule
  * No time to wait for other processes
  * Industrial equipment, automobile
  * Military environments
  * Exteremely sensitive to security issues
* UAV (Unmannged Aerial Vehicle)
  * Technical security controled that can be applied
    * Wireless signal encryption
    * Password Encryption
* Code Signing
  * Confiems the applications' source of origin
  * Validates the application's integrity
