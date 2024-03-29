# Week 1 homework
![uniswap.jpg](/images/uniswap.jpg)

## Overview and Origin

* Name of company? **Uniswap**

* When was the company incorporated? 

    2nd Nov 2018, final day of Devcon 4, smart contracts were deployed to the Ethereum mainet. <sup>1</sup>

* Who are the founders of the company?
    1. Hayden Adams <sup>1</sup>
    2. Karl Floersch
    3. Callil Capuozzo
    4. Uciel Vilchis
    5. Philip Daian
    6. Dan Robinson
    7. Andy Milenius
    8. Jinglan Wang

* How did the idea for the company (or project) come about?

    Adams was working as a mechanical engineer at Siemens.  
    On 6th July 2017, he got retrenched.  
    Karl Floersch of Casper FFG at the Ethereum foundation, introduced Adams to Ethereum & Smart Contracts. Capuozzo, Adam's friend from elementary school, helped out with the frontend. Vilchils refactored the Uniswap frontend codebase. Daian, Robinson, Milenius, Wang all acted as advisors to Uniswap. Vitalik Buterin provided the inspiration to name the company Uniswap instead of Unipeg. <sup>1</sup>

* How is the company funded? How much funding have they received?

    $100K 'Building for the end user' grant, as a Wave III Finalist from the Ethereum Foundation <sup>2</sup>  
    $1M from Charlie Noyes of Paradign Venture Capital <sup>3</sup>  
    $11M on 5th June 2020 from 12 different investors <sup>4</sup>  
    Andreesen Horowitz  
    Union Square Ventures LLC  
    Version One  
    Parafi Capital  
    Variant  
    SV Angel  
    A. Capital


## Business Activities:

* What specific financial problem is the company or project trying to solve?

    Uniswap is a protocol for creating liquidity and trading ERC-20 tokens on Ethereum. It eliminates the need for trusted intermediaries, prioritising decentralisation, censorship resistance, and security. This allows for fast, efficient trading.

* Who is the company's intended customer?

    Three types of users: Liquidity providers, traders, developers. <sup>5</sup>
    ![ecosystem.jpg](/images/ecosystem.jpg)

1. **Liquidity providers (LP) are incentivized to contribute ERC-20 tokens to common liquidity pools.**

    Passive LPs accumulate trading fees  
    Professional LPs focus on market making  
    Token projects become LPs to create liquidity for their tokens, unlocking interoperability with other DEFI projects through Uniswap  
    DEFI pioneers exploring complex liquidity provision interactions like incentivised liquidity, liquidity as collateral.

2. **Traders can swap these tokens for one another for a fixed 0.30% fee (which goes to liquidity providers).**

    Speculators swap tokens using liquidity pulled from a Uniswap Protocol  
    Arbitrage bots compare prices across different platforms to find an edge  
    DAPP (Decentralised applications) users buy tokens on Uniswap for use in other applications on Ethereum  
    Smart contracts execute trades on the protocol by implementing swap functionality

3. **Developers can integrate directly with Uniswap smart contracts to power new and exciting interactions with tokens, trading interfaces, retail experiences, and more.**

    UX (User Experience) experiments and front-ends  
    Wallets integrate swapping and liquidity provision functionality as a core offering of their product  
    DEX (Decentralised exchanges) aggregators pull liquidity from many liquidity protocols to offer traders the best prices  
    Smart contract developers invent new DeFi tools and experimental ideas (Unisocks, Zora etc)

    In total, interactions between these classes create a positive feedback loop, fueling digital economies by defining a common language through which tokens can be pooled, traded and used.

* Is there any information about the market size of this set of customers?

    As of 16/02/2021, total liquidity on Uniswap is $4.4B USD <sup>6</sup>
    ![liquidity.jpg](/images/liquidity.jpg)

* What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)

    Before Uniswap, Decentralised Exchanges like EtherDelta were inefficient, using orderbooks, as opposed to Uniswaps's Automated Market Maker & Liquidity Pools. <sup>7</sup>  
    Uniswap allows retail investors/traders (as opposed to institutions only) become liquidity providers, enabling them to earn trading fees of 0.3%, as well as $UNI token rewards for providing liquidity. <sup>7</sup>  
    For token projects which are not listed on major centralised exchanges (eg Binance), Uniswap is a way for them to create liquidity for their tokens. 

* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing–– you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)

    1. Cryptocurrency 
    2. Ethereum blockchain
    3. Decentralised finance
    4. Stable coins
    5. Automated liquidity protocol

## Landscape:

* What domain of the financial industry is the company in?
    1. Blockchain and Cryptocurrencies

