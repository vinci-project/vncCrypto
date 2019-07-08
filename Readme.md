# vncCrypto

The vncCrypto package is a subsystem of cryptographic operations required when working with the Vncsphere blockchain.
The package is being developed using the python 3.6 language the pyQt 5.10.1 library to improve integration within the ecosystem.
Current supported features:
- Calculation of the Blake2B hash function (digest_size = 32);
- Generation of ECDSA keys using the secp256k1 elliptic curve;
- Electronic digital signature;
- Verification of digital signature;
- Creating a merkle tree using the Blake2B hash function (digest_size = 32);
- Static verification of digital signature of transactions used in Vncspehre;
- Helpers for using the Fernet cryptographic package.