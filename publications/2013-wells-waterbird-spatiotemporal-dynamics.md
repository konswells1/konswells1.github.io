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
id: 2013-wells-waterbird-spatiotemporal-dynamics

# Purpose: Official publication title.
title: "Spatio-temporal dynamics in waterbirds during the non-breeding season: Effects of local movements, migration and weather are monthly, not yearly"

# Purpose: Short display title.
short_title: "Monthly drivers of non-breeding waterbird dynamics"

# Purpose: BAHE object class.
# Values: publication
object_type: publication

# Purpose: Publication category.
# Values: research-article, review, methods, perspective, commentary
publication_type: research-article

# Purpose: Publication subtype.
# Values: empirical-study, systematic-review, scoping-review, topical-review, meta-analysis, simulation-study, conceptual-framework, protocol
publication_subtype: empirical-study

# Purpose: Publication workflow status.
# Values: draft, submitted, accepted, published, archived
status: published

# Purpose: Publication year. # Format: YYYY
year_published: 2013

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2013-08-06

# Purpose: BAHE object creation date. # Format: YYYY-MM-DD
date_created: 2026-07-26

# Purpose: BAHE object modification date.
# Format: YYYY-MM-DD
date_modified: 2026-07-26

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
  - "Konstans Wells"
  - "Thomas Dolich"
  - "Johannes Wahl"
  - "Robert Brian O’Hara"

# Purpose: Canonical BAHE author ids.
bahe_authors:
  - konstans-wells

# Purpose: Structured author metadata.
author_entities:
  # Author position.
  - position: 1
    # Purpose: Full author name.
    name: "Konstans Wells"
    # Purpose: Canonical BAHE person id.
    person_id: konstans-wells
    # Purpose: ORCID identifier.
    orcid: "0000-0003-0377-2463"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - biodiversity-and-climate-research-centre
  # Author position.
  - position: 2
    # Purpose: Full author name.
    name: "Thomas Dolich"
    # Purpose: Canonical BAHE person id.
    person_id: ""
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids: []
  # Author position.
  - position: 3
    # Purpose: Full author name.
    name: "Johannes Wahl"
    # Purpose: Canonical BAHE person id.
    person_id: ""
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids: []
  # Author position.
  - position: 4
    # Purpose: Full author name.
    name: "Robert Brian O’Hara"
    # Purpose: Canonical BAHE person id.
    person_id: ""
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids: []

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions: {}

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "State of Hesse LOEWE programme"
    # Purpose: Canonical funder identifier.
    funder_id: ""
    # Purpose: Grant identifier.
    grant_number: ""
    # Purpose: Official grant title.
    grant_title: "Biodiversity and Climate Research Centre (BiK-F)"

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Basic and Applied Ecology"

# Purpose: Journal volume.
volume: "14"

# Purpose: Journal issue.
issue: "7"

# Purpose: Article pages or article number.
pages: "523–531"

# Purpose: Publisher.
publisher: "Elsevier GmbH"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Dolich, T., Wahl, J., & O’Hara, R. B. (2013).
  Spatio-temporal dynamics in waterbirds during the non-breeding season:
  Effects of local movements, migration and weather are monthly, not yearly.
  Basic and Applied Ecology, 14(7), 523–531.
  https://doi.org/10.1016/j.baae.2013.07.001

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2013), Basic and Applied Ecology, 14(7), 523–531.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1016/j.baae.2013.07.001"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1016/j.baae.2013.07.001"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.
  arxiv: ""

  # Purpose: OpenAlex identifier.
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1016/j.baae.2013.07.001"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Predicting population sizes and dynamics of mobile organisms is important for trend estimation, but this is difficult when the origin of individuals cannot be determined, i.e. residents and migrants are indistinguishable in the field. Here we examine fluctuations in populations during the non-breeding season (autumn to spring) of seven waterbird species, which co-occur on 122 neighbouring water bodies in south-west Germany. We asked whether site-level abundance patterns can be predicted by weather variables, and whether these effects vary over months and years. We used a spatially explicit hidden Markov model to estimate the effects of local and regional movement on population fluctuations. Although the species varied in their dynamics, with different amounts of movement estimated between sites, several patterns were common across species: density effects were highly month-specific, but with little variation in the strength of effects over years. The abundance of most species was positively related to temperature, especially in winter. The common teal Anas crecca and common pochard Aythya ferina were the most site-fidelic species once they were present in the study area, but also exhibited the strongest regional migration. The mallard Anas platyrhynchos, tufted duck Aythya fuligula and great crested grebe Podiceps cristatus each behaved more like a single population, as individuals more frequently moved between sites and abundance fluctuations at sites were not explained by migratory movements alone. Our study shows that the strength of population parameters and environmental forces can be decomposed into monthly and yearly effects. Estimating the unknown origin and movement of individuals may show that commensurate populations of mobile species may have different underlying dynamics, while responding similarly to environmental factors.

# Purpose: Source of abstract. # Values: publisher, author-manuscript
abstract_source: publisher

# Purpose: Indicates verbatim reproduction of original published abstract. # Values: true, false
abstract_verbatim: true

