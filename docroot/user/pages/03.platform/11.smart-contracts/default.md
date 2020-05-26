---
title: 'Smart Contracts'
---

# What are Smart Contracts?
A smart contract is generally the name used for decentralized apps, or dApps, on Ethereum. On Obyte, this type of on-chain applications are called Autonomous Agents. A Smart Contract is rather an agreement between two or more parties where the rules that applies is visible to the parties of the contract. The simplest form of a Smart Contract is a conditional payment from one user to another. What the condition is or how many there are can be defined by the creator of the Smart Contract.

## How do Smart Contracts work?
Generally, Smart Contracts are often created by chatbots, but the Obyte Wallet has built-in features making it rather easy to define Smart Contracts directly between users, without having to write a single line of code or know anything about how the Obyte protocol works. In order to create a Smart Contract, the parties must first pair their wallets. This is done by either sending a pairing invitation link to the counter party or accepting a pairing invitation from the counter party. Once the two users' wallets are paired, they can send chat messages to each other. The Obyte Wallet's chat has built-in features to make it easier to create Smart Contracts. The user wanting to create the Smart Contract first asks the counter party to insert his wallet address in the chat. This is done by clicking the (···) icon and selecting "Insert my wallet address". The wallet address will appear in the user's chat as a clickable link. When clicking the link the user selects the option "Offer a contract". 

## Conditions
A Smart Contract can have a single condition but more often multiple conditions define who and when can spend funds from it. The conditions can either be defined using the built-in template in the Obyte Wallet or the more complex conditions can be defined by headless wallets that can have beautiful and easy-to-use web interfaces. The built-in template makes simple conditions fast and easy to create in human readable language. The template defines the conditions for when two parties in the Smart Contract can spend funds. Once conditions are defined, the user sends the Smart Contract to the counter party who can review all conditions and decide whether or not to accept them. Conditions can be either on-chain events like transactions to/from a given address, dates, times or it can be off chain events that are introduced to the Obyte DAG through socalled Oracles.

## Shared wallets
A Smart Contract is actually a shared wallet between the involved parties. Shared Wallets appear as sub-wallets and the user can select it to review conditions or send funds from it. The unique design also allows a third party to create a Shared Wallet between two parties eliminating the need for the parties to pair their wallets as long as they both pair with the third party. This is commonly done through chatbots, making the process easy. Just like a tailor that made a leather wallet cannot spend the funds you put in it after you bought it, the creator of a Shared Wallet cannot spend from that either, unless the creating entity is defined as a party of the Smart Contract.

## Common use cases
The most common use cases for Smart Contracts on Obyte are insurance, sports betting, atomic swaps, ICO distribution but anywhere where conditioning a payment makes sense, Smart Contracts can be used to effectively aliminate the need for trust between parties.

## Oracles
Obyte allows external events to be used as conditions in Smart Contracts. This is achieved through oracles. An oracle is most often a headless wallet that is connected to an external API, a flight delays website for example. Once an event happens, the node picks it up from the API and creates a transaction on the Obyte DAG. Most often, these transactions are simple key-value pairs that describes a unique identifier and the resulting outcome. For sports betting, this can be a match-id at the result provider's API and the match's end result. While Smart Contracts enables fully trustless conditional payments, it is worth mentioning, that if an oracle is to provide the result, both users will need to trust this oracle to provide an honest result. It is also possible to create conditions that require the result from multiple oracles.