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
id: 2006-wells-rattus-primary-rainforest-borneo

# Purpose: Official publication title.
title: "Is Rattus rattus invading the primary rainforest on Borneo?"

# Purpose: Short display title.
short_title: "Rattus rattus in primary Bornean rainforest"

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
year_published: 2006

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: ""

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
  - "Dieter Kock"
  - "Maklarin B. Lakim"
  - "Martin Pfeiffer"

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
      - university-of-ulm
  # Author position.
  - position: 2
    # Purpose: Full author name.
    name: "Dieter Kock"
    # Purpose: Canonical BAHE person id.
    person_id: ""
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids: []
  # Author position.
  - position: 3
    # Purpose: Full author name.
    name: "Maklarin B. Lakim"
    # Purpose: Canonical BAHE person id.
    person_id: ""
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids: []
  # Author position.
  - position: 4
    # Purpose: Full author name.
    name: "Martin Pfeiffer"
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
  - funder_name: "German Academic Exchange Service"
    # Purpose: Canonical funder identifier.
    funder_id: ""
    # Purpose: Grant identifier.
    grant_number: ""
    # Purpose: Official grant title.
    grant_title: ""

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Malayan Nature Journal"

# Purpose: Journal volume.
volume: "59"

# Purpose: Journal issue.
issue: ""

# Purpose: Article pages or article number.
pages: "73–79"

# Purpose: Publisher.
publisher: "Malayan Nature Society"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Kock, D., Lakim, M. B., & Pfeiffer, M. (2006).
  Is Rattus rattus invading the primary rainforest on Borneo?
  Malayan Nature Journal, 59, 73–79.

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2006), Malayan Nature Journal, 59, 73–79.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: ""

  # Purpose: Publisher landing page.
  publisher_url: ""

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.
  arxiv: ""

  # Purpose: OpenAlex identifier.
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: ""
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Rats from the Rattus rattus species group have been introduced worldwide into many different temperate and tropical zones with considerable destructive consequences. Although this pest species is mainly restricted to human-converted habitats near settlements, it has also been recorded intruding into tropical rainforests in various areas. On Borneo, a rainforest hotspot in diversity and endemism, R. rattus was previously expected to be strictly confined to habitats disturbed by humans. We live-trapped small mammals in several primary and secondary rainforest sites in Sabah, Malaysia, and report recent captures of R. rattus in two primary rainforest sites on Borneo.

# Purpose: Source of abstract. # Values: publisher, author-manuscript
abstract_source: author-manuscript

# Purpose: Indicates verbatim reproduction of original published abstract. # Values: true, false
abstract_verbatim: false

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
  supplementary_material: ""

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
show_on_homepage: true

order: 20060100

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
      Two specimens identified as Rattus rattus sensu lato were captured inside
      primary dipterocarp rainforest at Danum Valley and Tawau Hills in Sabah,
      Borneo.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      The Danum Valley specimen was captured approximately 1.2 kilometres
      inside primary rainforest, and the Tawau Hills specimen approximately
      0.7 kilometres inside primary rainforest.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      More than 42,000 ground-trap nights and 5,000 canopy-trap nights across
      primary and secondary forest sites yielded only two such specimens,
      indicating very low apparent occurrence in the sampled primary forests.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Morphological and cranial comparisons supported assignment of the two
      Bornean specimens to Rattus rattus sensu lato, while uncertainty remained
      over separation from the Asian form Rattus tanezumi.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-05
    text: >
      The immature age and low capture frequency of the specimens were
      consistent with either dispersing individuals or an early invasion stage,
      rather than established abundant populations.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-06
    text: >
      The two records occurred in forests with contrasting surrounding
      landscapes, including an extensively forested matrix at Danum Valley and
      plantation-dominated surroundings at Tawau Hills.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Even low-density incursions of invasive rats into intact rainforest may
      pose ecological risks through competition with native small mammals,
      resource use and transmission of diseases or parasites.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-08
    text: >
      Early detection, taxonomic clarification and continued monitoring are
      required to determine whether Rattus populations are becoming established
      in Borneo's primary rainforests.
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
  This field and taxonomic study reports two captures of Rattus rattus sensu
  lato within primary dipterocarp rainforest in Sabah, challenging the prior
  assumption that the species was confined to human-disturbed habitats on
  Borneo.

# Knowledge-network summary.
knowledge_summary: >
  The publication combines intensive live trapping with morphological and
  cranial examination to document possible early-stage intrusion of an invasive
  commensal rat into intact rainforest. The rarity and immature age of the
  specimens prevent confirmation of established populations, while their
  occurrence far from forest edges shows that primary forest is not necessarily
  impermeable to Rattus dispersal.

# Scientific or societal significance.
impact_statement: >
  Detecting invasive rats at very low abundance inside primary rainforest
  highlights the need for early-warning surveillance before ecological impacts
  or disease transmission become widespread.

# Non-technical summary.
plain_language_summary: >-
  Black rats are usually associated with settlements and disturbed habitats on
  Borneo. This study found two young rats well inside primary rainforest at two
  sites in Sabah. The records do not prove that established populations were
  present, but they show that rats can enter intact forest and may represent an
  early stage of invasion requiring further monitoring.

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - biodiversity-global-change
  - animal-health-one-health
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
data_products: []

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
  - "What evidence is required to distinguish transient dispersers from an established invasive population?"
  - "How does taxonomic uncertainty within the Rattus rattus species complex affect invasion assessment?"
  - "Why can rare detections be important for conservation even when population establishment is unconfirmed?"
  - "How might surrounding land use influence the probability of invasive rats entering primary rainforest?"
  - "Which monitoring approaches would best detect changes from occasional incursion to population establishment?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Rattus rattus in Primary Bornean Rainforest | Wells et al. 2006"

# Purpose: Search description.
seo_description: >-
  Two rare captures of Rattus rattus sensu lato inside primary rainforest in
  Sabah raise concern about possible early-stage invasion of intact Bornean
  forests.

# Purpose: Search keywords.
keywords:
  - Rattus rattus
  - Rattus tanezumi
  - black rat
  - invasive species
  - Borneo
  - Sabah
  - primary rainforest
  - tropical rainforest
  - Danum Valley
  - Tawau Hills
  - small mammals
  - biological invasion
  - early detection
  - habitat disturbance
  - disease transmission
  - taxonomic uncertainty
  - rainforest conservation

# Purpose: Social sharing metadata.
social:
  title: "Is Rattus rattus Invading Primary Rainforest on Borneo?"
  description: >-
    Rare captures deep inside two Sabah rainforests suggest that invasive rats
    can enter intact forest and may require early-warning monitoring.
  image: ""
  card: summary_large_image

# =======
# Attribution and reuse
# =======

# Purpose: Attribution guidance.
attribution_note: >
  This BAHE knowledge object summarises and contextualises the peer-reviewed
  publication for research, teaching and interdisciplinary synthesis.
  Scientific observations, taxonomic interpretations and conclusions should be
  attributed to and cited from the original publication.

# Purpose: Reuse guidance.
license_note: >
  The article was published in the Malayan Nature Journal with all rights
  reserved. Public availability does not establish permission to reproduce the
  abstract, specimens, figures, tables or other published content. BAHE
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
    - author-manuscript

  # Purpose: Original source URL.
  source_url: ""

  # Purpose: AI assistance metadata.
  ai_assistance:
    system: ChatGPT
    roles:
      - metadata-extraction
      - draft-summary
      - concept-classification
    outputs_human_verified: false

  confidence:
    bibliographic_metadata: unreviewed
    claims: unreviewed
    summaries: unreviewed
    concept_classification: unreviewed


---

