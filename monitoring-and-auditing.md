# Understanding Monitoring and Auditing
### Honeypot
* The logs should be forwarded to a secure host. Otherwise the logs can be deleted by attackers

### Behaviour-based Monitoring
* A baseline of normal behavior must be established
* A database of known attack patterns is consulted

### Signature-based Detection
* Campairing known attacks against current activity

### Logs
* Audit logs
  * Differs from regular activity logs since they record administrative configuation activities, such as modifiying firewall rules

### Group Policy
* In an Active Directory env, Group Policy can be used to deliver settings to domain computers, such as audit settings for server

### Monitoring/Auditoring Tools
* Packet Sniffer (Protocol Analyzer)
  * Capture network traffic, but do not analyze it in any way
  
### SIEM (Security Information and Event Management)
* Provides a centralized way to monitor and manage security incidents
* Combines, or aggregate, like events to reduce duplicate event notifications and provide reports that correlate data
* During the response, the event de-duplication needs to be done first

### Misc.
* Log files should be part of the backup
* logging tracks more than just security events; auditing tracks specifically configured security events
* netstat
  * The built-in Windows command that can diaply local listening ports that accepts connections
