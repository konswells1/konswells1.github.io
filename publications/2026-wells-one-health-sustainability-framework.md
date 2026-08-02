---
# ============================================================================
# BAHE publication knowledge object

# Replace values only. Preserve field order and structure.
# ============================================================================

# =======
# Publication identity
# =======

# Purpose: Immutable canonical publication identifier.
# Format: yyyy-firstauthor-short-topic. # Rule: Never changes after object creation.
id: 2026-wells-one-health-sustainability-framework

# Purpose: Official publication title.
title: "A One Health Sustainability framework for ecologically mediated nature-based wellbeing"

# Purpose: Short display title.
short_title: "One health sustainability for nature-based wellbeing"

# Purpose: BAHE object class.
# Values: publication
object_type: publication

# Purpose: Publication category.
# Values: research-article, review, methods, perspective, commentary
publication_type: review

# Purpose: Publication subtype.
# Values: empirical-study, systematic-review, scoping-review, topical-review, meta-analysis, simulation-study, conceptual-framework, protocol
publication_subtype: topical-review

# Purpose: Publication workflow status.
# Values: draft, submitted, accepted, published, archived
status: published

# Purpose: Publication year. # Format: YYYY
year_published: 2026

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2026-06-30

# Purpose: BAHE object creation date. # Format: YYYY-MM-DD
date_created: 2026-07-11

# Purpose: BAHE object modification date.
# Format: YYYY-MM-DD
date_modified: 2026-07-18

# Purpose: Publication language. # Format: IETF language tag
publication_language: en-GB

# Purpose: BKOS schema version.
schema_version: BKOS-1.0

# Purpose: BPubAS (BAHE Publication Annotation Standard) profile version.
profile_version: BPubAS-1.0

# =======
# Authorship
# =======

# Purpose: Author names in citation order.
authors:
- Konstans Wells
- Menna Brown
- Carmen Jochem
- Brian Garrod

# Purpose: Canonical BAHE author ids.
bahe_authors:
  - konstans-wells

# Purpose: Structured author metadata.
author_entities:
  # Purpose: Citation order.
  - position: 1
    # Purpose: Full author name.
    name: "Konstans Wells"
    # Purpose: Canonical BAHE person id.
    person_id: konstans-wells
    # Purpose: ORCID identifier.
    orcid: "0000-0003-0377-2463"
    # Purpose: Affiliated canonical organisation objects.
    affiliation_ids:
      - swansea-university

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Menna Brown"
    # Purpose: Canonical BAHE person id.
    person_id: menna-brown
    # Purpose: ORCID identifier.
    orcid: "0000-0003-1427-1648"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - swansea-university

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Carmen Jochem"
    # Purpose: Canonical BAHE person id.
    person_id: carmen-jochem
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - bayreuth-university

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "Brian Garrod"
    # Purpose: Canonical BAHE person id.
    person_id: brian-garrod
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.    
    affiliation_ids:
      - swansea-university

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  konstans-wells:
    - conceptualization
    - methodology
    - data-curation
    - writing-original-draft
    - writing-review-editing
    - visualization

  menna-brown:
    - conceptualization
    - data-curation
    - writing-review-editing
  
  carmen-jochem:
    - writing-review-editing
  
  brian-garrod:  
    - conceptualization
    - data-curation
    - writing-review-editing
    
# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: ""
    # Purpose: Canonical funder identifier.
    funder_id: ""
    # Purpose: Grant identifier.
    grant_number: ""
    # Purpose: Official grant title.
    grant_title: 

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Environmental Research Letters"

# Purpose: Journal volume.
volume: "21"

# Purpose: Journal issue.
issue: "13"

# Purpose: Article pages or article number.
pages: "133001"

# Purpose: Publisher.
publisher: "IOP Publishing"

# Purpose: Open-access availability. # Values: true, false
open_access: true

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "CC BY 4.0"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Brown, M., Jochem, C., & Garrod, B. (2026).
  A one health sustainability framework for ecologically mediated
  nature-based wellbeing. Environmental Research Letters, 21(13), 133001.
  https://doi.org/10.1088/1748-9326/ae803f

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2026), Environmental Research Letters, 21(13), 133001.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1088/1748-9326/ae803f"
  
  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1088/1748-9326/ae803f"
  
  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""
  
  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1088/1748-9326/ae803f"
