---
layout: default
permalink: /worker/
language: en
---

# Overview

A so called **worker proposal** on the BitShares Blockchain is a means
to get rewarded for contributing to the BitShares ecosystem realized
in a decentralized and trustless way on the blockchain.
Once a worker proposal is approved by the BTS holders, funds are obtained
in BTS through an algorithm from the working budget of the BitShares DAC.

# Background

The BitShares Blockchain in its technical implementation only
knows one type of worker proposal. It contains a name, reward receiving
account, daily BTS rate and a link to provide insight into
the purpose of the worker proposal. Anyone can create a worker
proposal on-chain, and afterwards all BTS token holders can vote
on it. If it passes the threshold given by the refund workers and
receives at least part of the asked daily BTS, it is considered
active.

The BitShares community informally split worker proposal into two
types, reward and opinion worker proposals. The former is meant
to provide BTS for a kind of activity as defined by the worker
proposal, the latter is meant to make strategic decisions and to
agree on the consensus changing development and introducing new
features of the BitShares core (BitShares Improvement Proposals).

There are facilitating possibilities with an external company to
provide participants of a Worker Proposal with an Escrow
service.

In the following section more details are presented into an
exemplary escrow services. This may not be an exhaustive description,
yet is an attempt to outline best practices. The BitShares Blockchain Foundation
itself does not offer escrow services.

# How does an escrow procedure typically work

For worker proposals, an escrow service offers the following value
propositions:

 - Reduce volatility risk for both parties. The freelancer has
   the risk of being under-rewarded if the core token price drops,
   the blockchain has the risk to over-reward the freelancer if the
   core token price raises. From a business and service
   provider’s perspective both is unacceptible
 - Operating risk for the blockchain. If the freelancer would be
   rewarded directly from the blockchain, he gets rewarded no matter what
   (assuming the worker remains active), may not deliver what
   was promised, only partially or faulty. It may also happen
   that the freelancer decides to follow a different path with
   the budget, without the need to get re-approval from core
   token holders
 - Initial review and iteration on incoming worker proposals,
   utilizing deep knowledge, experience and feel for the need of
   the BitShares community to produce proposals with increased
   chances of approval. At the end proposals with clear tasks
   and value propositions are published

Certainly using escrow services introduces additional overhead and
requires both trust from the BTS token holders and the freelancer.

The purpose of such a service is to provide security and
transparency to both parties, the BitShares DAC, as well as the
freelancer that performs the work in expectation of receiving BTS.
Setting up a worker proposal with an Escrow service normally sticks to the following flow:

1. Establishing agreement for Escrow service for a defined task, review and iterate
2. Setting up a worker proposal on-chain
3. Escrow obtains BTS from reserves as agreed by majority vote
   in BTS holders
4. BTS can be exchanged into SmartCoins or other assets according to the agreement
5. Freelancer proves delivery
6. Escrow reviews delivery and invoice
7. Freelancer receives rewards
8. Escrow service returns excess BTS to Working Budget of the
   DAC

## Reward worker proposals

The BitShares Blockchain Foundation splits the reward workers into two sub-types,
namely escrow and budget workers. For both workers the

* **escrow workers**: With this, we organize
  freelancers around the world that want to work for the BitShares DAC
  through our trusted escrow setup which carefully vets the individual
  offers, sets them up on the blockchain and ensures the maximum of code
  quality for the BTS token holders.

* **budget workers**: These workers serve as a budget
  that can be tapped whenever it is needed for purposes defined in the
  individual budget workers. This serves as working budget that is more
  flexible then static escrow workers in the way that it allows to reward
  many different people for their support out of a single purpose-specific
  fund.

*Remark 1*
A reward on a worker can only send BTS that have been
obtained through the corresponding worker being active. The
freelancer himself monitors at all times the status of the worker
and available budget.

*Remark 2*
If not otherwise agreed and mentioned in the specific
worker proposal, usually an 5% escrow fee is applied to a reward
on workers. This fee is applicable for each outgoing amount and
needs to be accounted for publicly for each worker.

*Remark 3*
An Escrow service is always separately agreed with
either a legal entity or an individual that has been identified
with their real-world identity. Usually there is a two months
deadline after the handover of the delivery (e.g. when a sprint or
milestone has been completed). After this timeframe has passed,
deliveries will be considered most welcome volunteer contribution
to the open source repository of the decentralized Bitshares Blockchain

### Escrow Worker Model

The purpose of escrow workers is to ensure proper rewarding for
the work provided over a period of time and absorb volatility of
the BTS token during that time. Both the freelancer and the BitShares DAC
may experience a reduced risk during an escrowed worker proposal,
especially in longer agreements.

* An Escrow company will usually have an account on the BitShares Blockchain Foundation.
* The worker proposal will automatically redeem it’s funds on a regular basis and the escrow party will exchange these for smartcoins from the market (with reasonable premiums).
* For this reason and due to volatility of BTS, the actual reward of the worker is higher than the USD value.
* The worker proposal that is voted in, will only reward the agreed amount of rewards and will reward in one of the agreed upon assets to the escrow account.
* Every BTS that is not rewarded according to the terms of the worker proposal should be returned to the BitShares DAC's Working Budget
* The amounts available for individual budgets should be presented publicly.

### Budget Worker Model

Budget workers serve as workers that might provide a solution for
specific purposes where escrow workers do not fit, such as
translation work, bug fixing or bounties. The rules could be as
follows:

* An Escrow company will usually have an account on the BitShares Blockchain Foundation.
* The worker proposal will automatically obtain its funds from the BitShares DAC's Working Budget and the escrow party will exchange these for the agreed assets from the market (with reasonable premiums)
* For this reason and due to volatility of BTS, the available budget might vary over time.
* The amounts available for individual budgets should be obtained publicly.

## Opinion worker proposals

###  BSIP Worker Model

BSIP is the abbreviation for *BitShares Improvement Proposal* and is
describes the procedure of improving the BitShares protocol. Every major
change to the behavior of the BitShares Blockchain requires approval by
BTS holders by means of approval voting. This is implemented by means of
a BSIP worker.

## Transparency

Escrow arrangements should be open and transparent on-line where
it concerns dealings with BTS and the BitShares DAC.
All its accounting should be visible for all anonymous parties to see on-line.

# Beneficiaries and Reports

Escrow organisations need to be compliant. Beneficiaries of any of
these models will be asked to authenticate themselves with their
real-world identity. Due to the nature of being a public
decentralized blockchain, all reports for reward request must be published
on line. An approval procedure needs to be in place.
