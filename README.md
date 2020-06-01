# Factory of cyber apps

## Why?

Too much apps needs to be build! Its is not good to build apps ourselves. It's wise to create a tool and proper environment. Self-regulation is also vital for success of DeMa. Incentives for evangelists is absent after Genesis, so we have to find the ways above the protocol. Incentives for developers is absent by design which could be an epic fault.

## What?

The project is a factory which allow anybody create simple, but flexible and powerful tokenized and capitalized apps in Great Web with some clicks.

## Developers, developers, developers

- Low barrier to entry. The most simple apps are available with clicks
- Apps are universal and can use any chain
- App are natively supported by search
- Embedded marketing
- Embedded investments

## How?

Anybody can create a token with the following parameters
- Token name
- App hash
- CYB amount

Upon call the new token contract is being deployed, amount of app tokens in accordance to predefined curve is being distributed to caller and have the following methods:
- mint tokens
- burn tokens
- update app hash
- update self

## Mint tokens

Everybody can call the method to issue more tokens. CYBs stay in the curve.
- amount of CYB
- developers address

In the moment tokens are minted the following distribution happens (aha moment):
- Merchant - those who buy. Get 90% of minted app tokens
- App pool - 4%
- Hacker - calling app address. Get 3% of minted app tokens 
- Evangelist - account which bring the user to the blockchain: first tx. 2%.
- cyber~Foundation (pool at Cyber) - 1%

## Burn tokens

- amount of tokens

## Update app hash and tokens contract

Simple consensus of app holders have to be able to update app hash and token contract. I think 51 support with 1% quorum is a good default parameters. 

## Price of using the factory

Starts from 10 GCYB and fall 10 KCYB each time the factory used.

## Setting up the cooperative

The first entry in cooperative have to be the APP token which will manage default parameters of the factory and factory code.

## Apps page https://cyber.page/capps

If I have some tokens they stick to the top with the following fields
- Logo
- Name
- My tokens
- Share
- Play button

After, table of apps sorted by cap with the following fields
- Logo
- Name
- Supply
- Price
- Cap
- Users
- cyberRank
- Play button

Action bar: Create app. If clicked on the line: issue, burn (if have) 

## Create app https://cyber.page/capp/create

- App name
- Paste local code
- Add favicon
- Amount of CYB => will by you <amount> of

## App page https://cyber.page/capp/<APP>
  
Logo, name, Rank, Users, Cap
Tabs:
- Cybernomics: Supply/Price Curve chart. Action bar: issue, burn (if have) 
- Proposals: Board of proposals (update parametr, remote, local). Action bar: Propose update, if clicked - vote.
- Merchants: List of holders sorted by tokens : Action bar: issue, burn (if have) 
- Remote code. Action bar: Propose update
- Local code. Action bar: Propose update
