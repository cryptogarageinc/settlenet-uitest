# SETTLENET Release Note
Version: 0.14.0  
Commit hash:  12af27d (internal release only)  
Release Date:  15 April, 2020  
GUI Download not available

## New Features
* No change

## Improvements
* 	#1425 Add a validation for the max number of txin (100 each per counterparty)
* 	#471 Process 2 confirmations notice by sub-system and keep locking UTXO even if waiting for 2 confirmations is timeout. 
* 	#1480 Add **bearer** in authorization token  
    "authorization": "{token}" -> "authorization": "**bearer** {token}"  

## Bug Fixes
* #1338 Logout failure due to TCP Read Failed

## Operations
* No change
