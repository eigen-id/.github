# Eigen ID

## About

Eigen ID project is an experimental AVS solution to demostrate DID and Verifiable Credentials on Eigen layer, Currently the DID's are created with "did:elem:eigen" method.

## Testnet

Currently the project is runnning on Holesky testnet and Sidetree.js node service is running on locally system , need to deploy it to cloud for public testing. If someone wants to test it, he/she will need to run the sidetree.js on local system 

## Main repositories

- Sidetree.js : This repository contains node service which is responsible for  DID operations (create, resolve, update), Verifiable Credentials operations (create, revoke, verify)
- vade-eigen: Rust based sdk to provide interfaces for DID and Verifiable Credential operations
- id-operator: Rust based operator implementation , inspired from `hello-world` AVS project
- sidetree-avs-contracts: Solidity contracts for AVS integration with Sidetree DID service and `vade-eigen` SDK
   - contract address on holesky : 0xbc8fa26de333f73c0b8aadaf5274bc3092d81c51 


## Suggestion

Need Input and suggestions to implement a proper AVS and what functionalities it should have. Currently the operator is just resolving the DID's and printing the DID doc. 
