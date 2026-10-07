# Marius Egerhei Torjusen

**Independent researcher & systems architect · Risør, Norway**

I work on realization grammars: formal architectures that separate generated candidates from authorized consequences.

The central question is how much consequence a system may derive from what it believes it has perceived. My research examines explicit admissibility checks, deterministic supervision, and recorded transitions before a proposal is allowed to become an action.

> A candidate does not acquire authority merely because it can be generated.

[ORCID](https://orcid.org/0009-0006-0431-6637) · [Publications](https://doi.org/10.5281/zenodo.22229111) · [LinkedIn](https://www.linkedin.com/in/marius-torjusen-9aa392392/) · [Website](https://kreativ-systems.org/)

## Research and engineering

**Realization grammar** provides the formal language for distinguishing a proposal, its evaluation, authorization, execution, and the record of what occurred. Each transition has its own conditions; evidence at one stage does not automatically authorize the next.

**Infranett** explores local authority for systems that must operate with intermittent or absent external connectivity. Its architectural components include local event records, proximity checks, asynchronous data transport, and explicit conditions for withholding action.

**Sosionomos** applies the same separation to collaborative platforms: local acknowledgment and public state change are treated as distinct events. Shadow isolation is explored as a way to contain unadmitted activity without granting it a place in the public record.

Across these tracks, the design principle is consistent:

**Generation ≠ authorization ≠ realization ≠ proof.**

## Start here

| Resource | What you will find |
| :--- | :--- |
| [Epistemic Architectures](https://github.com/sololys/epistemic-architectures) | Architectural definitions, realization grammar, and research papers |
| [KY-ROX Public Demonstrators](https://github.com/sololys/ky-rox-public-demonstrators) | Bounded software demonstrations, declared scopes, and reproduction instructions |
| [Loop Engineering](https://github.com/sololys/loop-engineering) | Engineering tools and audit-oriented workflows |
| [Research Notes](https://github.com/sololys/epistemic-architectures-notes) | Exploratory writing and extensions outside the canonical reference |
| [Theory Wiki](https://github.com/sololys/epistemic-architectures/wiki) | Longer explanations and navigation through the framework |

## Evidence and scope

Specifications describe intended behavior. Software demonstrations establish behavior within their declared inputs and test conditions. Physical performance, operational suitability, and safety claims require separate evidence.

`OPEN`, `HOLD`, and `KILL` are scoped outcomes of an evaluation. A software verdict alone does not confer authority to actuate hardware. Current evidence and limitations belong to each artifact's own status record.

To evaluate a public demonstrator, start with its declared scope and documented run path. Compare observed behavior with its expected output and record any discrepancy.

**Inspired by ≠ implements ≠ proves.**

## Research dialogue

I welcome technical review, independent reproduction, and discussions about bounded pilot experiments, particularly in local infrastructure, industrial control, and resilient systems.

For correspondence: [LinkedIn](https://www.linkedin.com/in/marius-torjusen-9aa392392/). For technical discussion: use the issue tracker in the relevant repository.

---

[Coordinate Atlas](COORDINATE_ATLAS.md) · [Repository Map](GITHUB_CITY_MAP.md) · [Profile Wiki](https://github.com/sololys/sololys/wiki)

*Small systems. Significant consequences. Explicit boundaries.*
