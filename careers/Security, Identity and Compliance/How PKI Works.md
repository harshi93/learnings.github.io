# Introduction
    1. Pki is infrastructure to create, distribute, revoke digital certificates
    2. Digital certificate links public key to user or machine
    3. Public Key and Private key - Data encrypted with one can only be decrypted with other

# PKI Infrastructure Components
PKI is made up of following
1. **Certificate Authority**
    ○ Responsible for issuing digital certificates that will validate servers identity
2. **Registration Authority**
    a. Verifies identity of client or user requesting digital certificate 
    b. CA can also act as an RA
3. **Certificate Database** 
    a. Store certificates and related metadata including its validity
4. **Cryptographic Directory**
    a. Index and stores cryptographic keys
5. **Certificate Management System**
    a. Responsible for governing access and distribution of certificate
6. **Certificate Policy**
        a. A policy outlining procedures of PKI
        b. These can be used by outsiders to determine trustworthiness of CA

# Chain of Trust Validation 
    - Public key is requested by client, private key is calculated during SSL handshake
    - Microsoft and Apple publish list of trusted root CA
    - Online CA issues certificates using intermediate CA 
    - Microsoft Trusted Root Program
        ○ Root CA listed, Undergo regular and meeting specific security standards   
        ○ Root CA
            § Fully trusted source for validation and revocation of certs
            § Root CA use offline HSM to store private key
            § Root CA is responsible for establishing trust in intermediate CA
            § Eg DigiCert
        ○ Intermediate CA
            § Establish trust in online CA
            § private key for intermediate ca and online can is stored in online HSM
            § Eg DigiCert Intermediate CA
        ○ Online CA
            § Responsible for issuing cert for use by applications and user
            § Eg Lets Encrypt 
        ○ Certificate Revocation List / Online Cert Status Protocol
            §  used by recipient to confirm chain of trust and ensure certificate is not expired or is compromised
    - On windows “CTL Updater” is responsible for updating list of root CA
