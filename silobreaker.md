## Rationale for Complementary AI and Automation Capabilities alongside Silobreaker

Silobreaker remains an important component of our intelligence capability, particularly for information discovery, monitoring, search and investigation. The introduction of Mimir and other embedded AI functionality further enhances the platform.

However, a number of our use cases extend beyond information retrieval and summarisation. They require the ability to retain and analyse structured information, combine multiple data sources, compare frameworks and standards, validate findings, automate repeatable analytical processes, generate visual content, and transform intelligence into management-ready outputs.

For these purposes, external LLM and automation capabilities are complementary to Silobreaker.

### 1. Building an Internal Incident Intelligence Knowledge Base

We are progressively developing a structured database of cyber incidents and other relevant events to support internal analysis.

Rather than treating each incident as an isolated news item, the objective is to retain structured information that can subsequently be analysed for:

- recurring attack patterns and techniques;
- affected sectors and geographies;
- threat actors and campaigns;
- root causes and control failures;
- operational and financial impacts;
- recovery times;
- third-party dependencies;
- regulatory consequences; and
- emerging trends.

This type of analysis has already been requested in different contexts, including the SOC mission and work with the Payment Team.

Silobreaker provides valuable source intelligence, while external LLM and automation capabilities allow us to extract, normalise, classify and analyse incident information at scale. This creates a reusable internal intelligence asset rather than requiring repeated point-in-time searches.

### 2. Automated Intelligence Newsletter

Silobreaker's built-in AI functionality can assist in generating newsletters and summarising selected intelligence.

However, an important requirement of our newsletter process is continuity between reporting periods. We need to identify whether an item has already been reported and distinguish genuinely new developments from repeated coverage of an existing event.

Our current automated workflow uses the Silobreaker API together with Python and external LLM capabilities to:

- retrieve relevant intelligence;
- compare results against previously reported items;
- identify duplicate or substantially similar stories;
- distinguish updates to existing events from genuinely new events;
- classify and prioritise items;
- generate concise analytical summaries; and
- produce a consistent recurring intelligence product.

This provides stateful reporting across reporting cycles rather than treating each newsletter as an independent search.

### 3. Sectorial and Thematic Intelligence Reports

Silobreaker is effective for identifying and researching information relevant to sectorial or thematic assessments.

The subsequent analytical and production process, however, largely takes place outside the platform.

Custom AI-enabled workflows can ingest information from Silobreaker alongside other authorised sources and automate significant parts of the intelligence production lifecycle:

**Source collection → filtering → classification → analysis → synthesis → quality checks → report generation → presentation output**

The resulting analysis can then be transformed into management-ready reports and slides, with BNP Paribas formatting and analyst review applied to the final output.

This reduces the manual processing required between information discovery and production of a usable intelligence deliverable.

### 4. Adverse News and Historical Research

Silobreaker provides an important research capability for adverse-news reporting.

However, some investigations require historical research extending beyond the period currently available through Mimir. Adverse-news assessments can require examination of several years of information to determine whether an issue is isolated, recurring or part of a longer pattern.

We have also observed cases where relying on a single AI-assisted search does not identify all potentially relevant information.

External LLM capabilities allow Silobreaker research to be supplemented with broader authorised sources and alternative search and analytical approaches.

This is particularly relevant where the absence of a result from one search mechanism should not automatically be interpreted as evidence that no relevant adverse information exists.

### 5. Multi-Model Validation and Analytical Assurance

For higher-impact intelligence assessments, relying exclusively on a single AI model introduces single-model dependency.

A multi-model approach can be used to challenge findings, identify inconsistencies, compare interpretations and highlight areas requiring additional verification.

The process can therefore operate as:

**AI identifies → alternative model/method challenges → primary sources are verified → analyst assesses → final output is approved**

The objective is not to allow multiple AI models to determine that information is correct simply because they agree. Source-level verification and analyst judgement remain essential.

### 6. Framework, Standard and Guideline Analysis for Questionnaire Development

A separate use case is the development and review of risk assessment questionnaires.

Building an effective questionnaire can require analysis across multiple frameworks, standards, regulatory requirements and industry guidelines rather than reliance on a single source.

External LLM capabilities can support the simultaneous review and comparison of sources such as:

- NIST frameworks and guidance;
- ISO standards;
- regulatory requirements and supervisory guidance;
- operational resilience requirements;
- industry good practices;
- internal policies and control frameworks; and
- specialist guidance relevant to the subject being assessed.

