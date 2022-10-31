# Dev Community Whitepaper

```
Whitepaper Versioning
The current version of this whitepaper is v1.0.0.
```

```
This whitepaper is non-static and evolves over time as errors get corrected, new concepts and
technologies are incorporated, changes to governance protocols are made.
Old versions of the whitepaper are archived and hashed, to provide an immutable history .
```

#### We proudly open source the whitepaper's evolution for all to see.

## Abstract

This whitepaper discusses ideas and steps needed for the formation and connection of a powerful and decentralized network of developer communities.

The authors of this whitepaper are primarily developers and community organizers. Let their North star be creating solutions to the dev problems they face in their personal experience, and creating communities they themselves want to be a part of.

Welcome to the world's number-one developer community.
We provide the best solutions, the best teachers, and the best source of developer education in the world. We believe in transparency and adding value to the ecosystem without any central governance.

#### Table of Contents

**Part 1 - Blockchain Developers United Meetups**

```
Overview
M​eetups
Onboarding Organizers
BDU Membership
BDU Governance
```
**Part 2 - Devcash: Cash for the Developer Economy**

```
Overview
Devcash Bounty Marketplace
Private Bounties
Standards Track Adherence
Service Execution Agreements
```
**Part 3 - Developer Resource Economy**

```
Market Analysis
Devcash Allocation
Ethereum Contract Details
```


## Part 1 - Decentralized Developer Communities

### Overview


### Existing Dev Communities

### New Dev Communities

### The Power of Dev

“Software runs the world” is a common saying in this day and age. The world needs developers not only to build and maintain that software, but to do it in such a way that benefits humanity and the world instead of harming it.

As an emergent Decentralized Autonomous Organization our primary goal is to broaden and enrich
the blockchain ecosystem, beginning at the center and pushing out towards the periphery.

The meetups bring
together developers of varying technical skill to learn, share and develop technical skills. Our
mentorship programs aim to provide an advancing path for developers to earn a living in the space.

The bounty platform provides an interface for our developers to tackle new problems and
earn at the same time.

### History
Blockchain Developers United(BDU) began with a single Meetup Group in Toronto, Canada, which
focused on providing hands-on workshops on programming blockchain applications. The first meetup
took place in Toronto in June 2017 with the philosophy that no matter what the topic of the Meetup, it
must provide attendees with hands-on programming experience. Our modus operandi is to prioritize
hands on coding, ranging from step-by-step instructions in working code examples to more complex
concepts.


- To provide hands on developer training
- To train local blockchain developer talent
- To collaborate on projects small and large
- To provide a meeting place and open learning environment
- To provide community testing and debugging
- To provide the community access to commonly used developer resources
- To connect developers with teams looking for talent

The ideal tutorial is clear, straightforward, and demonstrates unambiguously a step by step approach
to achieving an end result. All tutorials fall within this basic framework:

```
● Define a goal
● Step-by-step tutorial
● Evaluate results and answer questions
```

We take no issue with using tutorials pulled from other sources, as long as they are open source and
fully credited. All tutorials must be open source under CC BY 4.0^1. A tutorial outline can be understood
as a map or a learning path for mastering a specific blockchain development platform, intended to
guide developers on their learning journey. BDU also hosts regular online seminars which are free
and open to everyone. Projects can have community designated project managers who can lead
coding efforts and manage incoming pull requests and issues. Useful blockchain tools, libraries, and
developer resources from across the internet-wide developer ecosystem can be reference-linked or
forked and modified.

(^1) https://creativecommons.org/licenses/by/4.0/

### Global Dev Registry

To become a member you need to have attended at least one BDU meetup. All core organizers have
the ability to verify new members. To record BDU membership, we use a dedicated smart contract
which only stores the name of the member and the local group they belong to. Since on-chain data is
fully public, joining BDU is understood to be an open declaration of membership, viewable by anyone
in the world. Our primary motivation is to encourage the reduction of barriers to entry in mastering
blockchain technology. We support this objective by incentivizing the completion of tutorials on BDU
and affiliate platforms.

### BDU Governance

