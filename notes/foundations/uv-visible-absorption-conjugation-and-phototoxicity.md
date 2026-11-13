# Molecular blueprint: UV–visible absorption, conjugation and phototoxicity

> **Original study note · 14 November 2026**  
> **Scope:** General organic chemistry and molecular pharmacology; amiodarone is one *clinical example*, not the basis of the general rules.  
> **Evidence:** External chemistry teaching sources and primary photobiology papers (linked below). This is **not a transcription of** *Step Up to MRCP*.  
> **MRCP link:** Amiodarone photosensitivity (*Step Up to MRCP*, 3rd ed., Cardiology, **PDF p. 47 / printed p. 21**). The fundamental chemistry discussion is additional study material.

## One-minute model

A molecule absorbs a photon if it has an **accessible electronic excitation at the photon's energy** and that transition has **nonzero transition probability**. To absorb **UVA strongly**, the molecule generally needs a suitable **chromophore** with a **strong allowed transition** in the **315–400 nm** window. Extended, well-aligned conjugation often helps, but neither a benzene ring nor aromaticity alone guarantees strong UVA absorption.

```text
Structure -> molecular orbitals -> excitation energy + transition strength
                               -> absorption spectrum
Absorption + excited-state chemistry + tissue exposure -> possible phototoxicity
```

**Three separate questions:** (1) *Where* does it absorb? (2) *How strongly* does it absorb? (3) *What happens after excitation?* The answers need not track together.

## 1. Orbital vocabulary from first principles

- **sp² carbon:** uses three hybrid orbitals for approximately planar σ bonds; one unhybridised **p orbital** stands perpendicular to that local plane.
- **σ (sigma) bond:** electron density along the bond axis. A C=C contains one σ bond and one π bond.
- **π (pi) bond:** sideways overlap between neighbouring, roughly parallel p orbitals, with electron density above and below the σ-bond framework.
- **Conjugation:** **continuous overlap of adjacent p orbitals**, allowing electrons to be delocalised over three or more atoms. Alternating double–single–double bonds are a common pattern, but a participating lone pair or empty p orbital can also extend conjugation.
- **Planarity:** the relevant backbone atoms are roughly coplanar **so the p orbitals remain aligned**. The key variable is orbital overlap, not perfect planarity of every atom in the molecule.
- **π molecular orbital:** a lower-energy, bonding combination of p orbitals. **π\*** is a higher-energy **antibonding** combination, with different nodal structure; `*` means antibonding.
- **n orbital:** a nonbonding orbital, often associated with a heteroatom lone pair.
- **HOMO / LUMO:** highest occupied and lowest unoccupied molecular orbitals, respectively. The lowest electronic excitation often involves these, but **not every strong spectral band is a simple HOMO→LUMO transition**.

### Compare conjugated and isolated double bonds

```text
1,3-butadiene: CH2=CH–CH=CH2
               p–p–p–p  (four consecutive p orbitals)  -> conjugated

1,4-pentadiene: CH2=CH–CH2–CH=CH2
                        sp3 carbon interrupts overlap -> two isolated C=C
```

Rotation that twists adjacent p orbitals out of alignment can weaken or interrupt effective conjugation. In 1,3-butadiene, the *central single bond* does **not** interrupt the chain because both carbons bonded across it still have p orbitals.

**Do not confuse conjugation with Hückel aromaticity:** the **4n+2 π-electron rule** applies to certain cyclic, planar, continuously conjugated aromatic systems; conjugated chains such as butadiene are **not aromatic** yet can absorb UV.

## 2. What does π → π* actually mean?

An incident UV/visible photon can promote an electron from a bonding π orbital to a higher-energy antibonding π* orbital. This is an **electronic excitation**, **not necessarily ionisation, bond cleavage or permanent damage**. Other common transitions in organic compounds are **n → π*** (often weak), **n → σ*** and **σ → σ*** (often higher-energy, shorter-wavelength).

```text
Energy
  ^
  |            π*   [   ]     excited electron can occupy this level
  |                  ^  photon, hν
  |            π    [↑↓]     occupied bonding π orbital
  +--------------------------------------
```

`ΔE = hν = hc/λ`, or **`ΔE (eV) ≈ 1240 / λ (nm)`**. UVA **315–400 nm** corresponds to about **3.94–3.10 eV**. To have absorption in this band, an *allowed* electronic transition must lie in or overlap that energy range.

