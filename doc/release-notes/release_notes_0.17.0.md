# SETTLENET Release Note
Version: 0.17.0  
Commit hash:  c98e46f
Release Date:  5 May, 2020  
[GUI Download](https://github.com/cryptogarageinc/settlenet-uitest/releases/tag/0.17.0-demo+c98e46f)

## New Features
* Add Signer service to sign JPYS MultiSig transaction  
  Endpoint: demo-signer.dev-settlenet.io:443

## Improvements
* 	#1425 Add a validation for the max number of txin (100 each per counterparty)
* 	#471 Process 2 confirmations notice by sub-system and keep locking UTXO even if waiting for 2 confirmations is timeout. 
* 	#1480 Add **bearer** in authorization token  
    "authorization": "{token}" -> "authorization": "**bearer** {token}"  


## Bug Fixes
* #1338 Logout failure due to TCP Read Failed

## Operations
* No change
