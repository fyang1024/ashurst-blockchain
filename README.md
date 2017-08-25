# ashurst-blockchain

Paperchain.io project


## task 1 - create a private blockchain

1. Install geth following [instructions](https://github.com/ethereum/go-ethereum/wiki/Installation-Instructions-for-Ubuntu) 

2. Execute `geth --datadir /path/to/data init /path/to/geth.json` in shell

3. Execute `geth --datadir /path/to/data --mine --rpc --networkid 201708 console` in shell 

## task 2 - Parity/light-client development

1. Install parity

2. update peers.txt to reflect the enode URLS running geth

2. Execute `parity --chain /path/to/parity.json --reserved-peers /path/to/peers.txt` in shell
