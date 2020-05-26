# SETTLENET Release Note
Version: 0.17.2  
Commit hash:  d2889e4  
Release Date:  26 May, 2020  
[GUI Download](https://github.com/cryptogarageinc/settlenet-uitest/releases/tag/0.17.2-demo%2Bd2889e4)

## New Features
* No change

## Improvements
* Add the confirmation dialog to pre-check the connection with Ledger Nano S on Trader App.
* Add a logic to update the transaction status to Failed when the transaction is not signed in 5 minutes.
* UTXO Manager:  
The differences between previous version and new one are found in utxomanager_diff.patch.
  - Add Version to manage support/investigation/analysis for future.
  - Remove user_id and legal_entity_id to simplify request calls and strengthen security . (access_token already includes these information)
  - Remove validations to avoid using an inconvenient external file.  

* Signer:  
  Endpoint: Old ver=demo-signer.dev-settlenet.io:443, New ver=demo-grpc-gateway.dev-settlenet.io:443

  **Previous version**  
    package signer;  
    option go_package = "signer";  
  **New version**  
  package settlenet_grpc_gateway;  
  option go_package = "settlenet_grpc_gateway";  
 
  - Change the package name to make the service more generic.
  - Add JWT for enhanced security. (Requires access token in metadata as the same as other services)  

Both previous and new versions of Signer service are available in the demo environment in parallel for a while.

## Bug Fixes


## Operations
* No change
