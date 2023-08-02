link:: https://w3c-ccg.github.io/did-method-web/
tags:: #DID

- Example using an #Ethereum address
- ```json
  {
    "@context": ["https://www.w3.org/ns/did/v1", "https://w3id.org/security/suites/secp256k1recovery-2020/v2"],
    "id": "did:web:example.com",
    "verificationMethod": [{
        "id": "did:web:example.com#address-0",
        "type": "EcdsaSecp256k1RecoveryMethod2020",
        "controller": "did:web:example.com",
        "blockchainAccountId": "eip155:1:0x89a932207c485f85226d86f7cd486a89a24fcc12"
    }],
    "authentication": [
        "did:web:example.com#address-0"
    ]
  }
  ```
-