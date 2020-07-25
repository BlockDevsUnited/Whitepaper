# Blockchain Developers United: An Optimistic Experiment in Decentralized Autonomous Organization

```
Whitepaper Versioning
The current version of this whitepaper is v0.04.
```
```
This whitepaper is non-static and evolves over time as errors get corrected, new concepts and
technologies are incorporated, changes to governance protocols are made.
Old versions of the whitepaper are archived and hashed, to provide an immutable history .
```
#### We proudly open source the whitepaper's evolution for all to see.

## Abstract

Blockchain Developers United (BDU) is a decentralized network of software developer groups who
seek fellowship. We are not an organization in the conventional sense of the word. There are no fees
or dues whatsoever. The only requirement for membership is an honest desire to improve as a
software developer. As a community our greatest wish is to be helpful to other software developers.
After many years of experience we have found nothing which has contributed more to the growth of a
software engineer than the willingness to share what they have learned. We are people who would
normally not mix. But there exists among us a fellowship, a friendliness, and an understanding which
enriches our vocation and personal lives. None of us make a sole vocation of this work. We do not
favour a particular convention or approach towards software development.


#### Table of Contents

**Abstract**

**Part 1 - Blockchain Developers United Meetups**

```
Overview
M​eetups
Onboarding Organizers
BDU Membership
BDU Governance
```
**Part 2 - DevCash: Cash for the Developer Economy**

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


## Part 1 - Blockchain Developers United

### Overview

As an emergent Decentralized Autonomous Organization our primary goal is to broaden and enrich
the blockchain ecosystem, beginning at the center and pushing out towards the periphery.
Meetups, Mentorships and Bounties are the three pillars of our organization. The meetups bring
together developers of varying technical skill to learn, share and develop technical skills. Our
mentorship programs aim to provide an advancing path for developers to earn a living in the space.
The bounty platform provides an interface for our developers to tackle new problems in the space and
earn at the same time.

In order to vitalize and motivate a new resource of the developer economy, we have created a
cryptocurrency called Devcash (DEV).
BDU aspires to be a benchmark towards the emergence of organizations founded on Decentralized
Autonomous Cooperation (DAC).
To contribute to this new economy of developers, we created Devcash (DEV), which is to be used to
support the growth of BDU. However geographically distributed we may be, together in our ambitions
we are united.

Blockchain Developers United(BDU) began with a single Meetup Group in Toronto, Canada, which
focused on providing hands-on workshops on programming blockchain applications. The first meetup
took place in Toronto in June 2017 with the philosophy that no matter what the topic of the Meetup, it
must provide attendees with hands-on programming experience. Our modus operandi is to prioritize
hands on coding, ranging from step-by-step instructions in working code examples to more complex
concepts.

Today, BDU spans a community across the globe with Meetup leaders.

The following is a list of all BDU based meetups:

- Toronto, Canada
- London, Canada
- Waterloo, Canada
- Kingston, Canada
- Montreal, Canada
- Sacramento, CA, USA
- Denver, CO, USA
- Delhi, India

The goals of the meetups are:
● To provide hands on developer training
● To train local blockchain developer talent
● To collaborate on projects small and large
● To provide a meeting place and open learning environment
● To provide community testing and debugging
● To provide the community access to commonly used developer resources
● To connect developers with teams looking for talent


To apply as an organizer for Blockchain Developers United, individuals are expected to commit to
hosting a meetup at least once a month. Each meetup community may determine aspects of its own

#### governance, as well as influence decisions over the governance of BDU as a whole.

## Meetups

Meetups are classified by difficulty: Beginner, Intermediate, and Advanced. A typical BDU meetup
consists of an introductory presentation followed by a 1-2 hour long tutorial.

The ideal tutorial is clear, straightforward, and demonstrates unambiguously a step by step approach
to achieving an end result. All tutorials fall within this basic framework:

```
● Define a goal
● Step-by-step tutorial
● Evaluate results and answer questions
```
**Hands On Tutorials:** ​ Formal presentations on specific developer tutorials. They must involve
hands-on training.

Here’s a simple example:
====================================
**Tutorial name:** ​Export private key from Bitcoin-Qt
**Goal:** ​To export a private key from your Bitcoin-Qt / Bitcoin Core client:
**Dependencies:** ​Bitcoin Core Wallet
**Step-by-step:**

1. Launch your Bitcoin client
2. Click on 'help' in the menu bar (top right)
3. Click on 'debug window'
4. Select the 'console' tab
5. If your wallet is protected by a passphrase (i.e. you have to enter a passphrase before you
    can send) unlock it by typing:
6. walletpassphrase "your walletpassphrase here" 600
7. dumpprivkey [your Bitcoin address here]
**Expected results:** ​This will return the private key which will start with the number 5
Once you have your private key if you had to unlock your wallet you can relock it by exiting or typing:
walletlock
====================================

