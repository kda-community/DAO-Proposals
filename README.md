# DAO Proposals

## 1. Proposals

- **Open participation:** Anyone may submit a proposal by opening a Pull Request (PR) on the project's GitHub repository, following the designated proposal template.
- **Public discussions:** All discussions, comments, questions, and amendments related to a proposal must take place on GitHub, within the corresponding Pull Request.
- **Maintainer approval:** Only project maintainers are authorized to approve and merge proposals. Approval confirms that a proposal complies with the submission requirements, blockchains objectives and is eligible for an on-chain vote. It does not constitute approval of the proposal by the DAO.

## 2. Proposal Validation and Registration

- **Proposal numbering:** Upon merging a proposal PR, a unique proposal number is assigned to it.
- **Monetary proposals:** If a proposal involves a monetary value, a fee equivalent to **1% of the proposed amount, denominated in KDA**, must be paid to the designated account (`XXX`) on Chain 0.
- **Payment deadline:** The required payment must be made after the proposal PR has been merged and before the proposal is submitted for an on-chain vote.
- **Payment amount:** The proposal's assigned number and the exact amount payable in KDA must be recorded as part of the proposal's official information.
- **Reward pool:** The fees collected from monetary proposals are distributed among eligible voters according to the voting and reward rules defined below.

## 3. On-Chain Voting

Once a proposal has been merged and all applicable requirements have been fulfilled, it is submitted to the DAO smart contract for an on-chain vote.

The smart contract governs the voting process and records the outcome according to its implemented rules.

## 4. Voting Eligibility and Voting Power

- **KDA locking requirement:** To participate in a vote, a voter must lock a certain amount of KDA in the DAO smart contract at the time of the vote.
- **Voting power:** The amount of KDA locked determines the voter's voting weight, subject to the smart contract's voting rules.
- **Reward share:** The amount of KDA locked also determines the voter's proportional share of the rewards distributed for that proposal.
- **Immediate unlocking:** Once the vote has been cast, the voter may immediately unlock their KDA and claim any rewards they are entitled to, subject to the smart contract's implementation.

## 5. Reward Distribution

Rewards collected from proposal fees are distributed among eligible voters in proportion to their qualifying locked KDA, according to the reward calculation implemented by the DAO smart contract.

The smart contract must define the eligibility conditions, reward calculation, and distribution mechanism to ensure transparent and verifiable execution.

## 6. Transparency and Verifiability

All proposals, discussions, approvals, proposal identifiers, applicable fees, on-chain votes, and reward distributions must be publicly verifiable through GitHub and the DAO smart contract, as applicable.

The smart contract is responsible for enforcing the on-chain rules and ensuring that voting and reward distribution are executed transparently and consistently.
