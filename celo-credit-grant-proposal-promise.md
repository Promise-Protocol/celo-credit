# Celo Credit Grant Proposal by Promise
Published February 5, 2020

## What is the name of your company/project?
Promise

## Where are you located?
San Francisco

## Provide your company URL:
[https://www.promiseprotocols.com/](https://www.promiseprotocols.com/)


## Describe your company/project
Promise is a decentralized credit protocol aimed at providing universal access to credit services that include credit, credit tracking, and repayment risk management for those without established credit or access to sophisticated credit services. The Promise team has extensive experience in cryptography, credit, and credit risk with over 10 years of credit and collections expertise.

Promise aims to build a useful on chain reputation-building systems without the need for extensive off-chain identity management. Promise uses a specific cryptography innovation called proxy re-signatures, developed by team member, Professor Giuseppe Antienese. Proxy re-signatures enable users of a protocol to use a proxy re-signature key to re-sign transactions on behalf of other, assigned users, that have created and distributed the proxy re-signature key. The resulting signature from the proxy re-signature key will be a signature that is indistinguishable from the private key signature of the original funds holder.

The capability of Promise is that it allows for group signature functionality that acts as re-signing functionality for the disbursement of funds, but with original signature as the recorded signature on the blockchain. Promise allows anyone to delegate spending, in their signature, so that commitments for repayment may be used via proxy re-signature to complete credit obligations within a specified period of time.

## Tell us about your team
**Taariq Lewis (Cryptography and Engineering):**
Cryptocurrency engineer community development since 2013. Credit and repayment expertise as founder of Aquila and Promise. Co-author of the Stronger Promises Protocol whitepaper for implementing decentralized, private credit transactions on a blockchain for reputation building. Expertise in repayment risk management for underbanked and low-credit scoring individuals. Founder of crypto payments platform Serica and digital gold and equities trading platform DigitalTangible.

**Professor Giuseppe Anteniese (Cryptography)**
Giuseppe Ateniese is the David and GG Farber Endowed Chair in Computer Science and department chair at Stevens Institute of Technology. He was with Sapienza-University of Rome (Italy) and Assistant/Associate Professor at Johns Hopkins University (USA), and one of the founders of the JHU Information Security Institute. He is the author of Proxy Re-Signatures: New Definitions, Algorithms, and Applications, 2005. More about Giuseppe is here: https://web.stevens.edu/facultyprofile/?id=2182

**Juan Jeni (Cryptographic engineer)**
Juan Jeni is an active contributor to the various blockchain protocols including, Cosmos, Grin, as well as Ethereum. Although he remains anonymous, he has extensive merged pull requests of code to support some of the leading blockchain protocols. Juan has deep expertise in signature upgrades to various chains. More about Juan Jeni is here: https://github.com/jleni

**Jason Jacobs (Platform Engineering):**
Jacob is the lead engineer at Aquila Services Inc. He has over 15 years of software engineering expertise and has over 3 years developing and shipping repayment performance tracking systems for Aquila. Jacob will bring engineering expertise to design proper credit performance tracking of proxy re-signature transactions. More about Jacob is here: https://www.linkedin.com/in/rootedbox/


## What is your proposal?
How would you like to contribute to our mission of building an open monetary system that creates conditions of prosperity for all?
Promise proposes to bring credit infrastructure to the Celo protocol called Celo Credit. Celo Credit will be built on a proposed fork and implementation of Promise’s proxy re-signature architecture on the Celo core protocol. Promise will then test its re-signature implementation with a demonstration of how this technology would work for the greater Celo community.

Celo Credit will allow users to delegate spending of delegated funds as the user, which requires more verification and trust effort instead of a group signature scheme such as a multisignature wallet. Celo Credit users will be able to participate in a credit community where funds can be spent to support credit obligations and commitments to replay.

The Celo community aims to target new and innovative ways of  developing reputations tied to digital identities. Celo also aims to make financial tools universal. It’s the Promise view that this resignature technology will enable a new type of decentralized credit system.


## What level of investment is required to achieve this?
We are seeking  a grant of $100,000 to implement proxy re-signatures on a Celo fork with the goal that the eventual functionality, if successful, will be merged into Celo’s core client as “Celo Credit”. We expect that this effort will take anywhere from 6 months to 1 full year of cryptography software engineering and cryptography work  in order to review successful deployment as a Celo fork for testing before proposing merges into Celo’s protocol.

**The investment required to cover the costs are outlined below:**

Celo Credit Grant Proposal Budget (Team of 4)

Milestone | Activity Description
--------- | --------------------
1 | Fork & Implementation of Al Gamal signature scheme
2 | Test and verification of signature scheme interaction on Celo
3 | Professor Ateniese Engagement for 2 months to advise project
4 | Creation of Proxy Re-signature scheme using strong Private Key and Weak Private Keys
5 | Proxy re-signature key signatures as valid spend transaction signatures in Celo
6 | Successful test of spending funds from a Celo public key to another public key as the original signature with proxy re-signature key
7 | Creation of Merkelized Asset Syntax Tree for storage of Celo Credit state
8 | Storage of successful repayment contract states in Celo without need for a smart contract
9 | Authorization public key implementation for proxy re-signature rules
10 | Consensus rules upgrade and testing for authorization keys to allow for valid and authorized transactions
11 | Perform security guarantee audit for authorization keys and proxy re-signature keys
12 | Documentation of Promise implementation of Celo Credit
13 | Celo Credit Testnet with Dashboard of Celo Credit lines open, in repayment, or in default
14 | Merge Celo Credit with Pull Request for evaluation by Celo Team


## What are the milestones to track progress?
The milestones will be as follows:
1. Milestone 1: Successful fork and implementation of proxy re-signature scheme on the Celo fork with the appropriate Al Gamal signature schemes.
2. Milestone 2: Implementation of  creation of proxy re-signature key on Celo fork. Implementation of re-signatures on Celo fork with the ability to spend funds from a Celo public key to another public key as the original signature
3. Milestone 3:
Demonstration of a proxy re-signature transaction on Celo
Demonstration of revocation of a proxy re-signature key
Demonstration of tracking of credit available and outstanding  of those public keys with proxy re-signatures and re-signature transactions
Presentation of Celo Credit to the Celo team with the offering of proxy re-signature keys
Demonstrate security guarantee audit for authorization keys and proxy re-signature keys
Documentation of Promise implementation of Celo Credit

## How do you plan to measure success?
We intend to measure success in the following ways:
1. Successful implementation of a proxy re-signature scheme on Celo fork
2. Demonstrate usage of the proxy re-signature scheme via a number of successful transfers of funds on Celo from a proxy re-signature scheme implementation where funds from one user are transmitted to another public key via a proxy re-signature key, while still maintaining the signature of the original private key
3. Demonstrate how Promises are stored on the Celo Credit blockchain data architecture
4. Demonstrate a credit wallet on Celo Credit fork where these features are invisible to the user, but the functionality for credit is demonstrable.
