---
title: "Nicotinamide (niacinamide)"
audit-log:
  - date: '2026-05-18'
    method: 4-sweep audit — wikipedia/grokipedia, openalex 2020-2026, synthesis (cochrane/AAD/NCCN/EADV/WHO-EML/ITP/DrugAge), trusted commentators (Lab Muffin, Patrick, Attia, Huberman, Blueprint)
    note: surfaced 4 high-priority gaps wired in — Hui 2020 Clin Exp Ophthalmol (n=57 crossover RCT, 219 cites) opening the glaucoma neuroprotection use case Wikipedia centers but the article didn't cover; Migaud 2024 Nat Rev Mol Cell Biol (92 cites) modern NAD+ metabolism synthesis updating Verdin 2015 + flagging that age-related NAD+ decline is mild (~30%) and inconsistent + NMN's FDA investigational-drug status; Schmults 2024 NCCN BCC guideline (111 cites) endorsing nicotinamide chemoprevention with 20% BCC reduction citation; Kandolf 2024 EADV/EuroGuiDerm AK + cSCC guideline (67 cites) more cautious framing citing both Chen 2015 + Allen 2023 + the German S3 non-recommendation for AK chemoprevention. Added a Glaucoma neuroprotection section + a Formal guideline status subsection showing the US-vs-EU divergence. Confirmed absences worth noting in prose — no Cochrane SR specifically on nicotinamide; no AAD nicotinamide-chemoprevention guideline; no ITP nicotinamide lifespan testing; no DrugAge mammalian nicotinamide lifespan data; no human aging-clock RCT on nicotinamide. Commentator sweep — Lab Muffin has no dedicated niacinamide deep dive (mentioned across 3 tangential posts); Patrick NAD+ topic page cites 6 DOIs (Mills 2016 NMN mouse, Liu 2018 NAD flux, Costford 2009 exercise NAMPT, Long 2015 NMN Alzheimer's mouse, Johnson 2018 NAD review, Beneke 2000 PARP1) — zero on human nicotinamide chemoprevention; Attia no nicotinamide-specific coverage; Huberman/Soleymani Aug 2024 cited Chen 2015 only (already in article); Bryan Johnson Blueprint takes NR (not nicotinamide) — directly illustrates the article's "longevity influencers pick the expensive precursor" framing.
---

**Nicotinamide** and **niacinamide** are two names for the same molecule — the amide form of vitamin B3 (pyridine-3-carboxamide). The dual naming is a marketing artifact: "nicotinamide" derives from the historical isolation by oxidation of nicotine (Huber 1867; different molecule, different effects); "niacinamide" was coined in the 1940s by the American Medical Association and food/vitamin industry specifically to dodge public association with tobacco when fortifying flour and bread with B vitamins.[^marques-2024-niacinamide-multiple-functions-mechanism] Medical research and Cochrane/PubMed/FDA use "nicotinamide"; consumer skincare brands (Olay, The Ordinary) and supplement bottles use "niacinamide." Same molecule, same NAD+ precursor mechanism via the salvage pathway.[^marques-2024-niacinamide-multiple-functions-mechanism][^verdin-2015-nad-aging-neurodegeneration] Distinct from **niacin** (nicotinic acid, the flushing form of vitamin B3) and from the more proximal NAD+ precursors **NMN + NR** marketed separately for longevity.[^verdin-2015-nad-aging-neurodegeneration]

Three main use cases anchor the evidence: **oral nicotinamide for non-melanoma skin cancer chemoprevention** (Chen 2015 ONTRAC, Phase 3 RCT, 23% NMSC reduction in immunocompetent high-risk patients — but Allen 2023 ONTRAC-2 found NO effect in transplant recipients, and the pooled meta-analysis is consistent with no significant effect; NCCN 2024 BCC guideline endorses it cautiously, EADV 2024 AK guideline more cautious still).[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention][^allen-2023-ontrac-2-nicotinamide-transplant-recipients][^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta][^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury][^schmults-2024-nccn-basal-cell-carcinoma-guideline][^kandolf-2024-eadv-actinic-keratosis-guideline] **Topical niacinamide for skin appearance** (Bissett 2004 5% face-half RCT; widely marketed as a \$6 cosmeceutical ingredient by P&G/Olay + The Ordinary + others) is much more popular but rests on weaker evidence — Lau 2024 explicitly excluded niacinamide from its Grade A/B/C cosmeceutical grading for lack of qualifying RCTs.[^bissett-2004-topical-niacinamide-aging-facial-skin][^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical][^lau-2024-cosmeceuticals-antiaging-systematic-review] **Oral nicotinamide for glaucoma neuroprotection** (Hui 2020 crossover RCT, n=57, 1.5–3.0 g/day improves inner retinal function on PhNR electroretinography in glaucoma patients already on IOP therapy) opens a third use case mostly absent from popular skincare discourse but established in ophthalmology.[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct]

For the broader skin-aging context see [skin](../organ/skin.md). NAD+ precursors (including nicotinamide) are classified as **caloric-restriction mimetics** per Madeo's 2019 framework — same autophagy-activating mechanism class as rapamycin, metformin, spermidine — though the empirical evidence that NAD+ supplementation reproduces fasting's longevity benefits in humans is weak. See [caloric restriction and fasting](caloric-restriction-and-fasting.md) for the framework context.[^verdin-2015-nad-aging-neurodegeneration]

## What it is

**Nicotinamide (= niacinamide)** is the amide form of vitamin B3.[^marques-2024-niacinamide-multiple-functions-mechanism][^nikas-2020-nicotinamide-cancer-chemoprevention-therapy-review] Vitamin B3 has two main forms:[^marques-2024-niacinamide-multiple-functions-mechanism][^nikas-2020-nicotinamide-cancer-chemoprevention-therapy-review]

| Form | Common names | Notable property |
|---|---|---|
| Nicotinic acid | niacin | Flushing reaction at oral doses ≥30mg (vasodilation via prostaglandin D2)[^marques-2024-niacinamide-multiple-functions-mechanism] |
| **Nicotinamide** | **niacinamide**, NAA, vitamin B3 amide | **No flushing** — better tolerated; the form used in chemoprevention + skincare[^marques-2024-niacinamide-multiple-functions-mechanism][^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention] |

Both convert to **NAD+ (nicotinamide adenine dinucleotide)** — the central cofactor for redox reactions, energy production (ATP synthesis), DNA repair (PARP1 substrate), and sirtuin signaling (SIRT1 substrate).[^verdin-2015-nad-aging-neurodegeneration][^imai-2000-sir2-nad-deacetylase][^nikas-2020-nicotinamide-cancer-chemoprevention-therapy-review] Nicotinamide enters the **salvage pathway** via NAMPT (nicotinamide phosphoribosyltransferase) → NMN → NAD+; this is the dominant NAD+ synthesis route in mammalian cells.[^verdin-2015-nad-aging-neurodegeneration][^nikas-2020-nicotinamide-cancer-chemoprevention-therapy-review]

**Distinct from the longevity-marketed NAD+ precursors**:[^verdin-2015-nad-aging-neurodegeneration]

- **NMN (nicotinamide mononucleotide)** and **NR (nicotinamide riboside)** are more proximal salvage-pathway intermediates; both convert to NAD+ via fewer enzymatic steps than nicotinamide. Marketed at 10–50× higher cost.[^verdin-2015-nad-aging-neurodegeneration]
- The human RCT evidence base for NMN + NR is much smaller than for nicotinamide; both raise plasma NAD+ in healthy adults (Martens 2018 NR 1 g/day raised blood NAD+ ~60% at 6 weeks in n=30; Igarashi 2022 NMN 250 mg/day raised blood NAD+ at 12 weeks in n=42 older Japanese men with improved gait speed + grip strength) but **no Phase 3 clinical outcome trials exist for either**.[^martens-2018-nicotinamide-riboside-healthy-adults-nad][^igarashi-2022-nmn-chronic-supplementation-blood-nad-older]
- Nicotinamide is the cheap, well-established alternative the NMN/NR conversation rarely centers.[^verdin-2015-nad-aging-neurodegeneration]

**Dietary sources** of vitamin B3: meat (chicken, beef, fish), grains (whole grains, fortified cereals), legumes, dairy.[^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta] **Tryptophan is a dietary precursor** at ~60:1 conversion ratio (60mg dietary tryptophan → 1mg niacin equivalent).[^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta] Dietary deficiency causes **pellagra** — dermatitis, diarrhea, dementia, death — historically associated with corn-dominant diets where niacin is bound in unavailable form. Pellagra is rare today in developed countries due to flour fortification (which adoption catalyzed the "niacinamide" naming chosen to avoid public anti-nicotine sentiment).[^marques-2024-niacinamide-multiple-functions-mechanism]

## Research history

- **1867** — Huber isolates nicotinic acid by oxidizing nicotine (tobacco alkaloid) — establishes the name "nicotinic acid" → later "nicotinamide" for the amide form.[^marques-2024-niacinamide-multiple-functions-mechanism]
- **1937** — Conrad Elvehjem identifies nicotinic acid as the pellagra-curing factor in liver extract; **niacin = vitamin B3** established.[^marques-2024-niacinamide-multiple-functions-mechanism]
- **1940s** — **American Medical Association coins "niacin" + "niacinamide"** to enable flour + bread fortification without public objection to "nicotine-related" naming. Consumer term diverges from medical term.[^marques-2024-niacinamide-multiple-functions-mechanism]
- **2000** — **Imai et al.** *Nature* publish foundational work showing **Sir2 (SIRT1 homolog) is a NAD+-dependent histone deacetylase** — establishes the molecular link between NAD+ availability and longevity-relevant cellular signaling.[^imai-2000-sir2-nad-deacetylase]
- **2002** — **Hakozaki et al.** (Procter & Gamble) publish the foundational mechanism paper showing **niacinamide blocks melanosome transfer from melanocytes to keratinocytes** (35–68% inhibition in vitro) — distinct from vit C's tyrosinase inhibition or hydroquinone's melanocyte toxicity. Two clinical trials (n=18 Japanese + n=120 white women) confirm clinical hyperpigmentation reduction.[^hakozaki-2002-niacinamide-melanosome-transfer-pigmentation]
- **2004** — **Bissett et al.** (P&G/Olay) publish the foundational topical niacinamide RCT for broader anti-aging — 5% topical niacinamide split-face trial in n=50 Caucasian women, 12 weeks: improved fine lines, hyperpigmented spots, texture, red blotchiness, yellowing. Procter & Gamble-sponsored; supports Olay Total Effects marketing.[^bissett-2004-topical-niacinamide-aging-facial-skin]
- **2015** — **Chen et al.** *NEJM* publish **ONTRAC** — Phase 3 double-blind RCT in n=386 patients with ≥2 prior NMSC: **oral nicotinamide 500mg twice daily reduced new non-melanoma skin cancers by 23%** (95% CI 4–38%, p=0.02) over 12 months. Effect dissipates after discontinuation.[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention] **Verdin** publishes the *Science* synthesis of NAD+ + aging + neurodegeneration — the foundational modern framework for NAD+ as a longevity-relevant target.[^verdin-2015-nad-aging-neurodegeneration]
- **2018** — **Martens et al.** *Nature Communications* establish that **nicotinamide riboside (NR) 1 g/day raises blood NAD+ by ~60% at 6 weeks** in healthy older adults (n=30) — the most-cited human NR biomarker trial; opens the NAD+ precursor supplementation pathway.[^martens-2018-nicotinamide-riboside-healthy-adults-nad]
- **2020** — **Nikas et al.** synthesize the broader cancer chemoprevention + radiotherapy adjunct evidence for nicotinamide — NMSC (per Chen 2015), head/neck SCC, laryngeal, urinary bladder cancers all have some Phase 3 evidence.[^nikas-2020-nicotinamide-cancer-chemoprevention-therapy-review]
- **2021** — **Boo** publishes the modern mechanism + clinical synthesis specifically for skin aging + pigmentation applications.[^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical]
- **2020** — **Hui et al.** *Clin Exp Ophthalmol* establish nicotinamide as a glaucoma neuroprotective adjunct: crossover RCT (n=57, 1.5–3.0 g/day over 12 weeks per arm) improves inner retinal function on PhNR electroretinography in glaucoma patients already on IOP-lowering therapy. Mechanism: NAD+ replenishment supports retinal ganglion cell mitochondrial function.[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct]
- **2022** — **Mainville et al.** publish the first comprehensive nicotinamide skin-cancer chemoprophylaxis meta-analysis (29 trials reviewed; 5 contributing to primary outcome) — concludes "evidence remains weak."[^mainville-2022-nicotinamide-skin-cancer-chemoprophylaxis-meta] **Igarashi et al.** *npj Aging* show NMN 250 mg/day for 12 weeks raises blood NAD+ + improves gait speed + grip strength in older Japanese men (n=42) — the most-cited NMN human RCT.[^igarashi-2022-nmn-chronic-supplementation-blood-nad-older]
- **2024** — **Migaud et al.** publish the modern *Nature Reviews Mol Cell Biol* flagship synthesis on NAD+ metabolism + targeting challenges (92 cites) — supersedes Verdin 2015 with honest framing that age-related NAD+ decline is "mild (~30%) and not entirely consistent" between individuals.[^migaud-2024-nad-metabolism-targeting-challenges-review] **Schmults et al.** publish the NCCN BCC guideline endorsing nicotinamide for chemoprevention (20% BCC reduction).[^schmults-2024-nccn-basal-cell-carcinoma-guideline] **Kandolf et al.** publish the EADV/EuroGuiDerm European S3 AK + cSCC guideline citing both Chen 2015 + Allen 2023 with cautious framing (the German S3 explicitly does NOT recommend chemoprevention for AK).[^kandolf-2024-eadv-actinic-keratosis-guideline]
- **2023** — **Allen et al. ONTRAC-2** (NEJM, n=158 organ transplant recipients) — same dose, same population (≥2 prior keratinocyte cancers), but immunosuppressed: **NO effect** on new keratinocyte cancers (rate ratio 1.0, 95% CI 0.8–1.3, p=0.96). Trial stopped early for poor recruitment. The negative replication that complicates the Chen 2015 framing.[^allen-2023-ontrac-2-nicotinamide-transplant-recipients] **Tosti et al.** meta-analyze 4 RCTs and find **pooled RR 0.82 (95% CI 0.61–1.12) — consistent with no significant effect** when immunocompetent + immunosuppressed populations are combined.[^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta]
- **2024** — **Marques et al.** publish a comprehensive *Antioxidants* mechanism synthesis covering niacinamide's NAD+ + DNA repair + antioxidant + anti-inflammatory + barrier + ECM + anti-pigmentation + antimicrobial roles in skin.[^marques-2024-niacinamide-multiple-functions-mechanism] **Lau et al.** cosmeceuticals SR explicitly **excludes niacinamide** from Grade A/B/C grading for lack of qualifying RCTs — the absence is informative.[^lau-2024-cosmeceuticals-antiaging-systematic-review]
- **2026** — **Tan E & Williams HC** publish critical appraisal *"Nicotinamide for Skin Cancer Chemoprevention: The Jury Was Out and Still is"* — argues the divergence between Chen 2015 + Allen 2023 + null pooled estimates means nicotinamide chemoprevention "is not yet confirmed" and "caution is warranted before widespread clinical adoption."[^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury]

**Honest reading as of 2026**: nicotinamide's strongest evidence is in the narrow indication of NMSC chemoprevention in immunocompetent high-risk patients (Chen 2015 ONTRAC).[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention][^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury] The popular oral-supplement and topical-cosmeceutical use cases have weaker evidence than the marketing implies; Lau 2024's exclusion is the dermatology synthesis verdict.[^lau-2024-cosmeceuticals-antiaging-systematic-review] The current consensus per Tan E 2026 is that even the chemoprevention claim has not been firmly established at synthesis-grade evidence quality.[^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury]

## Human evidence — oral chemoprevention

### Chen 2015 ONTRAC — the foundational Phase 3 RCT

**Chen et al.** (Australian + New Zealand academic team, NHMRC-funded — clean COI) randomized n=386 patients with ≥2 prior non-melanoma skin cancers in the past 5 years to oral nicotinamide 500mg twice daily or placebo for 12 months.[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention] Primary endpoint: rate of new NMSC at 12 months.[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention] Results:[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention]

- **23% reduction in new NMSC** at 12 months (95% CI 4–38%, p=0.02)[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention]
- 20% reduction in new SCC (p=0.05)[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention]
- 11% reduction in new actinic keratoses (cumulative p<0.001)[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention]
- **Effect dissipates within 6 months of discontinuation** — chemopreventive, not curative[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention]
- AE profile similar to placebo; no serious adverse events[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention]
- Clinical interpretation: a number-needed-to-treat (NNT) of ~6 patients to prevent 1 NMSC per year in this high-risk population[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention]

Mechanism rationale (per Chen + downstream literature): nicotinamide replenishes UV-depleted NAD+ → maintains ATP availability → enhances DNA damage repair via PARP1; reduces UV-induced immunosuppression by restoring Langerhans cell function.[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention][^verdin-2015-nad-aging-neurodegeneration][^marques-2024-niacinamide-multiple-functions-mechanism]

### Allen 2023 ONTRAC-2 — the negative replication

**Allen et al.** (NEJM, same Sydney team, NHMRC-funded) repeated the trial in organ transplant recipients (n=158) — same dose, same compound, same dermatology endpoint, different (immunosuppressed) population.[^allen-2023-ontrac-2-nicotinamide-transplant-recipients] Result:[^allen-2023-ontrac-2-nicotinamide-transplant-recipients]

- **No effect** on new keratinocyte cancers (rate ratio 1.0, 95% CI 0.8–1.3, p=0.96)[^allen-2023-ontrac-2-nicotinamide-transplant-recipients]
- 207 cancers in nicotinamide group vs 210 in placebo group at 12 months[^allen-2023-ontrac-2-nicotinamide-transplant-recipients]
- No significant between-group differences on SCC, BCC, AK counts, or quality of life[^allen-2023-ontrac-2-nicotinamide-transplant-recipients]
- Trial stopped early for poor recruitment — underpowered for smaller effects but rules out the Chen-2015-magnitude (23%) effect with high confidence[^allen-2023-ontrac-2-nicotinamide-transplant-recipients]

**The biological interpretation**: nicotinamide's chemopreventive mechanism likely requires intact immune surveillance — the precise pathway transplant patients lack on chronic immunosuppression. The Langerhans-cell restoration + UV-induced immunosuppression rescue that's plausibly central to Chen 2015's effect cannot operate when the immune compartment is pharmacologically suppressed.[^allen-2023-ontrac-2-nicotinamide-transplant-recipients]

### Pooled synthesis — "jury is still out"

**Tosti et al. 2023** meta-analyzed 4 RCTs (mixed immunocompetent + immunosuppressed populations) and found:[^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta]

- **NMSC overall**: RR 0.82 (95% CI 0.61–1.12) — **consistent with no significant effect**[^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta]
- SCC: RR 0.81 (0.48–1.37) — not significant[^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta]
- BCC: RR 0.88 (0.50–1.55) — not significant[^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta]

The pooled estimate's CI crosses 1.0 across all keratinocyte cancer types when immunocompetent + immunosuppressed are combined.[^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta] Tosti et al. nonetheless conclude with a pragmatic "may consider in high-risk immunocompetent patients" recommendation given the favorable safety profile + low cost.[^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta]

**Tan E & Williams 2026** critically appraise the evidence base (including a recent observational VA-veterans study reporting positive associations they argue is methodologically flawed) and conclude:[^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury]

- The 2022 (Mainville, 29 trials with 5 contributing to primary outcome) and 2023 (Tosti, 4 RCTs strict-inclusion) meta-analyses both concluded "weak evidence" for chemoprevention[^mainville-2022-nicotinamide-skin-cancer-chemoprophylaxis-meta][^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta][^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury]
- The 2023 meta-analysis pooled estimate (RR 0.82, 95% CI 0.61–1.12) is "consistent with no significant effect"[^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury][^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta]
- Observational evidence (VA-veterans study) has unmeasured confounders + immortal time bias + exposure misclassification[^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury]
- **"Current evidence does not yet confirm the chemopreventive efficacy of nicotinamide. Caution is warranted before its widespread clinical adoption — the jury, as it stands, is still out."**[^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury]

This is the honest framing for 2026. Reasonable practice in dermatology clinics is to recommend oral nicotinamide 500mg BID to immunocompetent patients with extensive actinic damage or history of multiple NMSCs (low cost, low harm, plausible benefit), while NOT recommending it to immunosuppressed (transplant) patients where the negative replication is direct.[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention][^allen-2023-ontrac-2-nicotinamide-transplant-recipients][^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury]

### Formal guideline status (diverges by body)

Two synthesis-grade guidelines published in 2024 take meaningfully different positions on nicotinamide chemoprevention despite reviewing similar evidence:[^schmults-2024-nccn-basal-cell-carcinoma-guideline][^kandolf-2024-eadv-actinic-keratosis-guideline]

- **NCCN BCC guideline (Schmults 2024)** has a dedicated section "Nicotinamide in Reducing BCC Development" citing Chen 2015 + Chen 2016 (Phase 2 renal transplant) + Surjana 2012 (Phase 2 AKs): "Data from phase II and phase III randomized trials indicated that treatment of actinic keratoses with nicotinamide reduced the occurrence of new BCCs, specifically by 20% at 12-month follow-up." Lists nicotinamide alongside celecoxib + acitretin + capecitabine + tazarotene as chemoprevention options for high-risk patients.[^schmults-2024-nccn-basal-cell-carcinoma-guideline] **Notably doesn't address Allen 2023 ONTRAC-2** — likely outside literature cutoff for this version.[^schmults-2024-nccn-basal-cell-carcinoma-guideline]
- **EADV/EuroGuiDerm AK + cSCC guideline (Kandolf 2024)** is more cautious — explicitly cites both Chen 2015 ONTRAC's 30% cSCC reduction in immunocompetent patients AND Allen 2023 ONTRAC-2's null effect in transplant recipients. Notes "no effect after nicotinamide discontinuation, and it is unclear if the preventive effects also pertain to AK." Points out that **the German S3 guideline does NOT recommend chemoprevention for AK**.[^kandolf-2024-eadv-actinic-keratosis-guideline]

The US-vs-EU guideline divergence on the same evidence base is informative — Tan E 2026's "jury is still out" framing aligns more closely with Kandolf 2024 EADV than with Schmults 2024 NCCN.[^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury][^kandolf-2024-eadv-actinic-keratosis-guideline][^schmults-2024-nccn-basal-cell-carcinoma-guideline]

### Other cancer indications (brief)

Beyond NMSC, **Phase 3 evidence supports nicotinamide as a radiotherapy adjunct** in head + neck squamous cell carcinoma, laryngeal cancer, and urinary bladder cancer — acts as an oxygen-mimetic radiosensitizer.[^nikas-2020-nicotinamide-cancer-chemoprevention-therapy-review] Preclinical evidence in other cancers (breast, colon, pancreatic) is mostly not yet evidence-based.[^nikas-2020-nicotinamide-cancer-chemoprevention-therapy-review]

## Human evidence — glaucoma neuroprotection

**Hui 2020** (Melbourne ophthalmology consortium, *Clin Exp Ophthalmol*, 219 OpenAlex cites) established nicotinamide as a glaucoma neuroprotective adjunct via a **crossover double-masked RCT** in n=57 glaucoma patients already on IOP-lowering therapy.[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct] Design: 6 weeks of 1.5 g/day NAM → 6 weeks of 3.0 g/day NAM → crossover to placebo. Endpoint: inner retinal function on photopic negative response (PhNR) electroretinography + visual field perimetry.[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct]

**Key results:**[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct]

- **PhNR Vmax improved 14.8% (p=0.02) on nicotinamide vs 5.2% (p=0.27) on placebo** — significant functional preservation[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct]
- **PhNR Vmax ratio improved 12.6% (p=0.002) on nicotinamide** vs 3.6% on placebo[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct]
- **23% of participants improved beyond 95% coefficient-of-repeatability threshold on nicotinamide vs 9% on placebo**[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct]
- Visual field trend: 27% improved ≥1 dB mean deviation on NAM vs 4% deteriorated on placebo (p=0.02)[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct]

**Mechanism rationale**: glaucoma involves retinal ganglion cell mitochondrial dysfunction; NAM as NAD+ precursor replenishes RGC NAD+ → supports mitochondrial complex I activity → preserves ATP-dependent RGC function.[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct][^migaud-2024-nad-metabolism-targeting-challenges-review] The proposed pathway parallels Pete Williams' (Karolinska, Hui 2020 co-author) mouse glaucoma work showing NAD+ depletion in RGCs precedes axon loss.[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct]

**Dose caveat**: Hui 2020 used 1.5–3.0 g/day — **3–6× the Chen 2015 ONTRAC chemoprevention dose** (1 g/day), approaching the >3 g/day hepatotoxicity threshold noted in Marques 2024.[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct][^marques-2024-niacinamide-multiple-functions-mechanism] PhNR is a surrogate endpoint, not long-term visual field preservation; longer-term trials underway.[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct] Wikipedia centers this use case as one of 4 main medical uses for nicotinamide despite being absent from popular skincare-focused niacinamide discourse — established in ophthalmology, less visible in dermatology + longevity contexts.[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct]

## Human evidence — topical skincare

### Bissett 2004 — the foundational topical RCT

**Bissett et al.** (Procter & Gamble Beauty + Personal Care, Cincinnati — heavily industry-sponsored, supports Olay Total Effects marketing) ran a 12-week split-face RCT in n=50 Caucasian women with moderate facial photoaging: 5% niacinamide cream on one side vs vehicle on the other.[^bissett-2004-topical-niacinamide-aging-facial-skin] Results:[^bissett-2004-topical-niacinamide-aging-facial-skin]

- Significant improvement on the niacinamide-treated side vs control side for: **fine lines/wrinkles, hyperpigmented spots, red blotchiness, skin yellowness, skin texture**[^bissett-2004-topical-niacinamide-aging-facial-skin]
- Effect sizes modest (small fractions of 0–5 scale points) but consistently significant across multiple endpoints[^bissett-2004-topical-niacinamide-aging-facial-skin]
- Tolerability good; no significant AEs[^bissett-2004-topical-niacinamide-aging-facial-skin]
- Mechanism rationale: improved barrier function (ceramide synthesis); reduced melanosome transfer (anti-pigmentation); NAD+ replenishment (anti-redox-stress)[^bissett-2004-topical-niacinamide-aging-facial-skin][^marques-2024-niacinamide-multiple-functions-mechanism]

### Modern mechanism synthesis

**Boo 2021** + **Marques 2024** provide modern mechanism syntheses covering topical niacinamide's multimodal effects:[^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical][^marques-2024-niacinamide-multiple-functions-mechanism]

- **Barrier function**: stimulates ceramide + free fatty acid synthesis; reduces TEWL — the "moisturizer-like" effect underlying the popularity[^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical][^marques-2024-niacinamide-multiple-functions-mechanism]
- **Anti-pigmentation**: inhibits melanosome transfer from melanocytes to keratinocytes (different mechanism from vit C's tyrosinase inhibition or hydroquinone's melanocyte toxicity) — useful for melasma + PIH[^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical][^marques-2024-niacinamide-multiple-functions-mechanism]
- **Anti-inflammatory**: NF-κB inhibition reduces TNF-α + IL-1β + IL-6 + IL-8 cascade[^marques-2024-niacinamide-multiple-functions-mechanism][^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical]
- **Sebum reduction**: clinically validated for acne (Lab Muffin's centerpiece use case)[^marques-2024-niacinamide-multiple-functions-mechanism]
- **ECM preservation**: stimulates collagen + elastin synthesis; inhibits MMPs[^marques-2024-niacinamide-multiple-functions-mechanism][^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical]

### The Lau 2024 exclusion problem

The **2024 Lau cosmeceuticals systematic review explicitly excluded niacinamide** from its Grade A/B/C grading "for lack of qualifying RCTs."[^lau-2024-cosmeceuticals-antiaging-systematic-review] This is the most-cited modern cosmeceutical grading framework — niacinamide didn't make the cut alongside retinol + topical vit C (Grade A), bakuchiol/growth factors (Grade C). The absence is informative: **the topical niacinamide evidence base is dominated by small industry-sponsored split-face RCTs (Bissett 2004 and many smaller P&G/Olay/L'Oréal trials)** that don't meet synthesis-grade RCT standards even when their pooled signal is real.[^lau-2024-cosmeceuticals-antiaging-systematic-review][^marques-2024-niacinamide-multiple-functions-mechanism]

The popular framing — niacinamide as a \$6 "must-have" skincare ingredient — outpaces the evidence quality. The biology is plausible (NAD+ + barrier + anti-pigmentation + anti-inflammatory); the clinical effect sizes are likely real but modest; the synthesis-grade evidence has not caught up.[^marques-2024-niacinamide-multiple-functions-mechanism][^lau-2024-cosmeceuticals-antiaging-systematic-review]

## Mechanism

Topical + oral nicotinamide operate through several converging mechanisms:[^marques-2024-niacinamide-multiple-functions-mechanism][^verdin-2015-nad-aging-neurodegeneration][^imai-2000-sir2-nad-deacetylase][^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical]

1. **NAD+ replenishment via salvage pathway** — nicotinamide → NMN (via NAMPT) → NAD+. Supports ATP synthesis, DNA repair (PARP1 substrate), and sirtuin-mediated gene regulation (SIRT1 substrate).[^verdin-2015-nad-aging-neurodegeneration][^imai-2000-sir2-nad-deacetylase] UV exposure depletes NAD+ in keratinocytes; nicotinamide replenishment maintains DNA repair capacity → mechanism for the Chen 2015 ONTRAC chemopreventive effect.[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention][^marques-2024-niacinamide-multiple-functions-mechanism]

2. **DNA damage repair enhancement** — PARP1 uses NAD+ as substrate to mark single-strand DNA breaks for repair; nicotinamide-driven NAD+ availability enhances this capacity.[^nikas-2020-nicotinamide-cancer-chemoprevention-therapy-review][^marques-2024-niacinamide-multiple-functions-mechanism] Direct mechanism for chemoprevention rationale.

3. **UV-induced immunosuppression rescue** — UV impairs Langerhans cell function + cytokine-mediated immune surveillance, which is one pathway by which UV-damaged keratinocytes escape immune clearance → carcinogenesis. Nicotinamide restores Langerhans cell function in human + animal models, the proposed key mechanism for Chen 2015's effect.[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention][^marques-2024-niacinamide-multiple-functions-mechanism] This mechanism likely doesn't operate in pharmacologically immunosuppressed populations (transplant recipients) — directly explains the Allen 2023 ONTRAC-2 null result.[^allen-2023-ontrac-2-nicotinamide-transplant-recipients]

4. **Antioxidant** — quenches ROS; supports glutathione recycling; tackles UV-driven oxidative damage that's a primary driver of photoaging.[^marques-2024-niacinamide-multiple-functions-mechanism][^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical]

5. **Anti-inflammatory** — NF-κB inhibition reduces TNF-α + IL-1β + IL-6 + IL-8 + iNOS cascade. Useful in acne, rosacea, post-procedural healing.[^marques-2024-niacinamide-multiple-functions-mechanism][^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical]

6. **Epidermal barrier function** — stimulates ceramide + sphingolipid + free fatty acid synthesis in keratinocytes; reduces transepidermal water loss; supports stratum corneum integrity.[^marques-2024-niacinamide-multiple-functions-mechanism][^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical] Mechanism for "moisturizer-like" effects underlying the popular skincare-ingredient framing.

7. **Anti-pigmentation via melanosome transfer inhibition** — niacinamide does NOT inhibit tyrosinase (unlike vit C) or kill melanocytes (unlike hydroquinone) — instead it **blocks the transfer of mature melanosomes from melanocytes to surrounding keratinocytes** (Hakozaki 2002 foundational P&G primary: 35–68% in vitro inhibition + clinical hyperpigmentation reduction in n=18 Japanese + n=120 white women).[^hakozaki-2002-niacinamide-melanosome-transfer-pigmentation][^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical][^marques-2024-niacinamide-multiple-functions-mechanism] Different mechanism layer; complementary to vit C + hydroquinone for combination treatment of melasma + PIH.

8. **Sirtuin and PARP1 dual role** — at low concentrations, nicotinamide is a substrate for NAD+ synthesis (enhances SIRT1 + PARP1 activity); at high concentrations, it directly inhibits SIRT1 + PARP1 enzymes.[^nikas-2020-nicotinamide-cancer-chemoprevention-therapy-review] Concentration-dependent dual mechanism — context-specific cellular effects (e.g., promotes apoptosis in cancer cells at high doses while supporting DNA repair in normal cells at physiological doses). Not clearly clinically dose-titrable today but mechanistically interesting.

**Key contrast with NMN + NR**: all three converge on NAD+ via the salvage pathway, but nicotinamide is the most upstream + cheapest precursor. NMN + NR are more proximal but the clinical-outcome evidence is much smaller; nicotinamide has the only Phase 3 RCT data for a clinical disease endpoint (Chen 2015 ONTRAC NMSC chemoprevention).[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention] The "NMN/NR is better than nicotinamide" claim popular in longevity discourse rests primarily on biomarker (plasma NAD+) data — **Martens 2018** showed NR 1 g/day raises blood NAD+ by ~60% in healthy older adults at 6 weeks (n=30), and **Igarashi 2022** showed NMN 250 mg/day raises NAD+ + improves gait speed/grip strength at 12 weeks in older Japanese men (n=42) — but neither has produced clinical disease outcomes.[^martens-2018-nicotinamide-riboside-healthy-adults-nad][^igarashi-2022-nmn-chronic-supplementation-blood-nad-older] Migaud 2024 notes that **age-related NAD+ decline is mild (~30%) and not entirely consistent between individuals**, and **few head-to-head NR vs NMN comparisons exist in rodents, NONE in humans** — challenging the longevity-discourse "NAD+ collapse causes aging" framing and the "NR is better than NMN" marketing.[^migaud-2024-nad-metabolism-targeting-challenges-review] **NMN is an FDA-regulated investigational drug** under DSHEA since 2022, ineligible for US dietary supplement distribution; NR has different regulatory status (granted dietary ingredient before investigational drug status).[^migaud-2024-nad-metabolism-targeting-challenges-review]

## Practical use

### Oral dosing

- **500 mg twice daily** is the Chen 2015 ONTRAC chemoprevention dose; same dose used in Allen 2023 ONTRAC-2. Standard recommendation for immunocompetent patients with history of multiple NMSCs.[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention]
- Available OTC as **vitamin B3 (niacinamide) supplements**, typically 500mg tablets, \$5–15/month.[^marques-2024-niacinamide-multiple-functions-mechanism]
- **Effect dissipates after discontinuation** — chemopreventive use requires sustained intake; not a one-course intervention.[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention]
- **Not recommended for immunosuppressed populations** (organ transplant recipients) per Allen 2023.[^allen-2023-ontrac-2-nicotinamide-transplant-recipients]

### Topical concentrations

- **2–5% niacinamide** is the standard cosmeceutical concentration; Bissett 2004 used 5%.[^bissett-2004-topical-niacinamide-aging-facial-skin]
- Available in dozens of products: The Ordinary Niacinamide 10% + Zinc 1% (\$6), Olay Total Effects, CeraVe Resurfacing Retinol Serum (with niacinamide), Paula's Choice 10% Niacinamide Booster, etc.[^marques-2024-niacinamide-multiple-functions-mechanism]
- Tolerated by all Fitzpatrick skin types; minimal irritation; compatible with most other actives (vit C, retinoids, AHAs).[^marques-2024-niacinamide-multiple-functions-mechanism][^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical]
- The popular "don't mix with vit C" claim is largely overstated — at modern formulation pH, niacinamide and vit C are stable together.[^marques-2024-niacinamide-multiple-functions-mechanism]

### Safety

- **Wide oral safety margin** — pellagra-prevention RDA is 14–18mg/day for adults; chemoprevention dose is 1g/day (~60× RDA); hepatotoxicity reported only at sustained doses >3g/day.[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention][^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta]
- **NO flushing** at any oral dose — distinct from niacin (nicotinic acid) which causes vasodilation at ≥30mg.[^marques-2024-niacinamide-multiple-functions-mechanism]
- **Pregnancy + breastfeeding**: well-tolerated; vitamin B3 is a standard prenatal supplement component.[^marques-2024-niacinamide-multiple-functions-mechanism]
- Topical: essentially no safety concerns at cosmeceutical concentrations across all skin types.[^marques-2024-niacinamide-multiple-functions-mechanism][^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical]

### When to consider

**Oral nicotinamide chemoprevention (500mg BID)** — reasonable for:[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention][^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta][^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury]
- Immunocompetent adults with **history of ≥2 prior NMSCs** (matches Chen 2015 population — strongest evidence)[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention]
- Adults with **extensive actinic damage + multiple AKs** as adjunct to topical/procedural treatment[^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta]
- NOT for primary prevention in low-risk populations (no evidence)[^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury]
- NOT for immunosuppressed populations (Allen 2023 null)[^allen-2023-ontrac-2-nicotinamide-transplant-recipients]
- Honest framing per Tan E 2026: "may consider given low cost + low harm + plausible benefit, but jury is still out — not synthesis-grade established"[^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury]

**Topical niacinamide (2–5% in serum or moisturizer)** — reasonable for:[^bissett-2004-topical-niacinamide-aging-facial-skin][^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical][^marques-2024-niacinamide-multiple-functions-mechanism]
- Mild-moderate hyperpigmentation (PIH, melasma) as combination therapy with vit C or hydroquinone[^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical]
- Mild barrier dysfunction / xerosis[^marques-2024-niacinamide-multiple-functions-mechanism]
- Adjunct in acne treatment routines (sebum + inflammation reduction)[^marques-2024-niacinamide-multiple-functions-mechanism]
- General "well-tolerated cosmeceutical with modest evidence" use case[^lau-2024-cosmeceuticals-antiaging-systematic-review]
- Don't expect retinoid-level or vit C-level effects on photoaging endpoints[^lau-2024-cosmeceuticals-antiaging-systematic-review]

## What we don't know

- **Whether chemoprevention efficacy generalizes beyond ≥2-NMSC immunocompetent populations** — Chen 2015 anchored the evidence in a narrow high-risk cohort; broader populations untested.[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention][^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury]
- **Whether nicotinamide chemoprevention works in any immunosuppressed population** — Allen 2023 null in transplant recipients; other immunosuppressed populations (HIV+, chronic immunosuppressive medications for autoimmune disease) untested.[^allen-2023-ontrac-2-nicotinamide-transplant-recipients]
- **Long-term oral safety beyond 12 months** — the chemoprevention dose (1g/day) is well-tolerated in trial settings to 12 months; long-term (years) safety data is sparse.[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention][^kapala-2022-isotretinoin-adverse-events-meta]
- **Whether nicotinamide adds to outcomes vs NMN or NR** in direct head-to-head trials — no human RCTs compare these NAD+ precursors on clinical outcomes. Martens 2018 (NR) + Igarashi 2022 (NMN) establish biomarker (plasma NAD+) evidence; no Phase 3 clinical outcome trials exist.[^martens-2018-nicotinamide-riboside-healthy-adults-nad][^igarashi-2022-nmn-chronic-supplementation-blood-nad-older][^verdin-2015-nad-aging-neurodegeneration]
- **Whether topical niacinamide meaningfully reduces photoaging endpoints** vs vehicle in synthesis-grade evidence — Lau 2024 explicitly excluded niacinamide for lack of qualifying RCTs; the field-wide trial quality is the limit.[^lau-2024-cosmeceuticals-antiaging-systematic-review]
- **Optimal topical concentration + frequency + combination strategies** — concentrations from 2% to 10% are marketed; head-to-head dose-response RCTs in well-defined populations are sparse.[^marques-2024-niacinamide-multiple-functions-mechanism]
- **Whether nicotinamide chemoprevention extends to melanoma** — Chen 2015 + Allen 2023 measured NMSC; melanoma risk reduction is a different question. Tosti 2023's one dietary-niacin observational study suggested potential SCC benefit but no melanoma signal.[^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta]
- **The concentration-dependent dual mechanism (NAD+ substrate at low doses, SIRT1/PARP1 inhibitor at high doses)** has not been clinically dose-titrated — could clinical effects be tuned by dose-stratification?[^nikas-2020-nicotinamide-cancer-chemoprevention-therapy-review]

<!-- begin-refs -->

[^marques-2024-niacinamide-multiple-functions-mechanism]: Marques C, Hadjab F, Porcello A, Lourenço K, Scaletta C, Abdel-Sayed P, et al.<br>
    [Mechanistic Insights into the Multiple Functions of Niacinamide: Therapeutic Implications and Cosmeceutical Applications in Functional Skincare Products](https://doi.org/10.3390/antiox13040425).<br>
    *Antioxidants*. 2024;13(4):425.<br>
    <span class="badge badge-review-type" title="Narrative review — author-selected synthesis of literature without a formal search protocol; vulnerable to selection bias.">narrative</span> <span class="badge badge-funding">💵 undisclosed</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 78</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2024</span>

[^verdin-2015-nad-aging-neurodegeneration]: Verdin E.<br>
    [NAD <sup>+</sup> in aging, metabolism, and neurodegeneration](https://doi.org/10.1126/science.aac4854).<br>
    *Science*. 2015;350(6265):1208–1213.<br>
    <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2015</span>

[^chen-2015-ontrac-nicotinamide-skin-cancer-chemoprevention]: Chen AC, Martin AJ, Choy B, Fernández-Peñas P, Dalziell RA, McKenzie CA, et al.<br>
    [A Phase 3 Randomized Trial of Nicotinamide for Skin-Cancer Chemoprevention](https://doi.org/10.1056/nejmoa1506197).<br>
    *New England Journal of Medicine*. 2015;373(17):1618–1626.<br>
    <span class="badge badge-design" title="Randomized controlled trial — participants randomly assigned to intervention or control; the gold standard for causal inference about intervention effects.">rct</span> <span class="badge badge-n">n=386</span> <span class="badge badge-outcome" title="Clinical outcome — directly meaningful to patients (death, MI, stroke, dementia diagnosis, hospitalization, fracture, quality of life).">clinical</span> <span class="badge badge-pre-reg" title="Pre-registered — protocol registered before participants enrolled, reducing outcome-switching and other p-hacking.">pre-reg</span> <span class="badge badge-funding">💵 NHMRC Australia (Blackmores donated tablets)</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 618</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2015</span>

[^allen-2023-ontrac-2-nicotinamide-transplant-recipients]: Allen NC, Martin AJ, Snaidr VA, Eggins R, Chong AH, Fernandéz-Peñas P, et al.<br>
    [Nicotinamide for Skin-Cancer Chemoprevention in Transplant Recipients](https://doi.org/10.1056/nejmoa2203086).<br>
    *New England Journal of Medicine*. 2023;388(9):804–812.<br>
    <span class="badge badge-design" title="Randomized controlled trial — participants randomly assigned to intervention or control; the gold standard for causal inference about intervention effects.">rct</span> <span class="badge badge-n">n=158</span> <span class="badge badge-outcome" title="Clinical outcome — directly meaningful to patients (death, MI, stroke, dementia diagnosis, hospitalization, fracture, quality of life).">clinical</span> <span class="badge badge-pre-reg" title="Pre-registered — protocol registered before participants enrolled, reducing outcome-switching and other p-hacking.">pre-reg</span> <span class="badge badge-funding">💵 NHMRC Australia</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 96</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2023</span>

[^tosti-2023-nicotinamide-nmsc-chemoprevention-sr-meta]: Tosti G, Pepe F, Gnagnarella P, Silvestri F, Gaeta A, Queirolo P, et al.<br>
    [The Role of Nicotinamide as Chemo-Preventive Agent in NMSCs: A Systematic Review and Meta-Analysis](https://doi.org/10.3390/nu16010100).<br>
    *Nutrients*. 2023;16(1):100.<br>
    <span class="badge badge-review-type" title="Meta-analysis — pools quantitative effect estimates from multiple studies into a single pooled estimate.">meta</span> <span class="badge badge-n">n=4</span> <span class="badge badge-funding">💵 undisclosed</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 19</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2023</span>

[^tan-e-2026-nicotinamide-skin-cancer-chemoprevention-jury]: Tan E, Williams HC.<br>
    [Nicotinamide for Skin Cancer Chemoprevention: The Jury Was Out and Still is](https://doi.org/10.1007/s40257-025-01005-y).<br>
    *American Journal of Clinical Dermatology*. 2026;27(2):209–215.<br>
    <span class="badge badge-review-type" title="Narrative review — author-selected synthesis of literature without a formal search protocol; vulnerable to selection bias.">narrative</span> <span class="badge badge-funding">💵 undisclosed</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 2</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2026</span>

[^schmults-2024-nccn-basal-cell-carcinoma-guideline]: Schmults CD, Blitzblau R, Aasi SZ, Alam M, Amini A, Bibee K, et al.<br>
    [Basal Cell Skin Cancer, Version 2.2024, NCCN Clinical Practice Guidelines in Oncology](https://doi.org/10.6004/jnccn.2023.0056).<br>
    *Journal of the National Comprehensive Cancer Network*. 2023;21(11):1181–1203.<br>
    <span class="badge badge-class" title="Clinical guideline or expert consensus statement.">guideline</span> <span class="badge badge-funding">💵 NCCN</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 111</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2023</span>

[^kandolf-2024-eadv-actinic-keratosis-guideline]: Kandolf L, Peris K, Malvehy J, Mosterd K, Heppt MV, Fargnoli MC, et al.<br>
    [European consensus‐based interdisciplinary guideline for diagnosis, treatment and prevention of actinic keratoses, epithelial <scp>UV</scp>‐induced dysplasia and field cancerization on behalf of European Association of Dermato‐Oncology, European Dermatology Forum, European Academy of Dermatology and Venereology and Union of Medical Specialists (Union Européenne des Médecins Spécialistes)](https://doi.org/10.1111/jdv.19897).<br>
    *Journal of the European Academy of Dermatology and Venereology*. 2024;38(6):1024–1047.<br>
    <span class="badge badge-class" title="Clinical guideline or expert consensus statement.">guideline</span> <span class="badge badge-funding">💵 EADV</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 67</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2024</span>

[^bissett-2004-topical-niacinamide-aging-facial-skin]: Bissett DL, Miyamoto K, Sun P, Li J, Berge CA.<br>
    [Topical niacinamide reduces yellowing, wrinkling, red blotchiness, and hyperpigmented spots in aging facial skin<sup>1</sup>](https://doi.org/10.1111/j.1467-2494.2004.00228.x).<br>
    *International Journal of Cosmetic Science*. 2004;26(5):231–238.<br>
    <span class="badge badge-design" title="Randomized controlled trial — participants randomly assigned to intervention or control; the gold standard for causal inference about intervention effects.">rct</span> <span class="badge badge-n">n=50</span> <span class="badge badge-outcome" title="Surrogate outcome — measured proxy expected to predict the clinical outcome (LDL, blood pressure, biomarker change, DNAm clock age); the surrogate-to-clinical translation is itself an empirical question.">surrogate</span> <span class="badge badge-funding">💵 Procter & Gamble</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 184</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2004</span>

[^boo-2021-niacinamide-skin-aging-pigmentation-mechanistic-clinical]: Boo YC.<br>
    [Mechanistic Basis and Clinical Evidence for the Applications of Nicotinamide (Niacinamide) to Control Skin Aging and Pigmentation](https://doi.org/10.3390/antiox10081315).<br>
    *Antioxidants*. 2021;10(8):1315.<br>
    <span class="badge badge-review-type" title="Narrative review — author-selected synthesis of literature without a formal search protocol; vulnerable to selection bias.">narrative</span> <span class="badge badge-funding">💵 undisclosed</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 174</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2021</span>

[^lau-2024-cosmeceuticals-antiaging-systematic-review]: Lau M, Mineroff Gollogly J, Wang JY, Jagdeo J.<br>
    [Cosmeceuticals for antiaging: a systematic review of safety and efficacy](https://doi.org/10.1007/s00403-024-02908-2).<br>
    *Archives of Dermatological Research*. 2024;316(5):173.<br>
    <span class="badge badge-review-type" title="Systematic review — comprehensive prespecified-protocol literature search and synthesis, without quantitative pooling.">systematic</span> <span class="badge badge-n">1,236 studies</span> <span class="badge badge-funding">💵 undisclosed</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 18</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2024</span>

[^hui-2020-nicotinamide-glaucoma-inner-retinal-function-rct]: Hui F, Tang J, Williams PA, McGuinness MB, Hadoux X, Casson RJ, et al.<br>
    [Improvement in inner retinal function in glaucoma with nicotinamide (vitamin <scp>B3</scp> ) supplementation: A crossover randomized clinical trial](https://doi.org/10.1111/ceo.13818).<br>
    *Clinical &amp; Experimental Ophthalmology*. 2020;48(7):903–914.<br>
    <span class="badge badge-design" title="Crossover trial — each participant receives every condition in randomized order, serving as their own control; reduces between-subject variance but vulnerable to carryover and period effects.">crossover</span> <span class="badge badge-n">n=57</span> <span class="badge badge-outcome" title="Surrogate outcome — measured proxy expected to predict the clinical outcome (LDL, blood pressure, biomarker change, DNAm clock age); the surrogate-to-clinical translation is itself an empirical question.">surrogate</span> <span class="badge badge-pre-reg" title="Pre-registered — protocol registered before participants enrolled, reducing outcome-switching and other p-hacking.">pre-reg</span> <span class="badge badge-funding">💵 undisclosed</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 219</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2020</span>

[^nikas-2020-nicotinamide-cancer-chemoprevention-therapy-review]: Nikas IP, Paschou SA, Ryu HS.<br>
    [The Role of Nicotinamide in Cancer Chemoprevention and Therapy](https://doi.org/10.3390/biom10030477).<br>
    *Biomolecules*. 2020;10(3):477.<br>
    <span class="badge badge-review-type" title="Narrative review — author-selected synthesis of literature without a formal search protocol; vulnerable to selection bias.">narrative</span> <span class="badge badge-funding">💵 Korea Health Industry Development Institute</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 133</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2020</span>

[^imai-2000-sir2-nad-deacetylase]: Imai S-i, Armstrong CM, Kaeberlein M, Guarente L.<br>
    [Transcriptional silencing and longevity protein Sir2 is an NAD-dependent histone deacetylase](https://doi.org/10.1038/35001622).<br>
    *Nature*. 2000;403(6771):795–800.<br>
    <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2000</span>

[^martens-2018-nicotinamide-riboside-healthy-adults-nad]: Martens CR, Denman BA, Mazzo MR, Armstrong ML, Reisdorph N, McQueen MB, et al.<br>
    [Chronic nicotinamide riboside supplementation is well-tolerated and elevates NAD+ in healthy middle-aged and older adults](https://doi.org/10.1038/s41467-018-03421-7).<br>
    *Nature Communications*. 2018;9(1):1286.<br>
    <span class="badge badge-design" title="Randomized controlled trial — participants randomly assigned to intervention or control; the gold standard for causal inference about intervention effects.">rct</span> <span class="badge badge-n">n=30</span> <span class="badge badge-outcome" title="Surrogate outcome — measured proxy expected to predict the clinical outcome (LDL, blood pressure, biomarker change, DNAm clock age); the surrogate-to-clinical translation is itself an empirical question.">surrogate</span> <span class="badge badge-pre-reg" title="Pre-registered — protocol registered before participants enrolled, reducing outcome-switching and other p-hacking.">pre-reg</span> <span class="badge badge-funding">💵 ChromaDex</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 567</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2018</span>

[^igarashi-2022-nmn-chronic-supplementation-blood-nad-older]: Igarashi M, Nakagawa-Nagahama Y, Miura M, Kashiwabara K, Yaku K, Sawada M, et al.<br>
    [Chronic nicotinamide mononucleotide supplementation elevates blood nicotinamide adenine dinucleotide levels and alters muscle function in healthy older men](https://doi.org/10.1038/s41514-022-00084-z).<br>
    *npj Aging*. 2022;8(1):5.<br>
    <span class="badge badge-design" title="Randomized controlled trial — participants randomly assigned to intervention or control; the gold standard for causal inference about intervention effects.">rct</span> <span class="badge badge-n">n=42</span> <span class="badge badge-outcome" title="Surrogate outcome — measured proxy expected to predict the clinical outcome (LDL, blood pressure, biomarker change, DNAm clock age); the surrogate-to-clinical translation is itself an empirical question.">surrogate</span> <span class="badge badge-pre-reg" title="Pre-registered — protocol registered before participants enrolled, reducing outcome-switching and other p-hacking.">pre-reg</span> <span class="badge badge-funding">💵 Mitsubishi</span> <span class="badge badge-funding">Oriental Yeast</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 106</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2022</span>

[^hakozaki-2002-niacinamide-melanosome-transfer-pigmentation]: Hakozaki T, Minwalla L, Zhuang J, Chhoa M, Matsubara A, Miyamoto K, et al.<br>
    [The effect of niacinamide on reducing cutaneous pigmentation and suppression of melanosome transfer](https://doi.org/10.1046/j.1365-2133.2002.04834.x).<br>
    *British Journal of Dermatology*. 2002;147(1):20–31.<br>
    <span class="badge badge-n">n=120</span> <span class="badge badge-outcome" title="Mechanism endpoint — cellular or molecular readout (gene expression, protein activity), more upstream than a surrogate.">mechanism</span> `💵 Procter & Gamble` <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 458</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2002</span>

[^mainville-2022-nicotinamide-skin-cancer-chemoprophylaxis-meta]: Mainville L, Smilga A-S, Fortin PR.<br>
    [Effect of Nicotinamide in Skin Cancer and Actinic Keratoses Chemoprophylaxis, and Adverse Effects Related to Nicotinamide: A Systematic Review and Meta-Analysis](https://doi.org/10.1177/12034754221078201).<br>
    *Journal of Cutaneous Medicine and Surgery*. 2022;26(3):297–308.<br>
    <span class="badge badge-review-type" title="Meta-analysis — pools quantitative effect estimates from multiple studies into a single pooled estimate.">meta</span> <span class="badge badge-n">n=29</span> <span class="badge badge-funding">💵 undisclosed</span> <span class="badge badge-cites" title="Citations counted by OpenAlex (typically more conservative than Google Scholar).">❝ 33</span> <span class="badge badge-year" title="Year of publication. Older papers may have been superseded; very recent papers may not yet be replicated.">2022</span>

[^migaud-2024-nad-metabolism-targeting-challenges-review]: Migaud ME, Ziegler M, Baur JA.<br>
    [Regulation of and challenges in targeting NAD+ metabolism](https://doi.org/10.1038/s41580-024-00752-w).<br>
    *Nature Reviews Molecular Cell Biology*. 2024;25(10):822–840.<br>
    <mark>narrative</mark> <mark>💵 undisclosed<mark> <mark>❝ 92</mark> <mark>2024</mark>

[^kapala-2022-isotretinoin-adverse-events-meta]: Kapała J, Lewandowska J, Placek W, Owczarczyk-Saczonek A.<br>
    [Adverse Events in Isotretinoin Therapy: A Single-Arm Meta-Analysis](https://doi.org/10.3390/ijerph19116463).<br>
    *International Journal of Environmental Research and Public Health*. 2022;19(11):6463.<br>
    <mark>❝50<mark> <mark>2022</mark>
<!-- end-refs -->
