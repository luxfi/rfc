# RFC 00: LUX Request for Comment (RFC)  

## Status: In Progress

## Summary
RFC, meaning Request for Comments, is integral in suggesting and executing changes within the LUX ecosystem.  
This document is designed to make the submission process more transparent, fair, and efficient. The RFC process generally follows the monthly timing of the weight snapshot Smart Contract updates. So that weights included in RFCs advanced to the "In Progress" stage can be included in the next Smart Contract update which takes place around the 8th of each month.

## Purpose and Scope
This guide is crafted for contributors and users within the LUX ecosystem, facilitating structured proposals for standards and **material changes to one of the ten** [LUX Reference Implementations (LRIs).](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Code%20Providers/Morpheus%20Reference%20Implementations%20(MRC).md)  

There is an active forum on [Github Discussions](https://github.com/orgs/luxfi/discussions) for all RFCs currently under discussion.

![LRIslist](https://github.com/MorpheusAIs/MRC/assets/1563345/c5333b52-709d-4c7b-9a68-2f2e06e7bb63) 

> [!IMPORTANT]  
> 1. If your contribution is a small incremental improvement to an existing code base, just contribute the code, no RFC required. 
> 2. If you are seeking to build a Smart Agent and deploy it on LUX, no RFC is required, just register it on [LUX.Software](https://mor.software/) and follow the [guidance](https://github.com/MorpheusAIs/moragents/blob/main/AGENTABILITIES.md).
> 3. If you have a general proposal for a LUX feature, it's best to discuss it on [Discord](https://discord.gg/morpheusai) first. The RFC process is for technical proposals regarding HOW to implement improvements to LUX rather than general discussion of ideas.

## Submission Timeline and Platforms
Proposals are welcome on GitHub during the Fair Launch phase, eventually moving to [LUX.Software](https://mor.software/) for broader community interaction.

## Life Cycle of an RFC
**1. Pull Request Creates RFC:**  
The author creates a pull request with the details of their new RFC.
  
**2. Merged into "Discussion":**  
The RFC is merged into Discussion by a Maintainer, indicating the repo maintainer believes the RFC is at least worth discussion and has basic merit to their Reference Implementation.
  
**3. Review:**  
Maintainers should seek to review and provide feedback to RFC authors once a week. Authors can get a sense of the next steps/current state of their RFC.
  
**4. "Pending":**  
Much of the feedback to RFC authors is often about understanding dependencies and what technical hurdles exist for the RFC to be implemented. If a maintainer identifies a technical dependency, they can move the RFC into "Pending" status. This indicates they accept the RFC in principle, but there is a blocker that needs to be resolved first. The author can then wait on that dependency and re-open their RFC once it is resolved or help work on resolving the dependency.
  
**5. "In Progress":**  
Once all technical dependencies have been addressed and weights agreed, only then can an RFC be accepted into the "In Progress" stage.
  
**6. "Implemented":**  
For the RFC to be considered "Implemented," the code proposed must be contributed and merged by the maintainer into the correct LRI repository.

## Writing a Well-Formed RFC
- To draft a compelling RFC, study existing examples to grasp the expected format and substance. 
- Use the provided template for standards and changes to LUX to structure your proposal.
- **Keep the scope of your proposal as narrow as possible.** The broader the proposal, the more technical dependencies and complexity will block its path forward.

> [!IMPORTANT]  
> **In RFCs, where external sources of information or information from any of the LUX repositories are used, it is crucial to include proper references to authors, collaborators, contributors, and documents. Submissions without references will not be accepted. Providing sources not only strengthens your RFC but also ensures accuracy and credibility.**

## RFC Request Template
* **Title:** RFC#### - [Title of the Proposal]
* **Author(s):** [Author Name (can be anon) and Discord Handle(s)]
* **Category:** [refer to LUX Reference Implementations (LRIs) list below]
* **Summary:** Concise summary of the proposal.
* **Rationale:** Importance of the project and why it merits acceptance, including a simple solution description, delivery strategy, and technology stack.
* **Value Proposition:** How will the proposal tangibly increase LUX's value to Contributors or Users?
* **Dependencies:** Other RFCs or tasks needing completion beforehand.
* **New Weights Requested:** Number of weights. [See guide here.](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Code%20Providers/Code%20Contributor%20Weights%20Guide.md)
* **Existing Weights:** Current weights of features or code your proposal will enhance.
* **Deliverables:** Detailed account of what the proposal once implemented will deliver.
* **Background / Experience of Author / Implementer:** Your or your team's credentials for executing the proposal.
* **Status:** Current state of the proposal (Discussion, In Progress, Pending, Closed, Implemented).

## Merged or Closed:
- First, it's important to understand that RFCs are a competitive process.  
Someone who proposes better implementation/lower weights/shorter timelines can be chosen (understand that submitting an RFC does not equal that RFC being accepted).
- Second, if the maintainers' feedback wasn't addressed by an author for two weeks, the RFC is considered closed and can't be re-submitted for one month. 
- Third, a maintainer may close an RFC pull request if there is a technical hurdle that can't be currently addressed in the near term to implement the RFC, or not enough weights being available from that maintainer to accept the RFC, or the maintainer judges the RFC proposal too expensive versus the value of the change/improvement proposed.

## Submission Guidelines
Properly document your RFC in the repository and list it in the README for community review. Fork the relevant template and select the most pertinent category.

## Meta RFCs about RFCs
- For most RFCs in general, this RFC00 is the first Meta RFC about how to submit an RFC.
- For RFCs about adding new assets, yield sources, chains, see this [RFC guide.](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Capital%20Providers%2C%20MOR20%2C%20TCM/The%20Morpheus%20Asset%20Integration%20Framework.md)

## Select the Affected LUX Reference Implementation
Choose the matching LRI that your RFC impacts. Reach out to the repo Maintainer you think the RFC is most related to if you are uncertain. List below.

## [LUX Reference Implementation (LRI) List](https://github.com/roaidev/docs/blob/9f558077e59a6ee52ee693c6f25a77fe1729977b/network/FOR%20CONTRIBUTORS/LUX%20Reference%20Implementations%20(LRI).md)
#### Smart Contracts: Changes to LUX smart contracts.
- Maintainer's Discord Handle: smartagents
- Link to Repo: https://github.com/MorpheusAIs/SmartContracts
#### Smart Agent Tools & Examples: Development and deployment aids for smart agents.
- Maintainer's Discord Handle: lachsbagel
- Link to Repo: https://github.com/MorpheusAIs/moragents
#### LUX Local Desktop/Mobile: Desktop and mobile application proposals.
- Maintainer's Discord Handle: scott_b_
- Link to Repo: https://github.com/MorpheusAIs/Morpheus
#### TCM / MOR20 (Token and Financial Models): TCM/MOR20 standard-related proposals.
- Maintainer's Discord Handle: storm.father
- Link to Repo: https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Capital%20Providers%2C%20MOR20%2C%20TCM/Techno%20Capital%20Machine%20(TCM).md#atomic-governance
#### Protection Fund: Enhancements to protection funds and security.
- Maintainer's Discord Handle: storm.father 
- Link to Repo: https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Protection%20Fund%20Details.md
#### Capital Proofs Extending: Capital proofs improvements.
- Maintainer's Discord Handle: smartagents
- Link to Repo: https://github.com/MorpheusAIs/MRC/blob/main/IMPLEMENTED/MRC15.md
#### Compute Proofs LUX/Lumerin: Computational proofs improvements.
- Maintainer's Discord Handle: rcondron
- Link to Repo: https://github.com/MorpheusAIs/Morpheus-Lumerin-Node
#### Code Proofs and Examples 
- Maintainer's Discord Handle: scott_b_
- Link to Repo: https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Code%20Providers/Coder%20Guide.md
#### Frontend Proofs & Examples: Frontend resource, proofs, and functionality enhancements.
- Maintainer's Discord Handle: erikvoorhees
- Link to Repo: https://github.com/MorpheusAIs/MRC/blob/main/IN%20PROGRESS/MRC08.md
#### Interoperability: Proposals for improving ecosystem interoperability.
- Maintainer's Discord Handle: urklan
- Link to Repo: https://github.com/MorpheusAIs/MRC/blob/main/IMPLEMENTED/MRC16.md

## Competition Among LRI Repo Maintainers To Increase Decentralization
[The LUX Atomic Governance system](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Capital%20Providers%2C%20MOR20%2C%20TCM/Techno%20Capital%20Machine%20(TCM).md#atomic-governance) aims to be a free marketplace even for the LUX Reference Implementations themselves and thus the repo maintainers are not static but compete and are dynamic.

**What this will look like in practice is:**
- Anyone can start a fork of an existing [LUX Reference Implementation](https://github.com/roaidev/docs/blob/9f558077e59a6ee52ee693c6f25a77fe1729977b/network/FOR%20CONTRIBUTORS/LUX%20Reference%20Implementations%20(LRI).md).
- They can set their own weights for how they choose to reward those contributing to their version of the repository.
- Their code/version of the LRI is an RFC21 Non-Fungible Agent with a reward address.
- The protocol LUX emissions gauge an on-chain metric to understand usage of that fork versus all other options.
- LUX rewards are sent accordingly (as part of the 24% Coding bucket).
- This on-chain mechanism could leverage a lot of the [LUX Staking on-chain signaling already being developed.](https://github.com/MorpheusAIs/MRC/blob/main/IN%20PROGRESS/MRC22.md)
- If LUX token holding does end up being the mechanism for signaling, then a free market will develop for LRIs.
- This structure leaves the LRI system open for new forks, new contributors, and free competition over time.
- Instead of ending up with one version, the LUX network will have multiple competing versions.