pdf: "https://iopscience.iop.org/article/10.1088/1748-9326/ae803f/pdf"

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Human health benefits associated with nature exposure are increasingly recognised in public health and environmental policy. 
  However, most evidence linking nature and wellbeing relies on broad anthropogenic exposure proxies, including greenness indices, land-cover categories, and self-reported visit frequency, rather than ecological measures capturing biodiversity, habitat condition, or ecosystem functioning. 
  Consequently, the ecological conditions that mediate health benefits, their exposure–response relationships, and the long-term sustainability of nature-based wellbeing interventions remain poorly understood. Here we examine how current research integrates human health, ecological integrity, and sustainability dimensions within nature-based wellbeing research. 
  A targeted evidence synthesis confirms that most research is conducted in urban or human-modified environments and relies predominantly on coarse spatial proxies or categorical exposure contrasts, with limited incorporation of ecological quality, biodiversity, or environmental pressures. Critically, ecological costs and feedbacks associated with nature use, including habitat disturbance, visitor pressure, and infrastructure expansion, are rarely accounted for in assessments of health outcomes. We propose a one health sustainability framework that conceptualises nature-based wellbeing as an emergent property governed by ecological integrity, biodiversity-mediated pathways, environmental pressures, and long-term sustainability feedbacks. Extending one health beyond its traditional focus on zoonotic disease, this framework links human wellbeing outcomes to ecological condition and sustainability constraints, enabling assessment of exposure efficiency and the capacity of ecosystems to sustain health benefits under increasing demand. Embedding ecological integrity and sustainability dynamics within nature-based wellbeing research provides a basis for developing integrated indicators that can evaluate not only whether nature exposure benefits health, but also under what ecological conditions such benefits remain equitable and durable over time.

# Purpose: Source of abstract. # Values: publisher, author-manuscript
abstract_source: publisher

# Purpose: Indicates verbatim reproduction of original published abstract. # Values: true, false
abstract_verbatim: true

# Purpose: Display publicly. # Values: true, false
abstract_public_display: true

# =======
# Resources and media
# =======

# Related code, data and media.
resource_links:
  code: ""
  data:
    zenodo: "https://zenodo.org/records/18891399"
    figshare: ""
    dryad: ""
  preprint: "https://ecoevorxiv.org/repository/view/11155/"
  supplementary_material: "https://doi.org/10.1088/1748-9326/ae803f/data1"

  news:
    university_story: "https://www.swansea.ac.uk/press-office/news-events/news/2026/06/not-all-green-space-is-equal-new-framework-highlights-overlooked-ecological-factors-in-nature-prescribing.php"
    medical_Xpress: "https://medicalxpress.com/news/2026-06-green-space-equal-framework-highlights.html"
    news_source_2: ""

  media:
    podcast: ""
    video: ""

  teaching:
    lecture_notes: ""
    discussion_guide: ""

# =======
# Image
# =======

# Relative image path.
image: "/images/images_publications/One-Health-Sustainability-Framework_Wells-2026.png"

image_alt: >-
  Conceptual One Health Sustainability framework linking human health and
  wellbeing, ecological integrity, biodiversity-mediated nature exposure,
  environmental pressures and sustainability feedbacks.

# Image caption  
image_caption: >-
  One Health Sustainability framework for ecologically mediated
  nature-based wellbeing.
  
image_license: "CC BY 4.0"
image_credit: "Konstans Wells et al. (2026)"
image_license_verified: true  
  

# =======
# BAHE display controls
# =======

featured: true
show_on_publications_page: true
show_on_homepage: true

order: 20260630

# =======
# Knowledge statements
# =======

# Purpose: Canonical knowledge statements represented from the publication.
#
# Each statement represents a complete, stand-alone unit of scientific knowledge that can be indexed, searched, classified and linked within knowledge network.
# Statements may describe empirical results, evidence syntheses, conceptual propositions, theoretical ideas, framework components,
# methodological contributions, recommendations or identified knowledge gaps.
# Item fields:
# id
#   Purpose: Locally unique statement identifier.
#   Format: statement-NN
# text
#   Purpose: Complete stand-alone scientific statement.
#
# knowledge_type
#   Purpose: Semantic classification of the knowledge statement.
#   Values:
#      empirical-result
#      simulation-based-result
#      evidence-synthesis
#      conceptual-proposition
#      theoretical-proposition
#      framework-component
#      methodological-proposition
#      hypothesis
#      interpretation
#      recommendation
#      policy-implication
#      knowledge-gap
# attributed_to
#   Purpose: Provenance of the statement.
#   Values: source-publication, cited-publication, author

