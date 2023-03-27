# Truffle-Enviroment
### Setup by @MaxflowO2
### Requirements
* nodejs and npm
```
sudo apt install nodejs npm -y
```
* npm dependacies
```
npm install
```
* setup .env
```
MNEMONIC = "12 word/private key"
INFURA_API_KEY = 
ETHERSCAN_API_KEY = 
BSCSCAN_API_KEY = 
FTM_API_KEY = 
POLY_API_KEY = 
AVAX_API_KEY = 
```
Contracts need to remain in ./contracts
```truffle deploy --network (network)``` command for deploying contracts
```truffle run verify (Contract name) --network (network)`` command for sending verified code to scans site (Binance or Etherium)

Networks configured:
* Developer (127.0.0.1)
* Ethereium
* Ethereium Goerli
* Optimism
* Optimism Goerli
* Arbitum
* Arbitum Goerli
* Polygon
* Polygon Mumbai
* Binance Smart Chain
* Binance Test Net
* Avalanche
* Avalanche Fuji, testnet
* Fantom
* Fantom Testnet
* Kava
* Kava Testnet
* Canto
* Canto Testnet
* Celo
* Celo Testnet
* Palm
* Palm Testnet
* Cronos Beta
* Cronos Beta Testnet
* BitTorrent
* Moonbeam

Boiler plate setup... do not delete Migrations.sol or 1_initial_migration.js

Current as of 27 Mar 2023

Pending updates:
* More chains configured
