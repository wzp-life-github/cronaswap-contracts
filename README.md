# CronaSwap Smart Contracts
This repo contains all of the smart contracts used to run [CronaSwap](https://cronaswap.org).

## Deployed Contracts - Mainnet 
CronaToken: `0xadbd1231fb360047525BEdF962581F3eee7b49fe`

MasterChef: `0x77ea4a4cF9F77A034E4291E8f457Af7772c2B254`

Router address: `0xcd7d16fB918511BF7269eC4f48d61D79Fb26f918`

Factory address: `0x73A48f8f521EB31c55c0e1274dB0898dE599Cb11`


## Deployed Contracts - Testnet3 
CronaToken: `0xf7266fBB31D353099837D6bEfa5E7F197a7cfcA0`

MasterChef: `0xd34dd7E16af11216F3478230e922A9E5289F1AE4`

Router address: `0x4a719c7fA89B5f44b850346F4CC012c27dE4730a`

Factory address: `0xa3899228D88Cd1D706BD7aA7cF105041DF6511f8`


## Running
These contracts are compiled and deployed using [Hardhat](https://hardhat.org/). They can also be run using the Remix IDE.

## Accessing the ABI (Temporarily not uploaded to NPM)
If you need to use any of the contract ABIs, you can install this repo as an npm package with `npm install --dev @cronaswap/cronaswap-contracts`. Then import the ABI like so: `import { abi as ICronaSwapPairABI } from '@cronaswap/cronaswap-contracts/artifacts/contracts/interfaces/ICronaSwapPair.sol/ICronaSwapPair.json'`.

## Attribution
These contracts were adapted from these Uniswap repos: [uniswap-v2-core](https://github.com/Uniswap/uniswap-v2-core), [uniswap-v2-periphery](https://github.com/Uniswap/uniswap-v2-core), and [uniswap-lib](https://github.com/Uniswap/uniswap-lib).
