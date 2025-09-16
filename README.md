
# Smart Contract Deployment Notebook

This notebook demonstrates a complete workflow for deploying and interacting with an ERC20 smart contract using Web3.py and Solcx.

Features
-	Securely encrypt and store a private key in .keystore.json.
-	Decrypt and load an Ethereum account.
-	Compile Solidity contracts with solcx.
-	Deploy contracts to a local RPC (HTTP/WebSocket).
-	Interact with the deployed ERC20 contract (mint, balance checks).
-	Subscribe to contract logs via WebSocket.

Requirements
-	Python 3.9+
-	Web3.py
-	py-solc-x
-	Local Ethereum RPC (e.g., Hardhat node, anvil)

Install dependencies:

`uv sync`

Usage
-	Run the notebook cells in order:
    -	Encrypt Key → saves .keystore.json.
    -	Load Account → decrypts and loads your account.
    -	Build Contract → compiles HateERC20.sol.
    -	Deploy Contract → deploys contract and returns address.
    -	Interact → check balance, mint tokens, and subscribe to events.
-	Update RPC endpoints if not using 127.0.0.1:8545.
