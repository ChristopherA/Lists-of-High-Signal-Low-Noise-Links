# #LinkedDataProofs #JSONLD

(Orginal: https://github.com/ChristopherA/Lists-of-High-Signal-Low-Noise-Links/blob/master/LinkedDataSignatures-JSONLD.md )

# Status & Copyright

Stub 0.0.0. Raw bookmarks, minimal organizing.

For information on this versioning scheme, see [Status & Versioning].

Copyright ©️2020 by Christopher Allen, and is shared under [CC-BY-SA-4.0](./LICENSE-CC-BY-SA-4.0.md) open-source license. See this repo's README.md for more details.

# #LinkedDataProof (aka JSON-LD Signature 1.1)

* Current reference implementation
    * https://github.com/digitalbazaar/jsonld-signatures
    * [security-vocab maintained by W3C CCG](https://github.com/w3c-ccg/security-vocab)

* JavaScript implementation
    * [Verifiable Credentials](https://github.com/digitalbazaar/vc-js)
    * [Secp256k1 ES256K](https://github.com/decentralized-identity/lds-ecdsa-secp256k1-2019.js)
    * [Secp256k1 ES256K-R (ethereum / bitcoin)](https://github.com/decentralized-identity/EcdsaSecp256k1RecoverySignature2020)
    * [Secp256k1 Keypair](https://github.com/digitalbazaar/secp256k1-key-pair)
    * [Ed25519 and RSA](https://github.com/digitalbazaar/crypto-ld)
    * [JWS / JWK](https://github.com/w3c-ccg/lds-jws2020)
    * [GPG](https://github.com/transmute-industries/lds-gpg2020)
    * [JCS / No LD-Cannonicalization](https://github.com/decentralized-identity/JCSJsonWebSignature2020)
    * [Old RsaSignature2017](https://github.com/transmute-industries/RsaSignature2017)
    * [Old Ed25519Signature2018](https://github.com/transmute-industries/Ed25519Signature2018)
    * [Old EcdsaKoblitzSignature2016](https://github.com/transmute-industries/EcdsaKoblitzSignature2016)
    * [Old EcdsaKoblitzSignature2016](https://github.com/transmute-industries/EcdsaKoblitzSignature2016)

* Java implementation
    * An active work-in-progress Linked Data Proofs from Danube Tech
        * https://github.com/WebOfTrustInfo/ld-signatures-java
        > implementation of the following cryptographic suites:
        > * Ed25519Signature2018
        > * EcdsaSecp256k1Signature2019
        > * RsaSignature2018
        > Highly experimental, incomplete, and not ready for production use! Use at your own risk!
    * Related: an active work-in-progress implementation of the Verifiable Credentials data model from Danube Tech
        * https://github.com/danubetech/verifiable-credentials-java
        > Not ready for production use! Use at your own risk! Pull requests welcome.

* Go implementation
    
* [Aries Framework Go](https://github.com/hyperledger/aries-framework-go)
    
* Rust implementation
    
*     
    
* C++ implementation
    * Partial or in-progress
    * JSON-LD Implementation for C++ (Digital Contract Design). Currently in progress, partial as it currently it only supports the expand(), toRdf() and normalize() functions.
        * https://github.com/dcdpr/jsonld-cpp

* Unknown Status, presumed out-of-date
    
* https://github.com/digitalbazaar/rdf-canonize-native
    
* Out-of-Date (possibly uses Linked Data Signatures 1.0) or Deprecated
    * Linked Data Signatures 1.0 Spec: https://w3c-dvcg.github.io/ld-signatures/
    * Linked Data Proofs 1.0 Spec: https://w3c-dvcg.github.io/ld-proofs/
    * JSON-LD Playground https://json-ld.org/playground/
    * Verifiable Credential Playground https://w3c-vc.github.io/playground/
    * Original 1.0 java implemention, does not support 1.1
        * https://github.com/jsonld-java/jsonld-java

# #JSONLD

* Current "Candidate Recommendation" for JSON-LD 1.1 (next and final step is "Recommendation")
    * JSON-LD 1.1 - A JSON-based Serialization for Linked Data (2020, 16 March)
        * https://www.w3.org/TR/json-ld/
    * JSON-LD 1.1 Processing Algorithms and API
        * https://www.w3.org/TR/json-ld-api/
    * All other drafts:
        * https://json-ld.org/spec/

* Other sites
    * [jsld.org](https://jsld.org/)

* Out-of-Date JSON-LD 1.0 specs
    * JSON-LD Implementation Report (2015, April 7 for JSON-LD 1.0)
        * https://json-ld.org/test-suite/reports/#instructions-for-submitting-implementation-reports

