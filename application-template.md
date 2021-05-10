# W3F Open Grant Proposal

> This document will be part of the terms and conditions of your agreement and therefore needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with a `>` (such as this one) can be removed.
>
> See the [Open Grants Program Process](https://github.com/w3f/Open-Grants-Program/#pencil-process) on how to submit a proposal.

* **Project Name:** Decentralized Exchange for Contracts
* **Team Name:** Chain Complex
* * **Payment Address:** BTC or Ethereum (DAI) payment address. We don't accept payments for the program in other currencies at this stage. (e.g. 123mp123...)


> ⚠️ *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*

## Project Overview :page_facing_up:

Many matching schemes do not only match agents but also determine contractual details of a matching. In practice, contracts are often incomplete and parties might renege on promises made during the contracting phase. Blockchain technology offers the possibility to write self-enforcing contracts that mitigates these problems and does not require legal enforcement in case of dispute. Moreover, it facilitates writing complete contracts that specify consequences for all possible contingencies.

### Overview

Please provide the following:

* Decentralized implementation of matching with contracts.
* A brief description of your project.
* An indication of how your project relates to / integrates into Substrate / Polkadot / Kusama.
* An indication of why your team is interested in creating this project.

### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

* Mockups/designs of any UI components
* Data models / API specifications of the core functionality
* An overview of the technology stack to be used
* Documentation of core components, protocols, architecture, etc. to be deployed
* PoC/MVP or other relevant prior work or research on the topic
* What your project is _not_ or will _not_ provide or implement
  * This is a place for you to manage expectations and to clarify any limitations that might not be obvious

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

We have three papers on the economic aspects and usecases of blockchains: 

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
    
### Team Code Repos

* https://github.com/Chain-Complex
* https://github.com/orgs/Chain-Complex/people/kakia89
* https://github.com/orgs/Chain-Complex/people/giorgi128

### Team LinkedIn Profiles

* https://www.linkedin.com/in/akaki-mamageishvili-b40824b3/
* https://www.linkedin.com/in/christoph-schlegel-77981943/

## Development Status :open_book:

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

* links to improvement proposals or [RFPs](https://github.com/w3f/General-Grants-Program/tree/master/rfp-proposal) (requests for proposal),
* academic publications relevant to the problem,
* links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
* references to conversations you might have had related to this project with anyone from the Web3 Foundation,
* previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that the scope of the work can fit within a three-month period and that teams structure their roadmap as 1 milestone ≈ 1 month.

For each milestone,

* make sure to include a specification of your software. _Treat it as a contract_; the level of detail must be enough to later verify that the software meets the specification.
To assist you in defining it, we have created a document with examples for some grant categories [here](../src/grant_guidelines_per_category.md).
* include the amount of funding requested _per milestone_.
* include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
* provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
* commit to providing Dockerfiles for the delivery of your project.
* indicate milestone duration as well as number of full-time employees working on each milestone, and include the approximate number of days along with the cost per day.
* _Deliverables 0a-0d are mandatory_ and shall not be removed, unless you explicitly specify a reason within the PR's `Additional Notes` section (e.g. Milestone X is research oriented and as such there is no code to test).

> :zap: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview

* **Total Estimated Duration:** 4 months
* **Full-Time Equivalent (FTE):**  0.8 FTE
* **Total Costs:** 30,000$

### Milestone 1 Example — Solution Concept

* **Estimated Duration:** 2 months
* **FTE:**  0.8
* **Costs:** 15,000 USD

We will come up with the solution concept and publish an academic paper about it.

### Milestone 2 Example — Defining Specifications
* **Estimated Duration:** 2 month
* **FTE:**  0.8
* **Costs:** 15,000 USD

We will define implementation roadmap, using Polkadot development tools. 

## Future Plans

Please include here

* In the short run, we will implement our algorithm, immediately after specifying required roadmap.
* We will find users to use our product or offer .


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website / Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

* Work you have already done.
* Wheter there are any other teams who have already contributed (financially) to the project.
* Previous grants you may have applied for.
