# Introduction to Cryptography
### Cryptography
* Symmetric
  * 3DES (Triple Digital Encryption Standard)
    * A 168-bit cipher
  * DES (Digital Encryption Standard)
    * A 56-bit chpher
  * RC4
  * AES
  * Blowfish
  * Twofish
    * Replaces Blowfish
  * OTP (One-time pad)
  * CBC (Cipher Block Chaining)
  * ECB (Eletronic Code Book)
  * GCM (Galois/Counter Mode)
    * Provides both confidentiality and integrity
* Asymmetric
  * RSA
  * DHE (Diffi-Hellman Ephemeral)
  * ECDHE (Elliptic Curve Diffi-Hellman Ephemeral)
  * ECC (Eliptic-curve cryptography)
    * Used most often in mobile devices
  
### Secure Protocol
* PGP (Pretty Good Privacy)
  * Uses public and private key pairs to encrypt and digitally sign messages (emails)
* FTPS (File Transfer Protocol Secure)
  * Uses SSL to secure FTP protocol
* SCP (Secure Copy)
  * Uses SSH when copying files between computers
* DNSSEC (DNS security extensions)
* S/MIME (Secure Multipurpose Internal Mail Extensions)
  * Uses PKI certificates to provide e-mail security with digital signatures and encryption
* SRTP (The Secure Real-time Transport Protocol)
  * Provides integrity and encryption services for streamed data, often in the form of voice or video traffic
* SNMPv3 (Simple Network Management Protocol version 3)
  * Enhances security of the original protocol used to manage and monitor network devices and hosts by adding authentication using keys instead of community strings used in previous versions
* IMAP (Internet Message Access Protocol)
  * Secured IMAP Port -> TCP 993
  * Insecure IMAP Port -> TCP 143
* POP (Post Office Protocol)
  * Secured POP Port -> TCP 995
  * Insecure POP Port -> TCP 110
  
### Insecure Protocol
* PAP (Password Authentication Protocol)
  * Does not encrypt trasmitted credentials
 
### VPN
  * Applicable for WAN, not LAN - Use IPSec for secure channel on LAN
  * Hardening
    * Disable PAP (Password Authentication Protocol) - exposes password in clear-text
    * Enable EAP-TLS (Extensible Authentication Protocol - Transport Layer Security)
    
### Digital Signature
* Provides
  * Integrity
  * Authentication
  * Non-repudiation
* A standard for digital signatures: DSA (Digital Signature Algorithms)
  
### Hashing
* Principles
  * Diffusion
    * Describes a situation where a small change introduced to the input data before encryption causes large changes in its encrypted version
  * Confusion
    * Output of a cryptographic function should be considerably different from the corresponding plaintext input
* Examples
  * MD5 (Message Digest 5)
  * SHA (Secure Hashing Algorithm)
  * RIPEMD (RACE Integrity Primitives Evaluation Message Digest)
  * HMAC (Keyed-Hashing for Message Authentication)
* Key stretching
* Converts weak keys such as passwords into stronger keys that are less susceptible to brute-force attacks
* Algorithms
  * Bcrypt
  * PBKDF2 (Password-Based Key Derivation Function 2)

### Misc.
* Nonrepudiation
  * Describes assuarance that a message is authentic and neither party can dispute its transmission or receipt
* SECaaS (Security as a Service)
  * Provides a subscription-based cloud service that enables organizations to outsource the acquisition and maintenance of security hardware and software while allowing customized threate management configurations
  * Much less expensive initially
* Smartcard
  * Low-power device - still can perform sufficient cryptographic calculations to be used in secure IT environments
* Security through obscurity
  * Code obfuscation
  * Steganography
  * SSID broadcast suppression
  * Substitution cipher (Caesar cipher)
* Obfuscation methods
  * Steganography
  * XOR cipher
  * ROT13 (Rotate by 13 places)
