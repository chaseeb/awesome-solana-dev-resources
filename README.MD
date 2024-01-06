# awesome-solana-dev-resources

**A curated list of awesome solana developer resources covering everything from docs, tutorials, courses, tooling and more.**
  
**Please submit a pull request if you know any resources that might be helpful to other developers!**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Table of Contents
=================

* [Solana Dev Overview](#solana-dev-overview)
* [Getting Started](#getting-started-for-noobs)
* [Guides And Tutorials](#guides-and-tutorials)
* [Video Learning Content](#video-learning-content)
* [Self Learning Courses](#self-learning-courses)
* [Tooling]()
  * [General Developer Tools]()
  * [Indexers]()
  * [RPCs]()
  * [Other]()
* [Ecosystem Docs and SDKs](#ecosystem-docs-and-sdks)
* [Open Source Repos](#open-source-repos)
* [Educational Programs]()
* [For Ethereum Devs]()

## Solana Dev Overview

If you're not new to Solana and just here for the resources, I hope this is helpful, but if you are new then I thought it would be helpful to give a brief explainer and overview to make the idea of building on a Solana a little less overwhelming. Also important to note that if you're coming from another blockchain then building on Solana is going to be a much different experience, so trying to make comparisons may be challenging and its almost best to come into this with the mindset of learning something for the first time. But don't worry its not as scary as it may seem. 

I'll spare going into too much detail about Solana the blockchain and focus mainly on how to think about developing on Solana. But I'll leave you with this.

**Solana is a blockchain built for mass adoption. It's a high performance network that is utilized for a range of use cases, including finance, NFTs, payments, and gaming. Solana operates as a single global state machine, and is open, interoperable and decentralized.**

So you may have heard that in order to build on Solana you have to learn Rust. Well I'm here to tell you that this is far from the truth. If you want to write programs (smart contracts) on Solana, then you'll eventually need to learn Rust OR Anchor Framework, but that's not entirely necessarily to get started. Really all you need is software development knowledge and javascript/typescript experience. Due to the composable nature of Solana, you can leverage existing programs on the Solana blockchain and even build an entire project or business without ever needing to write a single Rust program yourself. That's really all up to you and your goals.

Any easy way to think of Solana development is programs being server side (running on the blockchain), and all other development being client side. In order to interact with programs on the blockchain, all you really need is an SDK like Web3.js in order to send requests to those programs in order to update something on the blockchain or retrieve data from it. So if you're coming from web2, then simply put in relatable terms you can use client side SDKs to interact with the blockchain the same way you'd use an API in web2.

There are a wide variety of SDKs that exist today. Web3.js is a library for interacting with any Solana program, but there are specialized SDKs for things like payments, gaming, defi, NFTS, daos and more. You could essentially build a really cool app on Solana using a single SDK and never having to know anything about Rust or how the programs themselves work. It really can be that easy!

There are attitional tools that will give you even greater capabilities, and you can see that in the tooling section!

## Getting Started For Noobs

Your experience getting started with Solana development will vary depending on your interests and skill level, and in this section I'll be sharing some resources that should serve as good starting points in your Solana development journey.

If you're someone who just prefers to read documentation end-to-end feel free to hop on over to the [Solana Docs](https://solana.com/docs) and get rolling. Otherwise, continue on in this section.

  ### From the Docs
* [Setup Your Environment](https://solana.com/developers/guides/getstarted/setup-local-development)
* [Hello World](https://solana.com/developers/guides/getstarted/hello-world-in-your-browser)
* [Important Concepts](https://solana.com/docs#start-learning)

#### Other Great Resources

* [Solana Bytes (Playlist)](https://www.youtube.com/watch?v=pRYs49MqapI&list=PLilwLeBwGuK51Ji870apdb88dnBr1Xqhm)

#### Solana Dev Starter Pack

* [Web3.js Library](https://github.com/solana-labs/solana-web3.js)
* [Solana Playground](https://beta.solpg.io/) - Solana Program Web IDE

# Guides and Tutorials

# Video Learning Content

* [SolAndy](https://www.youtube.com/solandy)


# Ecosystem Docs and SDKs

#### General Solana

* [Solana Core Docs](https://solana.com/docs)

#### NFTs

#### Payments

#### Gaming

#### Defi

#### DAOs

# Open Source Repos

* [Solana Open Source Software](https://github.com/StockpileLabs/awesome-solana-oss)

