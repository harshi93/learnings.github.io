# How SSL/TLS Works
1. Hello Message
        a. Client lists ciphers and protocols supported by it, server responds with choice common to both 
2. Certificate Exchange and Authenticity Validation
        a. Server sends it public and certificate authority 
        b. Client uses the provided public key and certificate authority to validate authenticity of server
3. Public Key and Shared Session key exchange
        a. Client sends a message to server containing pre-master key secured using public key of server
        b. Pre-Master key is used to derive session key which is then used to encrypt subsequent messages
4. Finished Message
        a. Client and server send message to each other encrypted using shared session key 