We take no issue with using tutorials pulled from other sources, as long as they are open source and
fully credited. All tutorials must be open source under CC BY 4.0^1. A tutorial outline can be understood
as a map or a learning path for mastering a specific blockchain development platform, intended to
guide developers on their learning journey. BDU also hosts regular online seminars which are free
and open to everyone. Projects can have community designated project managers who can lead
coding efforts and manage incoming pull requests and issues. Useful blockchain tools, libraries, and
developer resources from across the internet-wide developer ecosystem can be reference-linked or
forked and modified.

(^1) https://creativecommons.org/licenses/by/4.0/


### Onboarding Organizers

Once we decide to add a potential meetup to the BDU network, we have a simple set of protocols to
onboard organizers of new meetups. The onboarding process includes online introductions of new
organizers to existing organizers, sharing an onboarding package, guidance on how to run developer
meetups, allocating a specified allotment of Devcash, and adding the new meetup to the BDU meetup
list.

### BDU Membership

To become a member you need to have attended at least one BDU meetup. All core organizers have
the ability to verify new members. To record BDU membership, we use a dedicated smart contract
which only stores the name of the member and the local group they belong to. Since on-chain data is
fully public, joining BDU is understood to be an open declaration of membership, viewable by anyone
in the world. Our primary motivation is to encourage the reduction of barriers to entry in mastering
blockchain technology. We support this objective by incentivizing the completion of tutorials on BDU
and affiliate platforms.

### BDU Governance

The purpose of BDU’s governance is to establish a convention over the structure of affairs within the
organization. At the outset it is most practical that the decision making powers be managed by the
core team. Over time however we intend to re-allocate this power to the community. We will select the
first wave of new governance actors on the basis of their capability and commitment to helping us
grow during the formative stages of the platform and its services.

## Part 2 - Devcash: Cash for the Developer Economy

### Overview

Devcash is a cryptocurrency which allocates its distribution to support the Blockchain Developes
United network. Two important aspects of Devcash are its utility and distribution. Good utility gives
people ways to use Devcash and a reason to hold it, and good distribution spreads it to those who
contribute the most as well as those who would have the greatest use for it.
We also use Devcash to promote learning and teaching blockchain development at BDU. Devcash
incentivizes individuals to share technical knowledge and conversely for individuals to strive to learn
and achieve competency, as we believe there is no better way to learn than to teach. We encourage
the reduction of barriers to entry in learning blockchain technology. This is achieved implicitly in


Devcash’s earning and spending structure. It encourages individuals to take their education and
involvement to the next level, whatever that may look like for them.

Unique utilities or discounts can be made available to those who have earned a reputation on the
network. The value of Devcash may increase for those with higher reputations. Therefore, Devcash’s
value might exceed the bare market value for these members and provide developer resource specific
value in addition to its monetary value.

### Devcash Bounty Marketplace

The Devcash Bounty Platform was first envisioned as a way to leverage the community building
activities of Blockchain Developers United. Having noticed the early job struggles of many developers
attending our meetups, our organizing body came to the decision of creating a bounties platform: a
place for the developers attending our meetups to get experience while earning and building out a
portfolio of completed tasks and projects in the blockchain space.

The Devcash Bounty Marketplace is where issuers can post bounties and release the bounty after
work is performed, and where bounty hunters can post requests for bounties and perform the work
once the request has been fulfilled.

**Private Bounties**
Some bounty issuers may not want to share their project details publicly for various reasons. In that
case, bounties can be set to private.

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
### Standards Track Adherence

In many standards track documents several words are used to signify the requirements in the
specification. These words are often capitalized. This document defines such words as they should
be interpreted only on the Devcash Bounty Marketplace. The mechanism of this interpretation is
enforced by the flow of the user experience.

The key words "MUST", "REQUIRED", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and
"OPTIONAL" are to be interpreted as described:

**1** ​**. “MUST”** ​/ ​ **"REQUIRED"** ​ means that there is an absolute required condition of the agreement.

**2** ​**. “SHOULD”** ​means that there is a required condition of the agreement. There might exist valid
reasons in particular circumstances to ignore this particular item, but this is of no consequence to the
agreement.


**3. "RECOMMENDED"** ​- means that there is a preference for a condition to be fulfilled but not an
absolute requirement.
**4. “MUST NOT”** ​ means that there is an absolute prohibited requirement as a condition of the
agreement.
**5. "NOT RECOMMENDED"** ​means that there may exist valid reasons in particular circumstances
when the particular action is acceptable or even useful, but the full implications should be well
undertaken when implementing any action described with this label. An alternative course of action
must be agreed upon by both parties prior to agreeing upon the terms.
**6. “MAY”** ​ / ​ **"OPTIONAL"** ​, means that an item is truly optional. One bounty hunter may choose to
include the item because it appears pertinent to the deliverable, or because it enhances the product

**Guidance in the use of these Imperatives**
Imperatives of the type defined in this document define the conditional operands of Service Execution
Agreements of the Devcash Bounty Marketplace.