- **Wavelength/location of the band:** set by allowed excitation energies (orbital gaps, molecular structure, environment).
- **Intensity/strength of the band:** set by transition probability (often discussed as **oscillator strength** or molar absorptivity, ε), *as well as* observed concentration and path length. Beer–Lambert: `A = ε c l`.
- A transition can fall in UVA yet be **weak** (many n→π* bands). A molecule can have an intense π→π* band in UVB/UVC but *not* absorb UVA strongly.

## 3. Structural checklist for predicting a strong UVA chromophore

| Pattern to inspect | Why it matters | Caution |
| --- | --- | --- |
| **Extended conjugated C=C/C≡C chain** | Often reduces the lowest π→π* excitation energy: absorption shifts to longer wavelengths | Very long conjugation can shift the main band into **visible** light, past UVA |
| **Several fused aromatic rings** | Larger coupled π system can create longer-wavelength bands (e.g. anthracene vs benzene) | A single benzene ring alone does not imply strong UVA |
| **Conjugated carbonyl** (enone, extended aryl ketone) | Alters both π→π* and n→π* energies | n→π* may be **weak**, even when its wavelength is long |
| **Electron donor–π–acceptor system** | Donor/acceptor groups can create lower-energy charge-transfer transitions | Direction/size of shift depends on position, protonation and solvent |
| **Azo, coumarin, benzotriazole, extended heteroaromatic systems** | Conjugated heteroatoms create new accessible transitions | Family labels do not tell you wavelength or ε without a spectrum |
| **Locally planar backbone / parallel p orbitals** | Good p overlap supports delocalisation | Twisting can reduce overlap; strict whole-molecule planarity isn't required |
| **Lone pair adjacent to π network or empty p orbital** | May join the conjugated system | An sp³ atom with no participating p orbital commonly interrupts it |

**Practical procedure for a new structure:** (1) identify connected p orbitals; (2) mark conjugated segments; (3) inspect planarity/torsion; (4) identify carbonyls and donors/acceptors; (5) ask if the lowest *allowed* transitions enter UVA; (6) check **measured UV–Vis spectrum or a validated calculation** for both peak wavelength and ε. Structure-based guesses are hypotheses until checked.

### Illustrative trends (wavelengths depend on solvent and the band selected)

- **Ethene:** short-wavelength UV π→π* absorption.
- **1,3-butadiene:** absorption near **217 nm**, despite *not* being aromatic.
- **More-conjugated polyenes:** absorption generally shifts to longer wavelength; sufficiently long systems (e.g. β-carotene) absorb in the **visible**, not just UVA.
- **Benzene:** important absorption well below UVA, including a weak band near **254–256 nm**.
- **Anthracene:** extended fused aromatic system has bands reaching the near-UVA region.

Increasing conjugation generally produces a **bathochromic (red) shift**, *not an unlimited guarantee of a larger UVA peak*. An **hyperchromic** effect means increased band intensity, a distinct concept.

## 4. Strong UVA absorption does not establish photosensitivity

After photoexcitation, possible pathways include internal conversion (heat), fluorescence, intersystem crossing/triplet-state chemistry, electron transfer, energy transfer to oxygen, reactive oxygen species (ROS), isomerisation or bond cleavage. **Phototoxicity** requires that light-triggered chemistry causes tissue damage in a relevant exposure setting. **Photoallergy** instead involves immune sensitisation and is a distinct mechanism.

```text
Drug or metabolite reaches skin
        + relevant UV photons
        + effective excited-state reaction
        -> ROS / membrane injury / other damage -> phototoxic reaction
```

A measured **absorption spectrum** of a compound is *not* identical to the **action spectrum** for a skin reaction. The clinical action spectrum also depends on metabolites, optical penetration through skin, drug localisation and the chemistry of damage.

**Not generally “DNA chelation”:** phototoxic reactions can damage nucleic acids, proteins and membranes via excited-state chemistry, but chelation is not a general prerequisite for UVA absorption or drug phototoxicity.

## 5. Clinical case: amiodarone, with evidence limits

