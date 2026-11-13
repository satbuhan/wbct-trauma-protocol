# Whole-Body CT in Traumatic Circulatory Shock — Interactive Decision Algorithm

An interactive, referenced walkthrough of the decision algorithm for
whole-body CT (WBCT) in traumatic circulatory shock — the immediate
life-threat gate that decides whether to scan at all, a metabolic (not
blood-pressure-only) definition of shock, the environment-safety gate that
decides whether the institution can deliver WBCT safely right now, the
single-pass acquisition protocol, and the three immediate-action pathways
once the scan is interpreted. Every box and decision point in the diagram
can be selected to reveal, in one place: what the step means, why the
algorithm calls for it, and the sources behind it.

**Live site:** https://satbuhan.github.io/wbct-trauma-protocol/

**Authors:** Dr. Özgür Karcıoğlu & Dr. Satuk Buğra Han Bozatlı

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24112602.svg)](https://doi.org/10.5281/zenodo.24112602)

This tool is part of a growing atlas of tools built the same way:

- [Clinical Algorithm Atlas](https://satbuhan.github.io/clinical-algorithm-atlas/) — the hub page for all of them
- [Acute aortic dissection — initial medical management](https://github.com/satbuhan/aortic-dissection-protocol) ([live site](https://satbuhan.github.io/aortic-dissection-protocol/))
- [Butyrophenone selection — acute agitation & hyperactive delirium](https://github.com/satbuhan/agitation-delirium-protocol) ([live site](https://satbuhan.github.io/agitation-delirium-protocol/))
- [Influenza antiviral selection — baloxavir marboxil vs oseltamivir](https://github.com/satbuhan/influenza-antiviral-protocol) ([live site](https://satbuhan.github.io/influenza-antiviral-protocol/))
- [Dexketoprofen vs ibuprofen — selecting an NSAID for acute pain](https://github.com/satbuhan/nsaid-pain-protocol) ([live site](https://satbuhan.github.io/nsaid-pain-protocol/))
- [Anticoagulant reversal in gastrointestinal haemorrhage](https://github.com/satbuhan/anticoagulant-reversal-protocol) ([live site](https://satbuhan.github.io/anticoagulant-reversal-protocol/))
- [The adult with obesity in emergency and critical care](https://github.com/satbuhan/obesity-critical-care-protocol) ([live site](https://satbuhan.github.io/obesity-critical-care-protocol/))
- [Dapagliflozin / SGLT2 inhibitor — overdose and acute illness management](https://github.com/satbuhan/dapagliflozin-overdose-protocol) ([live site](https://satbuhan.github.io/dapagliflozin-overdose-protocol/))
- [Lidocaine vs prilocaine — local anaesthesia for laceration repair](https://github.com/satbuhan/lidocaine-prilocaine-protocol) ([live site](https://satbuhan.github.io/lidocaine-prilocaine-protocol/))
- [Reperfusion therapy in acute pulmonary thromboembolism](https://github.com/satbuhan/pte-thrombolysis-protocol) ([live site](https://satbuhan.github.io/pte-thrombolysis-protocol/))
- [LMWH selection & renal dosing in NSTE-ACS](https://github.com/satbuhan/lmwh-nste-acs-protocol) ([live site](https://satbuhan.github.io/lmwh-nste-acs-protocol/))
- [Ketamine in head injury — safety & complication management](https://github.com/satbuhan/ketamine-head-injury-protocol) ([live site](https://satbuhan.github.io/ketamine-head-injury-protocol/))
- [Midazolam versus clonazepam — seizures, acute agitation & anxiety](https://github.com/satbuhan/midazolam-clonazepam-protocol) ([live site](https://satbuhan.github.io/midazolam-clonazepam-protocol/))
- [Vasopressor (aminergic) agent selection in shock states](https://github.com/satbuhan/vasopressor-shock-protocol) ([live site](https://satbuhan.github.io/vasopressor-shock-protocol/))
- [Epinephrine/Adrenaline revisited — contemporary decision-making algorithm](https://github.com/satbuhan/epinephrine-revisited-protocol) ([live site](https://satbuhan.github.io/epinephrine-revisited-protocol/))
- [Ketamine in emergency and critical care — indication-based decision algorithm](https://github.com/satbuhan/ketamine-indications-protocol) ([live site](https://satbuhan.github.io/ketamine-indications-protocol/))
- [Tenecteplase versus alteplase — fibrinolysis in STEMI](https://github.com/satbuhan/tenecteplase-alteplase-stemi-protocol) ([live site](https://satbuhan.github.io/tenecteplase-alteplase-stemi-protocol/))
- [Blood gas-guided assessment of the chemical warfare agent casualty](https://github.com/satbuhan/cwa-blood-gas-protocol) ([live site](https://satbuhan.github.io/cwa-blood-gas-protocol/))
- [Calcium channel blocker toxicity — phenotype-guided management](https://github.com/satbuhan/ccb-toxicity-protocol) ([live site](https://satbuhan.github.io/ccb-toxicity-protocol/))
- [Choosing an adjunct to haloperidol in hyperactive delirium with severe agitation](https://github.com/satbuhan/haloperidol-adjunct-protocol) ([live site](https://satbuhan.github.io/haloperidol-adjunct-protocol/))
- [Selection of a neuromuscular blocking agent for rapid sequence induction and intubation](https://github.com/satbuhan/succinylcholine-rocuronium-protocol) ([live site](https://satbuhan.github.io/succinylcholine-rocuronium-protocol/))
- [Pharmacological pain management in elderly patients](https://github.com/satbuhan/geriatric-pain-protocol) ([live site](https://satbuhan.github.io/geriatric-pain-protocol/))
- [Metoclopramide versus Ondansetron — Antiemetic Selection by Clinical Setting](https://github.com/satbuhan/metoclopramide-ondansetron-protocol) ([live site](https://satbuhan.github.io/metoclopramide-ondansetron-protocol/))
- [Needle Aspiration versus Tube Thoracostomy — Symptom-Led Management of Spontaneous Pneumothorax](https://github.com/satbuhan/spontaneous-pneumothorax-protocol) ([live site](https://satbuhan.github.io/spontaneous-pneumothorax-protocol/))
- [Suspected or Witnessed Button Battery Exposure in a Child](https://github.com/satbuhan/button-battery-protocol) ([live site](https://satbuhan.github.io/button-battery-protocol/))
- [Beta-Lactam Infusion Strategy in Sepsis and Septic Shock](https://github.com/satbuhan/beta-lactam-infusion-protocol) ([live site](https://satbuhan.github.io/beta-lactam-infusion-protocol/))

## Why this exists

A flowchart alone tells a reader *what* to do at each step but not *why*,
and a reader outside the authors' own team cannot easily check the evidence
behind a specific gate (why these four shock-environment conditions
together, why lactate and base excess alongside SBP, when WBCT should be
deferred rather than attempted). This page keeps the original algorithm
exactly as authored, and attaches the clinical reasoning and literature to
each box without cluttering the diagram itself.

The algorithm this page presents is Figure 1 of the authors' own
decision-making algorithm on whole-body CT in traumatic circulatory shock
(80 references); the supplementary content on this page draws on that
reference list, independently re-verified rather than accepted on trust —
see "Status" below, which is unusually long for this tool because that
verification turned up more problems than usual.

## Status

This is a working version, built to be tested on both desktop and mobile.
The reference list for this particular manuscript needed far more scrutiny
than any prior tool in this atlas, so this section is deliberately candid
and detailed rather than a quick summary.

- **The external verification pass (a separately-budgeted LLM reviewer,
  the same approach used for every tool in this atlas) was unusually
  unreliable for this manuscript, in both directions.** Independently
  re-checking its 80 verdicts against primary sources found:
  - **4 papers it called "fabricated" are real.** References 72, 73, 75
    and 76 are genuine, independently confirmed papers — in three of the
    four cases matching the manuscript's *original* DOI exactly, directly
    contradicting the external pass's own claim that the DOI "did not
    exist" or "resolved to an unrelated article." These are cited here
    with their correct, independently verified details.
  - **2 papers it called "verified" could not be independently
    located anywhere.** References 24 and 27 have the same "real
    journal, zero trace of this specific article" signature as the
    confirmed fabrications below, after exhaustive searching by title,
    author, DOI and PMID. This is absence of evidence rather than a
    contradicting-DOI smoking gun (unlike 72/73/75/76 above), so they are
    flagged as *likely* rather than confirmed fabricated. Neither is used
    on any flowchart node.
  - **1 of its own "corrections" was itself wrong.** For reference 28,
    the external pass claimed the manuscript's original DOI resolved to
    an unrelated COVID-19 surgery paper and substituted a different,
    older paper. Independent re-checking found the manuscript's original
    DOI was correct all along — it resolves to the real Treskes et al.
    (2021) REACT-2 cost-effectiveness paper, which is what is cited here.
    The external pass's substitute should not be used.
  - **2 fabrications it flagged are confirmed fabricated.** References 47
    and 71 really do not exist anywhere — no paper with the cited title,
    authors, or DOI could be found under any search strategy. Neither is
    used on any flowchart node; both are flagged in their own `kind`
    field with `url: null` and should be raised with the manuscript
    authors.
  - **Several references were corrected** for a wrong DOI, a wrong PMID,
    or missing volume/issue/page numbers the manuscript omitted — the
    real, correct bibliographic details are used throughout.
- **Roughly 25 of the 80 references could not be re-confirmed from a live
  primary source before this build was finished**, because independent
  verification of this bibliography ran into a session-wide web-search
  budget limit before every entry could be checked. For these, the DOI,
  PMID, journal, volume, issue and page numbers are corroborated against
  the external reviewer's own evidence (not invented), but the exact title
  wording was not re-fetched and quoted from a live source this session.
  Each one says so plainly in its own `kind` field — look for "not
  independently confirmed/re-verified this pass" — rather than being
  presented as fully checked. None of this group is known to be wrong;
  they simply were not re-verified to the same standard as the rest.
  Finishing this check is the single most useful thing a follow-up pass
  on this tool could do.
- **Every other reference has been independently verified** against a
  primary source (a live DOI/PMID lookup or publisher record, not
  accepted on trust from the manuscript's own list or from the external
  reviewer's verdict alone).

Given how much this particular manuscript's external verification pass
needed correcting, treat every citation in this tool as independently
checked here, not as inherited from that pass — and treat the four flagged
likely/confirmed fabrications (24, 27, 47, 71) as items for the authors to
resolve against their own source material, not as something this build
could resolve on its own.

## Disclaimer

This is an academic / educational reference tool, not a substitute for
institutional protocol or bedside clinical judgement. Verify any threshold
or timing against current local protocol before clinical use.

## How it's built

Plain HTML/CSS/JS, no build step and no framework — a single static site
that GitHub Pages can serve directly.

```
index.html          page structure
assets/style.css     design (the "paper" masthead/references,
                      the diagram scope + readout panel)
assets/content.js     ← single source of truth for every node's text,
                      and reference list. Edit this file to change
                      what the page says.
assets/app.js         rendering + interaction (builds the diagram and the
                      connector lines from content.js, handles the
                      click-to-expand panel on desktop and the bottom
                      sheet on mobile)
```

### Running it locally

No install needed:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

### Editing content

Open `assets/content.js`. Each entry in `NODES` is one box or decision
hexagon from the algorithm (`meaning`, `rationale`, and `refs` pointing at
numbered entries in `REFERENCES`). Add or edit a reference in `REFERENCES`
and point to it by `id` from any node. Never change a node's `label` or
`sub` text without the author team's sign-off — those fields are the
algorithm itself, transcribed verbatim from Figure 1. Steps 1 and 3 carry
their multi-line bulleted criteria lists as literal `\n`-separated bullets
in `sub` — preserve those exactly; they render as separate lines inside the
decision hexagon, because that is how the original boxes are drawn.

### Building the next tool in this atlas

See [`METHODOLOGY.md`](METHODOLOGY.md) — the full build/verification
process (fidelity rule, content schema, citation verification, QA steps),
written so that any collaborator or AI assistant can pick up this project
in a fresh session and build the next tool the same way.

## License

Content and code are released under
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) —
share and adapt with attribution, non-commercially, under the same license.
