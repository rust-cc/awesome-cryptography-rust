# Awesome Cryptography Rust
*Collect libraries and packages about cryptography in Rust.*

- [Collection Library](#Collection library)
- [Symmetric](#Symmetric cryptography)
- [Public-key / Asymmetric](#Public-key Cryptography / Asymmetric Cryptography)
- [One-way Hash Function](#One-way Hash Function)
- [Message Authentication Code (MAC)](#Message Authentication Code)
- [Digital Signature](#Digital Signature)
- [Rseudo Random Number Generator (PRNG)](#Rseudo Random Number Generator)
- [Zero-Knowledge Proofs (ZKP)](#Zero-Knowledge Proofs)
- [Homomorphic Encryption (HE)](#Homomorphic Encryption)
- [Secure Multi-party Computation (MPC)](#Secure Multi-party Computation)
- [Theorem]()
- [Math]()

## Cryptography
#### Collection library
- [mesalink](https://github.com/mesalock-linux/mesalink) MesaLink is a memory safe and OpenSSL-compatible TLS library.
- [ring](https://github.com/briansmith/ring) Safe, fast, small crypto using Rust. (curve25519, aes-gcm, sha-256, sha-384, sha-512, hmac, hkdf, pbkdf2, p-256, p-384, x25519, chacha20-poly1305, ed25519).
- [rust-crypto](https://github.com/DaGenix/rust-crypto) A (mostly) pure-Rust implementation of various cryptographic algorithms.
- [rustls](https://github.com/ctz/rustls) A modern TLS library in Rust.
- [sodiumoxide](https://github.com/sodiumoxide/sodiumoxide) Sodium Oxide: Fast cryptographic library for Rust (bindings to libsodium).

#### Symmetric cryptography
- [block-ciphers](https://github.com/RustCrypto/block-ciphers) Collection of block cipher algorithms written in pure Rust. (AES, Blowfish, DES + 3DES, Kuznyechik, Magma, RC2, Twofish).
- [stream-ciphers](https://github.com/RustCrypto/stream-ciphers) Collection of stream cipher algorithms.

#### Public-key Cryptography / Asymmetric Cryptography
###### RSA
- [RSA](https://github.com/RustCrypto/RSA) RSA implementation in pure Rust. (PKCS1v1.5: Encryption & Decryption, Sign & Verify)

###### DH
- [x25519-dalek](https://github.com/dalek-cryptography/x25519-dalek) Fast and efficient ed25519 signing and verification in Rust. (dalek)

#### One-way Hash Function
- [hashes](https://github.com/RustCrypto/hashes) Collection of cryptographic hash functions written in pure Rust. (sha1, sha2, sha3, md4, md5, BLAKE2, RIPEMD-160, RIPEMD-320, GOST94, Grøstl, Streebog, Whirlpool)
- [tiny-keccak](https://github.com/debris/tiny-keccak) A tiny implementation of SHA-3, SHAKE, Keccak, and sha3sum in rust.
- [poseidon252](https://github.com/dusk-network/poseidon252) Starkad and Poseidon: New Hash Functions for Zero Knowledge Proof Systems.

#### Message Authentication Code
- [MACs](https://github.com/RustCrypto/MACs) Message authentication code algorithms written in pure Rust. (CMAC, DAA, HMAC, PMAC)

#### Digital Signature
###### ECDSA
- [curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek) A pure-Rust implementation of group operations on Ristretto and Curve25519. (dalek)
- [ed25519-dalek](https://github.com/dalek-cryptography/ed25519-dalek) Fast and efficient ed25519 signing and verification in Rust. (dalek)
- [signatures](https://github.com/RustCrypto/signatures) Cryptographic signature algorithms (e.g. ECDSA, Ed25519).
- [rust-secp256k1](https://github.com/rust-bitcoin/rust-secp256k1) Rust language bindings for Bitcoin secp256k1 library. (rust-bitcoin)
- [libsecp256k1-rs](https://github.com/sorpaas/libsecp256k1-rs) Pure Rust Implementation of secp256k1. (Wei Tang)
- [Jubjub](https://github.com/zkcrypto/jubjub) Implementation of the Jubjub elliptic curve group.
- [BLS12-381](https://github.com/zkcrypto/bls12_381) Implementation of the BLS12-381 pairing-friendly elliptic curve group.
- [bls](https://github.com/w3f/bls) Aggregatable BLS sigantures. (w3f)

###### Threshold Signature & Multi Party Signatures
- [multi-party-ecdsa](https://github.com/KZen-networks/multi-party-ecdsa) Rust implementation of {t,n}-threshold ECDSA (elliptic curve digital signature algorithm).
- [multi-party-schnorr](https://github.com/KZen-networks/multi-party-schnorr) Rust implementation of multi-party Schnorr signatures over elliptic curves.
- [threshold_crypto](https://github.com/poanetwork/threshold_crypto) A pairing-based threshold cryptosystem for collaborative decryption and signatures.


#### Rseudo Random Number Generator
- [rand](https://github.com/rust-random/rand) A Rust library for random number generation.

#### Zero-Knowledge Proofs
- [bulletproofs](https://github.com/dalek-cryptography/bulletproofs) A pure-Rust implementation of Bulletproofs using Ristretto.
- [bellman](https://github.com/zkcrypto/bellman) zk-SNARK library. (zcash - librustzcash).
- [bulletproofs](https://github.com/KZen-networks/bulletproofs) Bulletproof Rust implementation for Aggregated Range Proofs over multiple elliptic curves.
- [rust-secp256k1-zkp](https://github.com/mimblewimble/rust-secp256k1-zkp)  ZKP fork for rust-secp256k1, adds wrappers for range proofs, pedersen commitments, etc
- [ZoKrates](https://github.com/Zokrates/ZoKrates) A toolbox for zkSNARKs on Ethereum
- [sonic](https://github.com/ebfull/sonic) a protocol for quickly verifiable, compact zero-knowledge proofs of arbitrary computations.
- [Dusk-Zerocaf](https://github.com/dusk-network/dusk-zerocaf) Fast, efficient and bulletproof-friendly cryptographic operations.

#### Homomorphic Encryption

#### Secure Multi-party Computation

#### Others
- [nalgebra](https://github.com/rustsim/nalgebra) Linear algebra library for Rust.
- [librustzcash](https://github.com/zcash/librustzcash) Rust-language assets for Zcash. (bellman-zk-SNARK, pairing-elliptic curves)
- [zexe](https://github.com/scipr-lab/zexe) Rust library for decentralized private computation.
- [RustySecrets](https://github.com/SpinResearch/RustySecrets) A Rust implementation of threshold Shamir's secret sharing.
- [Double Ratchet](https://github.com/sebastianv89/double-ratchet) Pure Rust implementation of the Double Ratchet algorithm. (communicate securely).
- [molasses](https://github.com/trailofbits/molasses) A Rust implementation of the Message Layer Security group messaging protocol.
- [KDFs](https://github.com/RustCrypto/KDFs) Collection of Key Derivation Functions written in pure Rust.
- [PAKEs](https://github.com/RustCrypto/PAKEs) Password-Authenticated Key Agreement protocols. (SRP, spake2)
- [password-hashing](https://github.com/RustCrypto/password-hashing) Password-based key derivation functions. (PBKDF2, scrypt)
- [rcmixed](https://github.com/rust-cc/rcmixed) Mixed cryptosystem. inspired by PGP.
- [kms-secp256k1](https://github.com/KZen-networks/kms-secp256k1) Multi Party Key Management System (KMS) for Secp256k1 Elliptic curve based digital signatures.
- [MLSAG](https://github.com/crypto-rs-go/MLSAG) Multilayered Linkable Spontaneous Anonymous Group, This particular version leverages Ristretto255.
- [vdf](https://github.com/poanetwork/vdf) An implementation of Verifiable Delay Functions in Rust.
- [schnorrkel](https://github.com/w3f/schnorrkel) Schnorr VRFs and signatures on the Ristretto group.


## Contribute
Contributions are most welcome

## License
[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