Goal:

Description:

Wordbank ​- to be used as a benchmark for providing context

```
● Add Create Build Make Improve
```
```
● Change Convert Modify Move Optimize
```
```
● Fix Refactor Resolve Update
```
```
● Configure Implement Integrate
```
```
● Allow Enable Ensure Include Verify
```
```
● Disable Remove
```
```
● Complete Provide Solve Support Use Write
```
Example:

Goal: ​Enhance WsProvider To Support Multiple Endpoints for Gitcoin

Description: ​Currently ​WsProvider​ only takes one endpoint, and incase this particular node
is down, it will lose access to the network. While it is possible to detect disconnect event and
create a new api instance, the existing subscription will be lost.


##### MUST/REQUIRED

Modify ​WsProvider​ to change type of ​endpoint​ to ​string | string[]​.

Update ​WsProvider#connect​ to use next endpoint.

Provide appropriate unit tests.

##### SHOULD

Write using ​web3.js​ library

Create with ​socket.io

##### MUST NOT

Use ​a client and server side transport API based on ​WebRTC​ & ​WebSocket

##### NOT RECOMMENDED

Complete Websocket server written in C

##### MAY/OPTIONAL

Implement ​websocket-as-promised​ - Promise-based W3C WebSocket wrapper: allows to
use promises when connecting, disconnecting and messaging with WebSocket server

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

### Market Analysis

The leader in this space, Gitcoin, has done a tremendous job of engaging and uniting members of the
Ethereum development economy, which includes many other projects that build on their platform and
chains that use the EVM or have developed a similar virtual machine. However, they have largely
ignored the community of blockchain developers from outside of this economy. This is evidenced by
the fact that most projects which don’t facilitate ethereum adoption, either explicitly or within the
aforementioned categories fail to receive submissions for their bounty posts on the Gitcoin platform.

Moreover, we are not strictly Ethereum focused and our ambition is to involve people from every
corner of the emergent decentralized economy. We are global, with resources that extend the world
over given our partnership with the Blockchain Education Network. All of this would be enough if our
team weren’t organized by developers, and weren’t driven to push the boundaries of developing
decentralized economies at scale.


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

#### User Experience

_All UX/UI improvements excluding the widget to be completed in next 2 months_

```
● Add torus sign in option below Portis.
```
```
● Torus Integration. Sign in interface that uses a similar UX/UI as the bar on
https://nano.org/​ (github, twitter, reddit, youtube, etc.) --- stretched across the bottom
of the screen when you first enter the page *you will be able to sign by clicking on
any of these icons see: ​https://app.tor.us/v1.7.3/
Torus DirecAuth to manage application specific private key and create DevCash
interface to replace Torus Wallet confirmations via pop ups.
```
```
● Share on twitter prompt after posting or hunting a bounty.
```
#### ● Export CSV function to allow users to get a complete copy of their transaction

#### history on the platform.

```
● Improvements to Home Page. Additional info re: using the platform
○ 4 animation user story like on paypal.com landing
○ Add logos of our partners at the bottom of Home Page
```
```
● Ability to switch wallets easily, this will sign you out of your current wallet and prompt
you to sign in on another one.
```
```
● When filling out a submission form, at the moment there is a small user experience
issue that the user is unable to see the contents of the post to which they are
submitting a response. Therefore, we would like it so that when the user clicks on
‘Hunt’, the pop out interface includes both the details of the bounty post and an
interface to submit a response. In effect, the pop out interface should expand to fill
most of the available space on the user interface and include two panels(like a book).
The left panel will include the submission details. Right panel allows you to type in
submission response
```
#### ● Creation of Widget for Devcash Bounty Platform - ​ within 3 months

```
See:​https://vuidget.danajanoskova.sk/
https://github.com/DJanoskova/Vuidget
a) Widget can be paired to an ethereum address(the one that the third party is
posting bounties with)
```

```
b) Displays all available bounties by the poster. It can be "hunted" directly on website
of the 3rd party. Bounties can be reviewed and submissions can be made. Bounty
and submissions status, confirmation, approval can all be seen within the widget.
The point being that Bounty Creation and Management can be securely managed
outside of the marketplace.
```
#### Back End Development

```
● Making Native Modules “Less Complicated” by writing Web Assembly Modules and
utilizing API’s and Complex Types to talk to Python Modules running in a Python
Runtime. - ​ within next 3 months
```
```
● Implement an actor model allowing webassembly functions to spawn other functions
and send data to each other, and have each function (a webassembly binary) safely
sandboxed and allow for multi-tenancy.
```
- ​ **within next 3 months**

```
● Developing a DappNode package - ​ within next 3 months
```
```
● Utilize ​https://github.com/netlify/git-gateway​ To be used in creating a full stack
solution for the platform for Events/Issues Section re: ​https://issuehunt.io/​ Ethereum
monitoring for transaction data using Alethio. ​- ​ within next 6 months
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
```
- ​ **within next 3 months**