knowledge_statements:
  - id: statement-01
    text: >
      Nature-based wellbeing should be understood as an emergent property of coupled socio-ecological systems rather than as a simple consequence of human exposure to nature.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-02
    text: >
      Ecological integrity, biodiversity and ecosystem functioning are fundamental determinants of nature-based wellbeing but remain largely unmeasured in current nature-health research.
    knowledge_type: evidence-synthesis
    attributed_to: source-publication

  - id: statement-03
    text: >
      Sustainable nature-based wellbeing requires balancing human health benefits with the ecological capacity of ecosystems, recognising that increasing nature use can undermine the ecological conditions supporting those benefits.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-04
    text: >
      A One Health Sustainability framework provides an integrated approach for evaluating human wellbeing, ecological integrity, environmental pressures, restoration, equity and governance within a common socio-ecological system.
    knowledge_type: framework-component
    attributed_to: source-publication

  - id: statement-05
    text: >
      Current evidence is dominated by anthropocentric exposure metrics such as greenness, proximity and visitation, limiting understanding of how ecological quality influences human wellbeing.
    knowledge_type: evidence-synthesis
    attributed_to: source-publication

  - id: statement-06
    text: >
      Integrating ecological and human health indicators within a common One Health Sustainability framework enables evidence-based planning, implementation and long-term evaluation of nature-based wellbeing interventions.
    knowledge_type: recommendation
    attributed_to: source-publication

  - id: statement-07
    text: >
      Understanding biodiversity-mediated pathways linking ecosystems to human wellbeing is essential both for identifying the ecological conditions that maximise nature-based health benefits and for evaluating the long-term sustainability of those benefits.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication


# =======
# Summaries
# =======

# Purpose:
# Multi-level summaries for different audiences and knowledge-management tasks.
# summary
#   Purpose: Concise scientific overview of the publication.
# knowledge_summary
#   Purpose: Scientific significance and contribution to knowledge.
# impact_statement
#   Purpose: Primary scientific or policy significance in one or two sentences.
# plain_language_summary
#   Purpose: Accessible summary for non-specialist audiences.

# Concise publication summary.
summary: >
  This topical review synthesises evidence from 54 influential studies and
  proposes a One Health Sustainability framework linking nature-based
  wellbeing to ecological integrity, biodiversity-mediated exposure,
  environmental pressures, restoration, equity and long-term
  socio-ecological resilience.

# Knowledge-network summary.
knowledge_summary: >
  The paper moves nature-health research beyond broad measures of greenness,
  proximity and visit frequency by treating wellbeing benefits as outcomes
  of coupled human-nature systems. It argues that ecological quality,
  biodiversity and ecosystem functioning may shape exposure efficiency,
  while rising demand for nature-based interventions can generate pressures
  that erode the ecological conditions supporting health benefits. The
  framework therefore links human wellbeing, ecological integrity,
  environmental costs, restoration and equity within a common one health
  sustainability perspective.

# Scientific or societal significance.
impact_statement: >
  The framework provides a basis for designing research, monitoring and
  policy that evaluate not only whether nature exposure benefits health, but
  also under which ecological conditions those benefits remain effective,
  equitable and sustainable over time.

# Non-technical summary.  
plain_language_summary: >-
  Contact with nature can support health and wellbeing, but these benefits do
  not depend only on how much green or blue space is available. They may also
  depend on biodiversity, habitat quality, ecosystem functioning and the
  environmental pressures created by increasing human use. This review
  proposes a framework for evaluating human-health benefits together with
  ecological integrity, restoration, equity and long-term sustainability.  
  
# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - nature-society-sustainable-futures
  - ecological-interactions-system-dynamics
  - biodiversity-global-change


# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - nature-based-wellbeing
  - one-health-sustainability
  - human-nature-interactions
  - ecological-integrity
  - biodiversity-mediated-exposure
  - exposure-response-relationships
  - exposure-efficiency
  - socio-ecological-resilience
  - environmental-pressure-feedbacks
  - nature-based-solutions
  - equitable-access-to-nature
  - ecological-sustainability
  - nature-prescribing

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - nature-based-wellbeing
  - one-health-sustainability
  - ecological-integrity
  - biodiversity-mediated-exposure
  - socio-ecological-resilience
  - equitable-access-to-nature

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - coupled-human-nature-systems
  - nature-based-wellbeing-interventions
  - urban-and-human-modified-environments
  - green-and-blue-space-exposure

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - homo-sapiens

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - targeted-evidence-synthesis
  - structured-literature-search
  - citation-rate-prioritisation
  - ai-assisted-data-extraction
  - manual-data-verification
  - cross-domain-taxonomy-synthesis
  - conceptual-framework-development
  - indicator-framework-development

