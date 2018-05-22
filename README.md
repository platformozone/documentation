# Ozone Platform FAQ

1. [About Ozone Platform](#about-ozone-platform)
    1. [What is Ozone Platform?](#what-is-ozone-platform)
    1. [How is Ozone Platform better than existing solutions for travel?](#how-is-ozone-platform-better-than-existing-solutions-for-travel)
    1. [How will Ozone Platform be launched?](#how-will-ozone-platform-be-launched)

1. [How Ozone Platform works](#how-ozone-platform-works)
    1. [What is the difference between protocol layer and application layer?](#what-is-the-difference-between-protocol-layer-and-application-layer)
    1. [Please describe the system architecture?](#please-describe-the-system-architecture)
    1. [What is the purpose of the Ozone Innovate Fund?](#what-is-the-purpose-of-the-ozone-innovate-fund)
    1. [What risks are involved in use of Ozone Platform?](#what-are-the-risks-involved-in-use-of-ozone-platform)

1. [Ozone Platform and its founders](#ozone-platform-and-its-founders)
    1. [Why did we create Ozone Platform?](#why-did-we-create-ozone-platform)
    1. [Is there a working MVP (minimum viable product) available?](#is-there-a-working-mvp-minimum-viable-product-available)
    1. [Is there a lock-up period for the Ozone team, partners and advisors?](#is-there-a-lock-up-period-for-the-ozone-team-partners-and-advisors)




## About Ozone Platform

### What is Ozone Platform?

Ozone Platform aims to **move the search, booking and settlement of travel inventory (airline seats, hotel rooms, rental cars) to blockchain**. Ozone Platform is blockchain based, and targets to disrupt the current providers of inventory providers, the Global Distribution System companies (GDSs), such as Amadeus or Sabre.

### How is Ozone Platform better than existing solutions for travel?

Ozone Platform allows for **more flexibility** when defining the actual air ticket. The extra-features, such as legroom, meal, luggage allowance and other attributes can easily be added. Furthermore, if it so allowed by the terms and conditions of individual airline companies, **it shall be possible to easily trade the ticket on the secondary market** through the blockchain, as each individual ticket shall be represented by a unique non-fungible token. 
   
Also, as the Platform is blockchain-based **the system is distributed, and inherently more reliable compared** to centralized platforms in addition to being tamper- and revision-proof. Finally, as the search, booking and settlement of the inventory is performed on the blockchain, it is **cheaper compared to current solutions**, and the fee charged for transactions will be lower, which will decrease the cost for the airlines and the end-user.

### How will Ozone Platform be launched?

Ozone platform plans to have the full-fledged solution for airlines, hotels and car rental companies by mid-2020. In order to achieve the desired scale, **Ozone Platform will perform an ICO towards the end of 2018**, with a private sale and pre-sale of tokens before the main ICO event. Both the private sale and the pre-sale will involve discounts on token purchases for early adopters.

## How Ozone Platform works

### What is the difference between protocol layer and application layer?

Ozone Ecosystem outlines a set of interworking methods, protocols, and specifications organized around two core layers:
 - Protocol layer and
 - Application layer.

The **protocol layer** describes the three roles integral to the system: buyer, distributor, and supplier, and defines four smart contracts encompassing and governing the whole travel booking value chain:
 - Inventory representation through non-fungible ERC721 Ozone Contract;   
 -   Booking, payment, and settlement through Booking Contract;
 -   Transactions and incentive structure through ERC20 Oxygen Contract and
 -   Digital identity of all actors in the system through ERC725 Digital Identity Contract.

   **Protocol layer** is separated from **application layer** and is application-agnostic. The code that powers the network is open-source and allows to build various applications which might be beneficial to the entire network.

   The application layer defines an **additional set of useful but non-essential applications and specifications** some of which might not be open-source. Such application might be a supplier API, payment system or buyer (user) interface. Ozone Platform will also invest in some of these applications on top of open-source protocol to further enhance the functionality of the network.

### Please describe the system architecture?

At present, Ozone Platform plans to use the **Ethereum blockchain network as its backbone**. Should a better solution emerge in the future, the Ozone Platform will consider the migration to the another blockchain network.

The architecture is segmented into two parts:
- Off-chain distribution network and
- Trustless exchange protocol

**The off-chain distribution network allows to cheaply modify order prices in response to market conditions**. The nature of air tickets and all the travel inventory is frequent price updates depending on the time left before the utilization and the overall availability of the inventory. While single on-chain transactions are cheap, the massive frequency of updates coupled with a huge inventory amount to a major cost. The distributors help broadcast trades and collect a fee each time they facilitate a trade. Distributors do not execute trades, consumers do this themselves, avoiding having to trust a third party. The first distributor shall be built by Ozone, but this is non-exclusive and other, third parties will be invited to participate as distributors. 

The open nature of the network shall allow **formation of many distributors**, some of which can be specialized for certain types of travel (e.g. high-end, remote travelers, no-frills) and the buyers would be able to send requests only to distributors with inventory relevant for the search reducing the amount of requests sent through the system.

The trustless exchange protocol consists of following smart contracts:
- ERC20 Oxygen Contract
- Booking Contract
- ERC721 Ozone Contract and Distributed File System
- ERC725 Identity

The ERC20 Oxygen contract is used for payments throughout the system, while ERC725 guarantees the identities of all the parties in the ecosystem. The **booking contract automatically executes transactions by transferring ownership and accrediting the token to the buyer's wallet**. The booking contract also settles accounts between buyer, suppliers and distributors. The travel inventory is represented by non-fungible, transferable ERC721 Etherum smart contract called Ozone.

### What is the purpose of the Ozone Innovate Fund?

The purpose of the Ozone Innovate Fund is to **foster the development of the Ozone ecosystem**. Anyone in the community (holding the Oxygen token) can suggest a project and the community will vote on whether or not the project will be financed. Ozone Innovate Fund will be funded through basis inflation and bonded stakes generated due to a breach of slashing conditions.

### What risks are involved in use of Ozone Platform?

Though the Ozone White Paper has been thoroughly audited, and any future implementations including smart contracts shall also be thoroughly audited, **there are always some potential risks**, as with any IT application. These include potential chain dependence and immutable bugs which might occur in spite of thorough audits.

## Ozone Platform and its founders

### Why did we create Ozone Platform?

We created the Ozone Platform because we **believe that blockchain is an ideal platform for the travel search, booking and settlement**. The current, Global Distribution System dominated ecosystem is slowly changing, but we want to change it even faster in a more radical way. Due to the incredible amount of data representing the travel inventory which in addition changes very quickly, we have envisaged a hybrid on-chain/off-chain system utilizing the best of both worlds and producing a unique, robust solution which is completely public-domain. Only some of the application layer elements will not be completely public-domain.

### Is there a working MVP (minimum viable product) available?

**The team is working hard on developing the MVP** and will post it online as soon as it is available.

### Is there a lock-up period for the Ozone team, partners and advisors?

**There is a lock-up period for the Ozone team**, and a shorter lock-up for partners and advisors. The details will be published prior to the ICO.
