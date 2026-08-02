# ============================================================================
# BAHE publication knowledge object

# Replace values only. Preserve field order and structure.
# ============================================================================

# =======
# Publication identity
# =======

# Purpose: Immutable canonical publication identifier.
# Format: yyyy-firstauthor-short-topic. # Rule: Never changes after object creation.
id: 2014-kubiczek-chaffinch-movement-forest-landscapes

# Purpose: Official publication title.
title: "Movement and ranging patterns of the Common Chaffinch in heterogeneous forest landscapes"

# Purpose: Short display title.
short_title: "Chaffinch movement in heterogeneous production forests"

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
year_published: 2014

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2014-06-19

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
  - Katrin Kubiczek
  - Swen C. Renner
  - Stefan M. Böhm
  - Elisabeth K. V. Kalko
  - Konstans Wells

# Purpose: Canonical BAHE author ids.
bahe_authors:
  - konstans-wells

# Purpose: Structured author metadata.
author_entities:
  # Purpose: Citation order.
  - position: 1
    # Purpose: Full author name.
    name: "Katrin Kubiczek"
    # Purpose: Canonical BAHE person id.
    person_id: katrin-kubiczek
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated canonical organisation objects.
    affiliation_ids:
      - ulm-university

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Swen C. Renner"
    # Purpose: Canonical BAHE person id.
    person_id: swen-c-renner
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - ulm-university
      - smithsonian-conservation-biology-institute

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Stefan M. Böhm"
    # Purpose: Canonical BAHE person id.
    person_id: stefan-m-bohm
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - ulm-university

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "Elisabeth K. V. Kalko"
    # Purpose: Canonical BAHE person id.
    person_id: elisabeth-k-v-kalko
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - ulm-university

  # Auhor position.
  - position: 5
    # Purpose: Full author name.
    name: "Konstans Wells"
    # Purpose: Canonical BAHE person id.
    person_id: konstans-wells
    # Purpose: ORCID identifier.
    orcid: "0000-0003-0377-2463"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - ulm-university
      - university-of-adelaide

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  katrin-kubiczek:
    - investigation
    - writing-original-draft
    - visualization
    - writing-review-editing

  swen-c-renner:
    - conceptualization
    - methodology
    - investigation
    - formal-analysis
    - resources
    - software
    - writing-original-draft
    - writing-review-editing

  stefan-m-bohm:
    - investigation
    - writing-review-editing

  elisabeth-k-v-kalko: []

  konstans-wells:
    - conceptualization
    - methodology
    - investigation
    - formal-analysis
    - writing-original-draft
    - visualization
    - writing-review-editing

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "Deutsche Forschungsgemeinschaft"
    # Purpose: Canonical funder identifier.
    funder_id: deutsche-forschungsgemeinschaft
    # Purpose: Grant identifier.
    grant_number: "KA 1241/15-1"
    # Purpose: Official grant title.
    grant_title: "DFG Priority Programme 1374 Biodiversity Exploratories"

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "PeerJ"

# Purpose: Journal volume.
volume: "2"

# Purpose: Journal issue.
issue: ""

# Purpose: Article pages or article number.
pages: "e368"

# Purpose: Publisher.
publisher: "PeerJ"

# Purpose: Open-access availability. # Values: true, false
open_access: true

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "CC BY 4.0"

# Purpose: Complete citation.
citation_full: >-
  Kubiczek, K., Renner, S. C., Böhm, S. M., Kalko, E. K. V., & Wells, K.
  (2014). Movement and ranging patterns of the Common Chaffinch in
  heterogeneous forest landscapes. PeerJ, 2, e368.
  https://doi.org/10.7717/peerj.368

