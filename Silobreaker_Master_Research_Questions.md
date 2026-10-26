# Silobreaker — Master Sectorial Cyber Resilience & Credit Intelligence Research Questions

**Version:** 3.1  
**Scope:** Reusable research library for 24 sectors  
**Primary audience:** Cyber Risk Intelligence analysts and Senior Credit Officers  
**Sector variable:** `{SECTOR}` (e.g., `manufacturing`)  
**Purpose:** Produce evidence-based sector intelligence, support four-dimension sector exposure classification, and connect cyber-related weaknesses to operational resilience and credit-relevant consequences.

> **Important:** These are research prompts, not pre-validated conclusions. Their output must undergo source verification and analytical review. The sector report does not constitute a cybersecurity audit, a determination of borrower-specific creditworthiness, or a regulatory compliance certification.

## How to run the questions

1. Replace `{SECTOR}` consistently with the selected sector. Use the same sector definition and subsector boundaries throughout the exercise.
2. Apply the **common research instructions** below to each research query or configure them as a standing instruction.
3. Execute **Q01–Q07** for core sector research; **Q10–Q14** for additional evidence supporting comparative classification.
4. Run **Q15** after those evidence-gathering stages, using a separately approved sector-rating methodology.
5. Run **Q08** with the actual credit questionnaire and its question identifiers available.
6. Run **Q09 last**, after Q08 and Q15, to assemble the slide-oriented executive report and evidence annex.
7. Preserve source links, dates, evidence confidence, limitations and references between questions. Reuse validated data rather than regenerating facts.

**Recommended execution order:** Q01 → Q02 → Q03 → Q04 → Q05 → Q06 → Q07 → Q10 → Q11 → Q12 → Q13 → Q14 → Q15 → Q08 → Q09.

## Common research instruction (apply to every question)

```text
Research sector: {SECTOR}.
Geographic scope: worldwide, with EU, UK and US analysis where applicable.
Use the most recent available evidence as of the research date and state the evidence cutoff.
Prioritise primary sources, official incident disclosures, regulatory publications, reputable threat intelligence, financial filings and documented sector studies.
For every material claim, provide source, publication date, event date where different, geography and confidence. Distinguish confirmed facts, reasonable analytical assessments and unverified allegations. Do not invent statistics, attack attribution, control failures or financial losses. Where evidence is unavailable, state the gap explicitly.
Analyse relevant subsectors and business models rather than treating the sector as homogeneous. Present reusable structured findings, supported by source references, suitable for a sectorial cyber resilience and corporate credit intelligence report.
Distinguish inherent sector exposure, observed sector preparedness, and borrower-specific materiality. Avoid interpreting sector incident counts as borrower probabilities without a defensible denominator and methodology.
```

---

# Part A — Core sector intelligence

## Q01 — Sector operating model and critical dependencies

**Objective:** Identify what keeps the sector operating, what can stop it, and where interdependencies concentrate disruption exposure.

```text
Analyse the {SECTOR} sector's critical operational processes and dependencies, distinguishing its major subsectors and business models. Identify critical IT and operational technology systems where applicable, production or service-delivery bottlenecks, single points of failure, essential suppliers, external service providers, and dependencies whose disruption could materially interrupt operations.

Assess reliance on energy, telecommunications, cloud, managed service providers, enterprise software, logistics, industrial infrastructure and other shared critical services, where relevant. Identify common dependencies capable of transmitting a single cyber incident across multiple businesses or sectors.

For each critical dependency, explain its business function, plausible cyber disruption mechanisms, potential operational consequences, availability of alternatives and importance to business continuity. Distinguish documented dependencies from general sector assumptions and provide supporting sources.

Also identify typical organisational and operating-model features—such as centralised versus decentralised operations, franchises, subsidiaries, joint ventures, multi-site activities and outsourced responsibilities—only where they affect visibility, accountability or disruption exposure. Do not infer poor governance merely from complexity.

Output: a subsector dependency map, critical systems and functions, major single points of failure, cross-sector concentration exposures, and material operating-model characteristics.
```

## Q02 — Historical and recent cyber incidents, including case studies

**Objective:** Build a deduplicated incident evidence base across landmark, 12-month and 30-day horizons.

