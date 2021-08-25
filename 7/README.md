# 7. Port an Existing Ethereum dApp to Polyjuice

## Video of the application running on Godwoken.

  https://youtu.be/WELJBJjbMIk


## Github code
  
  https://github.com/theyashmhatre/GuessAndWin_Dapp
  
  
## Transaction Hash

    0x5431d52a78468827b15f3464bf214742f8ab9f43abd8a15b8b8b645fc108c6d2
    
## Deployed contract Address

    0x5e420B066159C5D098f7B9f1e04541E708235e0b
    
## ABI of the deployed smart contract

    [
        {
            "inputs": [],
            "stateMutability": "payable",
            "type": "constructor"
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
            "name": "setBalance",
            "outputs": [],
            "stateMutability": "nonpayable",
            "type": "function"
        },
        {
            "inputs": [],
            "name": "getBalance",
            "outputs": [
                {
                    "internalType": "uint256",
                    "name": "",
                    "type": "uint256"
                }
            ],
            "stateMutability": "view",
            "type": "function"
        }
    ]
