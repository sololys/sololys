# SOLOLYS // VEIVISER OVER DE ÅPNE ROMMENE

$$\boxed{\text{GENERATION} \neq \text{AUTHORIZATION} \neq \text{WITNESSED CONSEQUENCE}}$$

Velkommen til den åpne overflaten av arbeidet ved **Locus Zero (Risør)**.  
Denne siden er et **skiltet kart** over de fem åpne repositoriene som ligger offentlig tilgjengelig. Hvert rom har én tydelig oppgave: **Ordet** (`skrivevaerelset`), **Porten i kode** (`ky-rox-public-demonstrators`), **Grunnloven** (`epistemic-architectures`), **Arbeidsnotatene** (`epistemic-architectures-notes`) og **Verktøyet** (`loop-engineering`).

---

## I. KOMPASSET — HVOR VIL DU GÅ?

```text
                             ▲  I. ORDET & LITTERATUREN
                             │  github.com/sololys/skrivevaerelset
                             │  • «Konseptuell Granitt — Et forsøk på sannhet» (73 s. PDF)
                             │  • «Kutt Flaten: Et Notis» & De fem kjerneprøvene
                             │  • Trilogien, Omnibus & essayene fra Risør
                             │
  ◄──────────────────────────┼──────────────────────────►
  III. GRUNNLOVEN & NOTATENE │                            II. PORTEN & MIKROTESTENE (24/24 PASS)
  epistemic-architectures    │                            ky-rox-public-demonstrators
  epistemic-architectures-   │                            • 1. Lysbrua (light_bridge.gd / .py)
       notes                 │                            • 2. ISAC Fase-Kjeglen (euclidean_phase_cone.py)
  • Formell epistemisk       │                            • 3. Punkt // Bane (yinyang_binpacking.py)
    styring & bevisklasser   │                            • 4. Relasjon (kernel_drift.py)
  • INSPIRED_BY !=           │
    IMPLEMENTS != PROVES     │
                             ▼  IV. VERKTØYET & TESTLØKKENE
                                github.com/sololys/loop-engineering
                                • Local-first CLI-verktøy
                                • Deterministiske evalueringsrammeverk & agent-disiplin
```

---

## II. SKILTET KART OVER DE ÅPNE REPOSITORIENE