```text
Conduct a comprehensive investigation of significant cyber incidents affecting the {SECTOR} sector worldwide, covering three time horizons:

1. Historical landmark incidents: identify the five most consequential documented cyberattacks, selected for business interruption, scale, financial consequences, supply-chain disruption or demonstrated security failures.
2. Last 12 months: identify major incidents, recurring attack patterns, emerging methods, affected subsectors and observable changes in attack activity.
3. Last 30 days: identify significant new incidents, campaigns and developments, stating whether each represents a new event or an update to an earlier incident.

Create a deduplicated incident register recording affected organisation, subsector, country, incident and disclosure dates, attack type, known initial access, exploited weaknesses, attacker attribution and confidence, affected systems, operational disruption, recovery duration, financial loss and regulatory consequences, where documented.

Include cyber-enabled fraud incidents where relevant and clearly distinguish them from malicious intrusions, internal fraud and purely operational outages.

Select three particularly instructive incidents for detailed case studies covering the attack sequence, confirmed or suspected actors, exploited weaknesses, operational and financial effects, recovery, regulatory consequences and lessons for resilience.

Clearly distinguish unknown facts from confirmed findings. Avoid presenting the most publicised incidents as statistically representative. Supply primary references wherever possible.

Output: historical top-five comparison, 12-month trend analysis, 30-day developments, structured incident register and three detailed case studies.
```

## Q03 — Threat assessment, attack pathways and exploited weaknesses

**Objective:** Convert incident evidence into defensible threat scenarios linked to specific weaknesses.

```text
Perform an in-depth cyber threat assessment of the {SECTOR} sector, using the incident research and the latest credible intelligence.

Identify the five most material cyber threat scenarios affecting the sector and its subsectors. Analyse relevant threat actors and their motivations, attack frequency indicators, exploitation trends, commonly targeted systems, initial access methods, attack paths, vulnerabilities and observed tactics, techniques and procedures.

Examine documented weaknesses including identity and access management, absent or ineffective MFA, privileged access, exposed remote services, unpatched vulnerabilities, IT/OT segmentation where applicable, third-party access, detection capabilities, backup and recovery, and other sector-specific controls. Consider cyber-enabled fraud scenarios where material, distinguishing them from fraud types that do not require cyber compromise.

For each scenario, explain which weaknesses could enable or amplify the attack, cite documented incidents demonstrating the relationship, distinguish confirmed exploitation from hypothetical vulnerability, and describe plausible operational consequences.

Assess the direction of the threat, severity of the operational scenario, strength of the evidence and confidence in the assessment. Do not convert incident counts into probabilities without a defensible methodology.

Output: five prioritised threat scenarios, attack-pathway analysis, evidence-supported control weakness matrix, key threat metrics, trend direction and intelligence confidence.
```

## Q04 — Cyber resilience capabilities and sector control benchmarks

**Objective:** Identify the capabilities most important for preventing, containing and recovering from the sector's credible disruption scenarios.

```text
Identify the cybersecurity and operational resilience capabilities most critical to organisations in the {SECTOR} sector.

Use authoritative cybersecurity standards, relevant sector guidance, empirical incident investigations, industry research and credible cybersecurity maturity studies.

Assess identity and access protection, MFA, vulnerability management, asset visibility, IT/OT security where relevant, network segmentation, security monitoring, incident response, third-party resilience, business continuity, disaster recovery, backup integrity, recovery testing and sector-specific safeguards.

For each capability, determine what critical operational process it protects, which observed attack pathways it mitigates, whether its absence or weakness has contributed to documented incidents, and what could happen if it fails.

Identify available sector benchmarks and recurring preparedness weaknesses. Distinguish mandatory requirements, recommended good practice and context-dependent capabilities. Avoid implying that all organisations need identical controls or that the absence of a particular technology necessarily indicates inadequate resilience.

Output: prioritised sector resilience capabilities, applicable benchmarks, documented control gaps, criticality rationale and recommended areas for improvement.
```

## Q05 — Financial impact, disruption trends and credit transmission

**Objective:** Translate credible incidents and disruption scenarios into potential financial and credit consequences.

