# Risq Protocol Frequently Asked Questions

Below is a compilation of the most commonly asked questions about Risq Protocol's ecosystem. If you still have any questions fter reading through the FAQ please reach out on [Discord](https://discord.gg/nWZDznS4) or [Telegram](https://t.me/risqprotocol).

## THE RISQ TOKEN

What is the RISQ token contract address? 
- [0xd9b4806a672a8da6666c9d9d4b3b30ef6311611d](https://www.bscscan.com/token/0xd9b4806a672a8da6666c9d9d4b3b30ef6311611d)

Why is a token needed?
- You need RISQ to buy a staking lot that earns settlement fees and for Protocol's governance purpose. More use cases will arise after the release of the Risq Protocol Hedge Fund Terminal.

What is the total supply?
- Total supply is **100,000,000 RISQ**. This is the total amount of RISQ that will ever exist. 

What are the benefits of holding RISQ?
- RISQ holders will be able to buy a staking lot. Also, in the future, it will be the way to delegate governance of the Risq Protocol to the community of token holders. TBD

Should I buy RISQ?
- Did you do your own research? To know if you did, can you answer these questions?
  - What is an option? What is Call option? What is Put option?
  - When do option buyers earn money? 
  - Who is selling options in RISQ?
  - Who are liquidity providers? 
  - How much money can liquidity providers lose?
  - What are the benefits of holding RISQ?
  - What are the risks of holding RISQ?

## TRADING RISQ / BUYING RISQ  

How Can I buy/sell $RISQ?
- Currently $RISQ is available only on decentralized exchanges. You can purchase/sell Risq Protocol at:
  - [Pancake Swap](https://exchange.pancakeswap.com/#/swap)
  - $RISQ can also be purchased/sold through the Bonding Curve in the [RISQ TOKEN](https://options.risq.capital/#/stake) page.
  - Each time $RISQ is purchased through the Bonding Curve, the price of $RISQ on the curve increases by a fixed value. This fixed value is set to 0.00000000001 BNB and can never be changed.
  - Each time $RISQ is sold through the Bonding Curve, the price of $RISQ on the curve decreases by a fixed value. This fixed value is set to 0.00000000001 BNB and can never be changed. 
  - Note: There is also a 10% swap fee for selling $RISQ on the bonding curve that is distributed to the Risq Protocol Development Fund.

Will you list $RISQ on Centralized Exchanges?
- There are currently no plans to list $RISQ in a Centralized Exchange.
- If a Centralized Exchange chooses to list $RISQ that would be at their discression. 

What is the price oracle for options pricing and settlement?
- Risq Protocol uses ChainLink oracles for the market prices of underlying assets. Currently Implied Volatility (IV) is set manually but is expected to become automated using an IV oracle from ChainLink once available.

## OPTIONS ON RISQ PROTOCOL

How are options on Risq Protocol priced?
- put options pricing formula: premium = sqrt(period) * IV * strike / price.
- call options pricing formula: premium = sqrt(period) * IV * price / strike.
- Note: there is also a 1% fee on all options purchased through the protocol that is paid to Risq staking lots.

When is my option in profit?
- A user will make a profit from option trading once the underlying asset's price exceeds the sum of the strike price plus the fee associated with purchasing the option.

When can I exercise my option?
- Anytime your option is in the money (ITM) you can exercise your option. 
- A call option is ITM once the underlying asset's price is higher than the strike price of the option.
- A put option is ITM once the underlying asset's price is lower than the strike price of the option. 
- NOTE: Users pay the fee for purchasing the option up front. Thus, ITM options are not profitable until the underlying asset's price is higher than the strike price + fee paid. Despite this, users should still exercise unprofitable ITM options before expiry as it will at least partially pay back the fee paid up front.

Exercising my options.
- If your option is Out of The Money (OTM) you will not be able to exercise it since there is negative value in the option (i.e. you would have to pay more coin to exercise).
- If your option is In The Money (ITM) at any time during the option's duration, you can manually exercise the option on the [Options Desk] tab.
- There is no option to partially exercise the option. You must exercise an option in its entirety when you decide to do so.

Do I need the capital to buy the underlying when exercising my options?
- No, Risq Protocol options do not pay out the underlying asset, rather just the difference between the price at the time of exercising and the strike price. The only requirement is enough gas to exercise the option. 

Why does my breakeven price keep changing?
- The price of the option is denominated in BNB and is not translated into USD at the time of purchase. So as the price of BNB changes throughout the duration of your option, so to does the price of what you paid for the option (and thus your breakeven point). E.g. If you pay 0.1021 BNB ($40) for an option and the price increases 10% during the contract, your breakeven price will go up $4 to reflect the higher price of BNB. 

What happens when my option expires?
- Risq Protocol options do not auto exercise. If your option is Out of The Money (OTM) at expiry, nothing will happen since there is no value in exercising the option. If you are In The Money (ITM) you will have to manually exercise the option before it expires or forego any potential upside that you might have received otherwise.

How are options priced? 
- Option purchasers pay a premium and fixed fee (currently 1%) on top of the strike price that is pre-determined prior to purchase. Given the flexibility of Risq Protocol options, this premium is variable but directly related to: 
  - The duration of the option is set by the option purchaser.
  - The strike price is set by the option purchaser.
  - Underlying asset pricing is obtained from ChainLink Oracles.
  - Implied volatility is currently obtained from Skew and manually updated but a plan to transition to ChainLink Oracles once they are implemented.

## BECOMING A LIQUIDITY PROVIDER (LP)

What is a liquidity pool?
- A Liquidity pool is the aggregation of tokens that are locked into a smart contract. Liquidity pools are used to facilitate the trading of the asset(s) within the pool and provide deep levels of liquidity. 

What is providing liquidity?
- Providing liquidity on Risq Protocol will require a user to deposit tokens into one of the options liquidity pools. Risq Protocol utilizes an innovative bi-directional pool design (described below) that allows for a single liquidity pool to provide depth to both put and call option purchasers.

What are the benefits of providing liquidity?
- By providing liquidity, a user is contributing to the usability and tradability of Risq Protocol options. The liquidity provided is drawn upon by options purchasers to collateralize their trade. Once an option expires/executes, the liquidity that was drawn to collateralize the option is returned to/partially removed from/wholly removed from the pool for future trading. The premiums paid for purchasing an option also accrue and are paid to liquidity providers. If the premiums paid are higher than the payouts to options holders, the liquidity providers will accrue more value in those tokens proportionate to their share of the pool. For providing liquidity, options will receive rewards in RISQ (coming soon). 

What are bi-directional pools?
- Risq Protocol's bidirectional liquidity pool design is unique and innovative in DeFi. The base asset that is deposited in the pool can be utilized simultaneously for both selling put and call options in an automated fashion. By doing so, liquidity providers do not have to 'guess' which way price will move in the next weeks or hedge liquidity provision on the long and short side. 

How do I add liquidity?
- Please refer to the Options Docs page for a [detailed walkthrough](https://github.com/risqprotocol/options-docs/blob/main/docs/Becoming_an_LP.md)
- NOTE: When providing liquidity, you are subject to a minimum 14 day lock-up period on your tokens. The purpose of this is to maintain stability in the liquidity pool for options buyers.

What are write tokens?
- Write tokens are LP tokens a liquidity provider will receive once the deposit tokens into the Risq Protocol liquidity pools.

How do I remove liquidity? 
- To remove liquidity will take *up to 14 days* from the day you last provided liquidity! 
- To withdraw: Once the 14 days has passed, you will need to navigate to the [WRITERS] page and under ///YOUR EARNINGS select WITHDRAW. By confirming the withdrawal, you will burn write tokens from your wallet and receive the corresponding tokens. 
- The earliest withdrawal date for write tokens sitting idle in your wallet will be displayed on the screen that pops-up when hit WITHDRAW on the [WRITERS] page.
- *Attention:* do not send write tokens to the contract address because you will lose your funds forever.

What is my risk exposure?
- Being a liquidity provider, you are short volatility. What this means is that if price movements are not too significant, liquidity providers have little risk exposure. However, despite providing liquidity to both put and call options, if a significant market move occurs the profits from deep in the money options will be paid for by the liquidity providers. By nature, puts and calls have limited downside, but on big market moves can have significant upside. If for example the price of Ethereum pumps $200 within a week, put options will be out of the money and only lose the fee they initially payed at the time of purchase. However, call options will be deep in the money and their profits (claim to ETH) will be funded by the liquidity pool.
- Liquidity providers can track their current profits/losses from providing liquidity on the [WRITERS] tab under ///YOUR EARNINGS. Here you will not only be able to observe your current profits or losses but also the upcoming Net Profit impact (to the pool and yourself) from all options if they were to expire at the current price of the underlying asset.

## STAKING LOTS

What is a staking lot?
- Staking lots represent a right to claim on the fees generated by Risq Protocol. 100% of settlement fees generated by the protocol are distributed among the staking lots holders. 

How many RISQ do I need for a staking lot?
- Each staking lot requires 10,000 Risq Protocol.

How do I purchase a staking lot?
- Holders with 10,000 RISQ can navigate to the [RISQ TOKEN] page to purchase a staking lot. You will need to decide which token's staking lot to partake in a share of the revenue generated by each lot.

Are RISQ tokens locked when deposited into a staking lot?
- Once a staking lot is either staked into a lot there is a 1 day lockup.
- Once the one day has passed, stakers are free to change or withdraw from staking lots.

Why stake RISQ tokens?
- Staking lots will receive three types of rewards:
  - 1% of each option's size will be evenly distributed amongst each asset specific staking lots (e.g. all 1% of all wBTC option size will be distributed between wBTC staking lots). These rewards can be withdrawn at any time.





