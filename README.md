# Proveably random Raffle Contracts

## About

This code is to create a proveably random smart contract lottery.

## How it works?

1. Users can enter by paying for a ticket
    1.The ticket fees are going to go to the winner during the draw
2. After X period of time, the lottery will automatically draw a winner
    1. And this will be done programatically
3. Using Chainlink VRF & Chainlink Automation
    1.VRF for a randomness
    2.Automation for a time-based trigger

## Tests!

1. Write some deploy scripts
2. Write our test
    1. Work on a local chain
    2. Forked Testnet
    3. Forked Mainnet