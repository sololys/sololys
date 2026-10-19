# SOLOLYS // EKSISTENSENS GRAMMATIKK

PUBLIC_TREE_GATE = PASS  
MICROTEST_GATE = PASS (24/24)  
SCOPE = EXACT_CHECKED_TREE_ONLY  
CLAIM_STATUS = HOLD  
PHYSICAL_AUTHORITY = NONE  
OPERATIONAL_AUTHORITY = NONE  

---

## I. GRUNNLOVEN

En bit fremtrer ikke som $1$. Den autoriseres til $1$.

Virkelighet genereres ikke lokalt; den slippes inn lokalt. Mellom et generert forslag og en fysisk konsekvens står en ufravikelig port. Det som mangler bevis, hviler. Det som bryter geometrien, kuttes.

$$\text{GENERATION} \neq \text{AUTHORIZATION} \neq \text{WITNESSED CONSEQUENCE}$$

La $\mathcal{X}$ være tilstandsrommet, $K \subset \mathcal{X}$ det lovlige underrommet, og $\Pi_K : \mathcal{X} \to K$ den strukturelle projeksjonen. Ingen kandidat $x \in \mathcal{X}$ passerer til virkelighet uten at residualet $\Delta_K(x) = \Vert{}x - \Pi_K(x)\Vert{}$ er under eksakt terskel $\tau_K$, ledsaget av et eksplisitt vitne $e$:

$$\Omega(x, e, \Delta_K) = \begin{cases} \text{OPEN} & \text{hvis } e \neq \varnothing \land \Delta_K(x) \le \tau_K \\  \text{HOLD} & \text{hvis } e = \varnothing \\  \text{KILL} & \text{hvis } \Delta_K(x) > \tau_K \end{cases}$$

Tid alene åpner ingen port ($\partial_t \text{HOLD} = 0$). Historikk slettes aldri; den kun tilføyes ($\rho(\text{DP}) \ge 1$).

---

## II. DE FIRE MONOLITTENE