- Amiodarone contains a **benzofuran-linked aryl ketone**, iodinated aromatic ring, and basic aminoether side chain; its aromatic/carbonyl chromophores are candidates for light absorption, but **do not assign a measured UVA band to one fragment solely from the structural drawing**.
- Older patient phototesting found prominent photoactivation at **350–380 nm** in one study, while another reported a broader action spectrum around **335–460 nm** with experimental uncertainty. These are **clinical phototoxic action spectra**, not the isolated drug's pure-compound UV–Vis absorption maximum.
- Laboratory experiments found phototoxic potential for **both amiodarone and desethylamiodarone**. Which species and reaction dominates in vivo is **not settled by the structural blueprint**.
- Separate adverse-effect mechanisms must not be conflated: **iodine release** helps explain thyroid hormone dysregulation; **drug/metabolite toxicity** contributes to destructive thyroiditis; **skin phototoxicity** requires photoactivation and damaging excited-state chemistry.

For MRCP revision: **amiodarone → photosensitivity**, and the mechanism is more precise than “all aromatics absorb UVA.”

## 6. Self-test (original questions; answers below)

1. Is **1,3-butadiene** conjugated? Is it aromatic? Why?
2. Why does a central **sp³ carbon** in 1,4-pentadiene prevent conjugation between the two C=C bonds?
3. In `π→π*`, what does the asterisk mean? Does excitation guarantee bond breaking?
4. If a transition has `ΔE = 3.3 eV`, is its wavelength approximately UVA, UVB, UVC or visible?
5. Name **two independent conditions** needed for strong UVA absorption.
6. Why might a substance absorb 365-nm light in vitro yet cause little skin phototoxicity?
7. Is a phototoxic **action spectrum** identical to a compound's UV–Vis **absorption spectrum**?

<details>
<summary>Answer key — open after trying</summary>

1. Yes: four contiguous p orbitals allow delocalisation; no: it is an acyclic conjugated system, not aromatic.
2. That CH₂ carbon is tetrahedral and lacks a p orbital aligned with both π systems.
3. Antibonding. No: the excitation can relax harmlessly or take various chemical paths.
4. `1240/3.3 ≈ 376 nm`: UVA.
5. A transition with an energy in UVA **and** sufficiently high transition probability/oscillator strength; adequate concentration and path length also affect measured absorbance.
6. Weak exposure in skin, lack of tissue accumulation, harmless excited-state relaxation, effective antioxidant defence or failure to produce damaging reaction products.
7. No; the action spectrum additionally depends on biological exposure, metabolites and photochemistry.

</details>

## Sources and audit trail

**External basic chemistry (not from the MRCP textbook):**

- [IUPAC Gold Book — π-conjugated system](https://goldbook.iupac.org/terms/view/08786/plain): definitions, delocalisation and exceptions to simple alternating bond drawings.
- [Chemistry LibreTexts — UV Spectroscopy](https://chem.libretexts.org/Ancillary_Materials/Worksheets/Spectroscopy_%28Worksheets%29/03%3A_UV_Spectroscopy): σ/π/n orbital transitions, ε and Beer–Lambert law.
- [Chemistry LibreTexts — Visible and Ultraviolet Spectroscopy](https://chem.libretexts.org/Bookshelves/Organic_Chemistry/Supplemental_Modules_%28Organic_Chemistry%29/Spectroscopy/Visible_and_Ultraviolet_Spectroscopy): conjugation trends and intensities.
- [OpenStax Organic Chemistry — effect of conjugation](https://chem.libretexts.org/Bookshelves/Organic_Chemistry/Organic_Chemistry_%28OpenStax%29/14%3A_Conjugated_Compounds_and_Ultraviolet_Spectroscopy/14.08%3A_Interpreting_Ultraviolet_Spectra-_The_Effect_of_Conjugation): HOMO–LUMO gap and absorption shifts.

**Primary photobiology studies (historical sample sizes; mechanisms not fully resolved):**

- [Walter et al., 1984 — *Amiodarone Photosensitivity*, Arch Dermatol](https://pubmed.ncbi.nlm.nih.gov/6508331/): phototesting peak region 350–380 nm.
- [Ferguson et al., 1985 — *A study of cutaneous photosensitivity induced by amiodarone*, Br J Dermatol](https://pubmed.ncbi.nlm.nih.gov/4063190/): broader patient action spectrum and in-vitro phototoxicity of the drug and desethyl metabolite.
- [Diffey et al., 1984 — *Photobiology of amiodarone*, Clin Exp Dermatol](https://doi.org/10.1111/j.1365-2230.1984.tb00791.x): clinical action-spectrum measurements and metabolite hypothesis.

**Reviewed:** 14 November 2026. **Safety:** Mechanism study note, not clinical prescribing guidance. Check current UK SmPC/BNF for drug-specific clinical decisions.