```text
Perform an in-depth financial and operational impact assessment of cyber incidents affecting the {SECTOR} sector worldwide.

Research the following sector-specific metrics where reliable evidence exists: average and median data breach cost; ransomware demand and actual payment; business disruption frequency and duration; average and median incident recovery time; breach identification and containment lifecycle; recovery and remediation expenditure; revenue and profit impacts; and incident cost trends over the past five years.

For every metric, state the currency, year, population, sample size where available, geographic coverage, statistical method, source and limitations. Explain when no defensible sector-specific average exists. Distinguish breach lifecycle from business interruption and operational recovery periods. Avoid treating ransom payments as total incident costs.

Analyse documented cases showing effects on production or service delivery, lost sales, EBITDA, margins, working capital, cash conversion, liquidity, capital expenditure, borrowing requirements, credit ratings, covenant headroom and debt-servicing capacity. Include material fraud and critical-supplier losses where supported, while avoiding double counting. Separate disclosed financial consequences from external estimates.

Develop illustrative one-week, four-week and eight-week disruption scenarios, adapting the scenarios to the sector's critical business processes. Explain potential financial transmission pathways, important assumptions, possible offsets such as alternative operations or insurance, and the borrower-specific data needed to assess materiality. Do not represent illustrative scenarios as historical averages or probability forecasts.

Output: financial metrics with methodological caveats, five-year trends where supportable, documented impact case studies, credit transmission analysis and illustrative disruption scenarios.
```

## Q06 — Regulatory authorities and cyber resilience expectations

**Objective:** Identify what relevant authorities require or expect and where non-compliance could have operational or financial consequences.

```text
Identify the principal regulators, legislative frameworks, supervisory authorities, industry-specific requirements and cybersecurity or operational resilience expectations relevant to the {SECTOR} sector.

Provide a jurisdiction-by-jurisdiction analysis covering the European Union, United Kingdom and United States, including important subsector distinctions and national or state-level variations where material.

For each applicable framework, explain the regulator or competent authority, entities and activities in scope, mandatory cyber risk management and resilience obligations, incident reporting requirements, continuity and recovery expectations, third-party and supply-chain security expectations, applicable deadlines, and enforcement or supervisory consequences.

Identify recent regulatory developments, material enforcement examples, published supervisory concerns and expected changes. Include sector-specific fraud prevention, outsourcing and governance requirements where applicable. Distinguish legislation, binding regulatory requirements, supervisory guidance, industry standards and voluntary good practice.

Evaluate which requirements have the greatest implications for operational resilience, potential financial liabilities, business continuity and borrower credit risk.

Output: EU, UK and US jurisdictional comparison; applicability-based checklist; key resilience obligations; supervisory priorities; regulatory developments and credit-relevant consequences.
```

## Q07 — Geopolitical cyber threats and systemic exposure

**Objective:** Explain which geopolitical developments measurably alter sector attack exposure and correlated disruption risk.

```text
Assess how the current geopolitical environment is influencing cyber threats, attacker motivations, targeting patterns and resilience risks affecting the {SECTOR} sector worldwide.

Analyse relevant state-sponsored and state-aligned operations, cyberespionage, disruptive or destructive activity, geopolitically motivated hacktivism, sanctions-related targeting, regional conflicts, strategic technology competition and cyber-enabled supply-chain disruption.

Identify which subsectors, countries, critical technologies, infrastructure services and business dependencies may be disproportionately exposed. Explain the mechanism connecting geopolitical developments to credible cyber threats, rather than providing generic political commentary.

Assess the potential for cyber incidents to propagate across organisations through shared technology providers, energy systems, telecommunications, logistics, software supply chains, outsourced service providers or other sector-specific critical dependencies. Identify documented examples of correlated disruption when available.

Distinguish observed state-linked campaigns from speculative scenarios and explain attribution confidence. Identify early warning indicators and developments that could materially alter the sector threat assessment.

Output: geopolitical threat drivers, relevant observed campaigns, vulnerable subsectors and regions, systemic exposure scenarios, credit-relevant implications and early warning indicators.
```

---

# Part B — Classification evidence extension

> These five data-gathering prompts address the four exposure dimensions in the sector-rating matrix. They do not replace the core research. Cross-sector benchmarking is especially important: incident volume alone must not determine ratings.

## Q10 — Sector fraud exposure and financial consequences

**Objective:** Cover fraud independently of cyber intrusions, including inherent exposure and documented losses.

