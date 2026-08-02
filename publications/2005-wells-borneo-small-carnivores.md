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
id: 2005-wells-borneo-small-carnivores

# Purpose: Official publication title.
title: "Viverrid and herpestid observations by camera and small mammal cage trapping in the lowland rainforests on Borneo including a record of the Hose’s Civet, Diplogale hosei"

# Purpose: Short display title.
short_title: "Small-carnivore observations in Bornean lowland rainforest"

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
year_published: 2005

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2005-01-01

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
- Konstans Wells
- Alim Biun
- Marius Gabin

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
      - ulm-university

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Alim Biun"
    # Purpose: Canonical BAHE person id.
    person_id: alim-biun
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - sabah-parks

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Marius Gabin"
    # Purpose: Canonical BAHE person id.
    person_id: marius-gabin
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - sabah-parks

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  konstans-wells:
    - conceptualization
    - methodology
    - investigation
    - data-curation
    - writing-original-draft
    - writing-review-editing
    - visualization

  alim-biun:
    - methodology
    - investigation
    - data-curation
    - writing-review-editing

  marius-gabin:
    - investigation
    - data-curation
    - writing-review-editing

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "German Academic Exchange Service"
    # Purpose: Canonical funder identifier.
    funder_id: german-academic-exchange-service
    # Purpose: Grant identifier.
    grant_number: ""
    # Purpose: Official grant title.
    grant_title: "Fieldwork support"

  # Purpose: Funding organisation.
  - funder_name: "Japan International Cooperation Agency"
    # Purpose: Canonical funder identifier.
    funder_id: japan-international-cooperation-agency
    # Purpose: Grant identifier.
    grant_number: ""
    # Purpose: Official grant title.
    grant_title: "Camera-trap equipment support"

  # Purpose: Funding organisation.
  - funder_name: "Eeon Company"
    # Purpose: Canonical funder identifier.
    funder_id: eeon-company
    # Purpose: Grant identifier.
    grant_number: ""
    # Purpose: Official grant title.
    grant_title: "Camera-trap equipment support"

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Small Carnivore Conservation"

# Purpose: Journal volume.
volume: "32"

# Purpose: Journal issue.
issue: ""

# Purpose: Article pages or article number.
pages: "12-14"

# Purpose: Publisher.
publisher: "IUCN/SSC Small Carnivore Specialist Group"

# Purpose: Open-access availability. # Values: true, false
open_access: true

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Biun, A., & Gabin, M. (2005). Viverrid and herpestid
  observations by camera and small mammal cage trapping in the lowland
  rainforests on Borneo including a record of the Hose’s Civet, Diplogale
  hosei. Small Carnivore Conservation, 32, 12-14.

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2005), Small Carnivore Conservation, 32, 12-14.

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
pdf: "Wells_etal_2005_SmallCarnivConserv.pdf"

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  No formal abstract was provided in the publication. The article reports camera-trap and small-mammal cage-trap observations of viverrids and herpestids in lowland rainforests of Sabah, Borneo. It documents a lowland record of Hose’s Civet (Diplogale hosei) at Mount Kinabalu National Park and compares species detected by camera trapping and live trapping across primary and secondary forest sites.

# Purpose: Source of abstract. # Values: publisher, author-manuscript
abstract_source: author-manuscript

# Purpose: Indicates verbatim reproduction of original published abstract. # Values: true, false
abstract_verbatim: false

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
  supplementary_material: ""

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
  No publication image assigned.

# Image caption  
image_caption: >-
  No publication image assigned.
  
image_license: ""
image_credit: ""
image_license_verified: false

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20050000

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
      A camera trap recorded Hose’s Civet (Diplogale hosei) in primary lowland rainforest at approximately 600 m elevation near Poring Hot Spring in Mount Kinabalu National Park, Sabah.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Approximately 100 camera nights produced 335 wildlife photographs, of which eight photographs represented four viverrid or herpestid species: Hose’s Civet, Banded Palm Civet, Banded Linsang and Collared Mongoose.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      More than 42,000 terrestrial and 1,800 arboreal cage-trap nights yielded 12 individual civets in 27 captures, representing Small-toothed Palm Civet, Common Palm Civet and Malay Civet.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      All live-trapped civets were captured in the primary forests of Danum Valley and Tawau Hills National Park, while no viverrids were captured in the sampled secondary forests.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Camera trapping and small-mammal cage trapping detected different subsets of the small-carnivore assemblage, demonstrating that low encounter rates and method-specific biases can produce incomplete species inventories.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-06
    text: >
      The lowland observation of Hose’s Civet adds evidence that the species’ habitat and elevational range may be broader than suggested by its predominantly montane records.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-07
    text: >
      Surveys of Bornean small carnivores should account for spatial heterogeneity across local and regional scales, forest condition and vertical strata, and should combine complementary recording methods.
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
  This field report combines approximately 100 camera nights with more than
  43,800 terrestrial and arboreal cage-trap nights across rainforests in Sabah,
  Borneo. It documents seven viverrid and herpestid species and reports a rare
  lowland record of Hose’s Civet at Mount Kinabalu National Park.

