# Sectorial Cyber Resilience & Credit Intelligence

Master Research Framework — Version 3.0 | 24 sectors

I agree. Rather than retaining your original ten questions and adding six more, we should consolidate overlapping research into a smaller number of comprehensive, reusable Silobreaker prompts.

The objective is to establish one standard research methodology that can be applied to all 24 sectors by changing only the sector name.

I would also preserve your original research intentions: major historical attacks, recent incidents, financial costs, threat assessments, successful attack case studies, regulatory expectations, geopolitics and the final executive briefing.

## 1. Proposed consolidated research framework

I recommend nine master questions, sequenced so that each builds on the previous research.

| New ID | Master research question                                                       | Origin                                            |
| ------ | ------------------------------------------------------------------------------ | ------------------------------------------------- |
| Q01    | Sector operating model and critical dependencies                               | Previous Q11, incorporating systemic dependencies |
| Q02    | Historical and recent cyber incidents, including case studies                  | Original Q1, Q2, Q3, Q8                           |
| Q03    | Sector threat assessment, attack pathways and exploited weaknesses             | Original Q5 + previous Q12                        |
| Q04    | Cyber resilience capabilities and sector control benchmarks                    | Previous Q13                                      |
| Q05    | Financial impact, disruption trends and cyber-to-credit transmission           | Original Q4 + previous Q14                        |
| Q06    | Regulatory authorities, resilience expectations and jurisdictional obligations | Original Q6, Q7                                   |
| Q07    | Geopolitical cyber threats and systemic exposure                               | Original Q9 + previous Q15                        |
| Q08    | Questionnaire interoperability and Credit Officer engagement                   | Previous Q16                                      |
| Q09    | Final Sector Cyber Resilience & Credit Intelligence Report                     | Original Q10, redesigned                          |

This removes repetition without losing your research scope.

One sequencing decision is deliberate: incident evidence comes before the threat assessment. We first establish what happened, then interpret the attack patterns and exposed controls.

The final two questions are synthesis stages, not independent research exercises.

## 2. The nine master Silobreaker prompts

All prompts use the variable `{SECTOR}`. For the pilot, substitute `manufacturing`; thereafter, change only this variable.

I recommend the following common instruction at the start of each research session:

Common research instruction

&#x20;Copy

```Research sector: `{SECTOR}`. Geographic scope: worldwide, with EU, UK and US analysis where applicable. Use the most recent available evidence as of the research date.

Prioritise primary sources, official incident disclosures, regulators, credible threat intelligence and financial filings. Document sources, dates, geography and confidence. Distinguish verified facts from analytical assessments or unverified allegations. Never invent financial losses, exploited weaknesses or attack attribution.

Analyse relevant subsectors and business models. Explicitly identify evidence gaps and produce structured findings suitable for reuse in the credit intelligence report.```

### Q01 — Sector operating model and critical dependencies

Retained from previous Q11

This is the question you explicitly wanted to keep. I have retained its core wording and incorporated cross-sector concentration and systemic dependencies to avoid a separate, overlapping question.

Silobreaker prompt

&#x20;Copy

Analyse the {SECTOR} sector's critical operational processes and dependencies, distinguishing its major subsectors and business models. Identify critical IT and operational technology systems where applicable, production or service-delivery bottlenecks, single points of failure, essential suppliers, external service providers, and dependencies whose disruption could materially interrupt operations.  Assess reliance on energy, telecommunications, cloud, managed service providers, enterprise software, logistics, industrial infrastructure and other shared critical services, where relevant. Identify common dependencies capable of transmitting a single cyber incident across multiple businesses or sectors.  For each critical dependency, explain its business function, plausible cyber disruption mechanisms, potential operational consequences, availability of alternatives and importance to business continuity. Distinguish documented dependencies from general sector assumptions and provide supporting sources.  Output: a subsector dependency map, critical systems and functions, major single points of failure, and cross-sector concentration exposures.

### Q02 — Historical and recent cyber incidents, including case studies

This combines your original first three questions and the request for three successful attack case studies.

It deliberately separates three time horizons: historical landmark cases, a 12-month baseline and a 30-day monitoring window.

Silobreaker prompt

&#x20;Copy