# Input environmental database/ data sources
data_products: []

# Data produced or archived by this study  
research_datasets:
  - zenodo-18891399  

projects:
  - one-health-nature-based-wellbeing

# =======
# Typed graph relationships
# =======

# Purpose: Explicit knowledge graph relationships.
relationships:
  - predicate: authored_by
    object_type: person
    object_id: konstans-wells

  - predicate: authored_by
    object_type: person
    object_id: menna-brown

  - predicate: authored_by
    object_type: organisation
    object_id: swansea-university

  - predicate: authored_by
    object_type: organisation
    object_id: bayreuth-university

  - predicate: produces
    object_type: dataset
    object_id: zenodo-18891399

  - predicate: contributes_to
    object_type: project
    object_id: one-health-nature-based-wellbeing

  - predicate: addresses
    object_type: concept
    object_id: nature-based-wellbeing

  - predicate: addresses
    object_type: concept
    object_id: ecological-integrity

  - predicate: addresses
    object_type: concept
    object_id: one-health-sustainability

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - one-health
  - nature-based-wellbeing
  - biodiversity-and-human-health
  - socio-ecological-systems
  - environmental-health
  - sustainability-assessment
  - evidence-synthesis
  - nature-based-solutions

# Purpose: Suggested discussion questions.
discussion_questions:
  - "How should ecological integrity be measured when evaluating the health effects of nature exposure?"
  - "When does nature exposure become ecologically unsustainable or self-limiting?"
  - "How can exposure-response relationships incorporate biodiversity, habitat condition and ecosystem functioning rather than only greenness or proximity?"
  - "Which indicators are most suitable for integrating human wellbeing, ecological pressure, restoration and equity in a common assessment?"
  - "How should positive health pathways be balanced against ecological hazards such as allergens, pathogens and vector-borne disease risk?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "One Health Sustainability Framework for Nature-Based Wellbeing | Wells et al. 2026"

# Purpose: Search description.
seo_description: >-
  Topical review by Konstans Wells and colleagues proposing a One Health
  Sustainability framework linking nature-based wellbeing, biodiversity,
  ecological integrity, environmental pressures and equitable long-term
  health benefits.

# Purpose: Search keywords.
keywords:
  - One Health
  - One Health sustainability
  - nature-based wellbeing
  - nature-based health
  - ecological integrity
  - biodiversity and human health
  - biodiversity-mediated exposure
  - nature prescribing
  - nature-based solutions
  - green space
  - blue space
  - exposure-response relationships
  - socio-ecological resilience
  - environmental pressures
  - equitable access to nature
  - ecosystem restoration
  - sustainability assessment

# Purpose: Social sharing metadata.
social:
  title: "One Health Sustainability Framework for Nature-Based Wellbeing"
  description: >-
    Konstans Wells and colleagues propose a framework linking nature-based wellbeing
    with biodiversity, ecological integrity, environmental pressures, equity
    and long-term sustainability.
  image: "images/images_publications/One-Health-Sustainability-Framework_Wells-2026.png"
  card: summary_large_image


# =======
# Attribution and reuse
# =======

# Purpose: Attribution guidance.
attribution_note: >
  This BAHE knowledge object summarises and contextualises the peer-reviewed
  publication for research, teaching and interdisciplinary synthesis.
  Scientific arguments and findings should be attributed to and cited from
  the original publication.

# Purpose: Reuse guidance.
license_note: >
  The article is published under the Creative Commons Attribution 4.0
  licence. Reuse must preserve attribution to the authors, article title,
  journal citation and DOI.

# =======
# Provenance and curation
# =======

# Purpose: Editorial review metadata.
curation:
  # Purpose: curation status. # Values: unreviewed, in-review, reviewed, revision-required
  status: reviewed
  reviewed_by: konstans-wells
  reviewed_on: 2026-07-18

# Purpose: Source provenance.
provenance:
  # Purpose: Original source type. # Values: publisher-pdf, publisher-html, repository, author, 
  source_type:
    - publisher-pdf
    - author
    
  # Purpose: Original source URL.
  source_url: "https://doi.org/10.1088/1748-9326/ae803f"

  # Purpose: AI assistance metadata.
  ai_assistance:
    system: ChatGPT
    roles:
      - metadata-extraction
      - draft-summary
      - concept-classification
    outputs_human_verified: true

  confidence:
    bibliographic_metadata: verified
    claims: verified
    summaries: verified
    concept_classification: reviewed

---