At the outset it is most practical that the decision making powers be managed by the
core team. Over time however we intend to re-allocate this power to the community. We will select the
first wave of new governance actors on the basis of their capability and commitment to helping us
grow during the formative stages of the platform and its services.

## Part 2 - Devcash: Cash for the Developer Economy

### Overview


Two important aspects of Devcash are its utility and distribution. Good utility gives
people ways to use Devcash and a reason to hold it, and good distribution spreads it to those who
contribute the most as well as those who would have the greatest use for it.

We also use Devcash to promote learning and teaching blockchain development at BDU. Devcash
incentivizes individuals to share technical knowledge and conversely for individuals to strive to learn
and achieve competency, as we believe there is no better way to learn than to teach. We encourage
the reduction of barriers to entry in learning blockchain technology. This is achieved implicitly in
Devcash’s earning and spending structure. It encourages individuals to take their education and
involvement to the next level, whatever that may look like for them.

**Earn Devcash**

Developers can earn DevCash by:

```
● Participating in our community. Answering questions on the forum (under active development)
and being voted the most useful response
● Posting bounties
● Completing bounties
● Hosting meetups
● Attending meetups
```

Unique utilities or discounts can be made available to those who have earned a reputation on the
network. The value of Devcash may increase for those with higher reputations. Therefore, Devcash’s
value might exceed the bare market value for these members and provide developer resource specific
value in addition to its monetary value.

### Devcash Bounty Marketplace

The Devcash Bounty Platform was first envisioned as a way to leverage the community building
activities of Blockchain Developers United.
building out a portfolio of completed tasks and projects in the blockchain space.

The Devcash Bounty Marketplace is where issuers can post bounties and release the bounty after
work is performed, and where bounty hunters can post requests for bounties and perform the work
once the request has been fulfilled.

### Service Execution Agreements

Service Execution Agreements (SEAs) define the conditions and fulfillments of a service as code in a
smart contract. This commitment between two (or more) actors explicitly states what the individuals
posting the bounty expects. This provides posters a more expressive way of defining what they are
looking for and a guarantee that the execution must meet the conditions in order to fulfill the payout of
the execution.

Conditions allow us to flexibly encode Proof-of-Service into SEAs. Conditions are the challenges to be
solved and fulfillments are the solutions. Reward logic distributes the outputs depending on the
fulfilled conditions. ​SEAs also add layers of mathematical security (encryption, signatures, hashes,
cryptographic proofs & attestations) and automation.​ ​The execution of these agreements can be
managed autonomously with little to no interaction once the terms have been agreed upon.


Service Execution Agreements present a powerful solution to a whole host of challenges on existing
bounties and freelance platforms.

In an imperfect world, we deal with off-chain, on-chain, side-chain and other-chain services and
events. These services can either execute correctly, fulfill partially, or even fail. At some point in time
the SEAs will be interested in knowing the status of these services to settle or resolve disputes.
Hence, we must have conditions and fulfillments: cryptographic and non-cryptographic conditions that
can be fulfilled. Each condition has a validation function that returns a state: “True”, “False“ or
“Unknown”. An “Unknown” value implies that a condition has not been fulfilled. All conditions have the
same initial state of “Unknown”. The validation logic is executed on-chain.

SEAs have a modular design to give flexibility for onboarding and consuming a variety of web2.
(cloud/on-premise) and web3.0 services.

The service agreements have several components: a ​ _DID_ ​ (decentralized identifier— ​defined​ by the
World Wide Web Consortium Credentials Community Group, the W3C CCG); a ​ _serviceAgreementId,_
referencing the unique agreement between the consumer and publisher; a ​ _serviceDefinitionId_
referencing the service the consumer wishes to use; and a ​ _templateId,_ ​referencing a service
agreement template from which the unique service agreement is derived. With these components, the
transaction can be clearly defined and executed.

We provide SEA templates for several contracts. Posters can select op of new conditions such as:

1) Digital Identity- holds certain credentials

2) Release partial payments of the term in agreement depending on the percentage of fulfillment

Once the new template is created, the user can create a new service agreement by calling the new
_templateId_ ​and submitting it to the network. Once the service agreement has been signed by both a
service provider and a consumer, it will be initialized on-chain, and a new and custom service
agreement is created and agreed upon.

