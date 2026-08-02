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
id: 2013-wells-individual-interaction-strength-networks

# Purpose: Official publication title.
title: "Species interactions: estimating per-individual interaction strength and covariates before simplifying data into per-species ecological networks"

# Purpose: Short display title.
short_title: "Per-individual interaction strength in ecological networks"

# Purpose: BAHE object class.
# Values: publication
object_type: publication

# Purpose: Publication category.
# Values: research-article, review, methods, perspective, commentary
publication_type: methods

# Purpose: Publication subtype.
# Values: empirical-study, systematic-review, scoping-review, topical-review, meta-analysis, simulation-study, conceptual-framework, protocol
publication_subtype: simulation-study

# Purpose: Publication workflow status.
# Values: draft, submitted, accepted, published, archived
status: published

# Purpose: Publication year. # Format: YYYY
year_published: 2013

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2013-01-01

# Purpose: BAHE object creation date. # Format: YYYY-MM-DD
date_created: 2026-07-25

# Purpose: BAHE object modification date.
# Format: YYYY-MM-DD
date_modified: 2026-07-25

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
- Robert B. O’Hara

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
      - biodiversity-and-climate-research-centre
      - university-of-ulm

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Robert B. O’Hara"
    # Purpose: Canonical BAHE person id.
    person_id: robert-b-ohara
    # Purpose: ORCID identifier.
    orcid: "0000-0001-9737-3724"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - biodiversity-and-climate-research-centre

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  konstans-wells:
    - conceptualization
    - methodology
    - software
    - formal-analysis
    - visualization
    - writing-original-draft
    - writing-review-editing

  robert-b-ohara:
    - conceptualization
    - methodology
    - formal-analysis
    - supervision
    - interpretation
    - writing-review-editing

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "Landesoffensive zur Entwicklung wissenschaftlich-ökonomischer Exzellenz"
    # Purpose: Canonical funder identifier.
    funder_id: loewe-hesse
    # Purpose: Grant identifier.
    grant_number: ""
    # Purpose: Official grant title.
    grant_title: "Biodiversity and Climate Research Centre"

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Methods in Ecology and Evolution"

# Purpose: Journal volume.
volume: "4"

# Purpose: Journal issue.
issue: "1"

# Purpose: Article pages or article number.
pages: "1-8"

# Purpose: Publisher.
publisher: "Wiley"

# Purpose: Open-access availability. # Values: true, false
open_access: true

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "CC BY 4.0"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., & O’Hara, R. B. (2013). Species interactions: estimating
  per-individual interaction strength and covariates before simplifying data
  into per-species ecological networks. Methods in Ecology and Evolution,
  4(1), 1-8. https://doi.org/10.1111/j.2041-210x.2012.00249.x

# Purpose: Short citation.
citation_short: >-
  Wells and O’Hara (2013), Methods in Ecology and Evolution, 4(1), 1-8.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1111/j.2041-210x.2012.00249.x"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1111/j.2041-210x.2012.00249.x"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1111/j.2041-210x.2012.00249.x"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  1. Ecological network models based on aggregated data from species interactions are widely used to make inferences about species specialization, functionality and extinction risk. While increasing number of network data are available and are used in comparative studies, data quality and uncertainty have received little attention. Moreover, key individual-level information such as the proportion of individuals not involved in interactions and underlying processes driving interactions are ignored by aggregated data analysis.
  2. We suggest an individual-level hierarchical interaction model as a more flexible approach to considering uncertainty, sampling effort and conditions under which interactions take place and from which network attributes can be derived. We performed a simulation exercise to compare inference under different sample sizes and from aggregated data matrices to those from our individual-level model.
  3. Formalizing the process of network formation in an individual-level model made clear that per-species interaction frequencies are not independent of sample size and population pools and also ignore important information given by the proportion of non-interacting individuals. Hierarchical linear models are a possible solution to infer community-level attributes of network formation and allow various kinds of comprehensive model extensions to capture variation of per-individual interactions in space and time that shape upper level organization.
  4. Individual-level hierarchical models provide the link between individual behaviour and interactions under variable environmental conditions and can be summarized into networks in a conceptually neat way. Such models may not only help to account for various sources of variation but also conceptualize aspects overlooked in aggregated data. In particular, the quantification of per-individual interactions under different sampling scenarios emphasizes that per-species interaction frequencies at the species level are not necessarily a surrogate of species abundance in natural systems under investigation.

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
    zenodo: ""
    figshare: ""
    dryad: ""
  preprint: ""
  supplementary_material: "https://doi.org/10.1111/j.2041-210x.2012.00249.x"

  news:
    university_story: ""
    medical_Xpress: ""
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
image: "/images/images_publications/Individual-interaction-strength-networks_Wells-2013.png"

