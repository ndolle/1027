# EXECUTIVE BRIEF – REVOLUT CUSTOMER DATA DISCLOSURE INCIDENT

**Date:** 14 September 2026\
**Audience:** Executive Committee\
**Classification:** Internal\
**Risk Areas:** Cyber Risk | Operational Risk | Data Protection | Fraud Risk

## Executive Summary

Revolut has confirmed that sensitive customer information was disclosed to an unauthorised third party following fraudulent information requests that appeared to originate from a legitimate government agency.

Importantly, **this does not currently appear to have involved a compromise of Revolut's technology infrastructure**.

According to Revolut, an unauthorised third party used an email account operating from a legitimate government agency domain to submit fraudulent requests for customer information. Revolut processed the requests believing them to be authentic.

Revolut describes the incident as a **"sophisticated external impersonation scam"** and states that only a **"very limited" number of customers** were affected.

The company has explicitly stated:

> "Revolut systems and customer funds are unaffected."

The significance of the incident therefore extends beyond conventional cyber intrusion. It demonstrates how an attacker may exploit **trust in an external organisation and an otherwise legitimate business process** to obtain sensitive information without compromising the target organisation's systems.

**Key Risk message:** A trusted communication channel should not automatically imply that the identity, authority or request behind it can also be trusted.

---

## 1. What Happened?

Based on information confirmed by Revolut, the attack appears to have followed the following sequence:

**Unauthorised third party**\
↓\
**Access/use of a legitimate government agency email domain**\
↓\
**Fraudulent request for customer information**\
↓\
**Request appears legitimate to Revolut**\
↓\
**Customer information disclosed through an authorised process**

The important distinction is that the attacker does not appear to have breached Revolut's systems to retrieve the information directly.

Instead, the attacker appears to have **manipulated the process through which Revolut legitimately discloses information to competent authorities**.

The precise government agency involved has not been publicly identified, and it remains unclear how the unauthorised email account was established or compromised.

---

## 2. What Revolut Has Officially Said

As of 14 September 2026, Revolut does **not appear to have published a dedicated press release on its public News & Media site** concerning the incident.

However, Revolut has formally confirmed the incident through statements provided by its spokesperson to multiple media organisations and through direct notifications to affected customers.

Revolut's stated position is that:

- the incident was a **"sophisticated external impersonation scam"**;
- an unauthorised third party used a **legitimate government agency domain email** to submit fraudulent information requests;
- a **very limited number of customers** were affected;
- affected customers have been contacted directly;
- the offending address was blocked once the incident was identified;
- the relevant government agency was alerted;
- law enforcement, data protection authorities and financial regulators were notified; and
- **Revolut systems and customer funds were unaffected**.

Revolut has not publicly disclosed the exact number of affected customers, the government agency involved, or whether the incident was limited to a particular jurisdiction.

---

## 3. Potential Data Exposure

Customer notifications reported by the media indicate that information potentially disclosed included:

**Identity data**\
Names, dates of birth, postal addresses, email addresses and telephone numbers.

**Identity verification / KYC data**\
Copies of passports and driving licences, and potentially identity-verification selfies.

**Banking information**\
Account statements, IBAN information and withdrawal records.

**Transaction information**\
Transaction histories, potentially including Bitcoin transaction activity for some customers.

This combination is particularly sensitive because it potentially brings together **identity + KYC + contact + financial behaviour data**.

Even where account credentials or funds have not been compromised, such information could enable highly credible subsequent social-engineering, impersonation, identity fraud or targeted fraud attempts.

---

## 4. Why This Incident Matters

The incident highlights a risk scenario that may bypass many traditional cybersecurity controls.

### The trusted channel became part of the attack path.

An email originating from an authentic government domain does not necessarily establish that:

**the sender is legitimate;**\
**the individual is authorised;**\
**the request itself is legitimate; or**\
**the requested disclosure is appropriate.**

This creates an important distinction between:

**Authentication of the communication channel**

and

**Authentication of the request and authority behind it.**

For financial institutions, the issue is particularly relevant to processes handling requests from law enforcement, courts, regulators, government agencies and other trusted third parties.

---

## 5. Risk Implications

### Cyber / Information Security

Highly sensitive customer information was disclosed to an unauthorised party despite there being no currently reported compromise of Revolut's infrastructure.

### Operational Risk

A legitimate operational process appears to have been manipulated into producing an unauthorised outcome.

The incident therefore demonstrates that **an authorised process can itself become an attack vector**.

### Data Protection / Regulatory Risk

The nature of the information potentially exposed — particularly KYC documents, financial records and personal information — creates significant confidentiality and privacy implications.

### Fraud Risk

The combination of identity, contact and financial information could enable sophisticated downstream social-engineering and impersonation attacks against affected customers.

### Third-Party / Ecosystem Risk

Perhaps most importantly, the incident demonstrates that **the security posture of trusted external organisations can directly influence the effectiveness of an institution's own controls**.

A bank may have strong internal controls while still being exposed through the compromised identity infrastructure of an organisation it trusts.

---

## 6. Key Question for Our Organisation

The incident suggests one immediate control question:

### **Do we authenticate the request, or only the channel through which the request arrives?**

A targeted review could therefore assess how requests for sensitive information from trusted external organisations are validated, particularly where they originate from:

**Law enforcement | Government agencies | Courts | Regulators | Other trusted third parties**

The review should determine whether sensitive disclosures require independent verification of:

**Identity → Authority → Request → Scope → Approval**

rather than relying primarily on the authenticity of the originating email/domain.

Relevant controls could include independent out-of-band verification, callback procedures, four-eyes approval, verification against established authority contact directories, anomaly detection and escalation for unusual or high-risk requests.

---

## Executive Takeaway

**This was not necessarily a failure to keep an attacker out. It appears to have been a failure to distinguish a malicious request from a legitimate one arriving through a trusted channel.**

The incident reinforces an important principle for financial institutions:

### **Trusted source ≠ trusted request.**

The identity of the third party, authenticity of the communication channel, authority of the requester and legitimacy of the requested action should be considered separately.

For Risk Management, this incident provides a useful opportunity to test whether existing controls remain effective when **the trusted third party itself becomes part of the attack path**.
