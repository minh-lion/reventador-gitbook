# FAQ

### **Is providing liquidity on Saddle safe?**

Saddle has been [audited ](https://docs.saddle.finance/smart-contract-audit)by Certik, Quantstamp, and OpenZeppelin. We have passed security auditing on all Saddle smart contracts, from the following auditors.

| **AUDITOR**                             | **PROTOCOL AUDIT**                                                                               | **VIRTUAL SWAP AUDIT**                                                                                        |
| --------------------------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------- |
| [Certik](https://certik.io)             | [PASSED](https://github.com/saddle-finance/saddle-audits/blob/master/10-29-2020\_Certik.pdf)     | N/A                                                                                                           |
| [Quantstamp](https://quantstamp.com)    | [PASSED](https://github.com/saddle-finance/saddle-audits/blob/master/12-09-2020\_Quantstamp.pdf) | [PASSED](https://github.com/saddle-finance/saddle-audits/blob/master/03-31-2021\_Quantstamp\_VirtualSwap.pdf) |
| [OpenZepplin](https://openzeppelin.com) | [PASSED](https://blog.openzeppelin.com/saddle-contracts-audit/)                                  | N/A                                                                                                           |

_**Disclaimer**:_ Investing in cryptocurrencies is risky. Using Saddle as an exchange should be significantly less risky, but keep in mind there are still risks. Refer to the [risks section](https://docs.saddle.finance/asset-specific-risks) for more details.

### **Is arUSD stablecoin value safe?**

The arUSD Morphing mechanism hard pegged 1:1 with nUSD and USDC bro so it must be safe la.

### Are there time locks on the SDL tokens?

There are two time locks on the SDL Token:

1. A non-transfer period of 3 to 12 months
2. A vesting period of 2 to 3 years

The reason for time lock is to allow community members to earn more and deter short-term profit-seekers and mercenaries. More details [here](https://docs.saddle.finance/sdl-token).&#x20;

### Why use Axial instead of another exchange?

Most decentralized exchanges are modeled after Uniswap V2. They are excellent models for swapping most cryptocurrencies; however, they are not great for swapping stablecoins or other value-pegged assets. This is because the model allows for lots of slippage on the tokens being swapped.

If a stablecoin pool undergoes a large transaction in this traditional model, then the two coins may be taken off peg. For example, one may trade slightly lower than $1, around $0.95, while the other may trade slightly higher, around $1.05. With Axial, this risk is mostly mitigated. In this scenario, the coins would still be relatively close to their $1 peg, closer to $0.99 and $1.01 respectively.

### What are the fees for using Axial?

All swaps through Axial liquidity pools have a 0.04% fee. 75% of those fees (0.03%) are shared amongst the pool's liquidity providers. The other 25% of the fees (0.01%) is sent to Axial's treasury.

Fee for morphing arUSD stablecoin is free at the moment. Fees will be included in the future.

### **How does Saddle work?**

Saddle is an automated market maker (AMM) enabling trading between pegged value crypto assets. Saddle liquidity pools implement the StableSwap mathematical formula to reduce slippage and keep the market liquid. First introduced by [Curve](https://curve.fi/whitepaper), Stableswap is a hybrid algorithm. The Stableswap hybrid combines both Constant Product and Constant Sum models.

For more on AMMs and Stableswap check out the [AMM section](https://docs.saddle.finance/automated-market-makers).

### How do I get ARCA tokens?

The maximum supply of ARCA is 120 million. It will never exceed that amount.

### How is the ARCA token being distributed?

The maximum supply of ARCA is 120 million. It will never exceed that amount. The distribution of AXIAL is as follows:

* **70%** Liquidity Incentives and Community
* **20%** Treasury: Locked for 2 years and followed by 4 months vesting. The community will decide how to distribute these tokens in the treasury.
* **10%** Development Team: Locked for 4 months and followed by 12 months vesting

The tokens are scheduled to be released over the course of 2 years. More details can be found in [Arca Tokenomics](governance/arca-token.md).

### What can I do with ARCA tokens?

At the moment you can provide liquidity with your ARCA and use it for any snapshot votes that are taking place. That being said, governance structures are being discussed and developed, and will introduce staking and more robust voting mechanisms. Want to take part in these discussions? Feel free to join our [**Discord**](https://discord.gg/NPsxMhcCrS). In the near future, the ARCA can be staked to earn xARCA.







