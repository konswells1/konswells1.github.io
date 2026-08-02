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
id: 2016-lurgi-landscape-invasive-species-management

# Purpose: Official publication title.
title: "A Landscape Approach to Invasive Species Management"

# Purpose: Short display title.
short_title: "Landscape-scale invasive species management"

# Purpose: BAHE object class.
# Values: publication
object_type: publication

# Purpose: Publication category.
# Values: research-article, review, methods, perspective, commentary
publication_type: research-article

# Purpose: Publication subtype.
# Values: empirical-study, systematic-review, scoping-review, topical-review, meta-analysis, simulation-study, conceptual-framework, protocol
publication_subtype: simulation-study

# Purpose: Publication workflow status.
# Values: draft, submitted, accepted, published, archived
status: published

# Purpose: Publication year. # Format: YYYY
year_published: 2016

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2016-07-29

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
- Miguel Lurgi
- Konstans Wells
- Malcolm Kennedy
- Susan Campbell
- Damien A. Fordham

# Purpose: Canonical BAHE author ids.
bahe_authors:
  - konstans-wells

# Purpose: Structured author metadata.
author_entities:
  # Purpose: Citation order.
  - position: 1
    # Purpose: Full author name.
    name: "Miguel Lurgi"
    # Purpose: Canonical BAHE person id.
    person_id: miguel-lurgi
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated canonical organisation objects.
    affiliation_ids:
      - university-of-adelaide

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Konstans Wells"
    # Purpose: Canonical BAHE person id.
    person_id: konstans-wells
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-adelaide
      - griffith-university

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Malcolm Kennedy"
    # Purpose: Canonical BAHE person id.
    person_id: malcolm-kennedy
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - department-of-agriculture-and-food-western-australia

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "Susan Campbell"
    # Purpose: Canonical BAHE person id.
    person_id: susan-campbell
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - department-of-agriculture-and-food-western-australia

  # Auhor position.
  - position: 5
    # Purpose: Full author name.
    name: "Damien A. Fordham"
    # Purpose: Canonical BAHE person id.
    person_id: damien-a-fordham
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-adelaide

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  miguel-lurgi:
    - conceptualization
    - methodology
    - software
    - formal-analysis
    - visualization
    - writing-original-draft
    - writing-review-editing

  konstans-wells:
    - conceptualization
    - methodology
    - interpretation
    - writing-review-editing

  malcolm-kennedy:
    - resources
    - ecological-interpretation
    - writing-review-editing

  susan-campbell:
    - resources
    - ecological-interpretation
    - writing-review-editing

  damien-a-fordham:
    - conceptualization
    - methodology
    - supervision
    - funding-acquisition
    - interpretation
    - writing-review-editing

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "Australian Research Council"
    # Purpose: Canonical funder identifier.
    funder_id: australian-research-council
    # Purpose: Grant identifier.
    grant_number: "LP110200805"
    # Purpose: Official grant title.
    grant_title: "Linkage Project"

  - funder_name: "Australian Research Council"
    funder_id: australian-research-council
    grant_number: "FT140101192"
    grant_title: "Future Fellowship"

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "PLOS ONE"

# Purpose: Journal volume.
volume: "11"

# Purpose: Journal issue.
issue: "7"

# Purpose: Article pages or article number.
pages: "e0160417"

# Purpose: Publisher.
publisher: "Public Library of Science"

# Purpose: Open-access availability. # Values: true, false
open_access: true

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "CC BY 4.0"

# Purpose: Complete citation.
citation_full: >-
  Lurgi, M., Wells, K., Kennedy, M., Campbell, S., & Fordham, D. A.
  (2016). A Landscape Approach to Invasive Species Management.
  PLOS ONE, 11(7), e0160417.
  https://doi.org/10.1371/journal.pone.0160417

# Purpose: Short citation.
citation_short: >-
  Lurgi et al. (2016), PLOS ONE, 11(7), e0160417.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1371/journal.pone.0160417"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1371/journal.pone.0160417"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1371/journal.pone.0160417"