| Skilt | Åpent Repositorium | Hva du finner der inne | Direkte inngang |
| :--- | :--- | :--- | :--- |
| **📖 ROM I: ORDET** | [**`sololys/skrivevaerelset`**](https://github.com/sololys/skrivevaerelset) | Bøkene, manuskriptene og de ferdig kompilerte PDF-utgavene: *Konseptuell Granitt — Et forsøk på sannhet* (`TILMEGSELV/`), *Kutt Flaten: Et Notis* (`01_BOKER_UNDER_ARBEID/`), Trilogien og de fem kjerneprøvene fra grunnfjellet. | [Gå til Skriveværelset $\to$](https://github.com/sololys/skrivevaerelset) |
| **⚡ ROM II: PORTEN** | [**`sololys/ky-rox-public-demonstrators`**](https://github.com/sololys/ky-rox-public-demonstrators) | De fire lukkede, deterministiske mikrotestene (`24/24 PASS`) for **Konsekvens** (*Lysbrua*), **Rom** (*Fase-Kjeglen*), **Bane** (*Punkt // Bane*) og **Relasjon** (*Kernel Drift*). Kan kjøres lokalt uten eksterne avhengigheter. | [Gå til Demonstratorene $\to$](https://github.com/sololys/ky-rox-public-demonstrators) |
| **⚖️ ROM III: LOVEN** | [**`sololys/epistemic-architectures`**](https://github.com/sololys/epistemic-architectures) | Formelle spesifikasjoner for suverent tilsyn, *fail-closed* epistemisk styring og kontrakten som skiller programvaremodell ($L1$) fra fysisk påstand. | [Gå til Epistemic Architectures $\to$](https://github.com/sololys/epistemic-architectures) |
| **📓 ROM IV: NOTATENE** | [**`sololys/epistemic-architectures-notes`**](https://github.com/sololys/epistemic-architectures-notes) | Arbeidsnotater, matematiske utledninger, randtilfeller og praktiske eksempler som ledsager `epistemic-architectures`. | [Gå til Arbeidsnotatene $\to$](https://github.com/sololys/epistemic-architectures-notes) |
| **🛠️ ROM V: VERKTØYET** | [**`sololys/loop-engineering`**](https://github.com/sololys/loop-engineering) | Local-first CLI-verktøy, strenge evalueringsrammeverk og deterministiske verifikasjonsløkker for kodeagenter. | [Gå til Loop Engineering $\to$](https://github.com/sololys/loop-engineering) |

---

## III. HURTIGVEIVISER ETTER HVA DU LETER ETTER

* **Vil du lese bøkene (PDF / Markdown)?**  
  $\longrightarrow$ Gå til [**`skrivevaerelset/TILMEGSELV`**](https://github.com/sololys/skrivevaerelset/tree/main/TILMEGSELV) for *Konseptuell Granitt — Et forsøk på sannhet*, eller [**`skrivevaerelset/03_FERDIGE_BOKER_PDF`**](https://github.com/sololys/skrivevaerelset/tree/main/03_FERDIGE_BOKER_PDF) for de øvrige trykkeklare utgavene.
* **Vil du kjøre de 24 deterministiske mikrotestene på egen maskin?**  
  $\longrightarrow$ Klon [**`ky-rox-public-demonstrators`**](https://github.com/sololys/ky-rox-public-demonstrators) og kjør `pytest` / `python3 -m unittest`.
* **Vil du se hvordan en konsekvensport ($0{,}00\text{ V}$ vs. $5{,}00\text{ V}$) er kodet i Godot 4 og Python?**  
  $\longrightarrow$ Se `light_bridge.gd` og `light_bridge_gate.py` i [**`ky-rox-public-demonstrators`**](https://github.com/sololys/ky-rox-public-demonstrators).
* **Vil du lese reglene for bevisføring og hvorfor koden har $0{,}00\%$ fysisk autonomi?**  
  $\longrightarrow$ Gå til [**`epistemic-architectures`**](https://github.com/sololys/epistemic-architectures) og [**`epistemic-architectures-notes`**](https://github.com/sololys/epistemic-architectures-notes).

---

## IV. GRUNNRISS AV ARKITEKTUREN I BØKENE OG KODEN

*Merk: Skissene nedenfor viser den kanoniske arkitekturen som binder bøkene i `skrivevaerelset` sammen med mikrotestene i `ky-rox-public-demonstrators` og styringsreglene i `epistemic-architectures` (`PHYSICAL_AUTHORITY = NONE`).*

### 1. Det Ortogonale Snittet ($\Pi_K$) & De 400 Klokkesyklusene
```text
                ┌──────────────────────────────────────────────────┐
                │        KANDIDAT I MULIGHETSROMMET: Φ(x_n)        │
                │   • Vektløst forslag i NP (0,00 V DC hvile)      │
                │   • Ingen fysisk kabling til aktuator            │
                └────────────────────────┬─────────────────────────┘
                                         │
                                         ▼
                ┌──────────────────────────────────────────────────┐
                │          DET ORTOGONALE SNITTET: Π_K             │
                │   • Involusjonstest: ||F(F(s)) - s|| <= ε_tol    │
                │   • Støkiometri: ΔR = 0,000000000000 kg          │
                │   • Kausal diamant: Δt <= 133,4256 ns (ds² <= 0) │
                └───────┬────────────────┬─────────────────┬───────┘
                        │                │                 │
         [ ρ(DP) < 1 ]  │   [ Tvilstil-  │                 │ [ Brudd på lov: ]
         [ Alt gyldig ] │     stand ]    │                 │ [ ds² > 0 / ΔR≠0]
                        ▼                ▼                 ▼
         ┌────────────────────┐ ┌────────────────┐ ┌──────────────────────┐
         │    DOM: ▶ OPEN     │ │  DOM: ⏸ HOLD   │ │     DOM: ✕ KILL      │
         │ (Konstruktiv vei)  │ │  (Karantene)   │ │  (Destruktivt kutt)  │
         └─────────┬──────────┘ └────────┬───────┘ └──────────┬───────────┘
                   │                     │                    │
                   ▼                     ▼                    ▼
         ┌────────────────────┐ ┌────────────────┐ ┌──────────────────────┐
         │ 1. VITNE FØRST (⊙) │ │ 1. STASIS (1)  │ │ 1. KUTT FØRST (1)    │
         │ Synkron fsync()    │ │ 0,00 V Høy-Z   │ │ 12,5 μs FPGA / 4,0ns │
         │ Venter i 5,0 ms    │ │ Brahman-punkt  │ │ Crowbar -> 0,00 V DC │
         │ (400 sykluser)     │ │ (Ingen fluks)  │ │ (0 syklusers nøling) │
         └─────────┬──────────┘ └────────┬───────┘ └──────────┬───────────┘
                   │                     │                    ║ (Parallelt)
                   ▼                     ▼                    ▼
         ┌────────────────────┐ ┌────────────────┐ ┌──────────────────────┐
         │ 2. HANDLING (1)    │ │ 2. LYTT (⊙)    │ │ 2. OBDUKSJON (⊙)     │
         │ Relé slår inn:     │ │ Diagnostisk    │ │ Asynkron fsync()     │
         │ 5,00 V DC innvilget│ │ passivt vitne  │ │ brenner bruddårsaken │
         └────────────────────┘ └────────────────┘ └──────────────────────┘
```

### 2. De 5 Millimeterne med Kald Luft (Menneskets Suverenitet)
```text
                      ┌──────────────────────────────────────────────┐
                      │         SILISIUMETS DOMENE (L1 / L2)         │
                      │  • Genererer kandidater i Φ med lysets fart  │
                      │  • Kutter ulovlige baner i Π_K på 12,5 μs    │
                      │  • Legger utgangen død på 0,00 V DC ved tvil │
                      └──────────────────────┬───────────────────────┘
                                             │
                                             ▼
                         =========================================
                          GAPET PÅ 5 MILLIMETER KALD LUFT (∞ Ω)
                          (Herdede stålfjærer i skapet ved fjellet)
                          Ingen kode, ingen sky og ingen matrise
                          eier muskler til å krysse denne spalten.
                         =========================================
                                             │
                                             ▼
                      ┌──────────────────────────────────────────────┐
                      │         MENNESKETS DOMENE (LEVEL 01)         │
                      │  • Biologisk sårbarhet, tyngdekraft & ansvar │
                      │  • Går ut i vintermørket over frossen grus   │
                      │  • Legger kroppstyngden mot bakelitthåndtaket│
                      │    og låser kobberet med 898 900 N (5,00 V)  │
                      └──────────────────────────────────────────────┘
```

---
*Brahman — Risør, Norge (`58.72° N, 9.24° E` · `−3400 m` under Det Fennoskandiske Skjold).*