# Knowledge-network summary.
knowledge_summary: >
  The publication provides occurrence data for an elusive Bornean small-carnivore
  assemblage and demonstrates that camera traps and cage traps recover different
  species subsets. The Hose’s Civet record at approximately 600 m contributes to
  evidence that this poorly known species is not restricted to montane forest.
  The authors emphasise that sparse detections, non-target trap design and
  rainforest heterogeneity constrain inventories and motivate multi-method,
  multi-stratum survey designs.

# Scientific or societal significance.
impact_statement: >
  The study adds an important lowland occurrence record for the rarely observed
  Hose’s Civet and shows why complementary survey methods are needed to assess
  Borneo’s elusive small-carnivore communities reliably.

# Non-technical summary.  
plain_language_summary: >-
  Camera traps and live traps in Sabah photographed or captured several civets
  and mongooses, including the rarely seen Hose’s Civet in lowland forest near
  Mount Kinabalu. Because the two methods found different species, the study
  shows that a single survey method can easily miss part of the local small-
  carnivore community.

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - biodiversity-global-change
  - ecological-interactions-system-dynamics
  - nature-society-sustainable-futures

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - small-carnivore-conservation
  - species-occurrence
  - camera-trapping
  - live-trapping
  - survey-method-bias
  - rainforest-biodiversity
  - habitat-distribution
  - lowland-rainforest
  - forest-disturbance
  - vertical-habitat-use

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - small-carnivore-conservation
  - species-occurrence
  - camera-trapping
  - survey-method-bias
  - lowland-rainforest

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - bornean-lowland-rainforest
  - primary-and-secondary-rainforest
  - small-carnivore-assemblages
  - terrestrial-and-arboreal-forest-strata

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - diplogale-hosei
  - hemigalus-derbyanus
  - prionodon-linsang
  - herpestes-semitorquatus
  - arctogalidia-trivirgata
  - paradoxurus-hermaphroditus
  - viverra-tangalunga

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - camera-trapping
  - terrestrial-live-trapping
  - arboreal-live-trapping
  - opportunistic-species-recording
  - comparative-field-survey

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

  - predicate: authored_by
    object_type: person
    object_id: alim-biun

  - predicate: authored_by
    object_type: person
    object_id: marius-gabin

  - predicate: affiliated_with
    object_type: organisation
    object_id: ulm-university

  - predicate: affiliated_with
    object_type: organisation
    object_id: sabah-parks

  - predicate: addresses
    object_type: concept
    object_id: small-carnivore-conservation

  - predicate: addresses
    object_type: concept
    object_id: species-occurrence

  - predicate: uses_method
    object_type: method
    object_id: camera-trapping

  - predicate: studies
    object_type: taxon
    object_id: diplogale-hosei

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - tropical-mammal-ecology
  - wildlife-survey-methods
  - camera-trapping
  - conservation-biogeography
  - rare-species-monitoring
  - rainforest-conservation
  - sampling-bias

# Purpose: Suggested discussion questions.
discussion_questions:
  - "What evidence does this record provide for the elevational and habitat range of Hose’s Civet?"
  - "Why did camera trapping and cage trapping detect different small-carnivore species?"
  - "How do trap size, bait and placement affect inference from non-target live-trapping surveys?"
  - "What survey design would best estimate the occurrence of rare civets across primary and disturbed forests?"
  - "How should vertical habitat stratification be incorporated into inventories of Bornean small carnivores?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Bornean Viverrid and Herpestid Records, Including Hose’s Civet | Wells et al. 2005"

# Purpose: Search description.
seo_description: >-
  Field observations from Sabah documenting viverrids and herpestids with
  camera traps and live traps, including a rare lowland record of Hose’s Civet
  in Mount Kinabalu National Park.

# Purpose: Search keywords.
keywords:
  - Hose’s Civet
  - Diplogale hosei
  - Borneo
  - Sabah
  - Mount Kinabalu National Park
  - lowland rainforest
  - small carnivores
  - Viverridae
  - Herpestidae
  - camera trapping
  - live trapping
  - cage trapping
  - species occurrence
  - survey bias
  - rainforest conservation
  - Banded Palm Civet
  - Banded Linsang
  - Collared Mongoose
  - Small-toothed Palm Civet
  - Common Palm Civet
  - Malay Civet

# Purpose: Social sharing metadata.
social:
  title: "Bornean Small-Carnivore Records Including Hose’s Civet"
  description: >-
    Wells, Biun and Gabin report camera- and live-trap observations of Bornean
    viverrids and herpestids, including a rare lowland record of Hose’s Civet.
  image: ""
  card: summary

# =======
# Attribution and reuse
# =======

# Purpose: Attribution guidance.
attribution_note: >
  This BAHE knowledge object summarises and contextualises the published
  field report for research, teaching and conservation synthesis. Species
  records, interpretations and recommendations should be attributed to and
  cited from the original publication.

# Purpose: Reuse guidance.
license_note: >
  The supplied publication does not state a Creative Commons licence.
  Copyright and reuse conditions should therefore be verified with the
  journal or rights holder before reproducing article text, tables or images.

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
    bibliographic_metadata: verified
    claims: verified
    summaries: verified
    concept_classification: reviewed

---
