## RFID Scanner Demo Web Application

Currently the webapp is pointing to the **EOS Jungle2.0 Testnet** hosting the RFID dApp.  The [RPi scanner software](https://github.com/EOSIoT/rfid-scanner-node) on your device must also be updated to submit data to the Jungle2.0 Testnet. `git pull` to update.

[View right now.](https://eosiot.github.io/rfid-html/)

This is a very simple HTML + javascript web application to pull RFID scanner data from the EOS blockchain rfid dApp.  It runs on any browser and uses the eosjs library to make API calls to the blockchain.

* The smart contract is running on account `eosiot12rfid` and is described [here](https://github.com/EOSIoT/rfid-contract).
* Open source project for building an RFID scanner device to submit data to the contract and become subsequently visible in this web-app is [here](https://github.com/EOSIoT/rfid-scanner-node).

