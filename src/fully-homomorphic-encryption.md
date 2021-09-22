# Fully Homomorphic Encryption (FHE)
=====================================

Homomorphic Encryption cryptosystem is a cryptosystem whose decryption is a morphism. 
```
Decrypt(a*b) = Decrypt(a) * Decrypt(b)
```

Homomorphic Encryption cryptosystem allows operate on ciphertexts without decryption.

It ensures end-to-end semantically secure, which is ensuring security against honest but curious adversaries. 

Different from confidential computing, FHE takes a software-based data encryption/protection.

Since FHE does not perform computational processing in Trusted Execution Environment (TEE), and unauthorized access or modification of data and application code during processing might occur. 
Thus, FHE does not support application code integrity nor code confidentiality.



