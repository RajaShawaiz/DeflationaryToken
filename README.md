# DeflationaryToken

Updated Deflationary Token with latest Solidity 0.8.18 support.

I will try to update the code and documentation on regular bases. If you find it useful, Kindly star this repo and check out my other latest projects as well.


What is Deflationary Token?

A deflationary token is a type of cryptocurrency where the total supply of the token decreases over time. This is achieved through various mechanisms, such as burning a portion of the tokens during transactions, locking up tokens in a smart contract, sending tokens to charity or any other cause, providing liquidity to the token, or redistributing tokens to holders.

In a deflationary token system, the supply of tokens decreases over time, which can lead to an increase in the token's value. As the supply of tokens becomes scarcer, demand for the token may increase, which can drive up the price.

One common mechanism used to create deflationary tokens is to charge a small fee for each transaction, which is then burned or removed from circulation. This fee is often referred to as a "burn fee" or "transaction fee". Another mechanism is to lock up a portion of the tokens in a smart contract, where they are removed from circulation for a set period of time. The ultimate goal of the deflationary token is to increase the value of the token over time by implementing various deflationary mechanism such as burning, reflecting tokens to holders or providing liquidity.

Deflationary tokens can provide benefits to holders by increasing the value of their holdings over time. However, they can also have drawbacks, such as increased transaction fees due to the burn mechanism, and reduced liquidity due to the reduced supply of tokens. Additionally, the long-term sustainability of deflationary token systems may depend on the ability of the token issuer to continue providing incentives for holders to hold the token.


Here is an ERC-20 implementation of Deflationary System. The Token has following Taxes and you can adjust the tax percantages according to your own Tokenomics.

1) Auto-Liquidity pool fee (_liquidityFee = 30)
2) Rewards for holders fee(_taxFee = 20)
3) Auto Burn fee(_burnFee = 10)
4) Development Fee(_developmentFee = 20)

You can set all these fees according to your requirements. For example if _liquidityFee = 30, it means that there is 3% auto liquidity pool fee on each transaction. 




The documentation is not complete yet, I will add more details in coming days.





