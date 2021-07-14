---
layout: page
title: Changelog
image:
---

## 4.3.0 (July 14, 2021)
### OctoFi DApp ([app.octo.fi](https://app.octo.fi))
- Fix Governance page from crashing
- Remove Wrong Network gate to allow other networks
- Simplified Navigation
- Update layout of footer
- Improve Dashboard layout and combine with Wallet page
- Combine components on Dashboard for more flexibility
- Consolidate Token Sets pages
- Update currency dropdown to indicate when a change occurs. Display chosen Currency
- Design updates for Dashboard, History, Exchange, Uniswap, NFT, Onramp
- Misc Bug fixes
- Initial performance updates for Currency lists and Governance spaces

More info for this release can be found in the [v4.3.0 Milestones](https://github.com/OctoFi/octofi-app-aquafarm/milestone/3?closed=1)

## 4.2.0 (June 19, 2021)
### OctoFi DApp ([app.octo.fi](https://app.octo.fi))
- Move pending transactions to the Account modal
- Create Settings Dropdown
- Improvements to the Navigation and Header
- Open Account modal when user clicks Account Address
- General design improvements
- Bug fixes

More info for this release can be found in the [v4.2.0 Milestones](https://github.com/OctoFi/octofi-app-aquafarm/milestone/2?closed=1)

## 4.1.0 (May 24, 2021)
### OctoFi DApp ([app.octo.fi](https://app.octo.fi))
- Update color theme
- UI updates to modals, cards, tables
- Fix duplicate data in homepage banner
- Fix errors causing Invest Pools to crash
- Fix layout and broken images for Fiat off ramp

More info for this release can be found in the [v4.1.0 Milestones](https://github.com/OctoFi/octofi-app-aquafarm/milestone/1?closed=1)

## 04.0.0 (May 05, 2021)
### OctoFi DApp ([app.octo.fi](https://app.octo.fi))
- Addressed findings from Certik and Bramah audits
- Bug fixes and performance improvements
- Added additional fiat off-ramp options
- Added multi-chain connectivity
- Added additional wallet connections
- Added cross-chain bridges and swaps

## 03.0.0 (March 03, 2021)
### OctoFi DApp ([octo.fi](https://octo.fi))
- Removed derivatives trading as API Errors been permanent with 3rd party
- Fixed Firefox problems 
- Fixed NFT section bugs
- Added Multi language support 
- Added Bell for pending and last 24h tx
- Added first Crosstopus option with ETH / BTC at Swaptopus
- Added the option for Uniswap Pools to withdraw pairs or just one asset 
- Fixed 1inch Swaptopus bug
- Fixed Curve.fi Swaptopus bug
- Swaptopus added the functions for recipient address
- Dark / Light mode
- Upgraded Uniswap functions to newest version
- Added more Swaptopus DEX
- Preparation for L2 OVM & BSC
- Preparation for showing platform data
- APY shown alongside each pool
- Performance improvements 

## 02.7.0 (February 18, 2021)
### OctoFi DApp ([octo.fi](https://octo.fi))
- Added Android App 
- Fixed Explorer Page crashing
- Fixed Firefox problems 
- Added Uniswap recipient address
- Added Slippage and Tolerance config
- Instant swap selection styling
- Renamed Instant Swap to Swaptopus
- Reorganised menu layout
- Borrow add sort by columns
- Pools add sort by columns
- Spot Market add sort by columns
- Remove requirement to connect wallet
- Performance improvements 

## 02.5.0 (January 31, 2021)
### OctoFi DApp ([octo.fi](https://octo.fi))
- Change domain from app.octo.fi to octo.fi
- Changed frontend to look more CEXier
- Added Wallet section with unlock / lock token for spot trading
- Added function to convert low balances to $OCTO
- Added Borrow & Lending 
- Added Tokensets
- Added SimpleSwap to instant swap module
- Performance improvements 

## 02.0.0 (December 31, 2020)
### OctoFi DApp ([app.octo.fi](https://app.octo.fi))
- Brand new 2.0 frontend
- Fiat off-ramp / on-ramp
- Smart Contracts for Uniswap LP incentive program
- New Wallet Overview (../account/wallet)
- NFT Marketplace
- Spot trading (Limit and Market Orders) (in testing)
- Lending and Borrowing aggregation (in testing)
- Lots of backend work to make platform faster and stronger

## 01.97.0 (December 10, 2020)
### AQUAFARM ([app.octo.fi](https://app.octo.fi))
- Enable fiat gateway
- Minor bug fixes and cosmetic changes
- Progressive Web App improvements
- Preparation for 2.0 migration

## 01.95.0 (November 29, 2020)
### AQUAFARM ([app.octo.fi](https://app.octo.fi))
- Animation for Copy Button indication
- Added Ledger Wallet with select HD derivation path
- Adding of Portis, Torus and Coinbase Wallet 
- Display Wallet Balance on Market pages
- Linking Asset overview with Market pages
- Function to withdraw pool liquidity 
- Added Pool Searchbox
- Added Governance Searchbox
- Highlighted OctoFi Governance 
- Added Fiat on-ramp for OCTO and other Token with over 10 Fiat currencies 
- New Instant Swap with DEX aggregation (1inch, Uniswap, Oasis, Radar Relay, Kyber, Bancor, 0x, Airswap, Paraswap, Sushiswap, Balancer, XBlaster…)

## 01.90.0 (October 31, 2020)
### AQUAFARM ([app.octo.fi](https://app.octo.fi))
- Added price aggregation (<s>oracles</s> tentacles beta)
- Added PWA (progressive web app) manifest
- Added 500+ ERC20 tokens (Dashboard)
- Performance improvements 
- Preparation for v2.0 DEX

## 01.80.0 (October 25, 2020)
### AQUAFARM ([app.octo.fi](https://app.octo.fi))
- Added DAOs Snapshot.pages
- Pools: UI fix
- Explore: direct buy and sell function 
- History: fixed display bugs
- Added OCTO Swap for access page 

## 01.60.0 (October 18, 2020)
### AQUAFARM ([app.octo.fi](https://app.octo.fi))
- Added Explore Tab (DeFi investment opportunities)
- Explore: Top 5 Gainer Tokens (24h)
- Explore: Top 5 Loser Tokens (24h)
- Explore: Trending on Coingecko
- Explore: Pools
- Explore: TokenSets
- Added History Tab (Still some display bugs, sorry)
- Added Market Tab (Preparation for Octo <s>Oracles</s> Tentacles)
- Added Buy Crypto Tab (Fiat on-ramp)

## 01.50.0 (October 12, 2020)
### AQUAFARM ([app.octo.fi](https://app.octo.fi))
- Added Access restrictions (Only with at least 1 OCTO you are able to access aquafarm)
- Added Dark / Light mode switch to settings
- Added Change connection button to wallet settings
- Added Logout button to wallet settings
- Added meta data to aquafarm
- Preparation for TokenSet integration (Invest tab)
- Preparation for Octobase (Incentives)
- Preparation for History tab
- Some npm package updates

## 01.30.0 (October 06, 2020)
### AQUAFARM ([app.octo.fi](https://app.octo.fi))
* Adding coingecko API to calculate the portfolio chart 
* Adding of DeFi Platform data for: 
	- Synthetix
	- Uniswap
	- Curve
	- 1inch 
	- Balancer 
	- yearn
	- compound
	- cream
	- Aave
	- Maker
* Several UI fixes 

## 01.23.0 (October 04, 2020)
### AQUAFARM ([app.octo.fi](https://app.octo.fi))
* Bug fix: Some invest options are not perfectly displayed
* Bug fix: Balance data is not showing up at the Dashboard 
* Adding better search options for invest page
* Adding new drop down menu functions for the wallet
* Preparing new invest options 

## 01.0.0 (October 02, 2020)
### AQUAFARM ([app.octo.fi](https://app.octo.fi))
* First deployment of aquafarm to gh-pages


***
