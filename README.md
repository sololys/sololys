# Marius Egerhei Torjusen (`sololys`)

Self-taught systems builder in Risør, Norway.  
Everything here explores one practical question: **how to keep cheap, reversible proposals in software separate from actions that cannot be undone**, using small fail-closed gates (`OPEN`, `HOLD`, `KILL` — defaulting to `0 V` / stop on doubt).

---

## Start Here — Choose a Door

Each repository has a single responsibility so code, specifications, working notes, and essays never get mixed together:

| Look here if you want... | Repository | Direct Entry |
| :--- | :--- | :--- |
| **Runnable code & FPGA gates** — Python (stdlib only) and synthesizable SystemVerilog gate prototypes | **[`ky-rox-public-demonstrators`](https://github.com/sololys/ky-rox-public-demonstrators)** | [`run_demo.py`](https://github.com/sololys/ky-rox-public-demonstrators/blob/main/run_demo.py) · [`L2_GATE/`](https://github.com/sololys/ky-rox-public-demonstrators/tree/main/L2_GATE) |
| **Specifications & transition rules** — Formal gate contracts, game-theoretic models, and standalone verifiers | **[`epistemic-architectures`](https://github.com/sololys/epistemic-architectures)** | [`L1_LAW/`](https://github.com/sololys/epistemic-architectures/tree/main/L1_LAW) · [`L2_GATE/`](https://github.com/sololys/epistemic-architectures/tree/main/L2_GATE) |
| **Working math & counterexamples** — Ongoing derivations, spectral checks, and test scripts in progress | **[`epistemic-architectures-notes`](https://github.com/sololys/epistemic-architectures-notes)** | [`notes/`](https://github.com/sololys/epistemic-architectures-notes/tree/main/notes) |
| **Project map & checksums** — Overview index and SHA-256 provenance seals across private prototype repos | **[`monolitt`](https://github.com/sololys/monolitt)** | [`verify_monolith_seals.py`](https://github.com/sololys/monolitt/blob/main/verify_monolith_seals.py) |
| **Books & essays (Norwegian)** — Long-form prose, philosophy of law, and essays (*Konseptuell Granitt*) | **[`skrivevaerelset`](https://github.com/sololys/skrivevaerelset)** | [`03_FERDIGE_BOKER_PDF/`](https://github.com/sololys/skrivevaerelset/tree/main/03_FERDIGE_BOKER_PDF) |

*(Older control-loop experiments are archived in [`loop-engineering`](https://github.com/sololys/loop-engineering), superseded by `ky-rox-public-demonstrators`.)*

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

Jeg er selvlært systemutvikler i Risør og bruker denne profilen som inngangsport til fem adskilte arbeidsrom — fra kjørende kode og maskinvareporter i [`ky-rox-public-demonstrators`](https://github.com/sololys/ky-rox-public-demonstrators) til norske bøker og essays i [`skrivevaerelset`](https://github.com/sololys/skrivevaerelset).

- **Avgrensning (`INSPIRED_BY != IMPLEMENTS != PROVES`):** Alt som ligger åpent her er lokale programvareprototyper (`L1`) og syntese-/tidsanalyser for FPGA (`L1.5`), ikke fysiske anlegg i drift. Revisjonslogger på disk er append-only SHA-256 hash-kjeder, ikke fysisk WORM-maskinvare.
- **Arkiv og lisens:** [ORCID `0009-0006-0431-6637`](https://orcid.org/0009-0006-0431-6637) · [`LICENSE`](LICENSE) · [`NOTICE`](NOTICE)
