# Risq Protocol Frequently Asked Questions

Below is a collection of the most routinely asked questions about Risq Protocol's ecosystem.  Any additional questions that are not covered here can be directed to our [Discord](https://discord.gg/nWZDznS4) or [Telegram](https://t.me/risqprotocol).

## THE RISQ TOKEN

What is the RISQ token contract address? 
- [0xC2c82622a7CB7159D44CEA7e39843a495f2674De](https://www.bscscan.com/token/0xC2c82622a7CB7159D44CEA7e39843a495f2674De)

What is RISQ token used for?
-	RISQ buys you a staking lot that earns settlement fees and for the Protocol's governance objectives. More usecases will emerge after the release of the Risq Protocol Hedge Fund Terminal.

What is the total supply?
- MAX Total supply is **100,000,000 RISQ**. This includes tokens to be bridged to Ethereum and Polygon. 

Should I buy RISQ?
WE DO NOT GIVE FINANCIAL ADVICE!  Any opinions, chats, messages, news, research, analyses, prices, or other information contained on this Website, Discord, Telegram, Medium, Reddit, Twitter, or any other social media are provided as general market information for educational and entertainment purposes only. RISQ Protocol is in BETA. RISQ protocol is unproved. You can lose 100% of your funds. Do your own research. 

## TRADING RISQ / BUYING RISQ  

How to buy/sell $RISQ?
- Risq Protocol is available for purchase/sell at:
  - [Pancake Swap](https://exchange.pancakeswap.com/#/swap)
  - $RISQ may be bought/sold through our Bonding Curve on the [RISQ TOKEN](https://options.risq.capital/#/stake) page.
  - A 10% swap fee is charged when $RISQ is sold on the bonding curve that is dispersed to the Risq Protocol Development Fund.

Will you list $RISQ on Centralized Exchanges?
- Not at this time.


What is the price oracle for options pricing and settlement?
- We are using Chain Link oracles for the retail prices of assets/tokens. Implied Volatility (IV) currently has to be programmed manually but is expected to be automated through ChainLink once soon.

## OPTIONS ON RISQ PROTOCOL

How are the options priced?
- Pricing formula for put options: premium = sqrt(period) * IV * strike / price.
- Pricing formula for call options: premium = sqrt(period) * IV * price / strike.
- A 1% fee on all options purchased through the protocol that is paid to Risq staking lots.

When is an option in profit?
- An Option becomes profitable when the price of the token is higher than the sum of the strike price, including the fee that the user is charged for purchasing the option.

How can my option be profitable?
-	It is exercisable when it is (ITM).
-	A call option is ITM when the token or underlying asset has a higher price than the strike price of the said option.
-	A put option is ITM when the token or underlying asset has a lower price than the strike price of the said option. 
-	NOTE: Since the user pays the fee for buying the option upfront, the ITM options are not making him/her money until the token price is higher than the strike price, including the fee is paid. It is recommended that users exercise ITM options at a loss in the case of expiry, as it will salvage a part of the original fee paid upfront.

Options Expiration
-	An Out of The Money (OTM) will not be able to be exercised because there will be a minus value in the option.  That is, it will cost you more coin to exercise it.
-	If, at any time during the lifetime of option, it becomes In The Money (ITM), you can exercise the option on the [Options Desk] tab yourself.
-	Keep in mind that there is no partial exercising of an option.  It must be entirely exercised or not at all.

How much capital do I need to buy the underlying asset when exercising the options?
-	None.  The underlying asset is not paid.  Instead, the difference between the exercising price and the strike price is paid.  It is important to keep enough gas in one’s wallet to exercise the option.  

Is my breakeven price supposed to stay the same?
-	The denomination of the option is BNB and is not converted into USD when purchased.  That means that if the price of BNB changes during the time when you’re holding the option, so does what you paid for the option (that means your breakeven point).   For example, if you pay 0.201 BNB ($100) for an option and the price goes up 10% within the contract’s lifetime, your breakeven price will increase $10 to since BNB is now higher in price. 

What happens during option expiry?
-	The Risq Protocol options don’t exercise.  If your option is Out of The Money (OTM) at expiry, it will just expire worthless.  But if you are In The Money (ITM) you will have to physically exercise the option prior to expiration or you will loose any potential upside that you may have gained.  

How can I understand the price of an option?
-	Option purchasers are charged a premium and permanent fee of 1% in addition to the strike price that is fixed before the purchase. Given choices in time periods when purchasing Risq Protocol options, this premium is flexible and based on: 
-	The length of time of the option is determined by the one who purchases the option.
-	The strike price is determined by the one who purchases the option.
-	Underlying asset/token price is received from ChainLink Oracles.
-	Implied volatility is received from Skew and manually renewed, but we plan to shift over to ChainLink Oracles based on future availability. 


## BECOMING A LIQUIDITY PROVIDER (LP)

What is a liquidity pool?
-	A Liquidity pool combines the tokens that are locked into the smart contract.  These pools not only allow users to trade asset(s) within the pool they also contribute to liquidity levels. 

How to provide liquidity?
-	The user should deposit tokens into one of the options liquidity pools found on Risq Protocol. Risq Protocol employs a leading-edge bi-directional pool method that is good for creating depth to a single liquidity pool for both call and put options purchasers. 

What are the benefits of providing liquidity?
-	It allows Risq Protocol users to trade options with ease. The liquidity, in turn, provides options purchasers the ability to collateralize their trade.  In the event of option expiration, the liquidity used to collateralize the options is removed either fractionally or entirely from the pool for subsequent trading.  The premiums paid for purchasing an option accumulate and are dispersed amongst the liquidity providers.  If the underlying value paid is higher than the returns to options holders, the LP’s (liquidity providers) will earn more in the value of those tokens corresponding to their portion of the pool.  In return for providing liquidity, options will get rewards in RISQ (coming soon). 

Definition of bi-directional pools.
-	Risq Protocol's bidirectional liquidity pool design is uncommon and relatively new in DeFi. The underlying token that is deposited in the pool can be used both for selling put and call options automatically and at the same time.  Thus, the guessing game for liquidity providers of whether or not the price will go up or down within the next two weeks is removed. 

Adding liquidity
- See [Becoming an LP](https://github.com/risqprotocol/options-docs/blob/main/docs/Becoming_an_LP.md) for full detials.
-	It is important to understand that you must lock up your tokens for 14 days when you provide liquidity.  This stabilizes the liquidity pool for all options buyers. 

Write tokens defined
- These are the tokens received (you’ll get them in the form of  LP tokens) when you, as a liquidity provider, deposit these tokens into the Risq Protocol liquidity pools.

Removing liquidity 
- Removing liquidity can take up to 14 days from the time liquidity was provided!  
- When you are ready to withdraw, you will need to go to the [WRITERS] page and under YOUR EARNINGS click on WITHDRAW. Once the withdrawal is confirmed, write tokens will be burned from your wallet, and you will get comparable tokens. 
-	The earliest date you can withdraw the write tokens in your wallet will pop up when you hit the WITHDRAW button on the Options Writers page.
- Please be aware not to send your write tokens to the contract address or funds will be lost and unrecoverable. 

Risk Exposure.
- Liquidity providers are short volatility. If price movements are not too volatile, liquidity providers have minimal risk exposure. Although, even if one provides liquidity to both call and put options, if the market swings too wildly up or down, the gains from deep in the money options will be paid for by the liquidity providers. Typically, puts and calls have a defined downside, but if the market moves too quickly can have considerable upside. If, for example, the price of Ethereum increases by only $200 within a week, put options will be out of the money and only lose the fee they originally contributed when they purchased the option.  On the flip side, the call options will be deep in the money and their gains (ETH earned) will be financed by the liquidity pool.
-	Navigate to the Options Writers tab under YOUR EARNINGS.  This is where liquidity providers can record their current profits/losses.  In this section of the Options Writers page you will not only be able to see how much you made/lost, but also your future Net Profit and the impact to the pool and yourself in the event that all options were to expire at the current price of the underlying token.

## STAKING LOTS

Staking lots Defined
- Staking lots are the right to claim fees made by Risq Protocol.  ALL settlement fees earned by the Protocol are given to the staking lots holders. 

What do I need for a staking lot?
-	One must accrue 10,000 Risq for a staking lot on Risq Protocol.

Purchasing a staking lot
- Holders with 10,000 RISQ must click onto the RISQ Token page of the DAPP to buy a staking lot. You will need to choose a token's staking lot in order to receive a share of the revenue produced by each lot.

Are RISQ tokens locked upon their transfer into a staking lot?
- When the lot is staked into a staking lot there is a 1 day lockup period.
- Once the 1 day lockup period has passed, stakers may exchange or withdraw from staking lots.

Why stake RISQ tokens?
- Staking lots will receive rewards as follows:
  - One percent of each option's amount will be evenly assigned amid each asset’s individual staking lots (e.g. all 1% of all wBTC option size will be assigned amongst wBTC staking lots). One may withdraw these rewards at any time.





