# Financial-services cyber-risk brief

**Review period: 12–18 October 2026**

## Executive summary

Three developments warrant second-line attention:

- **A South Korean sector review exposed systemic attack-surface control weaknesses:** 16 financial firms were affected by related cyber incidents, while 130 of 555 firms—nearly one-quarter—reported deficiencies including missing patches, unsupported systems, absent 24/7 monitoring, weak external-system authentication and missing MFA.
- **The FSB established a new global reference point for financial-sector AI governance:** its 12 final sound practices explicitly address AI-related cyber, ICT and third-party risk. Although non-binding, they are likely to influence supervisory expectations.
- **The Bank of England is surveying firms’ post-quantum readiness and developing sector-wide recovery approaches:** firms should expect pressure to evidence cryptographic inventories and the ability to restore critical services from a trusted, isolated foundation.

No consequential new DORA rule, technical standard or enforcement action was identified during the period. The other developments nevertheless have direct relevance to DORA implementation evidence.

## 1. Korean review turns individual compromises into a sector-wide EASM finding

**What changed — confirmed fact, 14 October**

South Korea’s Financial Services Commission said cyber incidents had been confirmed at **16 firms** spanning banks, savings banks, finance companies, fintech lenders, payment firms and virtual-asset providers. Approximately **100,000 personal-data records** were affected; account passwords and payment-card numbers had not been confirmed as exposed.

More significantly, a 12-control review covering **555 financial firms** found deficiencies at **130**. Reported weaknesses included unapplied security patches, poorly governed end-of-support systems, absent continuous monitoring, external systems lacking proper authentication or authorisation, and missing MFA. The authorities plan a comprehensive inventory of external connections, stronger access control and accountability, enhanced threat-information sharing, and more frequent testing of important external touchpoints. [금융위원회](https://www.fsc.go.kr/no010101/87927?curPage=\&srchBeginDt=\&srchCtgry=\&srchEndDt=\&srchKey=\&srchText=\&utm_source=chatgpt.com)

**Why it matters**

This is evidence of a **control-design and coverage problem**, not simply slow incident containment. The affected population also cuts across traditional banks, fintechs and smaller entities, illustrating how uneven control maturity can create sector-wide exposure.

The most transferable lesson is that owning an EASM tool does not demonstrate effective attack-surface management. Regulators are increasingly interested in whether externally reachable assets are complete, owned, supported, strongly authenticated, continuously monitored and promptly remediated.

**Practical 2LoD implication**

Require evidence that management can produce:

- Reconciliation between EASM discovery, DNS/cloud inventories, certificates, CMDB records and third-party-hosted services.
- Coverage metrics for external assets with an accountable owner, MFA, supported software, 24/7 monitoring and vulnerability-remediation SLA.
- Aged exceptions for unsupported or weakly authenticated external services, with named executives and time-bound risk acceptance.
- Independent sampling that tests whether “remediated” assets are actually closed or controlled from an external attacker’s perspective.
- Group-level oversight of fintech subsidiaries and smaller entities rather than reliance on self-attestation.

Escalate material unknown assets, unauthenticated interfaces or internet-facing end-of-support technology rather than treating them as routine vulnerability-management backlog.

## 2. FSB finalises an AI-governance benchmark with explicit cyber scope

**What changed — confirmed fact, 15 October**

The Financial Stability Board finalised **12 sound practices for responsible AI adoption**. They cover board oversight, alignment with risk appetite, defined accountability, documentation, materiality assessment, data governance, explainability, performance evaluation, human oversight, AI-related cyber and ICT risk, and third-party AI dependencies. The FSB explicitly encourages boards and senior management to use them when refining governance and controls. [Financial Stability Board](https://www.fsb.org/2026/10/fsb-finalises-sound-practices-for-the-responsible-adoption-of-artificial-intelligence-ai/?utm_source=chatgpt.com)

**Why it matters**

The practices are not binding rules, but they create a credible international supervisory baseline. They also make clear that AI governance cannot sit solely with model-risk or innovation teams: cyber defence agents, autonomous operational tooling and externally hosted models fall within enterprise risk and resilience frameworks.

For DORA-scoped institutions, the practices reinforce the need to incorporate material AI services into ICT risk management, testing, incident processes and third-party dependency analysis.

**Practical 2LoD implication**

Perform a targeted gap assessment against the 12 practices, prioritising:

- Completeness of the AI-use-case inventory, including embedded vendor features and cyber-defence agents.
- Materiality tiers linked to approval authority, testing depth and board reporting.
- Audit logs, human intervention, shutdown capability and restrictions on autonomous actions.
- Monitoring for performance drift, unsafe tool use and changes in model or hosting dependencies.
- Exit, substitution and continuity arrangements for concentrated AI providers.

Challenge aggregated “AI-compliance” scores. Assurance should show control effectiveness for individual material use cases and dependencies.

## 3. BoE moves post-quantum readiness toward evidence-based supervision

**What changed — confirmed reported remarks, 15 October**

Bank of England Deputy Governor Sarah Breeden said the Bank is **surveying firms on their preparedness for quantum threats to encryption** and will use the results, alongside NCSC guidance, to develop a system-wide plan with industry.

She also said the Bank is working with firms on “bare-metal” recovery options for core services because institutions can no longer assume that increasingly AI-enabled attackers will always be kept out. The Bank’s July Financial Stability Report had already identified isolated rebuild or minimum-service facilities as potential sector-level recovery options. [Reuters](https://www.reuters.com/legal/litigation/banks-need-bare-metal-recovery-face-ai-risks-says-boes-breeden-2026-10-15/?utm_source=chatgpt.com)

**Why it matters**

PQC readiness is shifting from a long-range technology strategy to a matter firms may have to evidence to supervisors. The principal near-term risk is not an immediate cryptographic break; it is an incomplete understanding of where vulnerable public-key cryptography, long-lived sensitive data and difficult-to-change dependencies reside.

The recovery message is equally important: conventional backups may be insufficient if identity, orchestration, hypervisors, cloud control planes or recovery tooling are compromised.

**Practical 2LoD implication**

Request a survey-ready evidence pack covering:

- Cryptographic inventory coverage by critical business service, application, data class and third party.
- RSA/ECC dependencies in PKI, HSMs, payments, APIs, code signing, messaging and long-lived archives.
- “Harvest now, decrypt later” exposure and retention-driven prioritisation.
- Vendor migration commitments, contractual dependencies, accountable owners and milestones.
- Scenario tests in which production identity and recovery orchestration are untrusted.

Do not accept a single PQC-readiness percentage without the underlying denominator, discovery method and known blind spots.

## DORA status

No consequential new DORA legislative, technical-standard or enforcement development was identified in the review period. Immediate attention should remain on **evidence quality**: external-asset completeness, ICT third-party dependencies, severe-but-plausible recovery testing, and demonstrable governance of material AI services.

## Prioritised watchlist

1. **South Korean incident investigation:** common intrusion path, attribution, additional affected firms and any mandatory control reforms.
2. **BoE quantum survey:** publication of its scope, evidence requirements, maturity benchmarks or sector-level timetable.
3. **FSB adoption:** incorporation of the AI practices into national supervisory reviews or board-attestation expectations.
4. **Recovery architecture:** regulatory movement from conventional backup assurance toward isolated rebuild and minimum-viable-service testing.
5. **External-edge exploitation:** new evidence of active exploitation affecting VPNs, identity infrastructure, remote-management systems or internet-facing financial-sector platforms.
