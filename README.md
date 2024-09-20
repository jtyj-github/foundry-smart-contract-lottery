# Provably Random raffle contracts

## What does it do?

1. Users can enter by paying for a raffle ticket
    1. The ticket fees are going to go to the winner during the draw
2. After X amount of time, the lottery will automatically draw a winner from the existing pool of players
    1. This is done programmatically to avoid bias
3. Using Chainlink VRF and Automation
    1. Chainlink VRF -> Randomness
    2. Chainlink Automation -> Time based triggers

## Tests

1. Write deploy Scripts
    1. Note, this will not work on zkSync as of now
2. Write Tests
    1. Local Chain
    2. Forked Testnet
    3. Forked Mainnet