image_alt: >-
  Conceptual comparison between individual-level observations and aggregated
  ecological networks, showing resource and consumer individuals, observed
  interactions, non-interacting individuals and the loss of sampling and
  abundance information when observations are simplified into a
  species-level adjacency matrix.

# Image caption  
image_caption: >-
  Conceptual framework linking per-individual interactions to species-level
  ecological networks. Individual resource and consumer observations retain
  information about sampling effort, species abundance, interaction rates and
  zero encounters, whereas aggregation into a species-level network can make
  differently sampled species appear to have similar interaction strength.

image_license: "CC BY 4.0"
image_credit: "Wells and O’Hara (2013)"
image_license_verified: true  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20130101

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
      Species-level interaction frequencies in ecological networks combine per-individual interaction strength with the numbers of sampled or available individuals and therefore cannot be interpreted independently of abundance and sampling effort.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-02
    text: >
      Aggregating individual observations into species-level adjacency matrices discards information about non-interacting individuals, observation effort and environmental conditions.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-03
    text: >
      Small sample sizes caused the network-level specialization index H2 to be overestimated when calculated directly from aggregated interaction data.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      With equal sampling, aggregated estimates of network specialization approached the exhaustive-sampling value only when approximately 15 or more individuals per species were sampled.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Unequal sample sizes among species produced increasingly biased estimates of network specialization from aggregated data even when total sample size increased.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Individual-level hierarchical models estimated per-species interaction strengths close to their generating values even under small sample sizes, while explicitly representing uncertainty.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Individual-level models distinguished true absence of interaction from false zero observations through a species-pair interaction indicator.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-08
    text: >
      Estimates of network specialization derived from the individual-level model were robust to heterogeneous sample sizes and improved as sample size increased.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-09
    text: >
      Per-individual interaction strength should be separated from per-species interaction frequency because the latter is inevitably influenced by species abundance.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-10
    text: >
      Hierarchical interaction models can incorporate individual traits, species attributes, environmental covariates, detection error and temporal or spatial variation before network metrics are calculated.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-11
    text: >
      Ecological network databases should retain individual-level observations and detailed sampling protocols rather than storing only aggregated interaction matrices.
    knowledge_type: recommendation
    attributed_to: source-publication

  - id: statement-12
    text: >
      Comparative network studies risk ecological fallacies when differences created by sampling design are interpreted as biological differences among species or communities.
    knowledge_type: interpretation
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
  This methods study developed a hierarchical model for estimating
  per-individual ecological interaction strength before aggregating results
  into species-level networks. Simulations compared inference under equal and
  unequal sample sizes using aggregated matrices and model-based estimates.

# Knowledge-network summary.
knowledge_summary: >
  The paper formalises ecological network formation as a hierarchy linking
  individual behaviour, species abundance and community-level network
  structure. It shows that aggregated interaction frequencies confound
  biological interaction strength with sample size and population pools,
  whereas individual-level models preserve zero encounters, estimate
  uncertainty and accommodate environmental covariates and detection effects.

# Scientific or societal significance.
impact_statement: >
  Ecological network analyses become more reliable when interaction strength,
  abundance, sampling effort and false zero observations are modelled before
  species-level network metrics are calculated.