```text
Perform a comprehensive fraud risk exposure assessment of the {SECTOR} sector worldwide, with particular attention to the EU, UK and US.

Identify the principal fraud typologies affecting the sector, including payment diversion, business email compromise, invoice and procurement fraud, supplier impersonation, insider fraud, asset misappropriation, financial statement manipulation, identity fraud and other sector-specific schemes.

Analyse:
1. Five significant documented fraud cases and their causes.
2. Available sector-specific fraud frequency, median and average losses, with five-year trends where reliable.
3. Fraud exposure arising from payment flows, transaction structures, supply chains, intermediaries and operating models.
4. Documented internal control weaknesses, detection failures and governance factors.
5. Business and financial consequences, including direct loss, recovery costs, liquidity effects and reputational damage.
6. Applicable fraud prevention and regulatory expectations.

Distinguish cyber-enabled fraud from internal or non-cyber fraud, and distinguish actual sector exposure from controls' observed effectiveness.

Output: five principal fraud scenarios, quantitative evidence where available, structural exposure drivers, documented cases, relevant control weaknesses and a preliminary inherent sector exposure assessment. Provide source references, methodology and evidence confidence.
```

## Q11 — Sector ICT exposure and cybersecurity maturity

**Objective:** Separate structural technology exposure from observable preparedness and resilience maturity.

```text
Assess the inherent Cyber / ICT exposure and available cybersecurity maturity evidence for the {SECTOR} sector.

Analyse:
1. Digital dependency and technology intensity across major subsectors.
2. IT/OT convergence, remote connectivity, cloud reliance, legacy systems and technology concentration where applicable.
3. Critical attack surface characteristics and common vulnerability exposure.
4. Comparative sector cyber incident and ransomware trends, adjusted for data availability and reporting bias.
5. Sector cybersecurity maturity studies, supervisory findings, audit research and documented recurring control weaknesses.
6. Evidence of preparedness for incident detection, containment, recovery and continuity.
7. Comparison with other sectors using reliable common datasets.

Separate inherent technological exposure from observed cybersecurity maturity. Identify where findings apply only to individual organisations rather than the sector as a whole.

Output: structural exposure indicators, sector maturity evidence, comparative benchmarks, significant gaps, supporting sources and confidence levels.
```

## Q12 — Operational resilience and third-party concentration

**Objective:** Determine structural interruption sensitivity and reliance on critical suppliers or infrastructure.

```text
Conduct a sector-level Operational Resilience and Third-Party Risk Management exposure assessment for the {SECTOR} sector.

Analyse:
1. Five significant documented operational disruptions involving cyberattacks, ICT failures or critical third parties.
2. Critical processes and their dependence on uninterrupted technology, suppliers, infrastructure and outsourced operations.
3. Concentration among cloud providers, managed service providers, software vendors, essential suppliers and infrastructure operators.
4. Single points of failure, substitutability, switching complexity and operational interdependencies.
5. Observed service disruption durations, recovery challenges, supply-chain effects and financial losses.
6. Available evidence on business continuity, disaster recovery and third-party resilience maturity.
7. Potential propagation of a single incident across multiple organisations and related sectors.

Distinguish structural disruption sensitivity from observed preparedness. Do not infer that all businesses have the same dependency arrangements.

Output: critical dependency matrix, disruption case studies, third-party concentration indicators, systemic exposure pathways, financial consequences and a preliminary sector exposure assessment with evidence confidence.
```

## Q13 — Governance structure and operating-model complexity

**Objective:** Assess sector-level structural governance complexity without claiming that complexity itself proves weak governance.

```text
Assess the inherent Governance Structure and Operating Model exposure of the {SECTOR} sector, focusing on the organisational characteristics that can complicate risk ownership, accountability and operational oversight.

Analyse:
1. Typical corporate structures, subsidiaries, joint ventures, franchises, decentralised operations and multi-jurisdictional activities.
2. Outsourcing, intermediaries, subcontracting and the distribution of operational responsibilities.
3. Organisational complexity created by mergers, acquisitions, legacy environments and fragmented technology ownership.
4. Evidence of governance failures associated with significant cyber, operational resilience or fraud incidents.
5. Relevant supervisory findings concerning governance, accountability, internal controls, risk management and third-party oversight.
6. Sector-specific challenges in assigning responsibility for shared technology, critical processes and external suppliers.
7. Comparable governance and operating-model complexity indicators across sectors.

Distinguish structural governance complexity from demonstrated governance failures. Do not conclude that a sector has ineffective governance solely because its organisations are large, complex or internationally distributed.

Output: principal governance complexity drivers, documented oversight failures, relevant benchmarks, implications for operational risk and a preliminary inherent sector exposure assessment with supporting evidence and confidence.
```

