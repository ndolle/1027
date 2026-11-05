
**TLP:AMBER**  
**5 November 2026 | Threat Intelligence Follow-up**

Dear all,

Following our initial briefing of 4 November concerning the suspected €133 million cryptocurrency theft linked to Crédit Mutuel Arkéa, several significant developments have emerged. The bank has now officially confirmed the incident, clarified the initial entry point, and provided further information on the financial impact. Meanwhile, expanded blockchain investigations have revealed additional details about the attackers' preparation, fund movements and laundering techniques.

### 1. Official Confirmation: Third-Party Compromise

Crédit Mutuel Arkéa confirmed on 4 November that the attackers gained access **through the platform of an external service provider**, rather than through its online banking subsidiary, Fortuneo.

Importantly, the stolen funds originated from **Arkéa's own bank account**, through fraudulent transfers to other financial institutions, before potentially being converted into cryptocurrency. This corrects the initial hypothesis that the bank's cryptocurrency exchange accounts had been directly compromised.

The bank estimates the amount involved at approximately **€100 million**, although the final loss remains under investigation. It confirmed that customer assets were unaffected, some funds had been blocked and the incident was contained. Certain transfers were temporarily suspended as a precaution.

The identity of the compromised provider and the precise technique used to obtain payment authority have not yet been disclosed.

### 2. Expanded Blockchain Investigation: $126 Million Traced

An updated investigation published by Bitquery on 5 November has expanded the cryptocurrency withdrawals identified from approximately $109 million to **$126 million**, involving 17 initial recipient wallets and 526 downstream wallets.

Several findings are noteworthy:

- **Advance preparation:** Twelve of the 17 wallets had previously received exchange withdrawals, some dating back to May 2026. This suggests that parts of the financial infrastructure may have been established well before the attack.
- **Transaction structuring:** Multiple wallets received amounts approaching $10 million, while one account processed 43 withdrawals of less than $50,000 each within 91 minutes. This raises questions about transaction limits and monitoring.
- **Continued withdrawals:** Approximately $17.2 million was withdrawn through Kraken on 2 November after the initial public disclosure, raising questions about the timing and effectiveness of exchange intervention.

The traced cryptocurrency amounts are not directly equivalent to Arkéa's confirmed financial loss and have not yet been fully reconciled with the banking transactions.

### 3. Laundering: Ether, Monero and Cross-Chain Transfers

Investigators identified increasingly sophisticated methods used to move and conceal the proceeds.

Approximately **$63 million was converted into Ether within four hours**, reducing opportunities for stablecoin issuers to freeze the stolen funds.

Investigators also identified transactions consistent with conversion into **Monero (XMR)** through the Wagyu swapping service. Monero is a privacy-focused cryptocurrency designed to conceal transaction participants and amounts, making subsequent blockchain tracing substantially more difficult.

Additional funds were transferred through cross-chain bridges, cryptocurrency exchanges and swapping services.

As of the morning of 5 November, Bitquery identified approximately **$37.3 million remaining on Ethereum**, while Tether had frozen approximately $1.14 million in USDT. These figures do not represent confirmed recoverable funds.

### 4. Updated Risk Assessment for 4

The confirmation of a third-party entry point materially changes the initial risk interpretation.

The principal concern is no longer a potentially compromised institutional cryptocurrency exchange account, but rather **the possibility of a trusted external provider being exploited to facilitate unauthorised banking transactions**.

This reinforces the importance of independently secured payment authorisation, third-party access governance and transaction monitoring, particularly where external platforms interact with sensitive financial operations.

The cryptocurrency laundering activity also demonstrates how quickly stolen funds can move beyond conventional recovery mechanisms, increasing the importance of early detection and coordinated intervention.

**Our current assessment remains Medium risk 4**, with no evidence of direct exposure or a shared compromised provider.

### 5. Outstanding Intelligence Priorities

Our monitoring will focus on identifying the compromised provider, establishing how fraudulent payment instructions were authorised, clarifying the extent of fund recovery and determining whether the attackers are linked to a broader campaign targeting financial institutions.

The Paris prosecutor's cybercrime unit has opened an investigation. No verified threat-actor attribution has been established.

**Sources**

[1] [Crédit Mutuel Arkéa – Official clarification, 4 November 2026](https://www.cm-arkea.com/arkea/banque/assurances/pa_38386/fr/informations-complementaires-suite-a-l-attaque-dont-le-credit-mutuel-arkea-a-ete-victime)

[2] [Reuters – €100 million missing after cyberattack, 5 November 2026](https://www.reuters.com/legal/government/french-bank-credit-mutuel-arkea-says-100-million-missing-after-cyberattack-2026-11-05/)

[3] [Bitquery – Expanded blockchain investigation, updated 5 November 2026](https://www.bitquery.io/investigations/eu-106m-crypto-theft)

*Assessment based on information available as of 5 November 2026. Blockchain findings remain independent investigative assessments.*
