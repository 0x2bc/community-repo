# About

This Objectives and Key Results (OKRs) guideline is designed to provide a framework for measuring the overall performance of the system, providing a signal to the council about how well the system is operating. The signal from this measurement will allow the council to adjust policies and reallocate resources to improve the performance of the system, ensuring that it is running as efficiently as possible.

OKRs should be used to guide activities and decision making within the WGs (working groups). By regularly tracking progress against the objectives, the working group can ensure that all members are working towards the same goal, and that progress is being made.

# High-level OKRs

The DAO has high level OKRs that it needs to focus and improve on. Below is a list of these high level OKRs. In the next paragraphs we will further break down these high level OKRs into individual OKRs for each working group. By focusing on these high level OKRs, we can ensure that all working groups have a clear understanding of the goals and objectives of the DAO.

## Income

DAO is distinct from a conventional organisation, as it spends its budget obtained via JOY inflation.   When discussing DAO income, we refer to anything that boosts the chances that DAO will pay its expenses over the short and long term. 

Below we consider not just JOY profits the DAO receives directly, but also any factors that can influence the price of JOY token. These are the factors:

- Gateways’ Payments
- Tokens burn
- Tokens lockup

### **Gateways’ Payments**

Revenue from gateway providers should be maximized and continue to grow over time. 

```jsx
GTW_PAYMENTS = GTW_NUMBERS * GTW_RESOURCES_CONSUMED * GTW_RESOURCES_PRICE
```

The formula gives us an overview of the main factors that gateway payments are depends on. 

*Comment: This is a simplified formula. In reality, we need to calculate each gateway provider's earnings separately. To get an accurate amount, we should multiply the cost of each resource used by the price of that resource, and then make a sum across all the resources used by a particular gateway provider.*

**`GTW_PAYMENTS`**  - Amount of payments DAO get from the gateways.  

**`GTW_NUMBERS`** -   Number of gateways.

**`GTW_RESOURCES_CONSUMED`** - Amount of resources consumed. Both DAO and Gateway operators will benefit from attempting to maximize the following metrics:

- Number of creators across the gateway
- Number of monthly active users across the gateway
- Number of channels across the gateway
- Hours of watched video content across the gateway
- Average user session time

**`GTW_RESOURCES_PRICE`**  - Price per resource. Different resources may have different prices.

### **Tokens burn**

There are different ways tokens can be burned. These may include token burning, permanent locking, sending tokens to an address from where they can't be retrieved, etc.

The following use cases are applicable for Gleev:

**NFT minting**

Every time an NFT is minted, Joystream takes a fee. This is also the case on all sales, both primary and secondary, just like on a platform like OpenSea.

**Creators token fee**

As you know, every creator can have their own token, and the same way an exchange like Binance charges a small fee on the trading of a token, so does Joystream.

### **Tokens lockup**

As was said before the ultimate objective is to maximize number of tokens in lockup. Token lockup is a part of following activities: 

- Staking and nomination
- Voting
- Bonding tokens for role
- Vesting

## Costs

Let’s reduce our costs while staying competitive on pricing and ensuring top-notch infrastructure services. There are several different areas where costs arise:

- WG and Council Salaries
- Validator rewards
- Grants and bounties
- Other operational costs (Marketing, MM, etc)

As the DAO is not a typical organisation, the term "costs" used in relation to it can be interpreted in a variety of ways. In some sense, even a high selling pressure can be considered as a financial burden or “cost” for DAO. 

## Quality of service

Let's make sure we offer reliable and excellent performing services:

- **Storage system**
    
    The storage providers, coordinated by the lead, have to provide a storage system which performs well in the following terms
    
    - Low latency and reliable uploading.
    - Very low probability of permanent data loss
    - High upload speed.
    - High upload volume capacity: many simultaneous parallel uploads.
    - A high upload speed to distributors.
    - A low replication latency for a new data objects to all providers for the given bag.
    - A low synchronization time of new storage providers.
    - Basic level of denial of service resistance at the public upload API.
- **Distribution system**
    
    For the distributors, coordinated by the lead, have to provide a distribution system which performs well in the following terms
    
    - Low latency and reliable downloading.
    - High download speed.
    - High download volume capacity: many simultaneous parallel downloads.
    - A high download speed from storage providers.
    - A low replication latency for a new data objects to all distributors for the given bag.
    - A low synchronization time of new distributors.
- **Content**
    - Moderation. Ensuring that the content available through the platform's public applications is legal, properly licensed and appropriate for the testnet environment and its participants.
    - Featuring. Ensuring that the most impressive content available on the platform is promoted to the maximum extent possible given the tools available, and as regularly as is feasible considering the volume of new high-quality content coming in.
    - Metadata Integrity. Maintaining a "clean" directory of content, with effective titles, descriptions, thumbnails and other metadata, as well as correct license information and the deployment of attribution best practices, and also the avoidance of spam.
- **Apps & Builders**
    - Manage the number of tokens going from the Gleev or other Gateway platform per unit of service. Assist the accumulating discrepancies between requested payment magnitudes from the provider (Joystream DAO), and the reports accumulated by the gateway
    - Help answer technical inquiries about integration with Joystream CDN from the Gleev team or other gateways.

## Ecosystem development

Lets work on the increasing the number of tools and services in our ecosystem, promote development activity, and strengthen the perception of the Joystream ecosystem among external entities

### Tools and services

Boost the quality and quantity of tools and services available to the Joystream community.

### Software developers

Ensuring that the number of software developers and their associated tech community (QA, desiners, etc) is growing and their daily activities are increasing, this ultimately leads to more tools and services becoming available.

### Assistance and support

The DAO must ensure that it is providing all necessary support to the ecosystem in order to promote its growth. This includes technical assistance, guides and tutorials, the necessary tools, and financing. All of these elements are essential for the successful growth of the ecosystem.

### Product development

BWG and the JSgenesis team should continue deeply collaborate to address issues and enhance the Pioneer, Atlas, and other products. 


# Appendix

### Appendix 1 - Old JSG Scores

- [General description](https://github.com/Joystream/handbook/tree/a8c9f89e433fe092487984c1675c2d3bd90cc208/testnet/council-period-scoring)
- [General working group Scor](https://github.com/Joystream/handbook/blob/a8c9f89e433fe092487984c1675c2d3bd90cc208/testnet/council-period-scoring/general-working-group-score.md)
- [Content directory Score](https://github.com/Joystream/handbook/blob/a8c9f89e433fe092487984c1675c2d3bd90cc208/testnet/council-period-scoring/content-directory-score.md)
- [Human resources Score](https://github.com/Joystream/handbook/blob/a8c9f89e433fe092487984c1675c2d3bd90cc208/testnet/council-period-scoring/human-resources-score.md)
- [Marketers Score](https://github.com/Joystream/handbook/blob/a8c9f89e433fe092487984c1675c2d3bd90cc208/testnet/council-period-scoring/marketers-score.md)
- [Storage providers Score](https://github.com/Joystream/handbook/blob/a8c9f89e433fe092487984c1675c2d3bd90cc208/testnet/council-period-scoring/storage-providers-score.md)
- [Distributors Score](https://github.com/Joystream/handbook/blob/a8c9f89e433fe092487984c1675c2d3bd90cc208/testnet/council-period-scoring/distributors-score.md)
- [Builders Score](https://github.com/Joystream/handbook/blob/a8c9f89e433fe092487984c1675c2d3bd90cc208/testnet/council-period-scoring/builders-score.md)

### Appendix 2 -  OKR discussion

[Pioneer discussion](https://pioneerapp.xyz/#/forum/thread/33?post=169)
