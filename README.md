#  Ethereum Lottery Smart Contract

This is a simple **Ethereum-based Lottery smart contract** built using **Solidity**. Participants can enter the lottery by sending ETH, and a random winner is selected using `keccak256`. The contract demonstrates core concepts like payable functions, modifiers, array management, and randomness simulation on-chain.

---

##  Tech Stack

- **Solidity** (Version: 0.4.x / 0.8.x)  
- **Remix IDE**   
- **Ethereum** (Testnets like Rinkeby, Sepolia, or Local Blockchain)  
- **Metamask** (for wallet integration)

---

## 🚀 Features

- ✅ Users can enter the lottery by sending ETH
- ✅ Only the contract manager can pick a winner
- ✅ Winner is selected using a pseudo-random method (`keccak256`)
- ✅ Funds are transferred to the winner automatically
- ✅ Contract resets after each round

