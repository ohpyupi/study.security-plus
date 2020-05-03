# Disaster Recovery and Business Continuity
### RAID (Redundant Array of Independent Disks)
* RAID 1
  * Refers to disk mirroring. When data is written to one disk, it is duplicated on the second disk
* RAID 0
  * Striping data across multiple disks to increase performance, but there is no fault-tolerance since a single disk failure would result in the loss of all data
* RAID 5
  * Stipes data across disks (minimum of three disks) but distributes parity (recovery) data on disks so that a single disk failure means data can still be reconstructed
* RAID 5+1
  * A mirrored RAID 5 array
  
### Backup strategies
* Differential backups
  * Archive data that has changed the last full backup
  * Restores the full backup plus the last differential
* Incremental backups
  * Archive data changed since the last incremental backup
  
### Types of Recovery Facilities
* Cold site
  * Often refered to as nothing more than leased space
* Warm site
  * Are functional only once the primary center goes down
  * Data backups are done periodically
* Hot site
  * Costly
  * Immediately available, and constantly synchronizes data from the primary center
  
### Recovery Plans
* DRP (Disaster Recovery Plan)
  * Involves implementing steps to get the business operational
  * Outlines exactly who must do what in case unfavorable events occur
  * This includes infected servers by malware and viruses
  * Installs confidence in shareholders
  * Must be tested to ensure its success
  * Must have management support and approval
  * Must be revisited periodically to ensure that it is in stop with changes in the business
  * Examples
    * Ranking risks
    * Assigning recovery tasks to personnel
    * Establishing an alternate location to continue business operations
* Business Continuity
  * Ensures business operations after the successful implementation of the DRP.
  
### Restoration Specialists
* Property Restoration Specialist
  * Efficiently restores the state of a facility so that a business can continue to operate
  * HVAC, electricity, water, lightning, and etc.
* Document Restoration Specialist
  * Has expertise in retrieving damaged data, whether it is physical (paper documents) or digital.
* Server Restoration Specialist
  * Are trained in quickly getting servers up and running to their previous state
  
### Metrics
* MTTR (Mean Time to Recovery)
* MTBF (Mean Time between Failures)
* MTTF (Mean Time to Failure)
* RPO (Recovery Point Objective)
  * The amount of that can elapse after a failure before system and data resume normal operation
  * Can exceed the amount of time
* RTP (Recovery Time Objective)
  * Denotes the amount of time it will take after an unexpected failure for systems to resum normal operation
    
 ### Privacy
 * Privacy Impact Assessment
  * Used to determine the response if PII security is breached
 * privacy Threshhold Assessment
  * identifies systems or data that process private information
    
### Misc.
* SAN (Storage Area Network)
* It is recommended to have a different person to review backup logs than the backup operator
* All data backups on the off-site must be encrypted
* Redundant Internet Links
  * Allow access to the webstie even if one Internet link fails
* After-action report
  * Takes lessons learned from previous incidents. Essentially they strive to improve upon identified problems that hampered incident response
  

