# SETTLENET Release Note
Version: 0.12.0  
Commit hash:  aabc7ed  
Release Date:  11 March, 2020  
[GUI Download](https://github.com/cryptogarageinc/settlenet-uitest/releases/tag/0.12.0-demo%2Baabc7ed)  

## New Features
* No change

## Improvements
* #1235 TradeHistory and DownloadTradeHistory  
  - Add "taker/maker" field
  - Change field name "Side" to "Buy/Sell"  
* #1253 Change "Done" status to "Settled" in Order and TradeHistory
* #1211 Add ChatRoomID and OrderID in parameters of following push notifications
  - Message_FINISH_WAITING_FOR_CONFIRMATION
  - Message_FINISH_SEND_TRANSACTION
  - [NEW] Message_FAIL_TRADE

* #1200 Implement an exclusive control function to call SendScriptSig and SendInvalidProposalTx only once.	
* #1213 Implement a validation check of passing ScriptSig by Taker

## Bug Fixes
* #1241 Password validation on Login windows in following cases  
  - When input in the password confirmation input area before the password input area
  - When change the input contents in the password input area

## Operations
* No change
