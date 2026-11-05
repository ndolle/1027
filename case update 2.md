
### 1. EXECUTIVE SUMMARY

French banking group Crédit Mutuel Arkéa has confirmed a sophisticated cyberattack involving approximately €100 million in fraudulent transfers. The attackers accessed the bank through an external service provider's platform and used Arkéa's own account to transfer funds to other financial institutions, where the money was reportedly converted into cryptocurrency.

The bank has confirmed that its customers' assets were unaffected, the incident has been contained, and some funds have been blocked. The final financial loss remains under assessment.

Blockchain investigations have traced approximately $126 million in cryptocurrency withdrawals associated with the suspected operation, revealing evidence of advance preparation, coordinated wallet activity and rapid laundering. The amount traced on-chain should not be interpreted as the bank's confirmed financial loss.

**Key concern for --------------:** The incident illustrates how a compromise of a trusted third-party platform could potentially enable large-scale financial fraud, particularly where external connectivity, payment authorisation and transaction-monitoring controls are insufficiently independent.

No direct exposure or technical vulnerability affecting BNP Paribas has been identified.

### 2. ATTACK MODUS OPERANDI

The available evidence indicates a multi-stage operation:

**Stage 1 – Third-party compromise (confirmed)**

Attackers gained access through the platform of an external service provider, allowing them to reach Crédit Mutuel Arkéa directly. The bank has explicitly ruled out Fortuneo as the entry point and stated that the incident was not caused by internal human error.

The provider's identity and the precise technique used to compromise or abuse its platform have not been disclosed.

**Stage 2 – Fraudulent banking transactions (confirmed)**

The attackers used Arkéa's own account to initiate transfers to other banks.

According to French investigative reporting, the recipient accounts were established using fraudulent identities, with beneficiary names matching those registered to the accounts. If confirmed, this would explain how conventional account-name verification may have been ineffective.

**Stage 3 – Cryptocurrency conversion and withdrawals (investigative findings)**

The transferred funds were reportedly converted into USDC, a US-dollar-backed stablecoin, through cryptocurrency exchanges.

Bitquery's latest investigation identified $126.04 million in withdrawals from Kraken, Crypto.com and OKX to 17 wallets over approximately 28 hours on 1–2 November.

Twelve of these wallets had received withdrawals previously, some dating back to May 2026. Several accounts handling relatively small amounts before the incident subsequently received millions of dollars.

The pattern suggests potentially pre-positioned infrastructure and coordinated activity, although the exchanges have not confirmed the identities or common ownership of the accounts.

**Stage 4 – Laundering and attempted recovery (investigative findings)**

Funds were rapidly redistributed through hundreds of wallets, converted into Ether and other assets, and moved through cryptocurrency exchanges and cross-chain services.

Bitquery identified approximately $63 million converted into Ether within four hours, significantly reducing opportunities for stablecoin issuers to freeze the proceeds.

At 08:47 UTC on 5 November, investigators identified approximately $37.3 million remaining in associated Ethereum wallets. Tether had frozen approximately $1.14 million in USDT.

These figures do not represent confirmed recoverable amounts. Kraken and Crypto.com have also reported taking restrictive measures against accounts associated with the incident, while denying compromise of their own platforms.

### 3. KEY DEVELOPMENTS AND TIMELINE

- **May–October 2026:** Some wallets later linked to the operation were already active, suggesting possible preparation over several months.
- **1–2 November:** Large-scale USDC withdrawals occurred across multiple exchange accounts. Investigators observed rapid consolidation and redistribution of funds.
- **2 November:** Approximately $17.2 million was reportedly withdrawn through Kraken after the initial public alert. The timing and effectiveness of exchange intervention remain under scrutiny.
- **4 November:** Arkéa confirmed the attack, identified the third-party entry route, ruled out Fortuneo involvement and stated that customer assets were unaffected.
- **5 November:** Arkéa's estimated financial exposure was reported at approximately €100 million. Expanded blockchain analysis identified 17 initial recipient wallets and 526 downstream wallets.

French judicial authorities have opened an investigation, and the bank has informed relevant supervisory authorities.

### 4. KEY INTELLIGENCE FINDINGS

**Third-party exposure:** The confirmed entry route demonstrates the potential consequences of external providers holding privileged connectivity to sensitive banking operations. The technical pathway from provider compromise to payment execution remains the most important unresolved question.

**Possible weaknesses in identity verification:** Accounts allegedly opened under fraudulent identities may have facilitated the movement of funds despite matching beneficiary names. The allegations have not yet been independently confirmed.

**Abnormal transaction behaviour:** Several wallets moved from relatively modest historical activity to multimillion-dollar withdrawals. Seven wallets in the initial analysis received between $9.3 million and $9.8 million each, potentially indicating deliberate transaction structuring. No specific exchange threshold has been established.

**Speed of laundering:** Rapid conversion from stablecoins into assets without issuer-controlled freezing mechanisms reduced opportunities for intervention. The case highlights the importance of detecting suspicious activity before withdrawal rather than relying primarily on subsequent asset recovery.