# Purpose: Short citation.
citation_short: >-
  Kubiczek et al. (2014), PeerJ, 2, e368.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.7717/peerj.368"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.7717/peerj.368"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.
  arxiv: ""

  # Purpose: OpenAlex identifier.
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.7717/peerj.368"
pdf: "https://peerj.com/articles/368.pdf"

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  The partitioning of production forests into discretely managed forest stands confronts animals with diversity in forest attributes at scales from point-level tree assemblages to distinct forest patches and range-level forest cover. We have investigated the movement and ranging patterns of male Common Chaffinches, Fringilla coelebs, in heterogeneous forest production landscapes during spring and summer in south-western Germany. We radio-tracked a total of 15 adult males, each for up to six days, recording locations at 10-min intervals. We then performed point-level tree surveys at all tracking locations and classified forest stand attributes for the areal covering of birds’ ranges. Movement distances were shortest in beech forest stands and longer in spruce-mixed and non-spruce conifer stands. Movement distances increased with stand age in beech stands but not in others, an effect that was only detectable in a multilevel hierarchical model. We found negligible effects of point-level tree assemblages and temperature on movement distances. Daily range estimates were from 0.01 to 8.0 hectare (median of 0.86 ha) with no evident impact of forest attributes on ranging patterns but considerable intra-individual variation in range sizes over consecutive days. Most daily ranges covered more than one forest stand type. Our results show that forest management impacts the movement behaviour of chaffinches in heterogeneous production forest. Although point-level effects of movement distances are weak compared with stand-level effects in this study, the hierarchical organization of forest is an important aspect to consider when analysing fine-scale movement and might exert more differentiated effects on bird species that are more sensitive to habitat changes than the chaffinch.

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
    biodiversity_exploratories: "https://exploratories.bgc-jena.mpg.de:444/Login/Account.aspx"
  preprint: ""
  supplementary_material: "https://doi.org/10.7717/peerj.368/supp-1"

  news:
    university_story: ""
    news_source_1: ""
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
  Male Common Chaffinch movement through a heterogeneous production-forest
  landscape composed of differently managed forest stands.

# Image caption
image_caption: >-
  Movement and ranging of Common Chaffinches across heterogeneous forest stands.

image_license: ""
image_credit: ""
image_license_verified: false

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20140619

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
      Movement distances of male Common Chaffinches differed among forest stand
      types, being shortest in beech stands and longer in spruce-mixed and
      non-spruce conifer stands.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Movement distances increased with stand age in beech forest but not in
      other stand types, and this interaction was detectable only when the
      hierarchical organisation of forest attributes was represented in a
      multilevel model.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Point-level tree density, tree-species composition and temperature had
      negligible effects on ten-minute movement distances compared with
      stand-level forest attributes.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Daily range sizes varied from 0.01 to 8.0 hectares, showed substantial
      intra-individual variation and were not evidently related to measured
      forest attributes, temperature or season.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Most daily ranges crossed multiple forest stands, indicating that
      Common Chaffinches routinely use heterogeneous mosaics of managed forest
      during daily activity.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Studies of animal movement in production forests should use analytical
      frameworks that explicitly represent the nesting of local habitat
      attributes within forest stands and should extend comparisons to
      habitat-specialist species.
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
  This empirical study examined fine-scale movement and daily ranging of 15
  adult male Common Chaffinches in heterogeneous production forests of
  south-western Germany. VHF radio telemetry at ten-minute intervals was
  combined with point-level tree surveys, forest-management maps, local
  temperature data, Bayesian multilevel modelling and mixed-effects range
  analysis to evaluate habitat effects across point, stand and range scales.

# Knowledge-network summary.
knowledge_summary: >
  The study shows that stand-level forest composition and its interaction with
  stand age explained chaffinch movement better than local tree assemblages,
  whereas daily range size was dominated by individual temporal variation.
  Its principal methodological contribution is the demonstration that
  scale-dependent habitat effects can be missed unless the hierarchical
  nesting of point-level conditions within forest stands is represented
  explicitly in the statistical model.

# Scientific or societal significance.
impact_statement: >
  Forest management can influence fine-scale bird movement even in a habitat
  generalist, and movement studies should align their analytical hierarchy
  with the spatial hierarchy of managed landscapes.

