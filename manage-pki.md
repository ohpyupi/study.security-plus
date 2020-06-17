# Managing a Public Key Infrastructure
### PKI
* Digital Certificate
  * Composes of a public key, a private key (optional), and a digital signature signed by a private key
  * Much secure than the use of username/password
* Recovery Agent
  * Has an ability to recover encrypted data when the original private key is unavailable
* CRL (Certificate Revocation List)
  * published either manually or on a schedule
* RA (Registration Authority)
  * Optional
  * Performs requestor verification before certificates are issued
* CA (Certificate Authority)
  * Revokes certificates
  * Uses its private key to digitally sign certificates
* OSCP (The Online Certificate Status Protocol)
  * Can query a CA for a single PKI certificate serial number instead of downloading a list of all all revoked certificate serial numbers, as is the case with CRL
* OSCP stapling
  * Checks digital certificate revocation status without contacting CA
* Certificate Pinning
  * Associates a host with its related public key
* CSR (Certificate Signing Request)
  * Submitted to CA to request a digital certificate
* Trust Model
  * Automatically updates browsers with a list of certificates for applications
  * Examples
    * Single CA model
    * Hierarchical model (root CA + intermediate CAs)
    * Mesh model (cross-certifying CAs)
    * Web of trust model (all CAs act as root CAs)
    * Client-server mutual authentication model
* HPKP (HTTP Public Key Pinning)
  * Allows HTTPS websites to resist impersonation by attackers using fradulent certificates
  * Deprecated due to its complexity in favor of Expect-CT
  
### Certificate Types
* Wildcard certificate
  * Allows multiple subdomains to be protected by a single certificate
* SAN (Subject Alternative Name) certificate
  * Allows multiple domains to be protected by a single certificate
  
### Certificate Formats
* DER (Distinguished Encoding Rules)
  * Used to store a binary representation of a digital signature
* PEM (Privacy Enhanced Mail)
  * The most common format in which CA issue certificates
* P12 and PFX (Personal Information Exchange Format)
  * Commonly used to store private keys and should be password-protected
### X.509 Standard
Defines a hierarchy of certificate authorities that issue, renew, and revoke certificates
  
### X.509 Certificates
* Cannot be renewed if expired; a new certificate must be created

### TPM (Trusted Platform Module)
* A firmware security solution that can use PKI certificate keys to encrypt and decrypt hard disk contents
* More secure than EFS; EFS is vulnerable for skilled hackers when they have physical access to the hardware

### Example of Digital Certificate
```
Expiry: 12 months
Bit length: 2048
Common Name: www.acme.com
Organization: Acme Inc.
OU: Sales
Country: US
State: TN
City: Memphis
```
  
### Misc.
* Key escrow
  * Refers to a trusted third party with a copy of decryption keys.
  * A court order may be necessary to use these keys under certain circumstances
  * A trusted third-party storage solution providing backup source for cryptographic keys
* Both OSCP and CRL can be used check if a digital certificate has been revoked
* OSCP is the fastest method of validating a digital certificate
