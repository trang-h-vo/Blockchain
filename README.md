## Bitcoin transactions in Script & Python
- `Generate keys and addresses`: P2PKH, P2SH, non-standard address, P2SH(P2WPKH) or nested P2WPKH.
- `Transactions`: Pay to address and spend an output containing different scripts, including: P2PKH, P2SH, MultiSignature, non-standard transactions and Segwit.
#### Library:
https://github.com/karask/python-bitcoin-utils
#### Tools:
- Blockchain explorer: https://blockstream.info/testnet/ and https://blockstream.info/
- Broadcasting transaction: https://blockstream.info/testnet/tx/push

## Ethereum smart contracts in Solidity

#### Smart contracts:
- `Simple Faucet`: Anyone can pay the contract to increase the contract's balance. Anyone can withdraw from the contract with a max amount being a variable that you specify.
- `Augmented Faucet`: Add max number of users to withdraw, specify the contract owner, function to reset the user list to allow new users to withdraw.
- `Blind Vickrey Auction`: Main properties include: Only a number of users can participate; Only owner can call the winner, when max_users have bid; The highest bidder wins the auction but pays the second best price; The winner get marked as "winner" inside the smart contract and everyone can see it; The losers must be reimbursed; The contract owner can reset everything and open the same contract again for another auction; and so on.
- `Hash Your Bid`: A complementary smart contract for the bidder to hash their bid in a Blind Vickrey Auction.

#### Tools:
- Solidity documents: https://solidity.readthedocs.io/en/v0.7.4/
- Wallet: Metamask web browser extension
- Test net: Ropsten Test Network
- Solidity Compiler & contract deployment: Remix IDE at https://remix.ethereum.org/ 