Conduct a comprehensive investigation of significant cyber incidents affecting the {SECTOR} sector worldwide, covering three time horizons:  1. Historical landmark incidents: identify the five most consequential documented cyberattacks, selected for business interruption, scale, financial consequences, supply-chain disruption or demonstrated security failures. 2. Last 12 months: identify major incidents, recurring attack patterns, emerging methods, affected subsectors and observable changes in attack activity. 3. Last 30 days: identify significant new incidents, campaigns and developments, stating whether each represents a new event or an update to an earlier incident.  Create a deduplicated incident register recording affected organisation, subsector, country, incident and disclosure dates, attack type, known initial access, exploited weaknesses, attacker attribution and confidence, affected systems, operational disruption, recovery duration, financial loss and regulatory consequences, where documented.  Select three particularly instructive incidents for detailed case studies covering the attack sequence, confirmed or suspected actors, exploited weaknesses, operational and financial effects, recovery, regulatory consequences and lessons for resilience.  Clearly distinguish unknown facts from confirmed findings. Avoid presenting the most publicised incidents as statistically representative. Supply primary references wherever possible.  Output: historical top-five comparison, 12-month trend analysis, 30-day developments, structured incident register and three detailed case studies.

### Q03 — Threat assessment, attack pathways and exploited weaknesses

This is where incident research is transformed into actionable sector threat intelligence.

It also establishes the evidence needed to connect your questionnaire to real-world attacks.

Silobreaker prompt

&#x20;Copy

Perform an in-depth cyber threat assessment of the {SECTOR} sector, using the incident research and the latest credible intelligence.  Identify the five most material cyber threat scenarios affecting the sector and its subsectors. Analyse relevant threat actors and their motivations, attack frequency indicators, exploitation trends, commonly targeted systems, initial access methods, attack paths, vulnerabilities and observed tactics, techniques and procedures.  Examine documented weaknesses including identity and access management, absent or ineffective MFA, privileged access, exposed remote services, unpatched vulnerabilities, IT/OT segmentation where applicable, third-party access, detection capabilities, backup and recovery, and other sector-specific controls.  For each scenario, explain which weaknesses could enable or amplify the attack, cite documented incidents demonstrating the relationship, distinguish confirmed exploitation from hypothetical vulnerability, and describe plausible operational consequences.  Assess the direction of the threat, severity of the operational scenario, strength of the evidence and confidence in the assessment. Do not convert incident counts into probabilities without a defensible methodology.  Output: five prioritised threat scenarios, attack-pathway analysis, evidence-supported control weakness matrix, key threat metrics, trend direction and intelligence confidence.

### Q04 — Cyber resilience capabilities and sector control benchmarks

This addresses an important question that your initial research did not explicitly answer:

Which security and resilience capabilities are especially important for this sector, and why?

Silobreaker prompt

&#x20;Copy

Identify the cybersecurity and operational resilience capabilities most critical to organisations in the {SECTOR} sector.  Use authoritative cybersecurity standards, relevant sector guidance, empirical incident investigations, industry research and credible cybersecurity maturity studies.  Assess identity and access protection, MFA, vulnerability management, asset visibility, IT/OT security where relevant, network segmentation, security monitoring, incident response, third-party resilience, business continuity, disaster recovery, backup integrity, recovery testing and sector-specific safeguards.  For each capability, determine what critical operational process it protects, which observed attack pathways it mitigates, whether its absence or weakness has contributed to documented incidents, and what could happen if it fails.  Identify available sector benchmarks and recurring preparedness weaknesses. Distinguish mandatory requirements, recommended good practice and context-dependent capabilities. Avoid implying that all organisations need identical controls or that the absence of a particular technology necessarily indicates inadequate resilience.  Output: prioritised sector resilience capabilities, applicable benchmarks, documented control gaps, criticality rationale and recommended areas for improvement.

### Q05 — Financial impact, disruption trends and credit transmission

This is a consolidated and substantially strengthened version of your original financial analysis question.

I would retain every financial metric you originally requested, while going beyond averages to examine actual credit risk consequences.

Silobreaker prompt

&#x20;Copy

