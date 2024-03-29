# Access Control
### Access Control Models
* Mandatory Access Model (MAC)
  * Enforces rules of the OS
  * Uses security labels to classify data
  * Enforces the strictest set of access rules
* Discretionary Access Control (DAC)
  * Leaves control of security to the data owner
  * Very flexible, but weak
  * For example, Linda creates a folder and puts files in the folder, and chooses people who will be shared with the folder contents
* Role-based Access Control (RBAC)
  * Places users into roles that have been granted groups of permissions to perform a job function
* Rule-based Access Control
  * For example, rules defined in network routers
  * For example, Lab network access is only available between 9AM to 5PM
* Attribute-based Access Control
  * An access control using conditions based on attributes such as department, project, and security clearance level
  * Aware of context
  * A "next generation" authorization model
  * Closely resembles natural language
  * Example of properties
    * Subject - user, process
    * Type of action - read, write, execute
    * Resource type - medical record, bank account
    * Environment - contextual data, time of day, geolocation
* Time-of-data Access Control
* Group-based Access Control
  * Users are placed in groups and permissions are applied to groups
  
### Roles
* System Owners
  * Receives role-based trainings on how to manage particular systems

### Trusted OS
* A trusted OS uses a secured OS kernel that supports mandatory access control (MAC), which applies security centrally to adhere with security policies
* Considered too strict for general use and is typically applicable only in high-security environments
* Uses MAC access control model

### Ports
* FTP -> TCP 20/21

### Security Controls
* Technical controls
  * Includes any hardware or software solution using access control in adherence with established security policies
  * Protects computing resources such as files, web sites, databases, and so on
  * Same as logical controls
* Physical controls
  * For example, door locks and fences to protect organizational assets from threats
* Operational control
  * For examples, data backups to ensure business continuity
* Administrative controls
  * Provide a foundation for how a business should be run
  * Examples
    * Risk assessments
    * Escalation procedures
    * Contingency planning
* Preventative controls
  * Prevents security breaches, such as the theft as a laptop
* Preventive control
  * OS hardening
  * Separation of duties
  * Security guards
* Deterrent controls
  * Discourages malicious or illegal actions but do not necessarily prevents them from happening
  * Are used to warn attackers
  * For example, lighting, CAPTCHA, warning signs, login banners
* Detective controls
  * Recognizes malicious activity and generates a notification
  * Examples
    * System logs
    * CCTV
    * Security audits
* Compensating controls
  * Used when other specific security requirements cannot be met but are mitigated through a different type of control
  * Examples
    * Backup generator
* Corrective controls
  * Mitigates damage once it has occurred, such as disaster recovery plan
  * Examples
    * Backup data recovery
    * Alternate site
    * IPS
