# Risks

#### Risk

Providing liquidity to Saddle is highly risky. Before using the protocol, we highly recommend [reading the code](https://github.com/saddle-finance/saddle-contract) and understanding the risks involved with being a Liquidity Provider (LP) and/or using the AMM to trade pegged value crypto assets.

#### Audits

The Arca smart contracts were forked from [Saddle Finance](https://saddle.finance), which has been thoroughly audited by [OpenZeppelin, Quantstamp, and Certik](https://github.com/Snowball-Finance/axial-protocol). None of the smart contracts main feature source code for was changed.

\
Please keep in mind that security audits don’t completely eliminate risks. Do not supply assets that you cannot afford to lose by using Axial or any other AMM as a liquidity provider.\
Using Axial to exchange assets is significantly less risky, but there is always risk when utilizing our contracts.

#### Admin keys

Saddle's admin keys are controlled by a 3/5 Gnosis Safe multisig. The signers are Mariano Conti, Kain Warwick, DegenSpartan, Klim K, and Damir Bandalo. This multisig has capabilities to pause new deposits and trades in case of technical emergencies. Users will always be able to withdraw their funds regardless of new deposits being paused. The multisig can also change the swap/withdrawal fees and the per pool/account deposit limits.

#### Permanent loss of a peg

If one of the assets in a pool significantly depegs, it will effectively mean that pool liquidity providers will be left holding only that asset.