## Q14 — Cross-sector comparative analysis

**Objective:** Establish defensible comparisons and avoid grading almost every sector High or Very High.

```text
Perform a comparative inherent non-financial risk exposure analysis of the {SECTOR} sector against other relevant economic sectors.

Compare four dimensions: Fraud, Cyber / ICT, Operational Resilience / TPRM, and Governance Structure / Operating Model.

For each dimension:
1. Identify objective structural exposure indicators.
2. Retrieve reliable comparable sector-level incident, loss, concentration and disruption evidence where available.
3. Normalise comparisons where possible for organisation size, sector population, geography, reporting period and data coverage.
4. Identify whether the sector is relatively more or less exposed than relevant peer sectors, and explain why.
5. Identify significant subsector differences and limitations of broad industry classifications.
6. Distinguish inherent exposure from control effectiveness, observed incident frequency and reporting bias.

Do not create artificial cross-sector rankings from incomparable datasets. Explicitly flag missing indicators and evidence limitations. Where available, use the agreed list of 24 sectors as the comparison universe.

Output: comparative sector exposure matrix, benchmark metrics, methodological limitations, peer-sector comparisons and confidence assessment.
```

## Q15 — Four-dimension sector exposure classification

**Objective:** Synthesise existing evidence into transparent proposed inherent sector ratings.

**Prerequisite:** A common, approved rating rubric defining Medium, High and Very High must be supplied. If none exists, results must be marked provisional rather than presented as formal classifications.

```text
Using all validated sector intelligence findings for {SECTOR}, prepare a defensible inherent exposure classification across four dimensions:

1. Fraud
2. Cyber / ICT
3. Operational Resilience / TPRM
4. Governance Structure / Operating Model

For each dimension:
- Identify three to five principal structural exposure drivers.
- Provide the strongest supporting empirical evidence and documented incidents.
- Explain the potential financial and operational consequences.
- Compare the sector with available cross-sector benchmarks.
- Apply the agreed corporate sector rating methodology to propose Medium, High or Very High.
- Explain the justification and limitations of the proposed rating.
- Assign a separate evidence confidence level: High, Medium or Low.
- Identify material subsector variations and missing information.

Do not invent numerical scores, sector averages, regulatory failures or unsupported conclusions. If the agreed rating criteria or adequate evidence are unavailable, mark the proposed rating as provisional or not assessable.

Output a four-dimension rating matrix with concise evidence-backed justifications suitable for Senior Credit Officers, followed by an analytical evidence annex for second-line review.
```

---

# Part C — Credit integration and final reporting

## Q08 — Questionnaire interoperability and Credit Officer engagement

**Objective:** Connect reported borrower control gaps to sector evidence, possible financial materiality and constructive discussion prompts.

**Prerequisite:** Supply the actual questionnaire including stable question IDs. Q08 is performed after the core evidence is available, and can incorporate proposed Q15 sector ratings when useful.

```text
Using the validated research findings for the {SECTOR} sector and the supplied corporate cyber resilience questionnaire, develop a sector-specific intelligence mapping and client discussion guide for Senior Credit Officers.

For each material questionnaire item, identify: the potential weakness indicated by an adverse response; the sector-specific threat scenarios and attack pathways it relates to; documented incidents demonstrating the relevance of the weakness; important operational dependencies; applicable regulatory resilience expectations where relevant; and plausible financial or credit consequences.

Explain the conditions that could make the weakness more or less material to a particular borrower, including business model, geography, compensating controls, operational concentration and financial resilience.

Provide two or three non-technical follow-up questions, practical resilience improvements and indicators that may warrant specialist review or closer monitoring. Prioritise the findings most likely to affect critical operations and financial resilience.

Use the actual questionnaire IDs supplied. If no questionnaire is available, produce a clearly labelled provisional mapping and do not fabricate question identifiers.

The guide must support constructive client discussions, not a cybersecurity audit. Do not treat self-reported answers as verified evidence, assume regulatory non-compliance or make automatic adverse credit judgements.

Output: questionnaire-to-threat-to-incident-to-credit mapping matrix, prioritised discussion prompts, suggested resilience improvements and escalation indicators.
```

## Q09 — Final Sector Cyber Resilience & Credit Intelligence Report

**Objective:** Create the reusable executive briefing and traceable analyst annex after Q08 and Q15 are complete.

