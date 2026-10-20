# SOLOLYS // SURFACE INDEX & VERIFICATION ENTRYPOINT

$$\boxed{\text{GENERATION} \neq \text{AUTHORIZATION} \neq \text{WITNESSED CONSEQUENCE}}$$

**EN:** Surface index for **Locus Zero (Risør, Norway · Brahman AS)**. Five public repositories with segregated responsibilities: **The Law** (`epistemic-architectures`), **The Gate** (`ky-rox-public-demonstrators`), **The Notes** (`epistemic-architectures-notes`), **The Tooling** (`loop-engineering`), and **The Manuscripts** (`skrivevaerelset`).  
**NO:** Overflateindeks for **Locus Zero (Risør · Brahman AS)**. Fem offentlige repositorier med adskilte ansvarsområder: **Loven** (`epistemic-architectures`), **Porten** (`ky-rox-public-demonstrators`), **Notatene** (`epistemic-architectures-notes`), **Verktøyet** (`loop-engineering`) og **Ordet** (`skrivevaerelset`).

* **Author:** Marius Egerhei Torjusen ([ORCID: `0009-0006-0431-6637`](https://orcid.org/0009-0006-0431-6637) · [Zenodo DOI: `10.5281/zenodo.18436983`](https://doi.org/10.5281/zenodo.18436983))
* **Epistemic Boundary:** `INSPIRED_BY != IMPLEMENTS != PROVES` · `PHYSICAL_AUTHORITY = NONE` (`L1` deterministic software only)

---

## I. QUICK-START EXECUTION // HURTIGVEIVISER (`0.00s` · Python Standard Library Only)

All public `L1` verifiers require **zero third-party packages** (`pip install` is not required; uses only Python $\ge 3.8$ standard library modules: `hashlib`, `json`, `math`, `sys`, `unittest`).

### 1. IT-OT Consequence Gate & Digital Twin Suite (SFI NORCICS / CPS4CIP Reference)
* **Specification:** [`IT_OT_CONSEQUENCE_GATE_NORCICS_BRIEF.md`](https://github.com/sololys/epistemic-architectures/blob/main/IT_OT_CONSEQUENCE_GATE_NORCICS_BRIEF.md) · [**PDF Brief**](https://github.com/sololys/epistemic-architectures/blob/main/IT_OT_CONSEQUENCE_GATE_NORCICS_BRIEF.pdf)
* **Domains Verified (`4/4 PASS`):**
  1. **Domain I (`Door 25` Digital Twin):** Involutive pre-execution collision test ($S_0 \xrightarrow{a} S_f \xrightarrow{a^{-1}} S_r$, $\|S_0 - S_r\| \le \varepsilon_{\mathrm{iso}}$) & envelope check.
  2. **Domain II (Constrained Local LLMs / HMIs):** Forward-invariant Nagumo barrier ($\langle \nabla h(x), f(x, u_{\mathrm{cand}})\rangle + \alpha(h(x)) \ge 0$) & dual receipt $W^2$.
  3. **Domain III (Maritime GNSS Denial):** Relativistic UWB Time-of-Flight light-cone bound ($d_{\mathrm{ToF}} \le c\Delta t/2$) & Euclidean AoA ($|\sin\theta| \le 1$).
  4. **Domain IV (VSG Microgrid BFT):** Screened dispersion gap ($\omega^2 = \mu_{\mathrm{eff}}^2 + c_s^2 k^2$) & multiplicative $(2f+1)$ quorum warrant.

```bash
git clone https://github.com/sololys/epistemic-architectures.git
cd epistemic-architectures
python3 tools/verify_norcics_digital_twin_llm_gate.py
```

<details>
<summary><strong>Zero-Trust Static Verification Trace (No Local Execution Required — SHA-256: <code>a30d7c93...ba785</code>)</strong></summary>

For reviewers operating under Zero-Trust policies that prohibit executing external scripts, [`tools/verify_norcics_digital_twin_llm_gate.py`](https://github.com/sololys/epistemic-architectures/blob/main/tools/verify_norcics_digital_twin_llm_gate.py) can be audited statically in the browser. Deterministic execution produces the following canonical JSON and SHA-256 witness chain:

```json
{
  "master_chain_sha256": "a30d7c934eaaa8b08600ae5ca54376df5440ac757a23fb6c6d4f2cbbd32ba785",
  "steps": [
    {
      "domain": "I_DIGITAL_TWIN_DOOR25",
      "reason": "TWIN_ASYMMETRY_DETECTED",
      "residual_iso": 0.05,
      "s0": [2.0, 3.0],
      "sf": [3.55, 2.0],
      "sr": [2.05, 3.0],
      "verdict": "KILL",
      "voltage_v": 0.0,
      "within_envelope": true,
      "witness_sha256": "1f85263c6a18673da92bc5d2c4969abef545880934b35e55dde1938f4a9c2691"
    },
    {
      "domain": "II_CONSTRAINED_LLM_HMI",
      "h_val": 0.2,
      "nagumo_lhs": -0.3,
      "reason": "RC-BARRIER-BREACH-KILL",
      "verdict": "KILL",
      "voltage_v": 0.0,
      "w2_valid": true,
      "witness_sha256": "051345c452bcbb22cd7908d0e44cc0a3380e18d00fb76972e914e04c5f2023f0"
    },
    {
      "d_tof_m": 14.989623,
      "domain": "III_MARITIME_UWB_LIGHTCONE",
      "gnss_divergence_m": 30.010377,
      "reason": "RC-CAUSAL-LIGHTCONE-VIOLATION",
      "s_obs_aoa": 0.5,
      "verdict": "HOLD",
      "voltage_v": 0.0,
      "witness_sha256": "b7ca2668dc98096554910cd2a5ebe12c0e2f487d16202bfa303ecebae551cd07"
    },
    {
      "active_votes": 3,
      "domain": "IV_VSG_DISPERSION_BFT",
      "mu_eff_rad_s": 10.0,
      "omega_rad_s": 12.0,
      "product_warrant": 1,
      "quorum_required": 3,
      "reason": "VSG_DISPERSION_QUORUM_PASS",
      "verdict": "OPEN",
      "voltage_v": 5.0,
      "witness_sha256": "0dd48e7eb23a5bdf56a7f9840ee29d4ab2560ef3ce8c470e1e86c365fcd920f2"
    }
  ]
}
```
</details>

### 2. The Four Monoliths Microtest Suite (`24/24 PASS`)
```bash
git clone https://github.com/sololys/ky-rox-public-demonstrators.git
cd ky-rox-public-demonstrators
python3 run_demo.py
```

---

## II. REPOSITORY DIRECTORY // KART OVER DE ÅPNE REPOSITORIENE

| Surface | Repository | Technical Scope & Artifacts | Entry |
| :--- | :--- | :--- | :--- |
| **⚖️ I. THE LAW** | [**`sololys/epistemic-architectures`**](https://github.com/sololys/epistemic-architectures) | Formal specifications for fail-closed projection ($\Phi \to \Pi_K \to \Omega \to W^2$), IT-OT consequence gating ([`IT_OT_CONSEQUENCE_GATE_NORCICS_BRIEF.pdf`](https://github.com/sololys/epistemic-architectures/blob/main/IT_OT_CONSEQUENCE_GATE_NORCICS_BRIEF.pdf)), and claim-level contracts. | [Open Repo $\to$](https://github.com/sololys/epistemic-architectures) |
| **⚡ II. THE GATE** | [**`sololys/ky-rox-public-demonstrators`**](https://github.com/sololys/ky-rox-public-demonstrators) | Four deterministic `L1` microtests (`24/24 PASS`): **Consequence** (`light_bridge_gate.py`), **Space** (`euclidean_phase_cone.py`), **Path** (`yinyang_binpacking.py`), and **Relation** (`kernel_drift.py`). | [Open Repo $\to$](https://github.com/sololys/ky-rox-public-demonstrators) |
| **📓 III. THE NOTES** | [**`sololys/epistemic-architectures-notes`**](https://github.com/sololys/epistemic-architectures-notes) | Working mathematical derivations, boundary counterexamples, and non-canonical extensions accompanying `epistemic-architectures`. | [Open Repo $\to$](https://github.com/sololys/epistemic-architectures-notes) |
| **🛠️ IV. THE TOOLING** | [**`sololys/loop-engineering`**](https://github.com/sololys/loop-engineering) | Local-first CLI evaluation harnesses and deterministic verification loops for autonomous coding agents. | [Open Repo $\to$](https://github.com/sololys/loop-engineering) |
| **📖 V. MANUSCRIPTS** | [**`sololys/skrivevaerelset`**](https://github.com/sololys/skrivevaerelset) | Long-form monographs and essays from Risør (*Konseptuell Granitt*, *Kutt Flaten: Et Notis*). Separated from engineering specifications to prevent scope conflation. | [Open Repo $\to$](https://github.com/sololys/skrivevaerelset) |

---

## III. ARCHITECTURAL INVARIANTS & SECURITY BOUNDARIES

### 1. Gate Subsumption & Asymmetric Timing ($\Phi \to \Pi_K \to \Omega \to W^2$)
```text
Candidate Phi(x_t)  --->  Projection Pi_K  --->  Verdict Omega in {KILL, HOLD, OPEN}
                                                   |-- KILL (0.00 V DC) : Immediate Cycle-1 cutoff; parallel post-mortem log
                                                   |-- HOLD (0.00 V DC) : High-Z quarantine; d/dt HOLD = 0
                                                   +-- OPEN (5.00 V DC) : Requires synchronous fsync() witness W^2 BEFORE actuation
```

### 2. Explicit Threat-Model Boundaries (DevSecOps & HIL Constraints)
1. **Bounded Physical Isolation (No Unbounded "Air-Gap Invulnerability" Claim):**  
   Physical air-gaps and dielectric barriers are bounded by Paschen breakdown ($V_B = f(p \cdot d)$), parasitic capacitance ($I_{\mathrm{disp}} = C\,\mathrm{d}V/\mathrm{d}t$), and radiative coupling. Hardware implementations (`L2/L3`) require explicit dielectric rating specification (e.g., $\text{Al}_2\text{O}_3$ optical isolation $\ge 25\text{ kV}$ and cylindrical $\text{TE}_{11}$ evanescent waveguide attenuation below cutoff $f_c$).
2. **Insider Threat & Coerced Operator Mitigation ($W^2 = W_{\mathrm{machine}} \land W_{\mathrm{human}}$):**  
   Human authority (`Level 01`) is **necessary for admission (`OPEN`) but never sufficient to override $\Pi_K$**. The actuation product is conjunctive:
   $$\mathrm{Actuate} = \mathbb{I}(\Omega(\Pi_K) == \mathrm{OPEN}) \cdot W_{\mathrm{machine}} \cdot W_{\mathrm{human}}.$$
   If a coerced or malicious insider attempts to force actuation while $\Pi_K$ evaluates to `KILL` or `HOLD` ($W_{\mathrm{machine}} = 0$), the mechanical/solid-state interlock remains trip-free at $0.00\text{ V DC}$.
3. **Cloud-Native Execution Guard (`PHYSICAL_AUTHORITY = NONE`):**  
   Public `L1` repositories are strictly mathematical/software evaluators and cannot be wired directly as unmediated cloud-to-actuator APIs:

```python
if deployment_mode == "CLOUD_UNMEDIATED_ACTUATION" or not hardware_interlock_present:
    enforce_hold_state(voltage_v=0.00)
    raise RuntimeError(
        "EPISTEMIC_BOUNDARY_VIOLATION: L1 software holds PHYSICAL_AUTHORITY=NONE. "
        "Requires local hardware consequence gate (Pi_K) and dual W^2 attestation."
    )
```

---
*Brahman AS — Risør, Norway (`ORCID: 0009-0006-0431-6637`).*
