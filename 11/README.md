# 11. Use a Tron Wallet to Execute a Smart Contract Call

## A screenshot of the accounts you created (account list) in ckb-cli.

 ![account_ss](https://user-images.githubusercontent.com/60573218/130331876-a9975b08-845a-4998-8ba7-a4efa53e84aa.png)


## A link to the Layer 1 address you funded on the Testnet Explorer.

    https://explorer.nervos.org/aggron/address/ckt1qyqg7f4j6z95ehej0fkf3wduuhmfyq7us7hsjwrdvp
    

## A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2.

 ![1](https://user-images.githubusercontent.com/60573218/130331893-edcdd432-0a31-4a72-bc4f-6c992dcbc933.png)


## A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2.

![2](https://user-images.githubusercontent.com/60573218/130331919-fea0d2f7-ba10-4c1e-9db3-8aa06675e31b.png)


## The transaction hash of the "Contract call" from the console output (in text format).

    0x3974ece2f3aaed28959a9a1ec01d589b7ad1f28cfc31c5c344d1cca3cd6c2697
    
## The contract address that you called (in text format).

    0xab309168027793ebFDb7327cB539c2cBDE146F86
    
## The ABI for contract you made a call on (in text format).

    [
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    }
   ]
  
  
## Your Tron address (in text format).

    TTTLypzkt8pq24GRFeyAERLLWpyuqp1tJh