* What have been the major trends and innovations of this domain over the last 5-10 years?
    
    1. Moving from traditional centralised finance to crypotocurrencies.
    2. Decentralised Crypto Exchanges gaining popularity over centralised Crypto exchanges

* What are the other major companies in this domain?
    1. SushiSwap (forked version of Uniswap) <sup>8</sup>
    2. Aave
    3. 1inch
    4. Binance
    5. Chainlink
    6. Polkadot

## Results

* What has been the business impact of this company so far?

    It is the biggest single decentralised liquidity source for DEX (Decentralised Exchange) aggregators <sup>5</sup> and estimated to be the 4th largest cryptocurrency exchange overal by daily traded volume. <sup>12</sup>

* What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?
    
    1. **Liquidity**
    As of 16/02/2021, total liquidity is $4.4B USD <sup>6</sup>
    2. **Volume (24hour)**
    As of 16/02/2021, Volume (24hour) is $1.1B USD <sup>6</sup>

* How is your company performing relative to competitors in the same domain?

    Sushiswap would be considered the main competitor in DEFI.
    When Sushiswap launched, liquidity of over $1B was transferred from Uniswap to Sushiswap within hours. <sup>8</sup> However the creator of Sushiswap 'Chef Nomi' sold $14M worth of ETH from a developer fund, leading to community backlash and eventually Nomi returning the funds and control of Sushiswap project back to FTX CEO Sam Bankman-Fried. <sup>9</sup>

    Uniswap in comparison has a level of transparency & decentralisation higher than that of Sushiswap. Uniswap pays higher fees to LPs, however Sushiswap incentivises Sushi holders. <sup>8</sup>

    | | Uniswap | Sushiswap|
    | :---:   | :-: | :-: |
    | Fees    | 0.3% to LP <sup>8</sup> | 0.25% to LP, 0.5% to Sushi Holders <sup>8</sup> |
    | Exchange UI | Smoother, cleaner, straightforward <sup>8</sup> | Izakaya interface novel idea <sup>8</sup> |
    | Transparency | High <sup>8</sup> | Questionable <sup>9</sup> |
    | Liquidity as of 16/02/2021 | 4.4B <sup>10</sup> | 3.57B <sup>11</sup>|
    | Volume (24 hour) as of 16/02/2021 | 1.1B <sup>10</sup> | 0.421B <sup>11</sup> |

    

## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)

    Decentralised Exchanges are still an extremely niche market in Cryptocurrency & Blockchain. It is a subset within a subset, and is hard to understand for the general population. More awareness needs to be provided in order to facilitate uptake by people with knowledge in cryptocurrency, but not necessarily DEFI  
    It will be a big challenge to uptake people who have no experience with cryptocurrency, or DEFI. In this instance, perhaps partnering with a mobile app would work. For example partnering with Uber. People could pay with $UNI tokens for instance, and that gets them interested in the Uniswap platform. This idea might or might not work, but it is a start.

* Why do you think that offering this product or service would benefit the company?

    It would increase their user base, and promote cryptocurrency among the general population.

* What technologies would this additional product or service utilize?

    Mobile Pyaments  
    Blockchain  
    Cryptocurrency  
    Coding  
    UX/UI of the Uber app

* Why are these technologies appropriate for your solution?

    Integration of cryptocurrency into a company's mobile app would possibly require an overhaul of the front end & back end of Uber's app.

## Links
1. https://uniswap.org/blog/uniswap-history/
2. https://blog.ethereum.org/2018/08/17/ethereum-foundation-grants-update-wave-3/
3. https://www.forbes.com/sites/michaeldelcastillo/2020/12/01/
4. https://www.crowdfundinsider.com/2020/08/165047-andreessen-horowitz-union-square-ventures-others-take-part-in-11-million-series-a-round-for-uniswap-a-non-custodial-ethereum-token-exchange/
5. https://uniswap.org/docs/v2/protocol-overview/ecosystem-participants/
6. https://uniswap.org/about
7. https://cryptotesters.com/blog/what-is-uniswap
8. https://blog.shrimpy.io/blog/uniswap-vs-sushiswap#:~:text=SushiSwap%20rewards%20liquidity%20providers%20with,as%20high%20as%2080%25%20APY
9. https://www.coindesk.com/sushiswap-creator-chef-nomi-returns-dev-fund
10. https://info.uniswap.org/home
11. https://sushiswap.vision/home
12. https://www.bloomberg.com/news/articles/2020-10-16/defi-boom-makes-uniswap-most-sought-after-crypto-exchange