```text
Using the validated outputs of research questions Q01–Q08 and Q10–Q15, prepare a professional Sector Cyber Resilience & Credit Intelligence Report for the {SECTOR} sector, designed for Senior Credit Officers assessing corporate borrowers.

The report must contain:
1. Executive sector assessment: four proposed exposure classifications (Fraud, Cyber / ICT, Operational Resilience / TPRM, Governance Structure / Operating Model), principal findings, top risks, trend direction and credit discussion implications.
2. Sector operating model: critical processes, digital dependencies, concentration risks and structural governance considerations.
3. Cyber threat landscape: three to five prioritised scenarios with documented incident evidence and relevant exploited weaknesses.
4. Geopolitical cyber exposure: material geopolitical drivers, targeting patterns and systemic dependencies.
5. Regulatory resilience expectations: relevant EU, UK and US obligations, applicability qualifications and supervisory priorities.
6. Control weakness intelligence: key security and resilience gaps, connected to observed attacks and the supplied questionnaire.
7. Operational and financial consequences: documented costs, business interruption pathways, financial sensitivity and credit transmission mechanisms.
8. Credit Officer engagement: concise targeted client discussion prompts, practical improvement opportunities and indicators requiring follow-up.

Produce a concise, executive-grade 16:9 slide briefing following the agreed 12-slide structure:
01 Sector intelligence cover
02 Executive sector risk snapshot / four-dimension classification
03 Sector anatomy and critical operating dependencies
04 Cyber threat landscape and scenarios
05 Geopolitical cyber threat outlook
06 Major cyber incidents and lessons learned
07 Critical control weaknesses and resilience priorities
08 Regulatory and supervisory resilience expectations
09 Financial impact of cyber incidents
10 Cyber-to-credit transmission and illustrative disruption scenarios
11 Questionnaire-to-sector intelligence mapping
12 Credit Officer engagement, questions and actions

Support this with a separate traceable evidence annex covering incident registers, three detailed cases, methodology, metrics, regulatory scope, rating rationales, question-to-scenario links and evidence confidence.

Use concise explanations accessible to non-specialist credit audiences. Make sector-specific judgements rather than generic cybersecurity statements. Distinguish inherent sector risk from individual borrower preparedness and borrower credit materiality.

For each major slide claim, cite sources and reference dates. Include evidence cutoff, publication version, source quality, limitations and unresolved research gaps. Do not invent missing evidence or present this work as a control audit, regulatory compliance assessment or borrower credit rating.

Output: slide-by-slide narrative and visual recommendations for the 12-slide executive deck, evidence annex, and short list of issues requiring analyst validation.
```

---

# Standard evidence and quality controls

## Required evidence fields

| Field | Guidance |
|---|---|
| Unique ID | e.g., `INC`, `THR`, `CTL`, `FIN`, `REG`, `GEO`, `DEP` |
| Sector and subsector | Define boundaries and applicability |
| Geographic scope | Country/region and cross-border relevance |
| Dates | Incident date, disclosure date, publication date, evidence cutoff |
| Claim or finding | Separate observed fact, analysis and hypothetical scenario |
| Supporting source | URL/reference and publisher; prioritise primary sources |
| Confidence | High / Medium / Low, with explanation |
| Operational impact | Business functions, duration and dependencies |
| Financial or credit relevance | Documented losses or credible transmission mechanism |
| Control/question mapping | Verified control-to-incident link and actual questionnaire IDs |
| Limitations | Missing data, sample bias, disputed findings, non-comparability |

## Four-dimensional classification rules

- Rate **inherent sector exposure**, not an individual organisation's control effectiveness or creditworthiness.
- Treat **fraud**, **cyber/ICT**, **operational resilience/TPRM**, and **governance/operating model** as distinct dimensions; explain overlaps rather than double-counting evidence.
- Never infer weak governance just from organisational complexity.
- Avoid deriving attack probabilities from media-reported incident counts.
- Separate **risk rating** from **evidence confidence**.
- Calibrate ratings against the common 24-sector universe under an agreed rubric.
- Flag **not assessable** or **provisional** when evidence or methodology is inadequate.

## Desired final analytical flow

**Sector exposure → threat and incident evidence → control and resilience significance → operational and financial consequences → credit officer discussion and proportionate follow-up.**

The shared research library should be managed once and reused across all 24 sectors, with sector-specific judgements, source validation, version control and periodic refreshes.
