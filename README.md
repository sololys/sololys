# Marius Egerhei Torjusen (`sololys`)

Self-taught systems builder in Risør, Norway.
Everything here explores one practical question: **how to keep cheap, reversible proposals in software separate from actions that cannot be undone**, using small fail-closed gates (`OPEN`, `HOLD`, `KILL` — defaulting to `0 V` / stop on doubt).

---

## Coordinate System — Five Rooms Around `(0,0)`

This profile sits at `(0,0)` between two axes so essays, working math, formal rules, runnable gates, and provenance checksums stay cleanly separated:

- **Vertical axis (expression):** from human language and legal philosophy down to runnable code and FPGA logic.
- **Horizontal axis (commitment):** from open working drafts where ideas can fail freely, over to sealed SHA-256 boundaries.

```text
                     Language, law & why
                              │
                       skrivevaerelset
                              │
  Open drafts ────────────────┼──────────────── Sealed boundary
    (notes)                 (0,0)                 (monolitt)
                              │
                   epistemic-architectures
                              │
                 ky-rox-public-demonstrators
                              │
                     Runnable code & RTL
```

| Stage | Repository | What lives here | Direct Entry |
| :--- | :--- | :--- | :--- |
| **1 · Word** | **[`skrivevaerelset`](https://github.com/sololys/skrivevaerelset)** | **Books & essays (Norwegian)** — Long-form prose, philosophy of law, and essays (*Konseptuell Granitt*) | [`03_FERDIGE_BOKER_PDF/`](https://github.com/sololys/skrivevaerelset/tree/main/03_FERDIGE_BOKER_PDF) |
| **2 · Draft** | **[`epistemic-architectures-notes`](https://github.com/sololys/epistemic-architectures-notes)** | **Working math & counterexamples** — Ongoing derivations, spectral checks, and test scripts in progress | [`notes/`](https://github.com/sololys/epistemic-architectures-notes/tree/main/notes) |
| **3 · Rule** | **[`epistemic-architectures`](https://github.com/sololys/epistemic-architectures)** | **Specifications & transition rules** — Formal gate contracts, game-theoretic models, and standalone verifiers | [`L1_LAW/`](https://github.com/sololys/epistemic-architectures/tree/main/L1_LAW) · [`L2_GATE/`](https://github.com/sololys/epistemic-architectures/tree/main/L2_GATE) |
| **4 · Gate** | **[`ky-rox-public-demonstrators`](https://github.com/sololys/ky-rox-public-demonstrators)** | **Runnable code & FPGA gates** — Python (stdlib only) and synthesizable SystemVerilog gate prototypes | [`run_demo.py`](https://github.com/sololys/ky-rox-public-demonstrators/blob/main/run_demo.py) · [`L2_GATE/`](https://github.com/sololys/ky-rox-public-demonstrators/tree/main/L2_GATE) |
| **5 · Seal** | **[`monolitt`](https://github.com/sololys/monolitt)** | **Project map & checksums** — Overview index and SHA-256 provenance seals across private prototype repos | [`verify_monolith_seals.py`](https://github.com/sololys/monolitt/blob/main/verify_monolith_seals.py) |

*(Older control-loop experiments are archived in [`loop-engineering`](https://github.com/sololys/loop-engineering), superseded by `ky-rox-public-demonstrators`.)*

---

## From Impulse to Seal — The Consequence Circuit

Across the five rooms, proposals travel through a planar circuit with three hard rules:

1. **No shortcut around friction:** A compressed idea (`p_art` in **1 · Word**) cannot enter the gate directly; it must pass through reversible search (`J` in **2 · Draft**) and temporal/physical constraints (`D` in **3 · Rule**).
2. **Bounded `HOLD` with a dual clock:** Doubt returns the candidate to the search loop with an explicit deficiency receipt (`Δ_K ≠ ∅`), while stalling past `τ_max` escalates authority (`P_int -> P_ext`) rather than freezing indefinitely.
3. **Asymmetry across the Gödel air gap:** Formal checks inside `F` (`Π_K` in **4 · Gate**) can issue `KILL` or `HOLD` on their own, but at `Δ_K = 0` they stop at `0.00 V DC · READY`. Crossing into `OPEN` (**5 · Seal**) requires external human witness (`W_ext ∉ F` at `(0,0)`) recorded in an append-only `SHA-256 WAL`.

```text
[ u_raw ] ──( L: Acoustics )──> [ M_L ] ──( A: Compression )──> [ p_art ∈ NP_COSMOS ]
                                                                          │
               ┌──────────────────────────────────────────────────────────┘
               │  ┌─── REVERSIBLE LOOP (Δ_K ≠ ∅, τ ≤ τ_max) ────────────────────────────┐
               ▼  ▼                                                                     │
       [ J: Search {γ_i} ] ──( D: Body / Time / Inertia )──> [ γ'_i : Candidate ]       │
                                                                          │             │
                                                                ┌─────────┴─────────┐   │
                                                                │  GATE IN F: Π_K   │   │
                                                                │ Σ read_permit ≤ 1 │   │
                                                                └─┬───────┬───────┬─┘   │
                                                                  │       │       │     │
                                                               [KILL]     │     [HOLD]  │
                                                                  │       │       └──┬──┘
                                                              (Discard)   ▼          └─> [ τ > τ_max : P_ext ]
                                                                [ Residual: Δ_K = 0 ]
                                                                [ 0.00 V DC · READY ]
                                                                          │
                                                               ═══════════╪═══════════  <-- GÖDEL AIR GAP (F ⊬ OPEN)
                                                                          ▼
                                                              [ Ω ← W_ext ∉ F : Human ]
                                                                          │
                                                                          ▼
                                                                [ OPEN + SHA-256 WAL ]
```

---

## Run in 10 Seconds (No Dependencies)

All public Python checks use only the Python 3.10+ standard library (no `pip install` needed):

```bash
git clone https://github.com/sololys/ky-rox-public-demonstrators.git
cd ky-rox-public-demonstrators
python3 run_demo.py
```

---

## Kort på norsk (og ærlig avgrensning)

Jeg er selvlært systemutvikler i Risør. Denne profilen fungerer som nullpunkt `(0,0)` i et enkelt koordinatsystem med fem adskilte arbeidsrom — langs bevegelsen **ordet** ([`skrivevaerelset`](https://github.com/sololys/skrivevaerelset)) → **kladden** ([`epistemic-architectures-notes`](https://github.com/sololys/epistemic-architectures-notes)) → **regelen** ([`epistemic-architectures`](https://github.com/sololys/epistemic-architectures)) → **porten** ([`ky-rox-public-demonstrators`](https://github.com/sololys/ky-rox-public-demonstrators)) → **seglet** ([`monolitt`](https://github.com/sololys/monolitt)).

- **Avgrensning (`INSPIRED_BY != IMPLEMENTS != PROVES`):** Alt som ligger åpent her er lokale programvareprototyper (`L1`) og syntese-/tidsanalyser for FPGA (`L1.5`), ikke fysiske anlegg i drift. Revisjonslogger på disk er append-only SHA-256 hash-kjeder, ikke fysisk WORM-maskinvare.
- **Arkiv og lisens:** [ORCID `0009-0006-0431-6637`](https://orcid.org/0009-0006-0431-6637) · [`LICENSE`](LICENSE) · [`NOTICE`](NOTICE)