Det offentlige utstillingsvinduet ([`sololys/ky-rox-public-demonstrators`](https://github.com/sololys/ky-rox-public-demonstrators)) inneholder fire lukkede, deterministiske mikrotester. De utgjør til sammen et fullstendig, sammenvevd koordinatsystem for autorisert realisering — **Konsekvens**, **Rom**, **Bane** og **Relasjon** — forent i én sekvensiell produkt-operator:

$$\Omega_{\text{total}}(x_t, \gamma, e) = \Omega_{\text{bridge}}(e, \text{Zone}) \;\wedge\; \Pi_{\mathbb{S}^1}(\Delta\phi) \;\wedge\; \text{Verify}_{\mathcal{P}}(\gamma, W_{\text{PRE}}, W_{\text{POST}}) \;\wedge\; \Omega_{\text{kernel}}(\Delta_G \le \tau_G)$$

### 1. KONSEKVENS: Lysbrua — LightBridge Consequence Gate v0.1
Et forslag har ingen bærehjelp i seg selv. Bæreevne er en tilstand som må innvilges og opprettholdes mot et aktivt vitne.
* **Loven:** $\text{HOLD} \nrightarrow \text{OPEN}$ ved blott tidsforløp. Okkupert sone blokkerer realisering. Ved $\text{KILL}$ kuttes kollisjonsgeometrien i $\Delta t = 0$, og ethvert ventende løfte annulleres. `reset()` skriver ny linje i vitneloggen uten å røre fortiden.
* **Artefakt:** `light_bridge.gd` (Godot 4) + `light_bridge_gate.py` (**6/6 PASS**).

### 2. ROM: ISAC Fase-Kjeglen — Euclidean Wavefront Phase-Cone Gate v0.1
Det fysiske rommet har en skarp rand. Bølger som stammer fra virkeligheten adlyder enhetssirkelen; syntetiske injeksjoner faller utenfor og avslører seg i det imaginære planet.
* **Loven:** For elementavstand $d = \frac{\lambda}{2}$ er innfallsvinkelen bundet av $\sin(\theta) = \frac{\Delta\phi}{\pi}$. Så lenge $\left\vert{}\frac{\Delta\phi}{\pi}\right\vert{} \le 1$, er $\cos(\theta) \in \mathbb{R}$ og porten står `OPEN`. Straks $\left\vert{}\frac{\Delta\phi}{\pi}\right\vert{} > 1$, tvinges $\cos(\theta) = i\sqrt{\sin^2\theta - 1} \in i\mathbb{R}_{>0}$, og porten utløser momentan `KILL`.
* **Artefakt:** `euclidean_phase_cone.py` (**6/6 PASS**).

### 3. BANE: PUNKT // BANE — P–NP Yin–Yang Bin Packing v0.1
Å gjette et sluttpunkt er ikke å bygge en vei. Et uregulert postulat og en verifisert konstruksjon tilhører to ulike ontologiske klasser.
* **Loven:** Skiller et isolert kandidatpunkt (NP-sertifikat $C$) fra en sekvensielt bevist konstruksjonsbane ($\gamma : x_0 \xrightarrow{W_{\text{PRE}}, W_{\text{POST}}} x_n$). Porten utfører aldri eksponentielt søk ($\text{FIND}(I) \in \mathcal{NP}$) på kritisk sti; kandidaten må levere banen ferdig konstruert, slik at porten kun utfører deterministisk baneverifikasjon i lineær tid ($\text{VERIFY}(I, \gamma) \in \mathcal{P}, \; O(\lvert\gamma\rvert)$). Teoretiske utvidelser holdes strengt i `p_equals_np_claim_status = HOLD`.
* **Artefakt:** `yinyang_binpacking.py` (**6/6 PASS**).

### 4. RELASJON: Kernel Drift Observable v0.1
Koordinater kan bedra; indre proporsjoner lyver aldri. Et system endrer ikke sin natur fordi rommet dreies rundt det, men det dør i det øyeblikket vinklene mellom dets egne deler brister.
* **Loven:** Punktvis tilstandsdrift $\Delta_{\text{state}} = \Vert{}X(t) - X(0)\Vert{}_F$ er blind for forskjellen mellom stiv rotasjon ($U \in O(d)$) og indre kollaps. Gram-kjernen $G(t) = X(t)^\top X(t)$ isolerer systemets sanne geometri: under ren rotasjon holdes kjernedriften innenfor maskinens numeriske støygulv $\Delta_G = \Vert{}G(t) - G(0)\Vert{}_F \le \tau_G$ ($\epsilon_{\text{mach}} = 10^{-12} \le \tau_G = 10^{-9} \implies \text{OPEN}$), mens indre skjærbrudd ($\Delta_G > \tau_G$) eller ikke-positiv semidefinitt injeksjon ($\lambda_{\min}(G_t) < -\epsilon_{\text{mach}}$) utløser momentan `KILL`.
* **Artefakt:** `kernel_drift.py` (**6/6 PASS**).

---

## III. TOPOLOGISK MATRISE

| Monolitt | Ontologisk Akse | Operator / Observabel | Bruddkriterium ($\to \text{KILL}$) | Status |
| :--- | :--- | :--- | :--- | :--- |
| **1. Lysbrua** | Tid & Konsekvens | $\Omega_{\text{bridge}}(e, \text{Zone})$ | Eksplisitt avbrudd / ulovlig overgang | `6/6 PASS` |
| **2. Fase-Kjeglen** | Euklidsk Rom | $\sin(\theta) = \Delta\phi / \pi$ | $\lvert\Delta\phi / \pi\rvert > 1 \implies \cos\theta \in i\mathbb{R}$ | `6/6 PASS` |
| **3. Punkt // Bane** | Konstruksjon ($O(\lvert\gamma\rvert)$) | $\text{Verify}_{\mathcal{P}}(\gamma, W_{\text{PRE}}, W_{\text{POST}})$ | Brutt vitnekjede / kapasitetsbrudd | `6/6 PASS` |
| **4. Kernel Drift** | Indre Geometri | $\Delta_G = \Vert{}X_t^\top X_t - X_0^\top X_0\Vert{}_F$ | $\Delta_G > \tau_G \lor \lambda_{\min}(G_t) < -\epsilon_{\text{mach}}$ | `6/6 PASS` |

---

## IV. DEN TERMODYNAMISKE SILISIUM-BROEN

En matematisk lov som ignorerer maskinvarens endelige minne, termiske støy og Landauer-skatt ($Q_{\text{erase}} \ge k_B T \ln 2$), kollapser ved første møte med fysisk entropi. Overgangen fra platonsk aksiom til endelig silisium styres av tre mekanismer:

1. **Termodynamisk Epoke-Foldning ($\rho(\text{DP}) \ge 1$ i $O(1)$ Minne):**  
   Fysisk lagring $M_{\max} < \infty$ er endelig, mens beviskjeden er strengt monoton. Når en lokal Write-Ahead Log-epoke $E_k$ når sin kapasitetsgrense $\lvert E_k\rvert = M_{\text{epoch}}$, foldes epoken inn i en uforanderlig kryptografisk akkumulator-rot før råbufferen rulleres:
   $$R_k = \text{SHA256}\!\left(R_{k-1} \;\parallel\; \text{MerkleRoot}(E_k) \;\parallel\; \Delta_G(t_k)\right), \qquad k \mapsto k + 1$$
   Frigjøring av rå arbeidstilstander betaler Landauer-skatten uten å røre den historiske beviskraften: kjeden av epokerøtter $R_0 \to R_1 \to \dots \to R_k$ forblir strengt *append-only* i $O(1)$ aktivt minne. Ved asymmetrisk strømbrudd (*torn write*) isoleres kun uforseglet hale til `HOLD`, mens $R_{k-1}$ står intakt.
2. **Numerisk og Termisk Dødbånd ($\epsilon_{\text{mach}} \le \tau_G \ll \tau_{\text{rupture}}$):**  
   Porten krever aldri platonsk flyttalls-null i et støybegrenset medium. Tersklene $\tau_K$ og $\tau_G$ definerer et eksplisitt admisjonsbånd over IEEE-754 avrundingsdrift ($\epsilon_{\text{mach}} = 10^{-12}$) og under strukturelt brudd ($\tau_G = 10^{-9}$).
3. **Fravær av «Optimistic UI» og Stille Interpolering:**  
   Arkitekturen tillater ingen spekulativ tilstandsforskuttering, ingen *soft-error* maskering og ingen maskinlært interpolering over manglende vitner:

```python
if not witness_chain.is_continuous(R_k) or delta_K > tau_K or delta_G > tau_G:
    gate.authorize("KILL")  # Ingen rollback. Ingen interpolering. Kollisjonsgeometri kuttet.
elif evidence_id is None or zone == "OCCUPIED":
    gate.authorize("HOLD")  # Tid alene åpner ingen port (d/dt HOLD = 0).
else:
    gate.authorize("OPEN")
```

---

## V. ARKITEKTONISKE GRUNNRISS (L1 MODELL $\to$ LEVEL 01 SUVERENITET)

*Merk: Tallfestede fysiske tidsbudsjetter, spenninger og mekaniske krefter nedenfor beskriver det kanoniske designet og de deterministiske simuleringsmodellene ($L1$). Koden i det offentlige treet har ingen direkte fysisk aktuator-autoritet (`PHYSICAL_AUTHORITY = NONE`).*

### 1. Det Ortogonale Snittet ($\Pi_K$) & De 400 Klokkesyklusene
Skillet mellom et vektløst forslag i mulighetsrommet og en bevitnet handling, styrt av involusjon, støkiometri og det asymmetriske tidsgapet mellom konstruktiv åpning ($5{,}0\text{ ms}$) og destruktivt kutt ($12{,}5\ \mu\text{s}$):

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

### 2. Alexandrov-Skranken & Landauer-Asymmetrien ved Kaien
Hvordan relativistisk kausalitet ($ds^2 = -c^2\Delta t^2 + \Delta r^2 \le 0$) brukes som et termodynamisk skjold før CPU, RAM og disk vekkes:

```text
  [ ANGRIPER I BÅT: 500 METER UTE ]              [ ÆRLIG KURER PÅ BRYGGA: <= 20 M ]
  • Avstand tur-retur: Δr = 1000,0 m             • Avstand tur-retur: Δr <= 40,0 m
  • Kostnad for koherent puls: 10 000 J          • Fysisk arbeid inn i sonen: 578,75 J
  • Lysets reisetid: 3335,64 ns                  • Lysets reisetid: <= 133,4256 ns
                  │                                              │
                  ▼                                              ▼
  ================================================================================
         ALEXANDROV-SKRANKEN I L1-SILISIUM (TDC / 2,0 mm Safir på Ti-6Al-4V)
         Frist: Δt_budget = 133,4256 ns (Luft) // 177,9898 ns (532 nm Sjø)
         Minkowski-metrikk: ds² = -c²(Δt)² + (Δr)²
  ================================================================================
                  │                                              │
     [ ds² = +998 400,2 m² > 0 ]                    [ ds² <= 0 (Tidslignende) ]
     [ Romlignende / For sent  ]                    [ Fysisk nærvær bevist    ]
                  │                                              │
                  ▼                                              ▼
  ┌───────────────────────────────────┐          ┌───────────────────────────────┐
  │    TIDLIG AVVISNING (TDC-JORD)    │          │    FULL KRYPTOGRAFISK SLUSE   │
  │ • Ingen RAM-allokering            │          │ • Noise_KK + Ed25519 signatur │
  │ • Ingen Ed25519-beregning i CPU   │          │ • 16-bits KY-intervall (257:1)│
  │ • Ingen diskskriving (0 fsync)    │          │ • Synkron POSIX fsync() i WAL │
  │ • Forsvarerens kostnad: 8,0 μJ    │          │ • Forsvarerens kostnad: 0,50 J│
  └─────────────────┬─────────────────┘          └───────────────┬───────────────┘
                    │                                            │
                    ▼                                            ▼
  ┌───────────────────────────────────┐          ┌───────────────────────────────┐
  │     DOM: ✕ GATE::KILL (0,00 V)    │          │    DOM: ▶ GATE::OPEN (5,00 V) │
  │ • Utmattelsesforhold:             │          │ • Nash-gevinst:               │
  │   η_defense = 1,25 × 10⁹ : 1      │          │   U_A = -1578,75 J < 0        │
  └───────────────────────────────────┘          └───────────────────────────────┘
```

### 3. De 5 Millimeterne med Kald Luft (Menneskets Suverenitet)
Hvorfor suvereniteten alltid ender i hånden som holder nøkkelen:

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

## VI. EPISTEMISK GRENSEMURS-ERKLÆRING

$$\text{INSPIRED\_BY} \neq \text{IMPLEMENTS} \neq \text{PROVES}$$

1. **Null Autonomi:** Koden i dette treet besitter $0.00\%$ juridisk, operasjonell eller fysisk makt (`PHYSICAL_AUTHORITY=NONE`). All suverenitet hviler udelt hos *Level 01 Supreme Human Authority*.
2. **Eksakt Omfang:** Verifikasjonen (`24/24 PASS`) gjelder utelukkende de matematiske og logiske egenskapene til det sjekkede treet (`SCOPE=EXACT_CHECKED_TREE_ONLY`).
3. **Låst Påstand:** Alle åpne teoretiske ekstrapolasjoner er frosset i `CLAIM_STATUS=HOLD`.

---
*ReismannPoint Systems AS — Risør, Norge.*

