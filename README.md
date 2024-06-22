# metacraft-ethereum-project

# Code outline
- This project contains
-  Public variables
-  Mapping
-  Mint function
-  Burn function

# Description
It is a smart contract that implements simple token system with the help of mint and burn functions

# Features
- Variables to store token details
- tokenName
- tokenAbbrv
- totalToken
- Mapping
- Mint
- Burn


# Functions
# Mint
- solidity function mint(address _address, uint _val) public
- it creates new tokens

# Burn
- function burn(address _address, uint _val) public
- it destroy tokens
- ensures that wallet address has least tokens before burning

# Deployment
- Solidity 0.8.18 installed
- Compile contract using solidity compiler
- Deploy contract to preffered ethereum network

# Usage
- Use mint function to create new tokens
- Use burn function to destroy tokens 

# Project by
- Shaswat Anand
