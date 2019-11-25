title: Loki Documentation | Frequently Asked Questions
description: What is Loki? Does Loki have Masternodes? What is Loki Messenger? Loki FAQ page goes into the frequently asked questions the Loki project receive.


# Frequently Asked Questions

## General

* [What is Loki?](#what-is-loki)

* [Is Loki Proof of Work (PoW) or Proof of Service (PoS)?](#is-loki-proof-of-work-pow-or-proof-of-service-pos)

* [What is the token supply?](#what-is-the-token-supply)

* [What do you do differently from Monero?](#what-do-you-do-differently-from-monero)

* [Who would use Loki Network?](#who-would-use-loki-network)

* [Is Loki an ERC20 token?](#is-loki-an-erc20-token)

* [Why the name Loki?](#why-the-name-loki)

* [What is the business model behind this peer-to-peer network?](#what-is-the-business-model-behind-this-peer-to-peer-network)

* [Will you guys commit back to the Monero source code?](#will-you-guys-commit-back-to-the-monero-source-code)

* [What's the difference from Monero?](#whats-the-difference-from-monero)

* [Can I see details about the premine?](#can-i-see-details-about-the-premine)

* [Why is there a 5% governance reward?](#why-is-there-a-5-governance-reward)

* [What is the block reward for mining?](#what-is-the-block-reward-for-mining)

* [What is the block generation time?](#what-is-the-block-generation-time)

* [Are there plans to support Loki on the Ledger Nano S hardware wallet?](#are-there-plans-to-support-loki-on-the-ledger-nano-s-hardware-wallet)

---

## Service Nodes

* [Why are Service Nodes required?](#why-are-service-nodes-required)

* [Is there a concept of Masternode's in Loki?](#is-there-a-concept-of-masternodes-in-loki)

* [What is the collateral requirement to run Service Nodes?](#what-is-the-collateral-requirement-to-run-service-nodes)

* [Can you run multiple service nodes in a single VPS server?](#can-you-run-multiple-service-nodes-in-a-single-vps-server)

* [Can a pool member request for the stake to be unlocked?](#can-a-pool-member-request-for-the-stake-to-be-unlocked)



---

## SNApps

* [Do SNApps run on Service Nodes only?](#do-snapps-run-on-service-nodes-only)

* [Are SNApps like DApps?](#are-snapps-like-dapps)

* [Where will SNApps and all of its data be hosted?](#where-will-snapps-and-all-of-its-data-be-hosted)

---

## Loki Services

* [What's Loki Messenger?](#whats-loki-messenger)

---

General
---

###**What is Loki?**

Loki provides users with tools to interact online in an anonymous, decentralised, secure and private way. By combining a private transaction network, the $LOKI cryptocurrency, and economically incentivised [Service Nodes](../ServiceNodes/SNOverview), Loki has created a trustless quorum-based onion router called [Lokinet](../Lokinet/LokinetOverview). Built into Lokinet is [Loki Messenger](../LokiServices/Messenger) — a decentralised, anonymous and private messaging service. Front end applications, known as [Service Node Apps](../Lokinet/SNApps) (SNApps) operate on Lokinet, and will allow browser integration and contribution from our open-source community.

###**Is Loki Proof of Work (PoW) or Proof of Service (PoS)?**

Loki uses a hybrid of [Proof of Work](https://en.wikipedia.org/wiki/Proof-of-work_system) and [Proof of Service](../ServiceNodes/SNOverview), similar to how DASH is secured by PoW but also has a reward for their masternodes through a Proof of Service.

###**What is the token supply?**

Like Monero, there is no total token supply. The current supply can be seen at [lokiblocks.com](https://lokiblocks.com).

###**What do you do differently from Monero?**

Aside from some minor changes in approach to the core currency, we implement a [Service Node](../ServiceNodes/SNOverview) network that performs a variety of functions, including an [anonymous networking layer](../Lokinet/LLARP), trustless quorum-based instant transactions (based on a system called "[Blink](../LokiServices/Blink)"), and a range of functions that leverage the networking layer for applications like secure [private messaging](../LokiServices/Messenger).

###**Who would use Loki Network?**

Loki provides both private transaction and private communication functionality, making the Loki Network important for users who want the highest level of privacy in their communication channels. As more [SNApps](../Lokinet/SNApps) are developed we imagine Loki will present it self as the network to run privacy-centric applications on top of.

###**Is Loki an ERC20 token?**

Loki is not an ERC20 token. Loki is its own coin, running its own mainnet. See [lokiblocks.com](https://lokiblocks.com)

###**Why the name Loki?**

Loki is the Norse god of trickery. This is fitting as we use a lot of digital 'tricks' to obfuscate transactional data. The name is also a play on words, as transactions and communications on the Loki network are very 'Low-Key'.

###**What is the business model behind this peer-to-peer network?**

Loki operates on an incentives structure provided by the network. Peer-to-peer communications only occurs through the [Service Node](../ServiceNodes/SNOverview) layer which is already incentivised to run so there is less of an incentive to provide any additional businesses models. The business model post-launch for the Loki Foundation is twofold: first, to continue to build core [Loki Services](/LokiServices/LokiServicesOverview), and second, to aid in the development of 3rd party SNApps which Loki Service Nodes can optionally operate.

###**Will you guys commit back to the Monero source code?**

Loki plans to push back any useful changes to Monero, such as optimisations, bug fixes, and feature adds.


###**What's the difference between Loki and Monero?**

Compared to Monero, Loki has a [fixed ring size](/Advanced/CryptoNoteElements/#ring-signature-size) with a minimum mixin of 10, [governance block reward](/Advanced/Cryptoeconomics/#block-reward-split) of 5% which will [fund community projects and developments](/Governance/LokiFundingSystem), and [emission curve changes](/Advanced/Cryptoeconomics/#loki-block-reward). These are base-layer changes that will differentiate us from Monero; however, the main change that is being implemented is the second layer of incentivised [Service Nodes](../ServiceNodes/SNOverview), [Loki Services](/LokiServices/LokiServicesOverview), and [Lokinet](/Lokinet/LokinetOverview).

###**Can I see details about the premine?**

Yes, see the [premine report](https://loki.network/loki-premine-report/).

###**Why is there a 5% governance reward?**

We intended to create a [self-funding system](../Governance/LokiFundingSystem) so that users can be certain that no external influences can drive the development funding of the network in an undesirable direction. The 5% block reward that is issued to the governance wallet is for this purpose.

This is a similar approach to other projects, such as the Zcash Foundation, who for the first 4 years of the network’s operation will receive a 20% block reward, and the DASH project, who receive a 10% block reward from the network.

We wanted to keep the governance reward significantly smaller than Zcash and DASH, but we also want to ensure that the amount is enough to sustain the project indefinitely.

In the future, the community may decide that this reward is unnecessary, or of too high or too low a proportion, in which case, a hard fork event may change the nature of this block reward split.

###**What is the block reward for mining?**

The exact block reward can be found at [www.lokiblocks.com](https://www.lokiblocks.com). This block reward is split as follows: 50% of the block reward goes to service nodes, 45% to miners, and 5% to the governance pool. You can see more details on the block reward split [here](../Advanced/Cryptoeconomics/#block-reward-split)

###**What is the block generation time?**

About 120 seconds.

###**Are there plans to support Loki on the Ledger Nano S hardware wallet?**
Yes, support is in the works.

---

Service Nodes
---

###**Why are Service Nodes required?**

[Loki Service Nodes](../ServiceNodes/SNOverview) form a second-layer network that allows for anonymous networking using a novel garlic routing technology. Service Nodes will route data being passed through our onion router, called [Lokinet](../Lokinet/LokinetOverview). [SNApps](../Lokinet/SNApps) are the front-end user-facing applications enabled by this network of service nodes. SNApps do not run on the blockchain, but rely on the consensus rules of the blockchain to enforce service node behaviour. This also means that SNApps do not impact blockchain scalability. Service nodes don't mine blocks, but they do propagate and validate blocks like regular full nodes.

###**Is there a concept of 'Masternodes' in Loki?**

Yes, they are called [Service Nodes](../ServiceNodes/SNOverview) in Loki.

###**What is the collateral requirement to run Service Nodes?**

The initial requirement is 20K $LOKI, though this will adjust downward over time. Pools are also allowed, and can include up to 4 people.
For more information on the collateral requirement [click here](../ServiceNodes/StakingRequirement).

Check out the collateral calculator [here](https://jagerman.com/sn/) to see the current requirement. You can either run a single node or join a pooled node. For a single node, you will need to stake the full collateral. For a pooled node, the operator and all but one of the 4 contributors must have at least 25% of the required total collateral. See more details on service nodes in the [Service Node Portal](https://loki.network/service-nodes-portal/).


###**Can you run multiple service nodes in a single VPS server?**

It is recommended that you run different VPS instances for each [service node](../ServiceNodes/SNOverview), however it is not required.

###**Can a pool member request for the stake to be unlocked?**

In pooled nodes, any contributor that requests the stake be unlocked will schedule the service node for expiration. 

---

SNapps
---

###**Do SNApps run on Service Nodes only?**

When accessing a [SNApp](../Lokinet/SNApps) your data is obfuscated by being routed through multiple service nodes. However, the SNApp you are accessing is hosted on servers, similar to hidden services in Tor, and is computed client-side.


###**Are SNApps like DApps?**

In the sense that their core function is 'decentralised,' yes. However, unlike most DApps, [SNApps](../Lokinet/SNApps) do not rely on on-chain execution or computation. All Loki SNApps are computed client-side, and the networking is handled offchain by the [service node](../ServiceNodes/SNOverview) network.

###**Where will SNApps and all of their data be hosted?**

[SNApps](../Lokinet/SNApps) are similar to hidden services in Tor; they are hosted on servers by users.

---

Loki Services
---

### **What is Loki Messenger?**

[Loki Messenger](../LokiServices/Messenger) is a decentralised, end-to-end encrypted private messaging service. Many other encrypted private messengers rely on central servers to route traffic. Loki Messenger leverages the power of public-private key cryptography and the [Loki Service Node](../ServiceNodes/SNOverview) architecture on the Loki network to create a service similar to the secure messaging application Signal, but with the added benefit of decentralisation and network anonymity.