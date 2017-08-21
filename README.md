# ashurst-blockchain

Paperchain.io project


## task 1 - create a private blockchain

1. Install geth following [instructions](https://github.com/ethereum/go-ethereum/wiki/Installation-Instructions-for-Ubuntu)

2. Copy genesis.json to ~/.ethereum 

3. Execute `geth account new` in shell to create a new account.

4. Copy the address from output of step 2 and replace the address in alloc with it in the genesis.json

5. Execute `geth init ~/.ethereum/genesis.json` in shell

6. Execute `geth --mine --rpc --nodiscover --networkid 8259 console` in shell 