# Purpose: Display publicly. # Values: true, false
abstract_public_display: false

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
  supplementary_material: "https://doi.org/10.1016/j.baae.2013.07.001"

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
image: ""

image_alt: >-
  ""

# Image caption
image_caption: >-
  ""

image_license: ""
image_credit: ""
image_license_verified: false

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20130806

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
      A spatially explicit hidden Markov model separated site persistence,
      movement among neighbouring water bodies and migration to or from a
      regional population pool using counts of unmarked waterbirds.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-02
    text: >
      Across seven waterbird species monitored at 122 sites, abundance in the
      preceding month explained approximately 12%–47% of variation in regional
      abundance fluctuations.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Variation in site-specific density effects was substantially greater
      among months than among years for all seven species.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Movements among adjacent surveyed sites explained little modelled
      variation, whereas site persistence and migration to or from the wider
      population pool differed strongly among species.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Common teal and common pochard showed the strongest site fidelity after
      arrival but also the strongest regional migration.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Mallard, tufted duck and great crested grebe behaved more like integrated
      regional populations because individuals moved more frequently among
      sites and local abundance was less dependent on regional migration alone.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-07
    text: >
      Abundance increased with warmer January or February temperatures for all
      species, while the strength of temperature effects varied mainly among
      months rather than among years.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Population monitoring of mobile species should represent movement and
      environmental drivers at monthly or similarly fine temporal scales rather
      than relying only on annual trends.
    knowledge_type: recommendation
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
  This study analysed 25 years of non-breeding-season counts for seven
  waterbird species across 122 water bodies in south-west Germany using a
  spatially explicit hierarchical Bayesian hidden Markov model.

# Knowledge-network summary.
knowledge_summary: >
  The model decomposed observed abundance into persistence at the same site,
  movement among neighbouring sites and migration to or from a wider regional
  pool. Species differed markedly in mobility and site fidelity, but the
  strongest temporal structure was consistently monthly rather than annual.
  Winter temperature influenced abundance across species, demonstrating that
  short-term weather and movement processes can dominate local count dynamics.

# Scientific or societal significance.
impact_statement: >
  Reliable trend assessment for mobile waterbirds requires monitoring and
  modelling frameworks that distinguish local persistence, regional movement
  and migration at within-season temporal scales.

# Non-technical summary.
plain_language_summary: >-
  Waterbird numbers at a lake can change because birds stay, move to nearby
  lakes or migrate into and out of the region. Using 25 years of monthly
  counts, the study found that these processes differed among seven species,
  but changed much more from month to month than from year to year. Warmer
  winter temperatures were generally linked to higher local abundance.

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - biodiversity-global-change
  - ecological-interactions-system-dynamics

# Purpose: Canonical concepts. # Values: concept ids
concepts: []

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts: []

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems: []

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: []

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods: []

# Input environmental database/ data sources
data_products:
  - international-waterbird-census
  - german-weather-service-gridded-climate-data

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

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses: []

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why are residents and migrants difficult to distinguish in repeated counts of unmarked waterbirds?"
  - "How does a hidden Markov model represent latent movement states from count data?"
  - "Why might weather effects be strong in particular winter months but weak when averaged annually?"
  - "What ecological mechanisms could produce high site fidelity together with strong regional migration?"
  - "How should waterbird monitoring programmes balance spatial coverage, monthly sampling and long-term continuity?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Monthly Drivers of Non-Breeding Waterbird Dynamics | Wells et al. 2013"

# Purpose: Search description.
seo_description: >-
  Hidden Markov analysis of 25 years of waterbird counts showing that local
  movement, migration and weather effects vary mainly among months, not years.

# Purpose: Search keywords.
keywords:
  - waterbirds
  - non-breeding season
  - bird monitoring
  - migration
  - site fidelity
  - local movement
  - hidden Markov model
  - hierarchical Bayesian model
  - monthly dynamics
  - weather effects
  - temperature
  - lake ecosystems
  - population networks
  - metapopulation dynamics
  - International Waterbird Census
  - Rhineland-Palatinate
  - Germany

# Purpose: Social sharing metadata.
social:
  title: "Waterbird Movement and Weather Effects Are Monthly, Not Yearly"
  description: >-
    Long-term counts reveal species-specific movement strategies and strong
    within-season variation in waterbird abundance across 122 German wetlands.
  image: ""
  card: summary_large_image

# =======
# Attribution and reuse
# =======

# Purpose: Attribution guidance.
attribution_note: >
  This BAHE knowledge object summarises and contextualises the peer-reviewed
  publication for research, teaching and interdisciplinary synthesis.
  Scientific arguments, methods and findings should be attributed to and cited
  from the original publication.

# Purpose: Reuse guidance.
license_note: >
  The article was published by Gesellschaft für Ökologie and Elsevier GmbH
  with all rights reserved. Public availability does not establish permission
  to reproduce the abstract, figures, tables or supplementary material. BAHE
  annotations and separately credited media may have distinct reuse conditions.

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
  source_url: "https://doi.org/10.1016/j.baae.2013.07.001"

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
    claims: unreviewed
    summaries: unreviewed
    concept_classification: unreviewed


---