# Non-technical summary.  
plain_language_summary: >-
  Ecological networks are usually built by adding together all observed
  interactions between species. This can be misleading because frequently
  sampled or abundant species appear to interact more strongly. Modelling
  interactions between individuals first allows researchers to separate real
  biological preferences from differences in sample size and abundance.  

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - quantitative-ecology-modelling
  - ecological-interactions-system-dynamics
  - biodiversity-global-change

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - ecological-networks
  - per-individual-interaction-strength
  - per-species-interaction-frequency
  - sampling-bias
  - species-abundance
  - hierarchical-interaction-models
  - false-zero-interactions
  - zero-inflation
  - network-specialization
  - ecological-fallacy
  - observation-process
  - interaction-detection
  - individual-heterogeneity
  - environmental-covariates
  - uncertainty-propagation

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - ecological-networks
  - per-individual-interaction-strength
  - sampling-bias
  - hierarchical-interaction-models
  - false-zero-interactions
  - network-specialization

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - simulated-consumer-resource-network
  - bipartite-ecological-networks
  - individual-to-community-interaction-hierarchy

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: []

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - hierarchical-bayesian-modelling
  - individual-level-interaction-modelling
  - poisson-regression
  - log-linear-modelling
  - zero-inflated-modelling
  - markov-chain-monte-carlo
  - gibbs-sampling
  - simulation-modelling
  - posterior-predictive-simulation
  - network-specialization-analysis
  - kullback-leibler-specialisation
  - sensitivity-analysis

# Input environmental database/ data sources
data_products:
  - simulated-consumer-resource-interaction-data

# Data produced or archived by this study  
research_datasets: []

projects: []

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
    object_id: robert-b-ohara

  - predicate: authored_by
    object_type: organisation
    object_id: biodiversity-and-climate-research-centre

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-ulm

  - predicate: addresses
    object_type: concept
    object_id: ecological-networks

  - predicate: addresses
    object_type: concept
    object_id: per-individual-interaction-strength

  - predicate: addresses
    object_type: concept
    object_id: sampling-bias

  - predicate: addresses
    object_type: concept
    object_id: false-zero-interactions

  - predicate: addresses
    object_type: concept
    object_id: network-specialization

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - ecological-network-analysis
  - quantitative-ecology
  - hierarchical-modelling
  - sampling-theory
  - statistical-ecology
  - simulation-modelling
  - community-ecology
  - zero-inflated-models
  - research-design

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why is per-species interaction frequency not equivalent to per-individual interaction strength?"
  - "What information is lost when individual interaction records are aggregated into an adjacency matrix?"
  - "How do unequal sample sizes bias estimates of ecological network specialization?"
  - "Why are zero observations informative in interaction studies?"
  - "How can hierarchical models incorporate environmental covariates and individual heterogeneity?"
  - "What minimum data should ecological network repositories preserve to support robust comparative analysis?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Per-Individual Interaction Strength in Ecological Networks | Wells & O’Hara 2013"

# Purpose: Search description.
seo_description: >-
  Methods study showing how individual-level hierarchical models separate
  interaction strength from species abundance, sampling bias and false zeros
  before ecological networks are constructed.

# Purpose: Search keywords.
keywords:
  - ecological networks
  - interaction strength
  - individual-level model
  - species-level interaction frequency
  - sampling bias
  - species abundance
  - hierarchical Bayesian model
  - false zeros
  - zero inflation
  - network specialization
  - H2 index
  - ecological fallacy
  - consumer–resource interactions
  - Poisson model
  - interaction detection
  - network inference
  - quantitative ecology

# Purpose: Social sharing metadata.
social:
  title: "Per-Individual Interaction Strength in Ecological Networks"
  description: >-
    Wells and O’Hara show why ecological interactions should be modelled at
    the individual level before being simplified into species networks.
  image: "images/images_publications/Individual-interaction-strength-networks_Wells-2013.png"
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
  The article is published under the Creative Commons Attribution licence.
  Reuse must preserve attribution to the authors, article title, journal
  citation and DOI.

# =======
# Provenance and curation
# =======

# Purpose: Editorial review metadata.
curation:
  # Purpose: curation status. # Values: unreviewed, in-review, reviewed, revision-required
  status: unreviewed
  reviewed_by: ""
  reviewed_on: ""

# Purpose: Source provenance.
provenance:
  # Purpose: Original source type. # Values: publisher-pdf, publisher-html, repository, author, 
  source_type:
    - publisher-pdf

  # Purpose: Original source URL.
  source_url: "https://doi.org/10.1111/j.2041-210x.2012.00249.x"

  # Purpose: AI assistance metadata.
  ai_assistance:
    system: ChatGPT
    roles:
      - metadata-extraction
      - draft-summary
      - concept-classification
    outputs_human_verified: false

  confidence:
    bibliographic_metadata: verified
    claims: needs-verification
    summaries: needs-verification
    concept_classification: unreviewed

---
