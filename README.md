## Proveably Random Raffle Contract
 
## About

This code is to create a provably random smart contract lottery.

## What we want it to do

1. Users should be able to enter the raffle by paying for a ticket. The ticket fees are the price the winner receives.
2. The lottery should automatically and programatically draw a winner after a certain period.
3. Chainlink VRF should generate a provably random number.
4. Chainlink automation should trigger the lottery draw regularly.

## Testing Raffle contract
1. Write deploy scripts
2. Write test scripts

# Usage

## Start a local node

```
make anvil
```

## Library

Installing the chainlink library, . 

```
make install
```

## Deploy

This will default to your local node. You need to have it running in another terminal in order for it to deploy.

```
make deploy
```
## Casting an account

```
cast wallet import account1 --interactive
```
## Deploy to sepolia-testnet

```
make deploy-sepolia
```