**Attribution:** No publicly verified threat-actor attribution is available. Investigators have not established a link between this incident and other cryptocurrency thefts reported during the same period.

### 5. POTENTIAL IMPACT ON ----------

**Direct exposure – Not identified**

No evidence currently indicates that BNP Paribas systems, customers or assets were affected. There is also no confirmed shared vulnerability or compromised supplier relationship.

**Third-party and payment infrastructure – Relevant**

The incident warrants consideration of whether any external service provider could initiate, modify or facilitate financial transactions through trusted interfaces, credentials or application connections.

**Digital-asset activities – Exposure dependent**

Institutional exchange accounts, custody arrangements, API keys and withdrawal permissions could present similar fraud and asset-movement risks. Actual exposure should be established internally rather than assumed.

**Fraud and financial crime – Heightened awareness**

The incident may also generate impersonation, phishing or fraudulent account-protection communications exploiting the publicity surrounding the attack.

### 6. RECOMMENDED ACTIONS

**Immediate – Next 24–48 hours**

1. **Digital Assets Operations / CISO:** Confirm whether relevant BNP Paribas entities maintain institutional cryptocurrency exchange or custody accounts, including their access models, API permissions and withdrawal controls.
2. **CISO / Third-Party Risk:** Identify external providers with the technical ability to initiate or influence high-value payment transactions, and confirm the existence of independent authorisation safeguards.
3. **Fraud Operations / SOC:** Assess whether monitoring can detect sudden increases in transaction value or velocity, new beneficiaries, abnormal withdrawal patterns and unusual changes to privileged access.
4. **CTI / Fraud Prevention:** Monitor for related phishing, impersonation campaigns and emerging technical indicators associated with the incident.

**Short term – Within 7 days**

Conduct a focused control review or tabletop exercise covering the compromise of a trusted payment-connected provider, fraudulent payment initiation, cross-institutional fund transfers and emergency containment.

The exercise should test the ability of cyber defence, fraud operations, payment teams and third-party management to respond jointly.

### 7. INTELLIGENCE GAPS AND NEXT MONITORING PRIORITIES

The investigation has not yet established:

- The identity of the compromised service provider and whether its services are used by other financial institutions.
- The technical method used to obtain access and authorise fraudulent transfers.
- Whether the alleged fraudulent identities and account-verification weaknesses contributed directly to the loss.
- The final amount stolen, frozen or successfully recovered.
- Whether the activity can be attributed to a known threat actor or wider campaign.

**Assessment:** Further intelligence collection should prioritise the technical relationship between the third-party compromise and payment authorisation. This is more relevant to banking-sector control assurance than the cryptocurrency laundering activity alone.

### 8. SOURCES

[1] Crédit Mutuel Arkéa – Official incident announcement, 4 November 2026\
[https://www.cm-arkea.com/arkea/banque/assurances/pa_38367/fr/credit-mutuel-arkea-annonce-avoir-ete-victime-d-une-attaque](https://www.cm-arkea.com/arkea/banque/assurances/pa_38367/fr/credit-mutuel-arkea-annonce-avoir-ete-victime-d-une-attaque)

[2] Crédit Mutuel Arkéa – Official clarification on the attack mechanism, 4 November 2026\
[https://www.cm-arkea.com/arkea/banque/assurances/pa_38386/fr/informations-complementaires-suite-a-l-attaque-dont-le-credit-mutuel-arkea-a-ete-victime](https://www.cm-arkea.com/arkea/banque/assurances/pa_38386/fr/informations-complementaires-suite-a-l-attaque-dont-le-credit-mutuel-arkea-a-ete-victime)

[3] Reuters – French bank Crédit Mutuel Arkéa says €100 million missing after cyberattack, 5 November 2026\
[https://www.reuters.com/legal/government/french-bank-credit-mutuel-arkea-says-100-million-missing-after-cyberattack-2026-11-05/](https://www.reuters.com/legal/government/french-bank-credit-mutuel-arkea-says-100-million-missing-after-cyberattack-2026-11-05/)

[4] Bitquery – On-chain investigation, updated 5 November 2026\
[https://www.bitquery.io/investigations/eu-106m-crypto-theft](https://www.bitquery.io/investigations/eu-106m-crypto-theft)

[5] Financial Times – Crédit Mutuel Arkéa seeks to recover funds after €100m hack, 5 November 2026\
[https://www.ft.com/content/3f6ef089-f478-4d00-a080-21a88ffd721b](https://www.ft.com/content/3f6ef089-f478-4d00-a080-21a88ffd721b)

*Assessment based on publicly available information as of 5 November 2026. On-chain findings and allegations concerning fraudulent identities have not been independently verified by Crédit Mutuel Arkéa.*

The revised structure removes the repeated explanation of the incident across the executive summary, timeline, key takeaways and bank-impact sections. It also places the confirmed third-party entry route at the centre of the assessment, with cryptocurrency tracing treated as supporting intelligence rather than the primary explanation of the compromise.
