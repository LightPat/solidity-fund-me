# Fund Me

A Solidity smart contract project from the **Cyfrin Updraft Solidity Smart Contract Developer** course, implementing a crowd-funding style contract using Chainlink Price Feeds for USD-based funding.
The FundMe contract allows users to:
- Fund the contract with ETH (minimum $5 USD equivalent)
- Convert ETH to USD using Chainlink's decentralized price oracle
- Allow only the owner to withdraw funds
- Track funders efficiently with an array and mapping

The project includes two contracts:
- `FundMe` – Main crowdfunding-style contract that allows users to send ETH (with a minimum USD equivalent), tracks funders, and enables only the owner to withdraw all funds safely.
- `PriceConverter` – Library for converting ETH amounts to USD using Chainlink's decentralized price feed, handling safe math and precise decimal scaling.

### Testnet Deployment (Sepolia)

Live Contract (Sepolia):
View on Etherscan 0x6780b1Ea74788a868D5BA5D4A28c6F1431d22404