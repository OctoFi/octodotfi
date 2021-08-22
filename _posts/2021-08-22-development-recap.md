---
layout: post
title: "Development Recap"
date: 2021-08-22 00:00:00
author: nathan
image: "/images/22.jpg"
---

I am half way into my work for the 3 month contract set up in OIP-19. This post will provide a general update and my plan for the next 5+ weeks.

My original plan was to make a lot of incremental changes to our dapp over the course of 3 months to fix existing issues and to add new features. This would allow users to see regular updates to the dapp and fix any issues they were experiencing along the way. However, while working on v4.4 and v4.5 I realized that the dapp was too tightly tied together and I was potentially introducing more bugs than I was fixing. I would make a change to the Swap page and it would cause something in the pools or loans pages to break. I also tried to add new networks but that also resulted in other features breaking. Even if these attempts were successful, there were snippets spread throughout the code that would prevent some pages from loading unless Ethereum was the detected network.

After a few days of chasing bugs around I made the decision to start refactoring the code base to separate features into smaller components and to remove any "ethereum only" snippets that prevented other networks from being added. As part of this effort, I have added a UI testing suite to the code to help test components and to identify edge cases along the way. Ideally, I'll be able to document all of our components using this library to help identify and prevent errors in the future. An early, early version of this can be found at [storybook.octo.fi](https://storybook.octo.fi) and will be expanded in the coming weeks with the components that I have separated already but haven't set up UI tests for.

I've been making good progress on the dapp and I'm still on track to complete everything I set out to do in the 3 months with the addition of a couple other features that I wanted to sneak in. I need a little more time before I feel comfortable showing anything but here is my general thought process. In the coming weeks I'll be releasing a beta version of the site, which is essentially a v5.0 release. It will run alongside the current site so users have the option of using the beta or classic version.

The goal for the initial release will be to mirror the features provided in the current dapp but with improvements to performance, fixes for errors, and some changes to the appearance. Once I've finished copying over all features I will spend a few days testing, fixing design issues, and getting feedback from the community. I will also begin adding the logic to support other networks, some of which I've been adding along the way. In some features like governance this is an easy add, but in others like Liquidity Pools, this will take a greater level of effort.

At any point, if we feel comfortable with the beta version it can be moved from the beta domain to our main app domain and the old app will move to classic.octo.fi. They can run side by side forever or we can archive the old site at any time.

If things go according to plan, I forsee some of these things being possible through our dapp.

- Exchange crypto on Ethereum, Polygon, or BSC. Simplified error handling and improved price quotes.
- Track your crypto portolio on all networks above, and expand the list of supported tokens.
- Governance via Snapshot will also be expanded to some of their [supported networks](https://snapshot.org/#/networks)
- Begin to expand our options for Invest and Pools
- Improvements to NFT wallet display, and looking to add an NFT page to drill down into the meta data for each NFT you own

Some of my free time is spent working in the Avalanche network so I'd like to expand the dapp to support that as well. Given the growth with recent announcements, I think it would be wise for us to branch out there and try to provide users with value. I haven't seen any good aggregators in that network yet.

I hope this update has been informative and finds you in good spirits. What a great industry to be a part of. I will continue to keep my head down and work hard toward launching this beta.
