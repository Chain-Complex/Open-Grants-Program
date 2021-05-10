# W3F Open Grant Proposal

> This document will be part of the terms and conditions of your agreement and therefore needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with a `>` (such as this one) can be removed.
>
> See the [Open Grants Program Process](https://github.com/w3f/Open-Grants-Program/#pencil-process) on how to submit a proposal.

* **Project Name:** Decentralized Exchange for Contracts
* **Team Name:** Chain Complex
* * **Payment Address:** Ethereum (DAI) payment address: 0xA015048555940B3fE5989Fbb75A2ef9E178e9859


> ⚠️ *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*

## Project Overview :page_facing_up:

* Decentralized implementation of matching with contracts.

### Overview

Many matching schemes do not only match agents but also determine contractual details of a matching. In practice, contracts are often incomplete and parties might renege on promises made during the contracting phase. Blockchain technology offers the possibility to write self-enforcing contracts that mitigates these problems and does not require legal enforcement in case of dispute. Moreover, it facilitates writing complete contracts that specify consequences for all possible contingencies. On the application layer we will design a user interface. There will be an off-chain distributed system calculating a matching -- using the programming languages C++ and Kotlin, the latter for shared-memory programming. On the smart-contract level, we will use Solang. On the blockchain (sub- or para- chain) level, we will maintain a distributed database and access controls for users. How exactly this mixture of off- and on-chain computations works is a part of a research question we address. 


### Project Details

* An overview of the technology stack to be used:

After checking Polkadot development tools, we find the following tools and projects (potentially) useful for our project:  

Smart Contract Language: Solang.
Parachain Dev Kits: Gantree.
Client Libraries: Go, C++, C, Haskell, Javascript, Substrate API Sidecar - TypeScript, Python, Java(new), PHP.
Randomness: DKG and Randomness Beacon.
Bridges: Ethereum by Centrifuge, POA <> Substrate, Substrate <> Ethereum DAI Bridge, BTC by ChainX, Polkadot Ethereum Bridge.
Privacy: ZeroChain, Automata Network.
ZKP: ZeroPool, Megaclite.


* Disclaimer: This is a first stage of a bigger project, so only solution concept and specifications will be provided. 

### Ecosystem Fit

Help us locate your project in the Polkadot/Substrate/Kusama landscape and what problems it tries to solve by answering each of these questions:

* Where and how does your project fit into the ecosystem?
* Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
* What need(s) does your project meet?
* Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem?
  * If so, how is your project different?
  * If not, are there similar projects in related ecosystems?

## Team :busts_in_silhouette:

### Team members

* Akaki Mamageishvili
* Jan Christoph Schlegel, Giorgi Nadiradze 

### Contact

* **Contact Name:** Akaki Mamageishvili
* **Contact Email:** akaki@chaincomplex.ch
* **Website:** http://chaincomplex.ch/

### Legal Structure

* **Registered Address:** Oerlikonerstrasse 94, 8057 Zurich
* **Registered Legal Entity:** Chain Complex KLG

### Team's experience

Akaki Mamageishvili holds a Bachelor's degree in mathematics from Tbilisi State University, and Master's and Ph.D. degrees in theoretical computer science from ETH Zurich. His research areas during Ph.D. studies were algorithmic game theory and algorithmic mechanism design. After his Ph.D. studies, he became a postdoc at the Department of Management, Technology and Economics at ETH Zurich, and was later promoted to senior researcher. He works on mechanism design and voting questions, often with applications to decentralized systems such as blockchains. He has published in leading journals in economic theory and operations research such as *Journal of Economic Theory, Games and Economic Behavior, International Journal of Game Theory, Operations Research Letters* as well as computer science conferences such as *WINE, MFCS, IEEE ICBC*. He is a regular participant of programming competitions. Recent successes include 4 times Google Haschode finals (2016,2017,2019,2020), with 3rd prize place in 2017.   


Webpage: \url{http://mamageishvili.info/}. 

Jan Christoph Schlegel holds Bachelor's and Master's degrees in mathematics from ETH Zurich and a Ph.D. in economics from HEC Lausanne (awarded the Prix de Faculté). Since finishing his Ph.D. studies in 2017 he works at the Department of Economics of the City, University of London first as a Lecturer (Assistant Professor) and now as a Senior Lecturer (Associate Professor). His main areas of research are market design and matching theory, in particular mechanism design for matching markets, and topics at the intersection of Economics and Computation. He has published extensively on these topics in leading economic theory journals such as the *Journal of Economic Theory, Games and Economic Behavior* and computer science conference such as the ACM Conference on *Economics and Computation (EC)*. He regularly works as an expert for \emph{Swiss Economics AG}, a consultancy, to advise blockchain start-ups on questions of pricing, ICOs, and the design of token economies.

Webpage: \url{https://christophschlegel.com}

Giorgi Nadiradze holds a Bachelor's degree in computer science from Tbilisi State University, a Master's degree in mathematics from the Central European University, and a Master's degree in computer science from Saarland University. Currently, he pursues Ph.D. studies at IST Austria. His research areas are distributed computing and machine learning. He has published in leading computer science conferences such as *SODA, PODC, ICALP, SPAA, AAAI. 

    
### Team Code Repos

* https://github.com/Chain-Complex
* https://github.com/orgs/Chain-Complex/people/kakia89
* https://github.com/orgs/Chain-Complex/people/giorgi128

### Team LinkedIn Profiles

* https://www.linkedin.com/in/akaki-mamageishvili-b40824b3/
* https://www.linkedin.com/in/christoph-schlegel-77981943/

## Development Status :open_book:

* References to conversations you might have had related to this project with anyone from the Web3 Foundation: Sebastian Muller and Marcin Gorny. 


### Overview

* **Total Estimated Duration:** 4 months
* **Full-Time Equivalent (FTE):**  0.8 FTE
* **Total Costs:** 30,000$

### Milestone 1 Example — Solution Concept

* **Estimated Duration:** 2 months
* **FTE:**  0.8
* **Costs:** 15,000 USD

We will research and enquire Polkadot blockchain properties for implementing contract matching algorithm in a decentralized way. During the research phase we will come up with the solution concept and publish an academic paper about it.

### Milestone 2 Example — Defining Specifications
* **Estimated Duration:** 2 month
* **FTE:**  0.8
* **Costs:** 15,000 USD

We will define implementation roadmap, relevant , using Polkadot development tools. 

## Future Plans

* In the short run, we will implement our algorithm, immediately after specifying required roadmap.
* We will find businesses to use our product or offer it as our product to end users.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website / personal recommendation

* Work we have already done.
   
   Three papers on the economic aspects and usecases of blockchains: 

   * Akaki Mamageishvili, Jan Christoph Schlegel:
      Optimal Smart Contracts with Costly Verification. IEEE ICBC 2020: 1-8
 
   * Akaki Mamageishvili, Jan Christoph Schlegel:
      Mechanism Design and Blockchains. CoRR abs/2005.02390 (2020)
    
   * Jan Christoph Schlegel, Akaki Mamageishvili
      On-Chain Auctions with Deposits.  	arXiv:2103.16681 (2021)

Akaki Mamageishvili has written 2 more papers relevant to this topic:

   * Simon Janin, Kaihua Qin, Akaki Mamageishvili, Arthur Gervais:
      FileBounty: Fair Data Exchange. EuroS&P Workshops 2020: 357--366
     
   * Hans Gersbach, Akaki Mamageishvili, Manvir Schneider:
      Vote Delegation and Malicious Parties. IEEE ICBC 2020: 1--2