pdf: "https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0160417&type=printable"

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Biological invasions are not only a major threat to biodiversity, they also have major impacts on local economies and agricultural production systems. Once established, the connection of local populations into metapopulation networks facilitates dispersal at landscape scales, generating spatial dynamics that can impact the outcome of pest-management actions. Much planning goes into landscape-scale invasive species management. However, effective management requires knowledge on the interplay between metapopulation network topology and management actions. We address this knowledge gap using simulation models to explore the effectiveness of two common management strategies, applied across different extents and according to different rules for selecting target localities in metapopulations with different network topologies. These management actions are: (i) general population reduction, and (ii) reduction of an obligate resource. The reduction of an obligate resource was generally more efficient than population reduction for depleting populations at landscape scales. However, the way in which local populations are selected for management is important when the topology of the metapopulation is heterogeneous in terms of the distribution of connections among local populations. We tested these broad findings using real-world scenarios of European rabbits (Oryctolagus cuniculus) infesting agricultural landscapes in Western Australia. Although management strategies targeting central populations were more effective in simulated heterogeneous metapopulation structures, no difference was observed in real-world metapopulation structures that are highly homogeneous. In large metapopulations with high proximity and connectivity of neighbouring populations, different spatial management strategies yield similar outcomes. Directly considering spatial attributes in pest-management actions will be most important for metapopulation networks with heterogeneously distributed links. Our modelling framework provides a simple approach for identifying the best possible management strategy for invasive species based on metapopulation structure and control capacity. This information can be used by managers trying to devise efficient landscape-oriented management strategies for invasive species and can also generate insights for conservation purposes.

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
  code: "https://doi.org/10.1371/journal.pone.0160417.s006"
  data:
    zenodo: ""
    figshare: ""
    dryad: ""
  preprint: ""
  supplementary_material: "https://doi.org/10.1371/journal.pone.0160417"

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
image: "/images/images_publications/Landscape-invasive-species-management_Lurgi-2016.png"

image_alt: >-
  Comparative diagrams of six metapopulation network topologies and simulated
  changes in maximum invasive-species abundance under population reduction and
  obligate-resource reduction. Curves compare random, spatially clustered and
  hub-targeted management strategies across increasing management extent.

# Image caption  
image_caption: >-
  Effects of metapopulation topology and spatial management strategy on
  invasive-species control. The upper row shows star, ring, neighbour,
  ring-random, ring-hub and scale-free networks. Lower panels compare general
  population reduction with reduction of an obligate resource as management
  extent increases. Resource reduction generally produces larger declines,
  while targeting highly connected populations is most beneficial in
  heterogeneous networks.

image_license: "CC BY 4.0"
image_credit: "Lurgi et al. (2016)"
image_license_verified: true  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20160729

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
      Reduction of an obligate resource was generally more effective than direct population removal for lowering invasive-species abundance at landscape scales.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Management extent was the dominant determinant of control success across most simulated invasive-species metapopulations.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Spatially targeting highly connected or neighbouring populations improved control most strongly in metapopulation networks with heterogeneous link distributions.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      In homogeneous and highly connected metapopulations, random, clustered and hub-targeted spatial management strategies produced similar outcomes.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      In model star and scale-free networks, management targeted at central populations reduced metapopulation abundance more effectively than random management.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Reducing carrying capacity by 60% in 90% of local populations decreased simulated metapopulation abundance by up to 50% at intermediate dispersal.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Direct population reduction produced substantial declines only when a large proportion of local populations was managed or dispersal was very low or very high.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      For real-world rabbit landscapes in Western Australia, management extent and intensity were more important than the spatial rule used to select local populations.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-09
    text: >
      Landscape connectivity mediates the value of spatial prioritisation because immigration from connected source populations can rapidly restore locally depleted populations.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-10
    text: >
      Simulation frameworks that integrate demography, dispersal, network topology and management capacity can identify efficient landscape-scale invasive-species control strategies.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-11
    text: >
      Detailed spatial planning should be prioritised for small or heterogeneously connected invasive-species networks, whereas highly homogeneous networks require broad management coverage rather than complex targeting.
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
  This simulation study used demographic metapopulation models to compare
  direct population reduction and obligate-resource reduction across six
  network topologies and ten real-world rabbit landscapes in Western
  Australia. Management extent, intensity, dispersal and spatial targeting
  were varied systematically.

# Knowledge-network summary.
knowledge_summary: >
  The study demonstrates that invasive-species management outcomes emerge
  from interactions among network topology, dispersal and intervention
  design. Resource reduction consistently outperformed direct removal,
  especially when applied broadly. Targeting central populations added value
  in heterogeneous networks, but had little effect in homogeneous,
  highly connected rabbit landscapes where recolonisation pathways were
  widely distributed.

# Scientific or societal significance.
impact_statement: >
  Landscape-scale invasive-species control should match intervention type and
  spatial targeting to metapopulation connectivity, with broad resource
  reduction favoured where feasible.

