# Introduction to Computer Forensic and Incident Response
### Incident Response
* Orders
  1. Analysis of the severity of an event
  2. Determines which other personnel must be called in
* Once the severity of the issue has been determined, the quickest way to control the spread of worm virus is to eliminate network connectivity

### Forensic Analysis
* Rules
  * Work only with a copy data
  * Seek legal permission to conduct an analysis

### Forensic Disk Software
  * Should run on a separate device or boots using its own OS and uses bitstream copying to copy entire hard disks contents
  * Generates file hash unique to the file on which it was based
  * Any change to the file invalidates the file hash
  * Protects data on the original disks
  * Data on a seized hard disk must remain intact
  
### Digital Forensic Tools
* Faraday Bag
  * Is a mobile device shield that prevents wireless signals to or from the mobile device
* Antistatic Bag
  * Shields sensitive electronic components from electrostatic discharge but do nothing to prevent wireless signals
* GPS (Global Positioning System) Jammer
  * Prevents unwanted GPS tracking
* Bitstream Forensic Copying Tool
  * Copies hard disk data at the bit level, not at the file level
  * When a file is deleted, it may disappear from the file system, but the file data in its entirety is intact on the hard disk until the hard disk is filled with new data
  * Deleted files are not copied with file-level copying, but they are with bitstream copying
  
### Medadata
* JPEG
  * Camera settings
  * Date and time
* Microsoft Word and PDF (Portable Document Format)
  * Author name
  * Registered company

### Terms.
* Chain of Custody
  * Involves documenting evidence being collected thoroughly and legally while ensuring that the evidence cannot be tampered with
  * Requires thoroughly documenting the state of seized equipment
  * Preserving, protecting, and documenting evidence
* Order of Volatility
  * Determines what type of data is most easily lost - for example, data in RAM versus data stored on a DVD
  * Electronic memory should be collected first
  * Hard disk, USB, and CMOS data exist even without power
  * Processor Cache < RAM < SWAP < Hard Disk < DVD-R
* Damage Control
  * Involves minimizing further damage in the event of an unfavorable event
* Time Offset
  * Used to validate the date and time stamps of digital forensic evidence
* Forensic Expert Witness
  * A person who has specialized knowledge and experience in a field beyond that of the average person, and thus her testimony is deemed authentic
* Steganography
  * The art of concealing data within other data, such as hidden messages within pictures

### Misc.
* RAID 5 array Imaging
  * Ensure that your imaging solution supports RAID
  * Image the array as a single logical disk
* GSM (Global System for Mobility)
* CDMA (Code-Division Multiple Access)
  * Stores user data directly on the mobile device
* SIM (Subscriber Identity Module)
  * Contains unique data such as a serial number, the user's contacts, text messages, and other relevant mobile subscriber data
  * Enables users to use any GSM device as long as a SIM card is inserted
  * Difficult to tamper compared to IP address, MAC, and etc.
* USB write-blocking devices
  * Ensures that data can travel in only one direction when collecting digital evidence from storage media, such as a digital camera's internal memory
* Ethernet switches isolate each port into its own collision domain
  * When capturing network traffic, this means you will not see traffic to or from other computers plugged into other switch ports, other than broadcast and multicast packets
* Swap files
  * Temporary files on a hard disk that are used as virtual memory
