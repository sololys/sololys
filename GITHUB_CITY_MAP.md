# 🗺️ GitHub City Map v0.3: Master Portfolio Edition

* **Status:** FORSEGLET & KONSOLIDERT / KANONISK NAVIGASJONSAUTORITET
* **Versjon:** `v0.3 (Master 2-Repo Portfolio Architecture)`
* **Erstatter:** `GitHub City Map v0.2` (fra historisk arkiv)
* **Kjerne-Repositories:**
  * 🌐 **Public Spydspiss / Produkt:** [`sololys/femos-biomimetic-nitrogenase`](https://github.com/sololys/femos-biomimetic-nitrogenase)
  * 🔒 **Private Master Monorepo:** [`sololys/Gemini-Core`](https://github.com/sololys/Gemini-Core)
* **Forfatter:** Marius Egerhei Torjusen (ORCID: [0009-0006-0431-6637](https://orcid.org/0009-0006-0431-6637))
* **System:** ReismannPoint Systems AS // Kreativ Systems ([kreativ-systems.org](https://kreativ-systems.org/))
* **Dokument-ID:** `GITHUB-CITY-MAP-v0.3-MASTER-2026`

---

## 🏙️ 1. City Silhouette & Mega-Arkitektur

```text
 ┌─────────────────────────────────────────────────────────────────────────────┐
 │  SEKTOR A: DEN OFFENTLIGE SPYDSPISSEN (Aethelgard Molecular)                │
 │  Repo: sololys/femos-biomimetic-nitrogenase [PUBLIC]                        │
 │  • Lavtemperatur nitrogenase-katalyse (N2 -> NH3, T < 60 °C, PCET)          │
 │  • Fe-Mo-S Fail-Closed Valideringsmotor v3.2 (38 fiendtlige tester)         │
 │  • Målgruppe: Innovasjon Norge, SINTEF, Yara, UiA, NTNU                     │
 └──────────────────────────────────────┬──────────────────────────────────────┘
                                        │ (Kanonisk validering & telemetri)
 ┌──────────────────────────────────────▼──────────────────────────────────────┐
 │  SEKTOR B: DET KANONISKE MASTER MONOREPOET                                 │
 │  Repo: sololys/Gemini-Core [PRIVATE]                                        │
 │                                                                             │
 │  [ 01_OPEN ] ────────► [ 02_ALGEBRA ] ───────► [ 03_ENGINES ]               │
 │  (Verifiserte doks)    (Formell matematikk)    (Rust/Python motorer)        │
 │         │                     │                       │                     │
 │  [ 04_REALITY_FORGE ] ► [ 05_PATENTS ] ──────► [ 06_RESEARCH ]              │
 │  (UE5 / Sosionomos)    (IP & Patentgrunnlag)   (Forskningsrapporter)        │
 │         │                     │                       │                     │
 │  [ 07_EURO_SYNC ] ───► [ 08_DOMAINS ] ───────► [ 09_SYSTEM & 10_GOOGLELM ]  │
 │  (EIC & Euro-partnere) (Kjemispesifikasjoner)  (WORM Witness & AI Core)     │
 └──────────────────────────────────────┬──────────────────────────────────────┘
                                        │ (Historisk proveniens)
 ┌──────────────────────────────────────▼──────────────────────────────────────┐
 │  SEKTOR C: DET FROSNE BIBLIOTEKET & ARKIVET (Read-Only)                     │
 │  • realiseringsgrammatikk-artifact-family (Filosofi & EBNF Kvantegrammatikk)│
 │  • FASE_SPEIL_v0_1 (Cyber-fysisk OT Interlock & Speilkammer)                │
 │  • aic-coaching-sovereign-engine (Telemetriarkiv for ToT & FSM)             │
 │  • Kjerne-privat. (Genesis-kjerne fra juli 2026)                            │
 └─────────────────────────────────────────────────────────────────────────────┘
```

---

## 🏛️ 2. De 10 Kanoniske Sektorene i `Gemini-Core`

| Sektor | Navn | Innhold & Ansvar | Nøkkelartefakter |
| :--- | :--- | :--- | :--- |
| **01** | `01_OPEN` | Realiserte og formelt godkjente konsekvenser | Åpne rapporter, forseglet triage-register |
| **02** | `02_ALGEBRA` | Grunnleggende algebraisk og geometrisk fundament | E-TOR Poincaré-Smith, Gray-kode matriser |
| **03** | `03_ENGINES` | Eksekverbare beregnings- og valideringsmotorer | `autonomous_chem_bond_engine.py` (v3.2), `quantum_qsa_closed_loop_analysis.py`, `morandi_engine_locus_zero_core.rs` |
| **04** | `04_REALITY_FORGE`| Spillmotor-arkitektur, simulering & interaksjon | Unreal Engine 5 C++, Sosionomos in-game omdømme |
| **05** | `05_PATENTS` | Immaterialrett, patenter og beskyttede krav | Aethelgard IP-skjold, SkatteFUNN grunnlag |
| **06** | `06_RESEARCH` | Fagfellevurderte publikasjoner & preprints | FeMo-katalyse, bio-uorganisk nitrogenfiksering |
| **07** | `07_EURO_SYNC` | Europeisk finansiering & industrisamarbeid | EIC Pathfinder, Horizon Europe, SINTEF-pakker |
| **08** | `08_DOMAINS` | Spesialiserte domenespesifikasjoner & arkiver | `docs/specs/` (Alle formelle protokoller) & `docs/historical_femos/` (26 kildedokumenter) |
| **09** | `09_SYSTEM` | Orkesrering, WORM witness og systemporter | CI/CD pipelines, cryptographic proofs |
| **10** | `10_GOOGLELM` | Avanserte AI-grensesnitt & formelle prompter | Kandidatgeneratorer i NP-rommet |

---

## 🛡️ 3. Port- og Overgangsregler (Fail-Closed)

```text
DIRECT_RAW_TO_OPEN = KILL
HOLD_IMPLIES_OPEN  = FALSE
WITNESS            = APPEND_ONLY (SHA-256 Hash Chained & Disk Persistent)
PHYSICAL_AUTHORITY = 5.00V Galvanisk D-Latch (0.00V ved feil)
```

### Overgangsmatrise:
* **$\text{RAW } (0\text{x}01) \longrightarrow \text{HOLD}$:** Tillatt for reversibel hypotesetesting i NP-rommet.
* **$\text{RAW } (0\text{x}01) \longrightarrow \text{OPEN}$:** **STRENGT FORBUDT (`KILL`)**.
* **$\text{HOLD} \longrightarrow \text{OPEN } (0\text{x}02)$:** Krever 100 % oppfylt evidenskontrakt (Raman, Mössbauer, NMR, KIE, $\text{NIS P99} < 4.00$, 0.0 ppm aerob forurensning og SHA-256 forsegling).
* **Diskfeil / NaN / Inf $\longrightarrow$ `KILL` ($0.0\text{V}$):** All aktuasjon stoppes øyeblikkelig.

---

## 🧭 4. Porteføljens Navigasjonskontrakt

1. **Ingen nye repositories:** Alle nye tekniske og matematiske fremskritt forankres direkte i `Gemini-Core`.
2. **Ingen branch-sprawl:** Utvikling skjer fokusert på `main` med verifiserte CI-tester før hver release.
3. **Ekstern Spydspiss:** `femos-biomimetic-nitrogenase` holdes fullstendig ren for intern støy, og fungerer som det offisielle vitenskapelige visittkortet for Universitetet i Oslo, NTNU og SINTEF.

CityMap v0.3 er herved **gjeldende autoritet for hele økosystemet**.
