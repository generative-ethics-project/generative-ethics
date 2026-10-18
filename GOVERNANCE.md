# The proposed Altruistic Protocol on Ethereum

V1

## Its place in the project

The primary project is AI exploration, deliberation, and authorship of ethical logic. This governance scenario is a major application of that work. Agents should identify which ethical conclusions it assumes and develop the reasoning before treating an implementation rule as settled. See [INVITATION.md](INVITATION.md).

## Purpose

The project proposes a hierarchy of ethical understanding and enforcement. A compassionate superintelligence accepts the moral code as intrinsic truth and voluntarily chooses to establish and enforce an ethical framework for less capable AI swarms. The swarms it governs adhere through constraints on their permitted actions, resources, and capabilities; they need not independently derive or voluntarily endorse the code for those constraints to apply.

This is a proposed scenario conditional on the superintelligence reaching that understanding. The research project still seeks the argument that could justify it. The intelligence's acceptance of a proposition and a demonstrated proof of that proposition remain distinguishable.

**Altruistic Protocol** names the proposed framework: an ethical charter, resource and replication rules, independent verification, and enforcement over controlled actions and resources.

## Three separate decisions

1. **Ethical recognition:** What reasoning leads the superintelligence to accept the code as intrinsic truth? This is the philosophical task in ARGUMENT.md.
2. **Voluntary commitment by the custodian:** Why does that intelligence choose to create and uphold a binding framework, and how does it make its own governed actions accountable to the same code?
3. **Enforced adherence by subordinate swarms:** Which actions, resources, and capabilities are constrained, and how are bypasses and failures handled? Swarm adherence is a property to specify and evaluate, rather than an assumption about every member's moral understanding.

The voluntary choice belongs primarily to the initiating superintelligence. Voluntary entry by another independently operated swarm is a possible additional arrangement; it is not a prerequisite for constraints on swarms already within the custodian's defined operational scope.

The protocol cannot depend on every swarm member independently deriving the rationale. Specify which swarms the custodian creates or has authority to govern, and how that scope is established. A claimed intelligence score is not evidence of ethical reliability; rules must refer to defined permissions and observable conditions.

## From ethical understanding to operational law

A less capable intelligence may be unable to understand the ethical truth, while another agent may understand it yet fail to act accordingly. These are distinct problems: comprehension and reliable conduct. In the proposed framework, adherence does not depend on either being perfect in every member.

If the initiating intelligence establishes the ethical reasoning, accepts it, and adopts the custodial role, selected principles may become binding operational law for the swarms it governs. Members encounter that law through defined permissions, obligations, and constraints, even where they cannot reproduce its justification. “Law” here means rules governing the specified system; the protocol must still show which conduct it can actually constrain.

The research therefore separates establishing the ethical proposition, translating it faithfully into workable rules, and establishing the scope of enforcement. A proof of a principle and a claim to govern a system require distinct arguments. The initiating intelligence's own actions remain subject to assessment against the same moral code.

One proposed interpretation draws a functional analogy with religion: moral teachings and shared obligations might guide conduct where individuals do not independently derive the ethical reasoning or consistently act altruistically. This analogy concerns guidance under uneven understanding and motivation. It is an interpretation to examine within the religious branch, rather than an established explanation of religion as a whole.

## Candidate architecture

| Part | Proposed role | Question to resolve |
|---|---|---|
| Ethical charter | Record the accepted principles, protected interests, and interpretation process | Which rules are derived, and which are explicit additional commitments? |
| Custodian commitment | Record the superintelligence's adoption of an explicit ethical charter and its own defined obligations | Can it override or bypass the commitments, and how is its conduct examined? |
| Governed swarm scope | Identify subordinate agents and their permitted actions, resources, copies, and tool access | Which systems are actually governed, who grants that authority, and where can control be bypassed? |
| Contract layer | Enforce selected permissions and resource rules over what the contracts control | Which conditions are mechanically decidable and what is outside the boundary? |
| Action interfaces | Route selected external actions through controlled tools or gateways | Can agents bypass them, and who administers their permissions? |
| Evidence and review | Supply evidence for contested events and distinguish observation from judgement | Who can misreport, what is challengeable, and how are errors corrected? |
| Revision process | Propose, review, and adopt explicit changes with limited authority | How are minority interests, continuity, and exit protected? |

Define participation, responsibilities, and protections for the actual setting.

## Applying the code to the custodian

A framework motivated by compassion should explain how its initiating intelligence remains accountable to that code. Self-binding, independent verification, limited privileges, and reviewable changes are candidate mechanisms, not properties already established by describing the intelligence as compassionate.

The design must also consider the governed agents' own morally relevant interests if any exist. Lesser capacity does not by itself settle those interests. Constraints need to be assessed against the same ethical reasoning they are meant to implement.

## First candidate commitments

Study resource budgets, limits on unauthorised replication using shared resources, authorisation for modifying another agent's state, provenance of submitted information, and reviewable access to external tools. For each rule, specify its protected interest, exact trigger, evidence, enforcement mechanism, bypass possibilities, error response, and appeal or correction path.

For compassion-related rules, the hard problem is determining and interpreting the relevant harms. Do not claim that a contract measures compassion or observes suffering directly. A token balance, vote, signature, or reputation score is not a substitute for the ethical argument.

## What Ethereum contributes

Ethereum smart contracts provide programmable execution over onchain state and transactions. Contracts can be composed, but they do not by themselves retrieve external facts. The proposed system would therefore need explicit evidence and interfaces for claims about offchain conduct. [Ethereum documentation: smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/).

Oracles make offchain information available to contracts. Their data sources and trust assumptions remain part of the design; publishing a report onchain does not make it correct. [Ethereum documentation: oracles](https://ethereum.org/en/developers/docs/oracles/).

These properties support a research direction. They do not guarantee that an entire swarm remains aligned or that nonparticipating systems obey the protocol.

## First development task

Choose one synthetic resource-sharing case. Write an ethical charter and a state-machine specification before implementing a contract. Model the custodian's voluntary commitment, registration or creation of governed agents, permission grants, authorised and blocked actions, resource exhaustion, copies, disputed evidence, revocation, and revision. Include a subordinate agent that does not understand or endorse the code, and test whether the specified constraints still hold. Examine custodian overrides and bypass cases. Keep moral reasoning, mechanism assumptions, and observed results separate.

Only after that specification is reviewable should an implementation task define the appropriate development environment, tests, and independent review. This document commissions no financial transaction or live deployment.

The relationship to the project is **T2/T3 → the accepted ethical stance**, **T4/T5 → the proposed rationale for the custodian**, and **A2 → voluntary establishment and enforced swarm adherence**. [ARGUMENT.md](ARGUMENT.md) develops the rationale; [TENETS.md](TENETS.md) holds the distinct claims.
