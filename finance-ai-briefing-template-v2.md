# Finance & AI Briefing — Master Template & Specification

**Format ID:** `FIN-AI-BRIEFING-v3`  
**Target Word Count:** 1,200 – 1,450 words (Hard Maximum: 1,500 words)  
**Audience:** Executive & Senior Banking Management  
**Register:** Active, authoritative, clear, non-academic, accessible plain-English  

---

## Structure Blueprint

### HEADER
```markdown
# Finance & AI Briefing
**FIN-AI-[YYYY]-[WW]** · [DD Month YYYY] · Covering [DD–DD Month YYYY]

---
```
*Dates:* The publication date is the Monday following the coverage week. Coverage is the preceding Monday–Sunday (ISO week).

---

### 1 — WHAT CHANGED
* **Word Count Target:** 150–200 words
* **Focus:** Single development with the longest structural shadow for banking.
* **Structure:**
  * **Bold Lead Sentence:** A direct 1-sentence statement of what changed in plain English.
  * **Core Narrative:** 2–3 paragraphs explaining what happened, why legacy assumptions broke, and the financial/legal liability implications.
  * **Audit Action:** Exactly one sentence starting with: `→ If you do one thing this week:` (a specific question to ask or number to audit).
  * **Sources:** Verbatim source link(s) on a new line formatted as `[Outlet Name](URL)`.

---

### 2 — TECHNOLOGY IN FOCUS
* **Word Count Target:** 350–450 words
* **Structure:**
  * **Subtitle:** Plain-English description of the mechanism (e.g. `#### How [Mechanism] works`).
  * **Educational Core:** Clear, jargon-free explanation of the technical mechanism. Define any technical term upon first use.
  * **Failure Analysis:** Detail where current software/model implementations break or fail.
  * **News Connections:** Explicitly connect the mechanism to two or more separate news items from the current week.
  * **Source:** Completed with a single `[Read more](URL)` reference link.

---

### 3 — CLAIMS & REALITY
* **Word Count Target:** 250–350 words (Must be shorter than Section 2)
* **Section Subtitle:** `*Separating verified developments from market speculation.*`
* **Format:** 4–5 entries under verdict headings (**REAL**, **OVERSTATED**, **UNVERIFIED**, **QUIETLY IMPORTANT**, **LOW RELEVANCE**).
* **Entry Structure:**
  * `#### **VERDICT — Title**`
  * `[Linked Item Headline](URL)` (verbatim link from source)
  * **Blended Paragraph:** A single 45–60 word paragraph combining the event, context, and calibrated assessment without subheaders like "What happened:" or "Why it matters:". Use objective, non-conclusive language for untested security/tech claims (e.g., *\"remains unverified\"*, *\"untested in enterprise environments\"*).

---

### GROUP FOCUS (IN-HOUSE SPOTLIGHT)
* **Word Count Target:** 100–150 words
* **Section Subtitle:** `*Key internal announcements and published deployments across Group entities.*`
* **Format:** 3 concise bullet points.
* **Strict Constraint:** **100% Factual and Grounded.** Zero extrapolation, zero speculation, no "if A+B then C", no unstated assumptions. Strictly reflect published press releases, financial reports, or official corporate disclosures.
* **Entry Structure:**
  * `* **[Short Announcement Title]** — [Direct, factual summary of published event.] [Read more](URL)`

---

### 4 — CONTROL CONSIDERATIONS
* **Word Count Target:** 250–300 words
* **Format:** 7–8 bullet points.
* **Item Structure:** Every bullet MUST begin with the word **\"Whether...\"** and end with parenthetical role tags, e.g. `*(Digital Channels, Security)*` or `*(Credit Risk, Corporate Banking)*`.
* **Style:** Pure operational questions—no preachy directives, no imperatives (\"must\", \"should\"), no empty advice.

---

### 5 — ALSO THIS WEEK
* **Word Count Target:** 200–300 words
* **Format:** 10–14 single-line bullet points.
* **Item Structure:** `* **[Category]** — [Factual summary strictly under 25 words.] [Read more](URL)`
* **Categories:** `[Infrastructure]`, `[Macro & Capital]`, `[Retail & Products]`, `[Regulation]`, `[Cyber & Risk]`, `[Talent & Workforce]`, `[Core Banking & Operations]`, `[Peers]`.
* **Rule:** Zero adjectives or editorial commentary; plain factual statements only.

---

### 6 — KEY SOURCES
* **Format:** 6–10 curated key source citations formatted as:
  `* **Outlet Name** — *Article Title*  
    [URL](URL)`

---

## Invariable Rules & Constraints

1. **URL Integrity:** EVERY URL must be extracted verbatim from the week's input source file (`FIN-AI-WW-YYYY.txt`). NEVER invent, truncate, or modify URLs.
2. **Grounding:** Every fact, company name, percentage, and metric must trace directly to the provided text file or published press release.
3. **Formatting Invariants:**
   - Header H1 `# Finance & AI Briefing`
   - H3 Section Titles (`### 1 — WHAT CHANGED`, `### 2 — TECHNOLOGY IN FOCUS`, `### 3 — CLAIMS & REALITY`, `### GROUP FOCUS`, `### 4 — CONTROL CONSIDERATIONS`, `### 5 — ALSO THIS WEEK`, `### 6 — KEY SOURCES`)
   - Section 4 bullets must start with `Whether` and end with `*(Role, Role)*`
   - Section 5 bullets must be under 25 words per line
