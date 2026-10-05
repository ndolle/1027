## Complementary Use of Silobreaker and Custom LLM Capabilities

Silobreaker remains an important component of our intelligence capability, particularly for search, monitoring, information discovery and investigation.

However, several of our current and emerging use cases require capabilities beyond information retrieval. These include persistent refinement of analytical outputs, multi-source analysis, automation, framework comparison, structured knowledge retention, visual production and the development of reusable analytical workflows.

The purpose of maintaining access to a custom LLM environment is therefore not to replicate Silobreaker, but to complement it and extend what can be achieved with the intelligence it provides.

---

## 1. Newsletter Production – Consistency and Continuous Improvement

Silobreaker can generate a newsletter using its embedded AI capability. However, we have identified two important limitations.

### Repetition across reporting periods

Silobreaker does not currently provide a persistent mechanism for ensuring that previously reported stories are systematically excluded from subsequent newsletters.

Our automated workflow uses:

* Silobreaker API data;
* Python;
* historical newsletter records; and
* a customised LLM workflow.

This allows us to identify previous stories, distinguish genuine updates from repeated reporting and retain continuity between reporting periods.

### Persistent refinement of output quality

A further issue is consistency.

Using the same instructions with Mimir can produce materially different newsletter outputs between runs.

With our custom LLM workflow, we have been able to progressively refine the behaviour of the model through repeated feedback, examples, prompt refinement, output rules and quality controls.

This means the model increasingly reflects the way the team expects intelligence to be:

* selected;
* prioritised;
* classified;
* summarised;
* written; and
* presented.

A standard, non-customised instance of the same underlying LLM does not produce equivalent results.

We have also tested the outputs independently. When reviewers are presented with alternative versions of the newsletter, the output produced through the customised workflow is consistently preferred.

The important distinction is therefore not simply access to an LLM. It is the ability to **build institutional knowledge and feedback into a repeatable analytical process**.

At present, we do not have an equivalent persistent feedback mechanism within Mimir that allows us to progressively shape its behaviour around our specific analytical requirements.

---

## 2. Incident Intelligence and Knowledge Retention

We are developing a structured database of incidents to move beyond individual news events towards longer-term analysis.

The objective is to retain information such as:

* incident type;
* sector and geography;
* threat actor or campaign;
* attack vector;
* root cause;
* control failure;
* third-party involvement;
* operational impact;
* financial impact;
* recovery duration;
* regulatory consequences; and
* lessons learned.

This creates an internal knowledge base that can subsequently be queried to identify patterns and trends.

This type of analysis has already been requested through work associated with the SOC mission and the Payment Team.

Silobreaker assists strongly with source discovery. The custom LLM layer allows us to extract, normalise, classify and analyse those incidents consistently over time.

---

## 3. Sectorial and Thematic Reporting

Silobreaker can support the research stage of sectorial reporting.

However, the production process extends considerably beyond search.

Our custom workflows can support:

* ingestion of information from Silobreaker and other authorised sources;
* classification and filtering;
* trend identification;
* synthesis of multiple sources;
* analytical commentary;
* executive summarisation;
* quality checking;
* slide construction; and
* preparation of presentation-ready material.

The workflow therefore becomes:

**Research → Structure → Analyse → Validate → Produce → Review**

rather than ending at information retrieval.

---

## 4. Adverse News Research

Silobreaker remains an important source for adverse-news research, but we encounter several practical limitations.

These include:

* Mimir's current historical research window;
* cases requiring research significantly beyond 12 months;
* instances where potentially relevant items are not identified by a single search approach;
* the need to distinguish new events from repeated reporting; and
* the need to reconcile information across multiple sources.

For more significant assessments, we therefore use multiple research approaches and, where appropriate, more than one LLM.

The purpose is not to assume that agreement between models proves correctness. Instead, different approaches are used to identify omissions or inconsistencies, followed by verification against primary or reliable sources.

This reduces dependence on a single search mechanism or model.

---

## 5. Questionnaire Development from Multiple Frameworks

Another important use case is the creation and review of risk questionnaires.

A questionnaire may require analysis of multiple:

* standards;
* regulatory requirements;
* frameworks;
* industry guidelines;
* internal policies; and
* control expectations.

For example, a single assessment may need to take account of several NIST, ISO, regulatory and internal requirements.

Custom LLM workflows allow us to:

* extract relevant requirements from each source;
* identify overlapping requirements;
* identify unique requirements;
* consolidate similar control expectations;
* identify gaps;
* map questions back to source requirements;
* rationalise duplicate questions; and
* generate an assessment structure appropriate to the intended risk decision.

The workflow can therefore be:

**Frameworks → Requirement Extraction → Cross-Mapping → Gap Analysis → Question Development → Traceability → Expert Review**

The same process can also be used in reverse to assess whether an existing questionnaire provides adequate coverage of selected standards or requirements.

---

## 6. Development and Review of Risk Methodologies

The custom environment is also used for analytical development rather than simply content generation.

Examples include:

* designing assessment structures;
* testing scoring methodologies;
* developing parent and child question structures;
* determining evidence requirements;
* developing maturity models;
* creating decision logic;
* challenging existing methodologies;
* identifying inconsistent or overlapping criteria; and
* developing scenario and stress-testing approaches.

This is an important distinction.

The capability is being used not only to **find information**, but to help turn complex information into repeatable risk-assessment methods.

---

## 7. Visual and Presentation Capabilities

Silobreaker does not currently provide the broader visual-production capability required for many of our management outputs.

Custom AI tools can assist in transforming analysis into:

* executive infographics;
* risk landscapes;
* process diagrams;
* timelines;
* heatmaps;
* matrices;
* framework mappings;
* operating models;
* incident visualisations; and
* presentation-ready slides.

The same underlying analysis can therefore be adapted for different audiences:

**Detailed Analysis → Executive Summary → Slide → Diagram → Infographic**

This substantially reduces the manual work required to translate analysis into management-ready material.

---

## 8. Experimentation and Development of New Capabilities

An important part of the team's work is also exploratory.

New intelligence requirements frequently emerge before there is an established process for addressing them.

A flexible LLM environment allows the team to:

* experiment with new analytical methods;
* rapidly prototype workflows;
* test new data sources;
* assess different models;
* develop new classifications or taxonomies;
* automate repetitive analytical tasks;
* test whether an idea is viable before industrialising it; and
* continuously improve existing processes.

This experimentation is important because many of the capabilities now being used operationally began as small analytical experiments.

Without an environment in which these approaches can be developed and tested, innovation becomes constrained to the functionality already provided by existing platforms.

---

## 9. Operational Impact of Conducting Research from the Corporate Network

There is also an operational consideration.

A significant proportion of our work involves cyber-threat research, investigation and access to infrastructure or content that may legitimately appear suspicious to security-monitoring systems.

When this activity is performed from standard corporate endpoints and networks, it can generate a significant volume of security alerts.

This has several consequences:

* additional alerts require investigation;
* legitimate research activity can become difficult to distinguish from potentially malicious activity;
* analyst time is consumed explaining or validating expected activity;
* investigation queues can become unnecessarily noisy; and
* confidence in alert prioritisation can be reduced.

This is particularly important because **investigation of genuine cyber-security alerts is a core responsibility of the team**.

Research activity should therefore, where possible, be conducted in a way that does not unnecessarily increase noise within the corporate security-monitoring environment or complicate investigations of genuine security events.

---

## 10. What Would Be at Risk Without Access to a Custom LLM Environment

The primary impact would not be the loss of basic intelligence search. Silobreaker would continue to provide substantial research capability.

The impact would instead fall on the analytical processes and deliverables that have been built around that research.

### Deliverables and capabilities potentially affected

* **Automated newsletter production**
  Loss of the current customised selection, deduplication, historical comparison and continuously refined editorial process.

* **Consistency of recurring intelligence products**
  Greater variation between reporting cycles and reduced ability to incorporate accumulated analyst feedback into future outputs.

* **Incident intelligence database**
  Reduced ability to extract, normalise and classify large volumes of incident information and perform longitudinal analysis.

* **Sectorial reports**
  Increased manual effort to transform research into structured analysis and management-ready presentations.

* **Adverse-news assessments**
  Reduced ability to conduct broader historical research, cross-check results and challenge findings using alternative models or methods.

* **Questionnaire development**
  Increased manual effort in reviewing multiple standards, cross-mapping requirements, identifying gaps and developing consolidated questionnaires.

* **Risk methodology development**
  Reduced ability to rapidly test and refine new scoring models, assessment structures and analytical approaches.

* **Visual reporting**
  Loss of automated support for diagrams, infographics, visual summaries and presentation-ready material.

* **New analytical workflows**
  Reduced capacity to experiment, prototype and automate emerging intelligence requirements.

* **Institutional knowledge**
  Reduced ability to progressively embed analyst feedback, examples, classifications and decision rules into reusable analytical processes.

The result would therefore be less an immediate loss of access to information and more a movement back towards **manual processing, less consistent outputs and reduced ability to develop new analytical capabilities**.

---

## Overall Capability Model

The respective capabilities can be summarised as follows:

### Silobreaker

**Discovery | Monitoring | Search | Source Intelligence | Investigation**

### Custom LLM and Automation Environment

**Multi-source Integration | Persistent Refinement | Historical Comparison | Deduplication | Structured Extraction | Framework Analysis | Cross-Mapping | Gap Analysis | Knowledge Retention | Workflow Automation | Multi-Model Challenge | Report Generation | Visualisation | Prototyping**

### Analyst

**Verification | Challenge | Interpretation | Contextualisation | Risk Assessment | Quality Assurance | Decision Support**

The combined model is therefore:

**Discover → Integrate → Structure → Analyse → Challenge → Validate → Retain → Refine → Visualise → Produce → Review → Inform**

The principal distinction is that Silobreaker provides a strong intelligence platform, while the custom LLM environment provides the flexibility to **develop, refine and operationalise analytical processes around that intelligence**.