Perform an in-depth financial and operational impact assessment of cyber incidents affecting the {SECTOR} sector worldwide.  Research the following sector-specific metrics where reliable evidence exists: average and median data breach cost; ransomware demand and actual payment; business disruption frequency and duration; average and median incident recovery time; breach identification and containment lifecycle; recovery and remediation expenditure; revenue and profit impacts; and incident cost trends over the past five years.  For every metric, state the currency, year, population, sample size where available, geographic coverage, statistical method, source and limitations. Explain when no defensible sector-specific average exists. Distinguish breach lifecycle from business interruption and operational recovery periods. Avoid treating ransom payments as total incident costs.  Analyse documented cases showing effects on production or service delivery, lost sales, EBITDA, margins, working capital, cash conversion, liquidity, capital expenditure, borrowing requirements, credit ratings, covenant headroom and debt-servicing capacity. Separate disclosed financial consequences from external estimates.  Develop illustrative one-week, four-week and eight-week disruption scenarios, adapting the scenarios to the sector's critical business processes. Explain potential financial transmission pathways, important assumptions, possible offsets such as alternative operations or insurance, and the borrower-specific data needed to assess materiality. Do not represent illustrative scenarios as historical averages or probability forecasts.  Output: financial metrics with methodological caveats, five-year trends where supportable, documented impact case studies, credit transmission analysis and illustrative disruption scenarios.

### Q06 — Regulatory authorities and cyber resilience expectations

This combines your two original regulatory questions, while retaining EU, UK and US jurisdictional analysis.

Silobreaker prompt

&#x20;Copy

Identify the principal regulators, legislative frameworks, supervisory authorities, industry-specific requirements and cybersecurity or operational resilience expectations relevant to the {SECTOR} sector.  Provide a jurisdiction-by-jurisdiction analysis covering the European Union, United Kingdom and United States, including important subsector distinctions and national or state-level variations where material.  For each applicable framework, explain the regulator or competent authority, entities and activities in scope, mandatory cyber risk management and resilience obligations, incident reporting requirements, continuity and recovery expectations, third-party and supply-chain security expectations, applicable deadlines, and enforcement or supervisory consequences.  Identify recent regulatory developments, material enforcement examples, published supervisory concerns and expected changes. Distinguish legislation, binding regulatory requirements, supervisory guidance, industry standards and voluntary good practice.  Evaluate which requirements have the greatest implications for operational resilience, potential financial liabilities, business continuity and borrower credit risk.  Output: EU, UK and US jurisdictional comparison; applicability-based checklist; key resilience obligations; supervisory priorities; regulatory developments and credit-relevant consequences.

### Q07 — Geopolitical cyber threats and systemic exposure

This preserves your geopolitical research and integrates threat-motivated targeting, conflict spillover and cross-sector concentration.

Silobreaker prompt

&#x20;Copy

Assess how the current geopolitical environment is influencing cyber threats, attacker motivations, targeting patterns and resilience risks affecting the {SECTOR} sector worldwide.  Analyse relevant state-sponsored and state-aligned operations, cyberespionage, disruptive or destructive activity, geopolitically motivated hacktivism, sanctions-related targeting, regional conflicts, strategic technology competition and cyber-enabled supply-chain disruption.  Identify which subsectors, countries, critical technologies, infrastructure services and business dependencies may be disproportionately exposed. Explain the mechanism connecting geopolitical developments to credible cyber threats, rather than providing generic political commentary.  Assess the potential for cyber incidents to propagate across organisations through shared technology providers, energy systems, telecommunications, logistics, software supply chains, outsourced service providers or other sector-specific critical dependencies. Identify documented examples of correlated disruption when available.  Distinguish observed state-linked campaigns from speculative scenarios and explain attribution confidence. Identify early warning indicators and developments that could materially alter the sector threat assessment.  Output: geopolitical threat drivers, relevant observed campaigns, vulnerable subsectors and regions, systemic exposure scenarios, credit-relevant implications and early warning indicators.

### Q08 — Questionnaire interoperability and Credit Officer engagement

This is the bridge between the intelligence research and the credit process.

There is one important dependency: Silobreaker must have access to the actual questionnaire, including its question IDs. Otherwise, it should provide provisional mappings rather than inventing questionnaire references.

Silobreaker prompt

&#x20;Copy

Using the validated research findings for the {SECTOR} sector and the supplied corporate cyber resilience questionnaire, develop a sector-specific intelligence mapping and client discussion guide for Senior Credit Officers.  For each material questionnaire item, identify: the potential weakness indicated by an adverse response; the sector-specific threat scenarios and attack pathways it relates to; documented incidents demonstrating the relevance of the weakness; important operational dependencies; applicable regulatory resilience expectations where relevant; and plausible financial or credit consequences.  Explain the conditions that could make the weakness more or less material to a particular borrower, including business model, geography, compensating controls, operational concentration and financial resilience.  Provide two or three non-technical follow-up questions, practical resilience improvements and indicators that may warrant specialist review or closer monitoring. Prioritise the findings most likely to affect critical operations and financial resilience.  Use the actual questionnaire IDs supplied. If no questionnaire is available, produce a clearly labelled provisional mapping and do not fabricate question identifiers.  The guide must support constructive client discussions, not a cybersecurity audit. Do not treat self-reported answers as verified evidence, assume regulatory non-compliance or make automatic adverse credit judgements.  Output: questionnaire-to-threat-to-incident-to-credit mapping matrix, prioritised discussion prompts, suggested resilience improvements and escalation indicators.