Conditions can vary from simple cryptographic challenges (e.g. provide a pre-image which hashes to
a value with 14 trailing zeros, or prove that you have the private key corresponding to a public key), to
more complex ones (e.g. STARKs, proof-of-retrievability) and to more subjective ones (e.g. m-of-n
signatures in a vote based attestation scenarios, stake/slash).

Each condition/fulfillment is a cryptographic challenge/proof pair such as:

- Hash / pre-image: find a pre-image that computes to a given hash. The computation of the
    hash of the pre-image happens on-chain. This condition is useful for a party to prove that they
    have knowledge of a secret (without revealing that secret).
- Public key + message / signature: sign a given message with a private key corresponding to a
    given public key. The verification of the signature happens on-chain. Useful for a party to
    prove that they have the private key corresponding to the given public key, and the message
    wasn't altered in transit.
- m-of-n threshold: validates the proof to be “True” if m out of n conditions have been correctly
    fulfilled. Useful for multi-party dispute resolution such as voting.


- Query/resolve: link to a publicly available state value (that is recorded with a timestamp) and
    resolve/compare that value upon validation. The query is executed on-chain, hence it’s
    limited to GET operations within the state context of the chain (e.g.
    contractAddress.getValue). This is useful to bridge services and oraclize off-chain values.

Conditions can be combined to build more complex logic to express:

- Payment conditions: the amount of tokens submitted to the contract equals the predefined
    asset price.
- Access control: an access-control secret has been communicated with one or more parties.
- Escrow or Hold Agreement: tokens are locked up in an SEA to be executed if all conditions
    are fulfilled before a timeout occurs. Executing the payment means that the locked tokens can
    be transferred to the receiving party. The agreement will be aborted if all the conditions aren’t
    fulfilled when the timeout occurs. Aborting the payment means that the locked tokens are
- returned to the party from which they initially belonged.

## Part 3: Developer Resource Economy

*To be shaped in coordination with all platform contributors through the term of the
forthcoming Initial Bounty Offering (IBO).



### Devcash Allocation

Initial distribution will be achieved via an Initial Bounty Offering. ​Devcash will be allocated towards
developer bounties to support the BDU ecosystem and ensure that it thrives with useful developer
resources. The plan for the Devcash IBO is under active decelopment.

### Ethereum Contract Details

DevCash contract address: ​0x73aa31Cd548AC14713F778f454348d90564e2dE
Contract code: ​https://github.com/BlockDevsUnited/DevCash-ERC
The maximum supply is 2,100,000,000.
DevCash allocation is managed from within a gnosis safe with 4 signing members and a requirements
of 3/4 signatures to move the balance. We are working on identifying alternatives and expect to
transition from this model to a more robust and stake based alternative.


### Current Task List


```
● Creation of Widget for Devcash Bounty Platform - ​ within 3 months
```
```
See:​https://vuidget.danajanoskova.sk/
https://github.com/DJanoskova/Vuidget
a) Widget can be paired to an ethereum address(the one that the third party is
posting bounties with)
```
```
● Github REST API v3 and Circle CI. Create labels for programming languages, web
frameworks. Utilize github commit history and topics to recommend user with
experience on a project that is similar.
See:​https://towardsdatascience.com/github-recommender-system-python-c8ff64dc
f4​ ​ ​- ​ within next 6 months
```

#### Layer 2 scaling solution - Evaluation

```
● ZkSync+Zinc - Superior Option but Zinc is still in development
Notes: zkSync can be used only for secure token transfers. However, smart contracts
are a cardinal part of the zkSync roadmap. Since summer 2019 there has been
significant progress on Zinc, a developer-friendly programming framework to create
zero-knowledge proof circuits. It will soon be possible to write smart contracts for
zkSync in Zinc following very similar conventions you are used to with programming
Ethereum in Solidity. ​ ​- ​ within next 6 months
```
```
● Matic Network - Strong Option, ready for production, but not as powerful as ZkSync.
Notes: Adapted version of Plasma framework that provides a solution for faster and
extremely low-cost transactions with finality on the main chain(ethereum).
```​ **within next 3 months**

-
