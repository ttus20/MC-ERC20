# ERC20 TOKEN PROJECT

Project: Create and Mint Token
The ERC20 or Ethereum Request for Comment number 20 is for creating interoperable tokens on the Ethereum Virtual Machine. The project requires executing in RemixEthereum with the use of the function of burning and transferring tokens.

## Description

For this project, you will write a smart contract to create your own ERC20 token and deploy it using HardHat or Remix. 
From your chosen tool, the contract owner should be able to mint tokens to a provided address and any user should be able to burn and transfer tokens.

## Getting Started

### Installing

* Go to Remix Ethereum
* Open a new solidity file to begin a clear file
* Make sure to have this at the beginning 

```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;
```

* Since this ERC20 uses OpenZeppelin this will require a specific code import

```
import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import "@openzeppelin/contracts/access/Ownable.sol";
```

### Executing program

* Run the given codes on the Remix IDE
* Compile the codes (.sol) on Remix Ethereum IDE
* After compiling in solidity compiler, go to deploy and run transaction
* Deploy the contract, the functions are already included when deploying
* Copy the link address and apply to the corresponding field


## Authors

Ghasutt Joshua   
https://github.com/ttus20