### Q09 — Final Sector Cyber Resilience & Credit Intelligence Report

Your original question asked for a board-level briefing. I propose changing this into the final deliverable for Senior Credit Officers, with the ability to derive a separate board briefing later.

Silobreaker prompt

&#x20;Copy

Using the validated outputs of research questions Q01–Q08, prepare a professional Sector Cyber Resilience & Credit Intelligence Report for the {SECTOR} sector, designed for Senior Credit Officers assessing corporate borrowers.  The report must contain: 1. Executive sector assessment: principal findings, top risks, trend direction and implications for credit discussions. 2. Sector operating model: critical processes, digital dependencies and concentration risks. 3. Cyber threat landscape: three to five prioritised threat scenarios with documented incident evidence and relevant exploited weaknesses. 4. Geopolitical cyber exposure: material geopolitical drivers, targeting patterns and systemic dependencies. 5. Regulatory resilience expectations: relevant EU, UK and US obligations, applicability qualifications and supervisory priorities. 6. Control weakness intelligence: the security and resilience gaps most relevant to the sector, connected to observed attacks and the supplied questionnaire. 7. Operational and financial consequences: documented costs, business interruption pathways, financial sensitivity and credit transmission mechanisms. 8. Credit Officer engagement: concise, targeted client discussion prompts, practical improvement opportunities and indicators requiring follow-up.  Produce a four-page-equivalent executive report supported by a separate, traceable evidence annex. Use concise, non-technical explanations without losing analytical rigour. Make sector-specific judgements rather than generic cybersecurity statements. Distinguish sector-level risks from individual borrower materiality.  Include source references, assessment confidence, evidence cutoff, version date and unresolved research gaps. Highlight conflicts or limitations in the underlying intelligence rather than hiding them. Do not invent missing evidence or present the report as an independent audit, regulatory compliance assessment or borrower credit rating.  Output: publication-ready sector report, evidence annex and a short list of intelligence gaps requiring analyst validation.

## 3. How I would operationalise this across 24 sectors

I would divide the nine questions into three production stages.

## 01

Research and evidence collection — Q01 to Q07

Reusable intelligence gathered for each sector. Research should be stored in structured records rather than only in a long conversational transcript.

## 02

Credit integration — Q08

Connect intelligence to the common questionnaire. This is where sector research becomes useful to Senior Credit Officers.

## 03

Report production — Q09

Produce the standardised sector briefing with an evidence annex, followed by analytical review and approval.

For the 24-sector programme, that gives us 168 core sector research executions (seven research questions across 24 sectors), followed by 24 questionnaire integration exercises and 24 report production exercises.

That is 216 stage executions, before any targeted follow-up research or validation. It is a useful planning baseline, not a requirement to make 216 completely independent Silobreaker calls: some intelligence can and should be shared across sectors.

## 4. Two things I would standardise from the beginning

First, common output identifiers. Every research result should have structured references such as `INC` for incident, `THR` for threat scenario, `CTL` for control weakness, `REG` for regulatory obligation and `FIN` for financial consequence. This lets us connect research across the seven analytical pillars and reuse it in the 24 reports.

Second, a consistent evidence standard. For material claims, retain the source, relevant dates, geography, subsector, level of confidence, and whether the finding is documented or inferred. Silobreaker's synthesis is useful, but it should never substitute for validation of an important claim.

## 5. My final assessment

This nine-question structure is a better foundation than either your original ten exploratory prompts or the expanded sixteen-question list.

It preserves the strengths of your original research, introduces the missing credit and resilience analysis, and removes unnecessary duplication.

One caveat: we can standardise the research questions, but not assume that every sector has the same threats, regulations, operating dependencies or available evidence. The common prompts must permit a finding of limited relevance or insufficient evidence rather than forcing identical conclusions.

The next important step is to test Q01–Q09 against the manufacturing sector, evaluate the actual outputs, and refine the common research instructions before deploying the template to the other 23 sectors.

I would treat these nine questions as our Master Research Framework V3.0, with manufacturing serving as the validation case.
