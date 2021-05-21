---
layout: post
title: Release the INKubator
date: 2021-04-15 00:00:00 
author: Dr. Octavius
image: '/images/war-on-rugs.jpg'
---

A couple of weeks ago we first teased the launch of the INKubator (OctoFi Launchpad). Today, we are here with an exciting update: Our launchpad is fully working!

The INKubator is a completely decentralized and automated ILO/Presale platform connected to liquidity locker and octomatically created uniswap trading.

## INKubator Launch

That’s right, this means we’re now ready to start onboarding projects. The first gem has been selected and has been embraced by our tentacles.

The Team & Octagon came together and decided it’s important the INKubator is accessible for both baby octopi (smaller holders) and our giant frentacles (large holders). As a result, for the first launch anyone who holds **at least 8 OCTO** can participate in the upcoming private sale.

## Launch & Application Process

As always, we aim to be as transparent as possible and would therefore like to map out the complete process from application to launch to listing on the open market for you.

1. A project reaches out to OctoFi (or gets contacted by the Octagon).
2. The Octagon does research to the project and sees if it fits our profile: it’s aligned with the manifesto and pre-vetted [\#WarOnRugs](https://twitter.com/octofinance/status/1317344191446360064).
3. The project gets whitelisted and can prepare for launch.
4. The Octagon prepares the announcement & other details, in order to inform the community about an upcoming INKubator project.
5. OCTO holders can access the INKubator at [app.octo.fi/#/invest/launchpad](https://app.octo.fi/#/invest/launchpad) & participate in the sale.
6. After the token sale, a Uniswap trading pair is immediately created and if the project decided to create a liquidity lock before the pre-sale start, the lock is created octomatically.

The INKubator is a fully decentralized launch platform, aimed to provide a go-to-market strategy for legitimate projects. 

## Technical Details

INKubator got forked from Unicrypt.network and is only listing whitelisted, vetted projects by the Octagon.
The frontend is hosted on github pages and fully open source. The business logic is built in a decentralized way 
via smart contracts:

-   [UniswapV2Factory.sol](https://etherscan.io/address/0x5654c8bd78546a5f4e12cb7733a7c0036dd3ee39#code)
-   [UniswapV2Locker.sol](https://etherscan.io/address/0xb167addc46b1787c76a2c7511acda2edf07ddfab#code)
-   [PresaleSettings.sol](https://etherscan.io/address/0xd1f0ef21bdf40351c5be3d1d4e1873a6c412bf90#code)
-   [PresaleFactory.sol](https://etherscan.io/address/0x727ee25289f03ceec5fa9ea6dc56386828cbe42b#code)
-   [PresaleLockForwarder.sol](https://etherscan.io/address/0x350d3a912dff76d6903470eba87aaf3a68c7c892#code)
-   [PresaleGenerator01.sol](https://etherscan.io/address/0x9b2a97f5495a66074c3a6b0f4dbfe4ff9c0a78bf#code)
-   [Presale01.sol](https://etherscan.io/address/0x7ed247ee654e686a607a004da814fcea9f5321b7#code)

## INKubator Details

Every ILO taking place has to lock between **30% and 100%** of the raised currency (e.g ETH, DAI, etc.) as counter liquidity to the sale token. We highly recommend locking 60%+ of the raised funds, in order to create market depth from day one.

In order to prevent a participant from initiating markets at an unfavorable rate, please bear in mind if you participate in any ILO, your tokens will be held in the contract until the presale has completed.

Once the ILO ends (soft cap reached by end block, or hard cap reached) a publicly callable function will show on the presale page allowing anyone to end the presale, create a DEX pair at Uniswap, lock liquidity and instantly allow withdrawals of the sale token.

The following presale information is displayed to the community:

| Information | Supported |
|-|-|
| Tokenomics | ✅ |
| Discussion areas | ✅ |
| Links (Twitter, Telegram, Website) | ✅ |
| Audits | ✅ |

### How are ILOs structured?

ILOs are taking place in 2 rounds. The details of each round are shared just below.

#### Round 1

- The first round of any ILO lasts 2 hours ⏰
- To participate, your wallet needs to hold at least 8 OCTO Tokens 👋 
- If the whitelist is enabled and the ILO is private, you will need to be on the whitelist to get in, as well as holding the above-mentioned tokens. ℹ️

#### Round 2

- The second of the ILOs can run during a period of up to 14 days. ⏰
- If the ILO does not sell out in the first 2 hours, it moves on to this second round. This round is still subject to a whitelist check if the presale creator chose to make the sale private. ℹ️

### How to participate in ILOs?

1. Make sure you are eligible for the round (see above) ✅
2. Open our INKubator at [app.octo.fi/#/invest/launchpad](https://app.octo.fi/#/invest/launchpad) 
3. Connect your wallet
4. Open the ILO you are interested in and select the amount you want to participate with, then proceed with the transaction
5. Once an ILO is a success (soft cap met + end block reached, or hard cap met), a publicly callable function will then be used and initialize the markets
6. Time to withdraw your tokens! 🎉

*More about Successes/Failures in the below section.*

### Success or Failure

#### ✅ Success

- Scenario 1: The soft cap of the ILO is met, and the end block of the second round. 
- Scenario 2: The hard cap of the ILO is met, prior to the end block of the second round.
- Publicly callable function to initialize the markets and lock the liquidity.
- Only then, participants can withdraw their tokens from [app.octo.fi](https://app.octo.fi).

#### ❌ Failure 

- Scenario: The soft cap of the ILO is not met by the end block of the second round.
- Participants can withdraw (ETH, USDC, DAI...) from [app.octo.fi](https://app.octo.fi).

## Who can launch on INKubator and how?

First of all, get in contact with our Octagon via [Telegram](https://t.me/OctoFi) or email hello@octo.fi. After that first contact they will do the due diligence and discuss further steps. 

*Following projects (smart contracts) are not allowed:* 

**⛔ Minting:** If a token contract has minting it is possible for the developers to mint as many tokens as they may like and dump them on the market

**⛔ Proxies:** If a token is behind a proxy, the contract can be changed in the future to anything they would like. Including freezing token transfers and minting more tokens. Anything is theoretically possible.

**⛔ Not commiting to our Manifesto:** As you know the [Tentacult Manifesto](https://octo.fi/manifesto) contains the guiding principles for how we act and how our partners have to act, as well.

*It is important to conduct your own research into a project before participating in a presale.*

That said, release the Kraken and let’s get prepared for the first INKubator project!