# Non-technical summary.  
plain_language_summary: >-
  Removing animals from a few places may fail when nearby populations quickly
  replace them. Simulations showed that reducing an essential resource, such
  as shelter, usually lowered invasive populations more effectively than
  repeated animal removal. Targeting central populations helped mainly when
  the population network was unevenly connected.  

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - biodiversity-global-change
  - ecological-interactions-system-dynamics
  - quantitative-ecology-modelling
  - conservation-ecology

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - invasive-species-management
  - landscape-scale-management
  - metapopulation-dynamics
  - network-topology
  - population-connectivity
  - dispersal
  - source-sink-dynamics
  - resource-reduction
  - population-reduction
  - management-extent
  - management-intensity
  - spatial-prioritisation
  - recolonisation
  - pest-management
  - ecological-network-intervention

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - invasive-species-management
  - landscape-scale-management
  - metapopulation-dynamics
  - network-topology
  - resource-reduction
  - spatial-prioritisation

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - western-australian-rabbit-landscapes
  - invasive-species-metapopulation-networks
  - agricultural-landscape-pest-system
  - connected-local-population-networks

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - oryctolagus-cuniculus

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - metapopulation-modelling
  - network-simulation
  - ricker-logistic-growth-modelling
  - dispersal-kernel-modelling
  - stochastic-simulation
  - scenario-analysis
  - boosted-regression-trees
  - local-polynomial-regression
  - linear-modelling
  - spatial-landscape-modelling
  - sensitivity-analysis
  - in-silico-experiments

# Input environmental database/ data sources
data_products:
  - australian-national-vegetation-information-system
  - long-term-australian-rabbit-abundance-data
  - western-australian-land-cover-data

# Data produced or archived by this study  
research_datasets:
  - plos-one-e0160417-supporting-information

projects:
  - landscape-invasive-species-management

# =======
# Typed graph relationships
# =======

# Purpose: Explicit knowledge graph relationships.
relationships:
  - predicate: authored_by
    object_type: person
    object_id: miguel-lurgi

  - predicate: authored_by
    object_type: person
    object_id: konstans-wells

  - predicate: authored_by
    object_type: person
    object_id: malcolm-kennedy

  - predicate: authored_by
    object_type: person
    object_id: susan-campbell

  - predicate: authored_by
    object_type: person
    object_id: damien-a-fordham

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-adelaide

  - predicate: authored_by
    object_type: organisation
    object_id: griffith-university

  - predicate: authored_by
    object_type: organisation
    object_id: department-of-agriculture-and-food-western-australia

  - predicate: uses
    object_type: data-product
    object_id: australian-national-vegetation-information-system

  - predicate: produces
    object_type: dataset
    object_id: plos-one-e0160417-supporting-information

  - predicate: addresses
    object_type: concept
    object_id: invasive-species-management

  - predicate: addresses
    object_type: concept
    object_id: metapopulation-dynamics

  - predicate: addresses
    object_type: concept
    object_id: network-topology

  - predicate: addresses
    object_type: concept
    object_id: resource-reduction

  - predicate: addresses
    object_type: concept
    object_id: spatial-prioritisation

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - invasion-ecology
  - conservation-management
  - metapopulation-ecology
  - ecological-network-analysis
  - spatial-ecology
  - pest-management
  - simulation-modelling
  - landscape-ecology
  - decision-support

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why can reducing an obligate resource outperform repeated removal of individuals?"
  - "How does network topology alter the value of targeting highly connected populations?"
  - "Why do different spatial management strategies converge in highly homogeneous metapopulations?"
  - "How does dispersal both undermine and sometimes enhance population-control outcomes?"
  - "What ecological and ethical constraints limit resource-removal strategies in real landscapes?"
  - "How could this framework be adapted for invasive species with different life histories or dispersal behaviours?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Landscape Approach to Invasive Species Management | Lurgi et al. 2016"

# Purpose: Search description.
seo_description: >-
  Simulation study showing how metapopulation topology, dispersal and
  management extent determine the effectiveness of population and resource
  reduction for invasive species.

# Purpose: Search keywords.
keywords:
  - invasive species management
  - landscape management
  - metapopulation
  - network topology
  - European rabbit
  - Oryctolagus cuniculus
  - resource reduction
  - population reduction
  - dispersal
  - source–sink dynamics
  - spatial prioritisation
  - pest management
  - Western Australia
  - boosted regression trees
  - simulation model
  - recolonisation
  - landscape connectivity
  - ecological networks

# Purpose: Social sharing metadata.
social:
  title: "A Landscape Approach to Invasive Species Management"
  description: >-
    Lurgi and colleagues show how network topology, dispersal and intervention
    extent determine landscape-scale invasive-species control.
  image: "images/images_publications/Landscape-invasive-species-management_Lurgi-2016.png"
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
  status: unreviewed
  reviewed_by: ""
  reviewed_on: ""

# Purpose: Source provenance.
provenance:
  # Purpose: Original source type. # Values: publisher-pdf, publisher-html, repository, author, 
  source_type:
    - publisher-pdf

  # Purpose: Original source URL.
  source_url: "https://doi.org/10.1371/journal.pone.0160417"

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
