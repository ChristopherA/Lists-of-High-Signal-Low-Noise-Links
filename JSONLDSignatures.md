# #JSONLDProofs #JSONLD

# Status & Copyright

Stub 0.0.0. Raw bookmarks, minimal organizing.

For information on this versioning scheme, see [Status & Versioning].

Copyright ©️2020 by Christopher Allen, and is shared under [CC-BY-SA-4.0](./LICENSE-CC-BY-SA-4.0.md) open-source license. See this repo's README.md for more details.

# #LinkedDataProof (aka JSON-LD Signature 1.1)

* Current reference implementation
    * https://github.com/digitalbazaar/jsonld-signatures
    * Issue about security context: https://github.com/digitalbazaar/jsonld-signatures/issues/82
    * Does this support secp256k1 keys?

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

* C++ implementation
    * Partial or in-progress
    * JSON-LD Implementation for C++ (Digital Contract Design). Currently in progress, partial as it currently it only supports the expand(), toRdf() and normalize() functions.
        * https://github.com/dcdpr/jsonld-cpp

* Unknown Status, presumed out-of-date
    * https://github.com/digitalbazaar/rdf-canonize-native

* Out-of-Date (possibly uses Linked Data Signatures 1.0) or Deprecated
    * Linked Data Signatures 1.0 Spec: https://w3c-dvcg.github.io/ld-signatures/
    * Linked Data Proofs 1.0 Spec: https://w3c-dvcg.github.io/ld-proofs/
    * Security Context https://github.com/w3c-dvcg/security-vocab
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
* Out-of-Date JSON-LD 1.0 specs
    * JSON-LD Implementation Report (2015, April 7 for JSON-LD 1.0)
        * https://json-ld.org/test-suite/reports/#instructions-for-submitting-implementation-reports

