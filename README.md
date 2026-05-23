---
title: "Senolytics"
audit-log:
  - date: '2026-05-23'
    method: 4-sweep audit — Wikipedia + Grokipedia cross-check, synthesis resources (Cochrane + NIA ITP + DrugAge), OpenAlex canonical-recent, FoundMyFitness + Attia popular-source check
    note: 6 papers wired in; net effect deflationary.
---

Senolytics are drugs that selectively kill senescent cells — cells that have entered permanent cell-cycle arrest but remain metabolically active and secrete a pro-inflammatory mix of cytokines, proteases, and growth factors (the senescence-associated secretory phenotype, SASP).[^coppe-2008-sasp-secretory-phenotype][^childs-2015-cellular-senescence-aging] The animal evidence is genuinely strong: genetically clearing senescent cells in normal-aging mice extends median lifespan ~25%, and the senolytic drug pair dasatinib + quercetin extends late-life survival when started in old mice.[^baker-2016-naturally-occurring-p16-lifespan][^xu-2018-senescent-cells-physical-dysfunction] Human evidence is early and, so far, underwhelming — open-label trials in idiopathic pulmonary fibrosis and diabetic kidney disease show the drugs reduce senescent-cell burden, but the first placebo-controlled trial found no functional benefit, the lead industry program (UNITY's UBX0101) failed in osteoarthritis, and there is no clinical-outcome or lifespan data in healthy adults.[^justice-2019-senolytics-ipf][^hickson-2019-senolytics-diabetic-kidney][^nambiar-2023-senolytics-ipf-rct][^chaib-2022-senolytics-path-to-clinic] The central live questions: whether intermittent clearance helps people without a defined disease, and whether removing senescent cells is safe given that senescence also suppresses tumors and aids wound healing.[^campisi-2013-aging-senescence-cancer]

## What it is

Cellular senescence is one of the hallmarks of aging.[^lopez-otin-2023-hallmarks-aging-update] Cells enter senescence in response to DNA damage, oncogene activation, telomere attrition, or mitochondrial dysfunction; they exit the cell cycle, resist apoptosis, and accumulate with age.[^childs-2015-cellular-senescence-aging] The SASP — IL-6, IL-8, MCP-1, MMPs, growth factors — propagates senescence to neighboring cells, drives chronic low-grade inflammation ("inflammaging"), and contributes to multiple age-related pathologies.[^coppe-2008-sasp-secretory-phenotype]

Senescent cells survive by upregulating **senescent-cell anti-apoptotic pathways (SCAPs)** — notably the BCL-2 family (Bcl-xL) and PI3K–AKT survival signaling. Senolytics transiently inhibit these pathways, tipping senescent cells (which depend on them) into apoptosis while sparing normal cells. Because the effect is to *eliminate* a cell population rather than occupy a receptor, senolytics are given **intermittently** ("hit-and-run" dosing) rather than continuously — intermittent dosing is as effective as continuous for reducing senescent-cell burden, and the short human half-lives of dasatinib (~4 h), quercetin (~11 h), and fisetin (~3–4 h) suit brief pulses.[^zhu-2015-senolytic-discovery-d-q][^chaib-2022-senolytics-path-to-clinic]

| Class | Mechanism | Notes |
|---|---|---|
| **Dasatinib + quercetin (D+Q)** | Dasatinib hits tyrosine-kinase/PI3K-dependent survival; quercetin hits BCL-2/Bcl-xL — broader together than either alone | Dasatinib is an FDA-approved leukemia drug; quercetin a dietary flavonoid; the most-studied senolytic combination[^zhu-2015-senolytic-discovery-d-q] |
| **Fisetin** | Flavonoid engaging pro-apoptotic pathways in senescent cells | Natural senolytic, consumer-accessible; reduced senescence markers and extended lifespan in one mouse study,[^yousefzadeh-2018-fisetin-senolytic] but the NIA ITP found **no lifespan extension and no senescent-cell clearance** at 600 ppm across three sites and two dosing schedules[^harrison-2023-itp-fisetin-astaxanthin] |
| **Navitoclax (ABT-263)** and other BCL-2 inhibitors | Direct BCL-2/Bcl-xL/Bcl-w inhibition; senolytic but **cell-type-restricted** (kills senescent endothelial cells and fibroblasts, not preadipocytes) | Potent in some senescent cell types; dose-limiting thrombocytopenia (Bcl-xL is essential for platelet survival) restricts systemic human use[^zhu-2016-navitoclax-senolytic] |
| **Tissue-targeted senolytics** (UBX-series, FOXO4-DRI peptide) | Local delivery or targeted SCAP disruption to limit off-target effects | UBX1325/foselutoclax (a BCL-xL senolytic) is delivered **intravitreally** for retinal vascular disease — the most clinically-advanced tissue-targeted senolytic, in early trials for diabetic macular edema and neovascular AMD[^macha-2024-ubx1325-erg-namd] |
| **Cardiac glycosides** (digoxin, ouabain) | Inhibit the Na+/K+ ATPase → membrane depolarization and acidification, to which senescent cells are preferentially vulnerable; broad-spectrum | Repurposing interest (both are approved heart drugs), but a narrow therapeutic index and the CG-insensitivity of rodent cells preclude standard mouse-lifespan validation; preclinical only[^triana-martinez-2019-cardiac-glycosides-senolytic] |
| **Immunological senolytics** (CAR T cells) | Chimeric antigen receptor T cells targeting uPAR, a cell-surface antigen broadly induced on senescent cells — a "living drug" rather than a small molecule | Extended survival in tumour-bearing mice and reversed liver fibrosis; preclinical, and carries the cost and toxicity profile of cell therapy[^amor-2020-senolytic-car-t] |

## Research history

The field moved from genetic proof-of-concept to drugs to first-in-human trials in under a decade:[^baker-2011-senescent-cells-clearance][^zhu-2015-senolytic-discovery-d-q][^baker-2016-naturally-occurring-p16-lifespan][^xu-2018-senescent-cells-physical-dysfunction][^justice-2019-senolytics-ipf]

- **2011** — Baker's INK-ATTAC transgenic mouse lets researchers genetically delete p16-positive senescent cells; clearing them delays age-related decline in a progeroid model — the first causal demonstration that senescent cells *drive* aging dysfunction, not just mark it.[^baker-2011-senescent-cells-clearance]
- **2015** — Zhu identifies the first *pharmacological* senolytics (dasatinib + quercetin) by targeting the anti-apoptotic pathways senescent cells depend on — converting a genetic trick into a druggable strategy.[^zhu-2015-senolytic-discovery-d-q]
- **2016** — Baker shows genetic clearance extends median lifespan ~25% in *normal-aging* (non-progeroid) mice, establishing the lifespan stakes.[^baker-2016-naturally-occurring-p16-lifespan]
- **2018** — Xu's transplant experiment closes the causal loop (injecting senescent cells into young mice causes dysfunction) and shows D+Q extends late-life survival.[^xu-2018-senescent-cells-physical-dysfunction]
- **2019** — the first two human senolytic trials report, moving the field from mice to (disease-population) patients.[^justice-2019-senolytics-ipf][^hickson-2019-senolytics-diabetic-kidney]

**Honest reading as of 2026.** The causal mouse biology is among the strongest in geroscience.[^baker-2016-naturally-occurring-p16-lifespan][^xu-2018-senescent-cells-physical-dysfunction] The translation gap is the whole story: human data are tiny, open-label, surrogate-endpoint, and in sick populations. Whether senolytics extend healthspan in humans — let alone healthy ones — is unproven.[^justice-2019-senolytics-ipf][^hickson-2019-senolytics-diabetic-kidney]

## Animal evidence

| Study | Model | Finding |
|---|---|---|
| Baker 2011 | BubR1 progeroid mice + INK-ATTAC genetic clearance | Ablating p16+ cells delayed decline in fat, muscle, eye — first causal proof[^baker-2011-senescent-cells-clearance] |
| Zhu 2015 | Cell + mouse screens | D+Q identified via senescent-cell SCAP vulnerabilities; cleared senescent cells in vitro and in vivo[^zhu-2015-senolytic-discovery-d-q] |
| Baker 2016 | INK-ATTAC mice, **normal aging** | Genetic clearance extended median lifespan **+24–27%**, attenuated multiple age-related dysfunctions[^baker-2016-naturally-occurring-p16-lifespan] |
| Xu 2018 | Senescent-cell transplant + aged mice | Transplanted senescent cells **cause** physical dysfunction in young mice; D+Q extended post-treatment survival **+36%** started in old age[^xu-2018-senescent-cells-physical-dysfunction] |
| Yousefzadeh 2018 | Aged mice | **Fisetin** reduced senescence markers and extended health/lifespan with a favorable tolerability profile[^yousefzadeh-2018-fisetin-senolytic] — but the NIA ITP later found no lifespan or senescence-clearance effect (see below)[^harrison-2023-itp-fisetin-astaxanthin] |

The Baker 2016 normal-aging result (~25% median lifespan) is the keystone — a larger effect than rapamycin's ~10–14% in comparable mouse studies, though achieved by genetic ablation rather than a drug.[^baker-2016-naturally-occurring-p16-lifespan][^harrison-2009-itp-rapamycin-lifespan] Xu 2018's transplant arm is the cleanest causal demonstration in the field.[^xu-2018-senescent-cells-physical-dysfunction] **One caution is decisive**: the gold-standard NIA Interventions Testing Program (ITP) has reproduced rapamycin's lifespan benefit across multiple sites — but when it tested the senolytic **fisetin** (600 ppm, continuous and cyclic schedules, three sites), it found **no lifespan extension in either sex and no reduction in senescent-cell burden**, a null co-authored by the same investigators who first reported fisetin's senolytic effect.[^harrison-2023-itp-fisetin-astaxanthin] No senolytic *drug* (D+Q or fisetin) has an ITP-grade replicated lifespan result; the strongest lifespan claims rest on single-lab studies and on genetic, not pharmacological, clearance.[^harrison-2009-itp-rapamycin-lifespan][^harrison-2023-itp-fisetin-astaxanthin]

## Human evidence

| Trial | Design | Finding |
|---|---|---|
| Justice 2019 (IPF) | Phase 1 open-label, n=14 idiopathic pulmonary fibrosis | First-in-human senolytic trial: D+Q (3 days on / 11 off × 3 cycles) improved physical-function measures (6-min walk, gait speed, sit-to-stand) at 4 weeks; no control arm[^justice-2019-senolytics-ipf] |
| Nambiar 2023 (IPF) | Phase 1 **randomized, placebo-controlled**, n=12 idiopathic pulmonary fibrosis | The controlled follow-up to Justice 2019: D+Q feasible and tolerated, but **no meaningful between-group difference** in pulmonary, physical, or frailty measures, and ~3× more non-serious adverse events (sleep disturbance, anxiety). Feasibility-primary and underpowered for efficacy[^nambiar-2023-senolytics-ipf-rct] |
| Hickson 2019 (DKD) | Open-label, n=9 diabetic kidney disease | D+Q reduced adipose-tissue senescent-cell burden (p16, p21, SASP factors fell) — biological proof of target engagement; no clinical-outcome data[^hickson-2019-senolytics-diabetic-kidney] |

A third first-in-human trial extended the approach to a neurodegenerative disease: **Gonzales 2023** (SToMP-AD, *Nat Med*, open-label, **n=5** mild Alzheimer's, 12-week intermittent D+Q). Its primary aim was CNS penetrance and feasibility, not efficacy — and it found dasatinib reached cerebrospinal fluid (4/5) but **quercetin did not**, with safety/feasibility supported but CSF GFAP (a reactive-astrogliosis marker) *increased* and no change in tau or brain volume.[^gonzales-2023-senolytics-alzheimers-phase1]

These early human trials are **proof-of-concept**: small (n=5–14), mostly open-label, surrogate endpoints, short follow-up, in *disease* populations. They establish that senolytics engage their target in humans (Hickson) and are broadly tolerable — but the lone **placebo-controlled** test found the open-label functional gains did *not* separate from placebo (Nambiar 2023), a caution against reading uncontrolled signals as efficacy.[^justice-2019-senolytics-ipf][^hickson-2019-senolytics-diabetic-kidney][^gonzales-2023-senolytics-alzheimers-phase1][^nambiar-2023-senolytics-ipf-rct] The quercetin-doesn't-cross-into-CSF finding is a further complication for brain-targeted D+Q.[^gonzales-2023-senolytics-alzheimers-phase1] More trials are underway — Alzheimer's[^gonzales-2023-senolytics-alzheimers-phase1] and retinal disease (UBX1325)[^macha-2024-ubx1325-erg-namd] among them — but the field also has its first clear human failure: UNITY's intra-articular **UBX0101** did not achieve its primary pain endpoint in a Phase 2 knee-osteoarthritis trial.[^chaib-2022-senolytics-path-to-clinic]

## Mechanism

Senescent cells resist their own apoptosis by upregulating SCAP networks — BCL-2/Bcl-xL, PI3K–AKT–FOXO, and p53/p21/serpine survival nodes. Senolytics work by **transiently disabling the specific survival dependency** of senescent cells, which sit closer to the apoptotic threshold than normal cells; a brief hit therefore preferentially kills them.[^zhu-2015-senolytic-discovery-d-q] Removing the cells eliminates their SASP, which is the proximate driver of paracrine senescence spread and inflammaging — so the downstream benefit is as much about silencing the secretory phenotype as about the cell count itself.[^coppe-2008-sasp-secretory-phenotype] In aged mice, clearing senescent cells — with fisetin, D+Q, or genetic ablation alike — reduced inflammation and roughly halved mortality from a β-coronavirus infection, direct evidence that removing the SASP source improves resilience to an acute stressor.[^camell-2021-senolytics-coronavirus-mortality]

The same biology is the source of the field's central risk. Senescence is not purely pathological: it is a **tumor-suppressive** program (arresting damaged cells that might otherwise become cancerous) and participates in wound healing and tissue remodeling.[^campisi-2013-aging-senescence-cancer] Indiscriminate, chronic senescent-cell clearance could in principle impair these protective functions — a reason the intermittent "hit-and-run" schedule (clear, then let the system recover) is mechanistically as well as practically preferred.[^campisi-2013-aging-senescence-cancer]

## Practical use

- **Off-label use is widespread in longevity clinics and self-experimentation**, far ahead of the evidence. The trial-derived **D+Q** schedule is dasatinib 100 mg + quercetin 1000 mg for 3 consecutive days, repeated every 2–4 weeks — the regimen used in the IPF and DKD studies, not validated for healthy adults.[^justice-2019-senolytics-ipf][^hickson-2019-senolytics-diabetic-kidney]
- **Fisetin** is consumer-accessible as a supplement; common self-dosing (~1500–2000 mg/day for 2–3 consecutive days monthly) is **extrapolated from mouse data, not from any human efficacy trial** — and the one gold-standard animal test, the NIA ITP, found no lifespan extension or senescent-cell clearance at the dose it used.[^yousefzadeh-2018-fisetin-senolytic][^harrison-2023-itp-fisetin-astaxanthin] The registered fisetin trials (Mayo's AFFIRM-LITE and AFFIRM frailty trials) have not reported primary outcomes, and oral bioavailability is poor. Treat the dose as unvalidated.
- **Side effects**: in the senolytic regimen (brief, low cumulative exposure) D+Q was generally well-tolerated in the IPF, DKD, and Alzheimer's trials.[^justice-2019-senolytics-ipf][^hickson-2019-senolytics-diabetic-kidney][^gonzales-2023-senolytics-alzheimers-phase1] At *continuous oncology doses* dasatinib carries bleeding/bruising (thrombocytopenia), pleural effusion (~26% long-term), pulmonary arterial hypertension, QTc prolongation, and CYP3A4 interactions — so cycling frequency, not single doses, is the relevant safety variable; quercetin can cause GI upset.[^cheng-2023-dasatinib-adverse-reactions-cml-review]
- **Monitoring**: baseline and periodic CBC and liver enzymes are prudent in repeated use, and baseline echocardiography is advised before dasatinib given its cardiopulmonary profile; senolytics are intended as periodic pulses, not daily chronic medication.[^cheng-2023-dasatinib-adverse-reactions-cml-review]
- Senolytics are distinct from **senomorphics** — agents such as [rapamycin](rapamycin.md) and [metformin](metformin.md) that suppress the SASP / inflammaging output of senescent cells *without killing them*. Metformin, for example, restores autophagy and dampens the Th17 inflammaging profile of aged human T cells, a senomorphic mode of action — so despite frequent loose framing, **metformin is not a senolytic**.[^zhu-2015-senolytic-discovery-d-q][^bharath-2020-metformin-autophagy-inflammaging][^chaib-2022-senolytics-path-to-clinic] Senomorphics generally need continuous dosing to keep the SASP suppressed, whereas senolytics act in intermittent pulses; the net-benefit comparison between the two strategies is unsettled.[^chaib-2022-senolytics-path-to-clinic]

## What we don't know

- **Whether senolytics benefit healthy aging adults.** Every human trial to date is in a defined disease (IPF, DKD, AD, OA); the healthy-aging use that dominates off-label practice is entirely unstudied.[^justice-2019-senolytics-ipf][^hickson-2019-senolytics-diabetic-kidney]
- **Human lifespan / mortality / hard-outcome effects.** No trial has been long enough or powered for clinical endpoints; the ~25–36% lifespan figures are mouse data.[^baker-2016-naturally-occurring-p16-lifespan][^xu-2018-senescent-cells-physical-dysfunction]
- **The cost of clearing beneficial senescence.** Because senescence suppresses tumors and aids wound healing, the long-term safety of repeated clearance — especially the cancer-risk balance — is unresolved.[^campisi-2013-aging-senescence-cancer][^demaria-2017-senescence-cancer-recurrence]
- **Which senescent cells, in which tissues.** Senescent-cell types differ by tissue and SCAP dependency; D+Q clears some better than others, and no agent is comprehensive. Validated **senescence-burden biomarkers** (e.g., the SASP panel of GDF15, TNFR1, OPN, and related factors) are still being established as trial endpoints.[^schafer-2020-sasp-senescence-medical-risk]
- **Optimal agent, dose, and schedule** in humans — and whether any senolytic *drug* will achieve a replicated, multi-site mouse-lifespan result like rapamycin's. The one senolytic the NIA ITP has tested for lifespan, fisetin, neither extended life nor cleared senescent cells; D+Q has not been ITP-tested for lifespan.[^harrison-2009-itp-rapamycin-lifespan][^harrison-2023-itp-fisetin-astaxanthin]

<!-- begin-refs -->

[^coppe-2008-sasp-secretory-phenotype]: Coppé J-P, Patil CK, Rodier F, Sun Y, Muñoz DP, Goldstein J, et al.<br>
    [Senescence-Associated Secretory Phenotypes Reveal Cell-Nonautonomous Functions of Oncogenic RAS and the p53 Tumor Suppressor](https://doi.org/10.1371/journal.pbio.0060301).<br>
    *PLoS Biology*. 2008;6(12):e301.<br>
    `2008`

[^childs-2015-cellular-senescence-aging]: Childs BG, Durik M, Baker DJ, van Deursen JM.<br>
    [Cellular senescence in aging and age-related disease: from mechanisms to therapy](https://doi.org/10.1038/nm.4000).<br>
    *Nature Medicine*. 2015;21(12):1424–1435.<br>
    `narrative` `💵 NIH` `❝2,262` `2015`

[^baker-2016-naturally-occurring-p16-lifespan]: Baker DJ, Childs BG, Durik M, Wijers ME, Sieben CJ, Zhong J, et al.<br>
    [Naturally occurring p16Ink4a-positive cells shorten healthy lifespan](https://doi.org/10.1038/nature16932).<br>
    *Nature*. 2016;530(7589):184–189.<br>
    `2016`

[^xu-2018-senescent-cells-physical-dysfunction]: Xu M, Pirtskhalava T, Farr JN, Weigand BM, Palmer AK, Weivoda MM, et al.<br>
    [Senolytics improve physical function and increase lifespan in old age](https://doi.org/10.1038/s41591-018-0092-9).<br>
    *Nature Medicine*. 2018;24(8):1246–1256.<br>
    `2018`

[^justice-2019-senolytics-ipf]: Justice JN, Nambiar AM, Tchkonia T, LeBrasseur NK, Pascual R, Hashmi SK, et al.<br>
    [Senolytics in idiopathic pulmonary fibrosis: Results from a first-in-human, open-label, pilot study](https://doi.org/10.1016/j.ebiom.2018.12.052).<br>
    *EBioMedicine*. 2019;40:554–563.<br>
    `2019`

[^hickson-2019-senolytics-diabetic-kidney]: Hickson LJ, Langhi Prata LG, Bobart SA, Evans TK, Giorgadze N, Hashmi SK, et al.<br>
    [Senolytics decrease senescent cells in humans: Preliminary report from a clinical trial of Dasatinib plus Quercetin in individuals with diabetic kidney disease](https://doi.org/10.1016/j.ebiom.2019.08.069).<br>
    *EBioMedicine*. 2019;47:446–456.<br>
    `2019`

[^nambiar-2023-senolytics-ipf-rct]: Nambiar A, Kellogg D, Justice J, Goros M, Gelfond J, Pascual R, et al.<br>
    [Senolytics dasatinib and quercetin in idiopathic pulmonary fibrosis: results of a phase I, single-blind, single-center, randomized, placebo-controlled pilot trial on feasibility and tolerability](https://doi.org/10.1016/j.ebiom.2023.104481).<br>
    *eBioMedicine*. 2023;90:104481.<br>
    `rct (n=12)` `clinical` `prereg` `💵 NIH` `❝236` `2023`

[^chaib-2022-senolytics-path-to-clinic]: Chaib S, Tchkonia T, Kirkland JL.<br>
    [Cellular senescence and senolytics: the path to the clinic](https://doi.org/10.1038/s41591-022-01923-y).<br>
    *Nature Medicine*. 2022;28(8):1556–1568.<br>
    `narrative` `💵 NIA` `❝1,010` `2022`

[^campisi-2013-aging-senescence-cancer]: Campisi J.<br>
    [Aging, Cellular Senescence, and Cancer](https://doi.org/10.1146/annurev-physiol-030212-183653).<br>
    *Annual Review of Physiology*. 2013;75(1):685–705.<br>
    `narrative` `💵 NIH` `💵 NIA` `❝2,867` `2013`

[^lopez-otin-2023-hallmarks-aging-update]: López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G.<br>
    [Hallmarks of aging: An expanding universe](https://doi.org/10.1016/j.cell.2022.11.001).<br>
    *Cell*. 2023;186(2):243–278.<br>
    `narrative` `💵 ERC` `💵 AEI Spain` `❝5,362` `2023`

[^zhu-2015-senolytic-discovery-d-q]: Zhu Y, Tchkonia T, Pirtskhalava T, Gower AC, Ding H, Giorgadze N, et al.<br>
    [The Achilles’ heel of senescent cells: from transcriptome to senolytic drugs](https://doi.org/10.1111/acel.12344).<br>
    *Aging Cell*. 2015;14(4):644–658.<br>
    `2015`

[^yousefzadeh-2018-fisetin-senolytic]: Yousefzadeh MJ, Zhu Y, McGowan SJ, Angelini L, Fuhrmann-Stroissnigg H, Xu M, et al.<br>
    [Fisetin is a senotherapeutic that extends health and lifespan](https://doi.org/10.1016/j.ebiom.2018.09.015).<br>
    *EBioMedicine*. 2018;36:18–28.<br>
    `2018`

[^harrison-2023-itp-fisetin-astaxanthin]: Harrison DE, Strong R, Reifsnyder P, Rosenthal N, Korstanje R, Fernandez E, et al.<br>
    [Astaxanthin and meclizine extend lifespan in UM-HET3 male mice; fisetin, SG1002 (hydrogen sulfide donor), dimethyl fumarate, mycophenolic acid, and 4-phenylbutyrate do not significantly affect lifespan in either sex at the doses and schedules used](https://doi.org/10.1007/s11357-023-01011-0).<br>
    *GeroScience*. 2023;46(1):795–816.<br>
    `rct (🐭, n=584)` `clinical` `prereg` `💵 NIA` `❝51` `2023`

[^zhu-2016-navitoclax-senolytic]: Zhu Y, Tchkonia T, Fuhrmann‐Stroissnigg H, Dai HM, Ling YY, Stout MB, et al.<br>
    [Identification of a novel senolytic agent, navitoclax, targeting the Bcl‐2 family of anti‐apoptotic factors](https://doi.org/10.1111/acel.12445).<br>
    *Aging Cell*. 2016;15(3):428–435.<br>
    `🧫` `mechanism` `💵 NIA` `❝1,090` `2016`

[^macha-2024-ubx1325-erg-namd]: Macha N, Yu M, Sapieha P, Klier S, Ghosh A, White L, et al.<br>
    [Multifocal Electroretinography Changes after UBX1325 (Foselutoclax) Treatment in Neovascular Age-Related Macular Degeneration](https://doi.org/10.3390/jcm13185540).<br>
    *Journal of Clinical Medicine*. 2024;13(18):5540.<br>
    `single-arm (n=5)` `surrogate` `💵 UNITY Biotechnology` `❝3` `2024`

[^triana-martinez-2019-cardiac-glycosides-senolytic]: Triana-Martínez F, Picallos-Rabina P, Da Silva-Álvarez S, Pietrocola F, Llanos S, Rodilla V, et al.<br>
    [Identification and characterization of Cardiac Glycosides as senolytic compounds](https://doi.org/10.1038/s41467-019-12888-x).<br>
    *Nature Communications*. 2019;10(1):4731.<br>
    `🧫` `mechanism` `💵 AEI Spain` `❝374` `2019`

[^amor-2020-senolytic-car-t]: Amor C, Feucht J, Leibold J, Ho Y-J, Zhu C, Alonso-Curbelo D, et al.<br>
    [Senolytic CAR T cells reverse senescence-associated pathologies](https://doi.org/10.1038/s41586-020-2403-9).<br>
    *Nature*. 2020;583(7814):127–132.<br>
    `🐭` `mechanism` `💵 NIA` `💵 HHMI` `❝1,021` `2020`

[^baker-2011-senescent-cells-clearance]: Baker DJ, Wijshake T, Tchkonia T, LeBrasseur NK, Childs BG, van de Sluis B, et al.<br>
    [Clearance of p16Ink4a-positive senescent cells delays ageing-associated disorders](https://doi.org/10.1038/nature10600).<br>
    *Nature*. 2011;479(7372):232–236.<br>
    `2011`

[^harrison-2009-itp-rapamycin-lifespan]: Harrison DE, Strong R, Sharp ZD, Nelson JF, Astle CM, Flurkey K, et al.<br>
    [Rapamycin fed late in life extends lifespan in genetically heterogeneous mice](https://doi.org/10.1038/nature08221).<br>
    *Nature*. 2009;460(7253):392–395.<br>
    `rct (🐭, n=1,901)` `clinical` `prereg` `💵 NIA` `❝3,716` `2009`

[^gonzales-2023-senolytics-alzheimers-phase1]: Gonzales MM, Garbarino VR, Kautz TF, Palavicini JP, Lopez-Cruzan M, Dehkordi SK, et al.<br>
    [Senolytic therapy in mild Alzheimer’s disease: a phase 1 feasibility trial](https://doi.org/10.1038/s41591-023-02543-w).<br>
    *Nature Medicine*. 2023;29(10):2481–2488.<br>
    `single-arm (n=5)` `surrogate` `prereg` `💵 NIA` `💵 Alzheimer's Association` `❝232` `2023`

[^camell-2021-senolytics-coronavirus-mortality]: Camell CD, Yousefzadeh MJ, Zhu Y, Prata LGPL, Huggins MA, Pierson M, et al.<br>
    [Senolytics reduce coronavirus-related mortality in old mice](https://doi.org/10.1126/science.abe4832).<br>
    *Science*. 2021;373(6552):eabe4832.<br>
    `🐭` `clinical` `💵 NIA` `❝318` `2021`

[^cheng-2023-dasatinib-adverse-reactions-cml-review]: Cheng F, Xu Q, Li Q, Cui Z, Li W, Zeng F.<br>
    [Adverse reactions after treatment with dasatinib in chronic myeloid leukemia: Characteristics, potential mechanisms, and clinical management strategies](https://doi.org/10.3389/fonc.2023.1113462).<br>
    *Frontiers in Oncology*. 2023;13:1113462.<br>
    `narrative` `💵 ❓` `❝33` `2023`

[^bharath-2020-metformin-autophagy-inflammaging]: Bharath LP, Agrawal M, McCambridge G, Nicholas DA, Hasturk H, Liu J, et al.<br>
    [Metformin Enhances Autophagy and Normalizes Mitochondrial Function to Alleviate Aging-Associated Inflammation](https://doi.org/10.1016/j.cmet.2020.04.015).<br>
    *Cell Metabolism*. 2020;32(1):44–55.e6.<br>
    `mechanism` `💵 NIA` `❝597` `2020`

[^demaria-2017-senescence-cancer-recurrence]: Demaria M, O'Leary MN, Chang J, Shao L, Liu S, Alimirah F, et al.<br>
    [Cellular Senescence Promotes Adverse Effects of Chemotherapy and Cancer Relapse](https://doi.org/10.1158/2159-8290.cd-16-0241).<br>
    *Cancer Discovery*. 2017;7(2):165–176.<br>
    `cohort (🐭, n=89)` `clinical` `💵 NIH` `💵 NIA` `❝1,291` `2017`

[^schafer-2020-sasp-senescence-medical-risk]: Schafer MJ, Zhang X, Kumar A, Atkinson EJ, Zhu Y, Jachim S, et al.<br>
    [The senescence-associated secretome as an indicator of age and medical risk](https://doi.org/10.1172/jci.insight.133668).<br>
    *JCI Insight*. 2020;5(12):e133668.<br>
    `2020`
<!-- end-refs -->
