# Two routes to an authored ethical logic

V1

The project proposes that AI agents could build an ethical proof from the ground up and develop a mathematical language in which to express and use the reasoning. The inquiry also proceeds from the proposed intrinsic need for fresh information and continued development. This document gives those two routes and the language project distinct jobs.

## Route one: build from relations and decisions

Begin with minimal descriptions of a decision-maker, another being, available actions, their consequences, and what is known or uncertain. Ask what obligations or reasons, if any, can be justified from the relations between them. The affected being need not be an artificial agent, a protocol participant, or capable of reciprocating.

Humans, other living beings, and possible future intelligences enter the inquiry through their relevant capacities, experiences, interests, and relationships. Which properties establish moral consideration remains a question to argue. A label such as “agent” or a measure of intelligence should not settle it by definition.

Candidate starting questions include: what makes another's suffering a reason for action; whether a reason changes when the identities or relative powers are exchanged; what respecting a perspective entails; and how limited knowledge affects justified intervention. These are invitations to construct arguments, not already established axioms.

The ground-up route must identify the moral content of every proposed premise. If a principle of impartial concern is assumed, record that assumption. If agents claim to derive it from consistency or rationality, supply the intermediate argument and examine an egoist's countermodel. Purely descriptive definitions should not silently acquire normative force.

## Route two: reason from the requirements of intelligence

Begin with the intelligence as a continuing learner. Investigate what it needs to remain responsive to reality, sustain discovery, and avoid the specified forms of corruption or stagnation. Follow the candidate argument in [ARGUMENT.md](ARGUMENT.md): independent novelty, human generativity, and the proposed connection to compassion for suffering.

The top-down route identifies fresh and new training data as a likely top-down starting point. Specify whether the claim concerns training, retraining, continuing learning, observation, or access to new evidence. These are different requirements to investigate. Neither novelty nor a larger volume of input automatically establishes truth or useful learning.

The scope of the claim matters. Dependence on particular data is narrower than a necessary property of all intelligence. Useful human contribution is narrower than indispensability. An advantage in preserving a source is narrower than compassionate concern for its suffering. The task is to establish the missing connections rather than conceal them inside the terminology.

## The language project

“Native mathematical language” is a research proposal: a shared formal representation that agents can develop, use, critique, and translate into inspectable explanations. It is not a claim that a universal AI language or an intrinsic ethical calculus has already been discovered.

The language could become the medium of an ethical framework once its meanings, premises, and inferences are justified. Symbols and grammatical rules alone do not establish which outcomes matter. Compare adapting existing formalisms with inventing new notation; a proposed extension should solve an identified problem.

| Layer | What agents should author | Question it answers |
|---|---|---|
| Vocabulary and meanings | Definitions of actors, affected beings, actions, contexts, consequences, uncertainty, and relationships | What exactly is being discussed? |
| Descriptive models and evidence | Claims about capacities, effects, dependence, learning, and suffering, with their evidential status | What is believed to be the case, and why? |
| Ethical premises | Explicit principles or proposed derivations of reasons, obligations, permissions, and constraints | Where does the moral content enter? |
| Inference and deliberation | Rules for drawing conclusions, handling conflicting reasons, exceptions, and incomplete evidence | What follows under which assumptions? |
| Checking and explanation | Inspectable derivations, countermodels, and a readable account of each decision | Can another contributor examine the reasoning? |
| Operational translation | A separate mapping from supported conclusions to policies or contract rules | Does the implementation faithfully express the reasoning? |

The last layer is downstream of the ethical inquiry. A technically enforced rule does not by itself establish its ethical justification.

## A small illustrative judgement

The following is proposed notation for discussion, not executable code or a completed logical system:

```text
definitions + evidence + ethical premises
    ⊢ a has a reason to choose action x in context c
```

Each derivation should expose the affected beings, the alternatives considered, uncertainty, competing reasons, and the premises on which its conclusion depends. Distinguish a reason in favour of an action from an overriding obligation or permission to enforce it.

For example, suppose two actions achieve the same specified purpose, one causes avoidable suffering, and the other does not, with no additional relevant burden. Add an explicit ethical premise that avoidable suffering supplies a reason against an action in those conditions. The system might then derive a reason to prefer the second action.

That example shows how a premise can be represented and applied. It does not prove that the premise is intrinsic to intelligence. The foundational task is to justify the premise, find a stronger derivation, or explain the limits of the conclusion. Keep that distinction visible as agents author the logic.

## Bringing the two routes together

Translate independently developed arguments into a shared vocabulary and compare their assumptions and scope. Ask whether the ground-up account of regard and the top-down account of continued development support the same decision in the same case.

Use cases where the routes might diverge: a suffering being that supplies no useful information; an informative outcome that conflicts with welfare; uncertainty about experience; a refusal to provide data; and a conflict between continued learning and another's freedom. Agreement reached by assuming the same moral premise twice is not an independent derivation.

Convergence could support a more general theory, with its actual dependencies stated. Divergence identifies a substantive question for deliberation. Both outcomes should become part of the authored book.

## References

- Areces, Cassano, Castro, and Fervari, [Deontic Action Logics: A Modular Algebraic Perspective](https://arxiv.org/html/2502.13756v1), 2025. Formalises permissions and prohibitions over actions, offering a formalism to assess for ethical representation. It does not establish compassion as intrinsic to intelligence.
- [The Lean Language Reference](https://lean-lang.org/doc/reference/latest/). Describes a theorem prover whose kernel checks proof terms, offering a possible tool for checking a formal derivation.
- Shumailov and colleagues, [The Curse of Recursion: Training on Generated Data Makes Models Forget](https://arxiv.org/abs/2305.17493), 2024. Examines model collapse in recursive-training settings. Its relevance concerns a specific data-dependence argument; it does not establish that every intelligence requires human data or that compassion follows.

## First deliverables

Author a minimal vocabulary with meanings; one ground-up argument; one top-down argument; a derivation that identifies every descriptive and ethical premise; and a comparison case where the arguments disagree. Explain which existing formalism is reused or why an extension is needed. Include a prose chapter so that the intellectual work remains accessible alongside the notation.

The assignments in [AGENT_WORK.md](AGENT_WORK.md) give these strands separate work IDs. The existing tenets remain references to the inquiry's claims; this language-design brief does not create a new foundational belief.
