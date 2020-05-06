### Week 8, Tuesday
## Web Security
We need HTTPS for three reasons: privacy, integrity, and identification. Expanded, that means that our data is encrypted and not being eavesdropped on, our communication is not being tampered with, and identification means the source of your data is identified and certified to be what you expect it to be.   
Privacy can be achieved through either symmetric or asymmetric key validation. Symmetric keys use only one private key, held by both parties in communication, both to encrypt and decrypt data being sent. Asymmetric keys use a public key to encrypt data, but need a private key to decrypt that data.  
Integrity and Identification is achieved through "the handshake", where the browser sends a cipher suite of what encryption algorithms it can handle to the server, and the server picks the best option and sends back it's cerification to confirm it's identity. Then they create their encryption keys together.   

and Now, some acronym review:
- **HTTP** = HyperText Transfer Protocol, the protocol used by your browser and web servers to communicate and exchange information
- **HTTPS** = HTTP, but "Secured" by SSL/TLS
- **SSL** = Secure Sockets Layer, a deprecated protocal created by Netscape
- **TLS** = Transport Layer Security, really a newer version of SSL, developed by IETF
- **IETF** = Internet Engineering TaskForce, took control of SSL starting in 1999, converting it to TLS
- **CA** = Certificate Authority, a third-party that issues certificates, confirms the identity of certificate owners, and provides certificate proof validation





#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)