# Non-technical summary.
plain_language_summary: >-
  Researchers followed 15 male Common Chaffinches through managed forests in
  southern Germany using small radio transmitters. The birds moved shorter
  distances in beech stands than in some conifer-dominated stands, but the
  trees immediately around each recorded location had little additional
  influence. Most birds crossed several forest stands each day, and their
  daily activity areas changed considerably from one day to the next. The
  findings show that the arrangement and management of whole forest stands
  can matter more for movement than very local tree conditions.

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - ecological-interactions-system-dynamics
  - biodiversity-global-change
  - applied-ecology-conservation-management

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - animal-movement
  - daily-ranging-patterns
  - habitat-use
  - landscape-heterogeneity
  - hierarchical-habitat-selection
  - forest-management
  - forest-stand-composition
  - forest-stand-age
  - scale-dependent-habitat-effects
  - individual-variation

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - animal-movement
  - daily-ranging-patterns
  - landscape-heterogeneity
  - hierarchical-habitat-selection
  - forest-management

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - central-european-production-forests
  - heterogeneous-managed-forest-landscapes
  - temperate-forest-bird-communities

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species:
  - fringilla-coelebs

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - vhf-radio-telemetry
  - homing-in-tracking
  - repeated-location-sampling
  - point-level-tree-inventory
  - forest-management-map-analysis
  - bayesian-multilevel-hierarchical-modelling
  - markov-chain-monte-carlo
  - local-convex-hull-range-estimation
  - linear-mixed-effects-modelling
  - multi-scale-habitat-analysis

# Input environmental database/ data sources
data_products:
  - regional-forest-management-map-fogis-2006
  - biodiversity-exploratories-environmental-monitoring

# Data produced or archived by this study
research_datasets:
  - biodiversity-exploratories-chaffinch-tracking-data

projects:
  - biodiversity-exploratories

# =======
# Typed graph relationships
# =======

# Purpose: Explicit knowledge graph relationships.
relationships:
  - predicate: authored_by
    object_type: person
    object_id: katrin-kubiczek

  - predicate: authored_by
    object_type: person
    object_id: swen-c-renner

  - predicate: authored_by
    object_type: person
    object_id: stefan-m-bohm

  - predicate: authored_by
    object_type: person
    object_id: elisabeth-k-v-kalko

  - predicate: authored_by
    object_type: person
    object_id: konstans-wells

  - predicate: affiliated_with
    object_type: organisation
    object_id: ulm-university

  - predicate: affiliated_with
    object_type: organisation
    object_id: smithsonian-conservation-biology-institute

  - predicate: affiliated_with
    object_type: organisation
    object_id: university-of-adelaide

  - predicate: contributes_to
    object_type: project
    object_id: biodiversity-exploratories

  - predicate: studies
    object_type: taxon
    object_id: fringilla-coelebs

  - predicate: addresses
    object_type: concept
    object_id: animal-movement

  - predicate: addresses
    object_type: concept
    object_id: hierarchical-habitat-selection

  - predicate: addresses
    object_type: concept
    object_id: forest-management

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - animal-movement-ecology
  - habitat-selection
  - forest-ecology
  - landscape-ecology
  - wildlife-telemetry
  - hierarchical-modelling
  - conservation-management

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why did stand-level forest attributes explain movement better than point-level tree assemblages in this study?"
  - "How does nesting point locations within forest stands change the interpretation of habitat effects?"
  - "Why might daily range size vary strongly within individuals even when measured environmental covariates have little explanatory power?"
  - "How might results differ for a forest specialist compared with the Common Chaffinch?"
  - "Which forest-management interventions could be evaluated using a similar multiscale movement framework?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Common Chaffinch Movement in Heterogeneous Forest Landscapes | Kubiczek et al. 2014"

# Purpose: Search description.
seo_description: >-
  Radio-telemetry study of Common Chaffinch movement and daily ranging across
  heterogeneous production forests, showing stronger stand-level than
  point-level habitat effects.

# Purpose: Search keywords.
keywords:
  - Common Chaffinch
  - Fringilla coelebs
  - animal movement
  - bird movement
  - radio telemetry
  - daily range
  - habitat use
  - forest management
  - production forest
  - landscape heterogeneity
  - hierarchical habitat selection
  - multilevel hierarchical regression
  - Bayesian modelling
  - forest stand age
  - forest stand composition
  - Biodiversity Exploratories

# Purpose: Social sharing metadata.
social:
  title: "Common Chaffinch Movement in Heterogeneous Forest Landscapes"
  description: >-
    Kubiczek and colleagues show that forest stand type and stand age influence
    fine-scale Common Chaffinch movement more strongly than local tree
    assemblages in managed forest mosaics.
  image: ""
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
  source_url: "https://doi.org/10.7717/peerj.368"

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
    claims: source-grounded
    summaries: source-grounded
    concept_classification: draft

---