The objective is not simply to summarise each framework individually. The models can be used to identify common requirements, overlaps, differences and gaps and then translate these into a consolidated set of assessment questions.

For example:

**Frameworks / Standards / Guidelines → Requirement Extraction → Cross-Mapping → Common Themes → Gap Identification → Question Development → Review → Final Questionnaire**

This enables questions to be traceable to underlying requirements while avoiding unnecessary duplication where several frameworks address substantially the same control objective.

The same capability can also be used in reverse: an existing questionnaire can be assessed against selected frameworks to identify areas that may be underrepresented or missing.

This approach has practical application to the development of cyber resilience, third-party risk, operational resilience, technology risk and other risk assessment questionnaires.

### 7. Cross-Framework Mapping and Control Rationalisation

Beyond questionnaire creation, the same capability can support broader framework and control analysis.

Multiple standards frequently express similar expectations using different terminology and structures. Reviewing these manually can be time-consuming, particularly when the analysis spans several large documents.

External LLM capabilities can assist with:

- mapping equivalent or related requirements;
- identifying unique requirements;
- identifying common control objectives;
- highlighting potentially conflicting expectations;
- mapping questions to controls and controls to frameworks;
- identifying potential coverage gaps;
- rationalising overlapping assessment requirements; and
- maintaining traceability between source requirements and resulting assessments.

This allows the analysis to move from **"what does each document say?"** to **"what is the consolidated requirement and how are we assessing it?"**

### 8. Visual and Infographic Generation

Silobreaker is primarily focused on intelligence discovery and analysis and does not provide the broader visual-generation capabilities required for some of our outputs.

External AI capabilities can transform analytical findings into visual forms appropriate for different audiences, including:

- executive infographics;
- risk landscapes;
- timelines;
- process diagrams;
- operating-model diagrams;
- incident lifecycle visualisations;
- control and framework mappings;
- heatmaps and matrices;
- trend visualisations; and
- presentation-ready graphics.

This is particularly useful where complex technical or risk information needs to be communicated quickly to senior management.

The capability therefore extends beyond generating text. The same underlying analysis can be transformed into different communication formats depending on the audience:

**Underlying Analysis → Detailed Report / Executive Summary / Slide / Infographic / Diagram**

### 9. Combining Multiple Intelligence and Information Sources

Our requirements are not limited to information contained within a single commercial platform.

External LLM and automation capabilities allow authorised information from multiple sources to be combined, including Silobreaker API outputs, public information, regulatory publications, standards and internally maintained datasets.

This allows the analytical question to determine the information required rather than constraining the analysis to the information available within a single platform.

### 10. Reusable Analytical Workflows

A significant capability is the development of reusable workflows for recurring activities.

For example:

**Adverse News**  
Search → historical expansion → entity matching → deduplication → source validation → chronology → analyst review

**Incident Analysis**  
Collection → extraction → taxonomy mapping → database enrichment → trend analysis → management insight

**Sector Reports**  
Collection → classification → trend identification → analysis → executive summary → presentation generation

**Questionnaire Development**  
Source selection → requirement extraction → framework comparison → cross-mapping → gap analysis → question generation → traceability → expert review

Once developed, these workflows can be reused and refined rather than rebuilding the analytical process for each request.

### 11. Supporting Analyst Capacity

The purpose of these capabilities is not to replace analyst judgement.

They allow repetitive processing activities to be automated so that analyst time can be concentrated on interpretation, challenge and decision support.

Activities such as collecting information, comparing documents, extracting requirements, identifying duplicate information, mapping controls, formatting outputs and preparing initial presentation structures can consume significant analyst capacity.

AI and automation can perform much of this preparatory work while retaining human review at the points where professional judgement is required.

## Overall Capability Model

Silobreaker and external AI capabilities therefore operate at different, complementary stages of the analytical lifecycle.

**Silobreaker**

Discovery | Monitoring | Search | Source Intelligence | Investigation

**External AI & Automation**

Multi-source Integration | Historical Research | Deduplication | Structured Extraction | Framework Comparison | Cross-Mapping | Gap Analysis | Multi-Model Challenge | Knowledge Retention | Workflow Automation | Report Generation | Visual Generation

**Analyst**

Source Verification | Challenge | Interpretation | Risk Assessment | Contextualisation | Quality Assurance | Decision Support

Together, these capabilities support a broader analytical lifecycle:

**Discover → Integrate → Structure → Compare → Analyse → Challenge → Validate → Retain → Visualise → Produce → Review → Inform**
