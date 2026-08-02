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
id: 2018-camacho-sanchez-summit-rat-interglacial-refugia

# Purpose: Official publication title.
title: "Interglacial refugia on tropical mountains: Novel insights from the summit rat (Rattus baluensis), a Borneo mountain endemic"

# Purpose: Short display title.
short_title: "Interglacial refugia and the Borneo summit rat"

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
year_published: 2018

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2018-09-01

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
- Miguel Camacho-Sanchez
- Irene Quintanilla
- Melissa T. R. Hawkins
- Fred Y. Y. Tuh
- Konstans Wells
- Jesus E. Maldonado
- Jennifer A. Leonard

# Purpose: Canonical BAHE author ids.
bahe_authors:
  - konstans-wells

# Purpose: Structured author metadata.
author_entities:
  # Purpose: Citation order.
  - position: 1
    # Purpose: Full author name.
    name: "Miguel Camacho-Sanchez"
    # Purpose: Canonical BAHE person id.
    person_id: miguel-camacho-sanchez
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated canonical organisation objects.
    affiliation_ids:
      - estacion-biologica-de-donana

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Irene Quintanilla"
    # Purpose: Canonical BAHE person id.
    person_id: irene-quintanilla
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - estacion-biologica-de-donana

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Melissa T. R. Hawkins"
    # Purpose: Canonical BAHE person id.
    person_id: melissa-t-r-hawkins
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - smithsonian-conservation-biology-institute
      - smithsonian-national-museum-of-natural-history

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "Fred Y. Y. Tuh"
    # Purpose: Canonical BAHE person id.
    person_id: fred-y-y-tuh
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - sabah-parks

  # Auhor position.
  - position: 5
    # Purpose: Full author name.
    name: "Konstans Wells"
    # Purpose: Canonical BAHE person id.
    person_id: konstans-wells
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - griffith-university

  # Auhor position.
  - position: 6
    # Purpose: Full author name.
    name: "Jesus E. Maldonado"
    # Purpose: Canonical BAHE person id.
    person_id: jesus-e-maldonado
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - smithsonian-conservation-biology-institute
      - smithsonian-national-museum-of-natural-history

  # Auhor position.
  - position: 7
    # Purpose: Full author name.
    name: "Jennifer A. Leonard"
    # Purpose: Canonical BAHE person id.
    person_id: jennifer-a-leonard
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - estacion-biologica-de-donana

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  miguel-camacho-sanchez:
    - conceptualization
    - methodology
    - investigation
    - data-curation
    - formal-analysis
    - visualization
    - writing-original-draft
    - writing-review-editing

  irene-quintanilla:
    - investigation
    - methodology
    - data-curation
    - writing-review-editing

  melissa-t-r-hawkins:
    - investigation
    - resources
    - writing-review-editing

  fred-y-y-tuh:
    - investigation
    - resources
    - writing-review-editing

  konstans-wells:
    - investigation
    - ecological-interpretation
    - writing-review-editing

  jesus-e-maldonado:
    - methodology
    - resources
    - supervision
    - writing-review-editing

  jennifer-a-leonard:
    - conceptualization
    - methodology
    - supervision
    - funding-acquisition
    - writing-review-editing

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "Ministerio de Economía y Competitividad"
    # Purpose: Canonical funder identifier.
    funder_id: ministerio-de-economia-y-competitividad-spain
    # Purpose: Grant identifier.
    grant_number: "BES-2011-049186; CGL2010-21524; CGL2014-58793-P; EEBB-I-12-05317"
    # Purpose: Official grant title.
    grant_title: ""

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Diversity and Distributions"

# Purpose: Journal volume.
volume: "24"

# Purpose: Journal issue.
issue: "9"

# Purpose: Article pages or article number.
pages: "1252-1266"

# Purpose: Publisher.
publisher: "Wiley"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Camacho-Sanchez, M., Quintanilla, I., Hawkins, M. T. R., Tuh, F. Y. Y.,
  Wells, K., Maldonado, J. E., & Leonard, J. A. (2018). Interglacial
  refugia on tropical mountains: Novel insights from the summit rat
  (Rattus baluensis), a Borneo mountain endemic. Diversity and
  Distributions, 24(9), 1252-1266. https://doi.org/10.1111/ddi.12761

# Purpose: Short citation.
citation_short: >-
  Camacho-Sanchez et al. (2018), Diversity and Distributions, 24(9), 1252-1266.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1111/ddi.12761"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1111/ddi.12761"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1111/ddi.12761"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Aim: The genetics of organisms currently isolated in refugia has received little attention compared to post-glacial expansions. We study the population history and connectivity of a rat endemic to montane habitat in Borneo to better understand the history and potential of populations in interglacial mountain refugia.
  Location: Sabah, Borneo, Malaysia.
  Methods: We performed a field survey of the summit rat (Rattus baluensis) on two mountains, Mt. Kinabalu and Mt. Tambuyukon, its entire known distribution. We sequenced mitogenomes and 27 introns (19 of which were polymorphic) in 49 individuals from both populations. We analysed their current genetic structure and diversity, and inferred their demographic history with approximate Bayesian computation.
  Results: Summit rats were tightly associated with mountain mossy forest and scrubland above 2,000 m, facilitating the prediction of their past and future distributions. The genetic analysis supports a Holocene fragmentation of a larger population into smaller ones that are now isolated in interglacial refugia on mountaintops. These findings are consistent with climatic reconstructions and the retreat of upland forest to higher elevations after the Last Glacial Maximum (LGM), ~21 kya.
  Main conclusions: The two isolated populations of summit rats formed through the upland shift of their habitat after the LGM. The current trend of global warming will likely lead to diminishing suitable upland habitat and result in the extinction of the population on Mt. Tambuyukon. The population on Mt. Kinabalu, the higher peak, could persist at higher elevations, highlighting the singular value of high tropical mountains as reservoirs of biodiversity during past and ongoing climate change.

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
  supplementary_material: "https://onlinelibrary.wiley.com/doi/10.1111/ddi.12761/suppinfo"

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
image: "/images/images_publications/Interglacial-refugia-summit-rat_Camacho-Sanchez-2018.jpg"

image_alt: >-
  Multi-panel figure showing the distribution and ecology of the summit rat
  on Mount Kinabalu and Mount Tambuyukon in Borneo. Panels include a study
  map, a photograph of a summit rat visiting a Nepenthes rajah pitcher plant,
  mountain elevation profiles with trapping locations, and genetic ancestry
  assignments separating the two mountain populations.

# Image caption  
image_caption: >-
  Distribution, habitat association and genetic structure of the summit rat
  across Mount Kinabalu and Mount Tambuyukon. The species was recorded mainly
  in upper montane forest and scrubland above 2,000 m, including sites with
  Nepenthes rajah. Genetic ancestry estimates identify two distinct
  populations corresponding to the two mountains, despite their separation by
  less than 18 km.

image_license: "All rights reserved"
image_credit: "Camacho-Sanchez et al. (2018); summit rat photograph by Ch’ien C. Lee"
image_license_verified: false  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20180901

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
      The summit rat occurs in upper montane mossy forest, dwarf forest and scrubland above approximately 2,000 m on Mount Kinabalu and Mount Tambuyukon in Sabah, Borneo.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Discovery of a second summit rat population on Mount Tambuyukon expanded the known distribution of a species previously considered endemic to Mount Kinabalu.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Nuclear and mitochondrial genetic data identify the Mount Kinabalu and Mount Tambuyukon summit rats as strongly differentiated and effectively isolated populations.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Approximately 22% of nuclear and mitochondrial genetic variation was partitioned between the two mountains, despite their separation by less than 18 km.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Genetic diversity and estimated effective population size were higher on Mount Kinabalu than on Mount Tambuyukon.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Approximate Bayesian computation supports fragmentation of a larger ancestral summit rat population during the Holocene, with population separation estimated at approximately 3,000 years ago.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      The lower-elevation forest between Mount Kinabalu and Mount Tambuyukon functions as a dispersal barrier for a species specialised on cool upper-montane habitat.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-08
    text: >
      The summit rat's current genetic structure is consistent with interglacial refugia formed when upland forest retreated to higher elevations after the Last Glacial Maximum.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-09
    text: >
      Continued climatic warming is expected to contract suitable summit rat habitat upslope, placing the lower Mount Tambuyukon population at particularly high extinction risk.
    knowledge_type: policy-implication
    attributed_to: source-publication

  - id: statement-10
    text: >
      High tropical mountains can preserve endemic biodiversity during climatic warming by retaining cool habitat above the elevational limits available on lower peaks.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-11
    text: >
      Multi-locus nuclear markers, complete mitochondrial genomes and approximate Bayesian computation provide complementary evidence for recent fragmentation and demographic history in isolated mountain populations.
    knowledge_type: methodological-proposition
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
  This phylogeographic study surveyed the summit rat across Mount Kinabalu and
  Mount Tambuyukon in Sabah and analysed complete mitochondrial genomes and
  nuclear introns from 49 individuals. Population-genetic analyses and
  approximate Bayesian computation reconstructed the species' recent
  fragmentation and demographic history.

# Knowledge-network summary.
knowledge_summary: >
  The study provides empirical evidence that tropical mountain endemics can
  persist in interglacial refugia formed by post-glacial upslope habitat
  contraction. Summit rats on Mount Kinabalu and Mount Tambuyukon are
  genetically isolated, with the smaller Tambuyukon population retaining less
  genetic diversity. Their inferred Holocene split accords with the retreat of
  upper-montane forest after the Last Glacial Maximum and illustrates how
  elevational habitat barriers can generate strong population structure over
  short geographical distances.

# Scientific or societal significance.
impact_statement: >
  Lower tropical mountains may lose summit-restricted endemic populations as
  warming drives habitats upslope, making high-elevation protected areas
  critical reservoirs of climate-sensitive biodiversity.

# Non-technical summary.  
plain_language_summary: >-
  Researchers discovered that the Borneo summit rat lives on two nearby
  mountains rather than only on Mount Kinabalu. Genetic evidence shows that
  the two populations have been isolated for thousands of years after cooler
  mountain habitat contracted uphill. Future warming could remove suitable
  habitat from the lower Mount Tambuyukon, while the higher Mount Kinabalu may
  continue to provide refuge.  

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
  - interglacial-refugia
  - tropical-mountain-biodiversity
  - sky-islands
  - phylogeography
  - population-fragmentation
  - genetic-isolation
  - elevational-range-shifts
  - climate-change-vulnerability
  - demographic-history
  - effective-population-size
  - population-genetic-structure
  - mountain-endemism
  - habitat-contraction
  - last-glacial-maximum
  - montane-refugia

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - interglacial-refugia
  - tropical-mountain-biodiversity
  - phylogeography
  - genetic-isolation
  - elevational-range-shifts
  - climate-change-vulnerability

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - mount-kinabalu-montane-ecosystem
  - mount-tambuyukon-montane-ecosystem
  - borneo-sky-island-system
  - summit-rat-population-system

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - rattus-baluensis
  - nepenthes-rajah
  - tupaia-montana

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - elevational-transect-sampling
  - live-trapping
  - mitochondrial-genome-sequencing
  - nuclear-intron-sequencing
  - population-genetic-analysis
  - bayesian-clustering
  - analysis-of-molecular-variance
  - haplotype-network-analysis
  - approximate-bayesian-computation
  - demographic-modelling
  - genetic-diversity-estimation
  - digital-elevation-modelling

# Input environmental database/ data sources
data_products:
  - shuttle-radar-topography-mission
  - pantheria
  - genbank

# Data produced or archived by this study  
research_datasets:
  - genbank-mg423625-mg425911
  - genbank-ky611359-ky611390

projects: []

# =======
# Typed graph relationships
# =======

# Purpose: Explicit knowledge graph relationships.
relationships:
  - predicate: authored_by
    object_type: person
    object_id: miguel-camacho-sanchez

  - predicate: authored_by
    object_type: person
    object_id: irene-quintanilla

  - predicate: authored_by
    object_type: person
    object_id: melissa-t-r-hawkins

  - predicate: authored_by
    object_type: person
    object_id: fred-y-y-tuh

  - predicate: authored_by
    object_type: person
    object_id: konstans-wells

  - predicate: authored_by
    object_type: person
    object_id: jesus-e-maldonado

  - predicate: authored_by
    object_type: person
    object_id: jennifer-a-leonard

  - predicate: authored_by
    object_type: organisation
    object_id: estacion-biologica-de-donana

  - predicate: authored_by
    object_type: organisation
    object_id: smithsonian-conservation-biology-institute

  - predicate: authored_by
    object_type: organisation
    object_id: sabah-parks

  - predicate: authored_by
    object_type: organisation
    object_id: griffith-university

  - predicate: uses
    object_type: data-product
    object_id: shuttle-radar-topography-mission

  - predicate: produces
    object_type: dataset
    object_id: genbank-mg423625-mg425911

  - predicate: produces
    object_type: dataset
    object_id: genbank-ky611359-ky611390

  - predicate: addresses
    object_type: concept
    object_id: interglacial-refugia

  - predicate: addresses
    object_type: concept
    object_id: genetic-isolation

  - predicate: addresses
    object_type: concept
    object_id: elevational-range-shifts

  - predicate: addresses
    object_type: concept
    object_id: climate-change-vulnerability

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - conservation-genetics
  - phylogeography
  - island-biogeography
  - climate-change-ecology
  - tropical-mountain-biodiversity
  - population-genetics
  - approximate-bayesian-computation
  - species-distribution
  - conservation-planning

# Purpose: Suggested discussion questions.
discussion_questions:
  - "How do interglacial refugia differ from the more commonly studied glacial refugia?"
  - "Why can populations on mountains separated by less than 18 km become genetically isolated?"
  - "What evidence supports a Holocene fragmentation of the ancestral summit rat population?"
  - "Why is the Mount Tambuyukon population more vulnerable to future warming than the Mount Kinabalu population?"
  - "How do complete mitochondrial genomes and nuclear introns provide complementary evidence about population history?"
  - "What conservation actions could protect climate-sensitive endemic species restricted to tropical mountaintops?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Interglacial Refugia and the Borneo Summit Rat | Camacho-Sanchez et al. 2018"

# Purpose: Search description.
seo_description: >-
  Genetic and ecological study showing that summit rats on Mount Kinabalu and
  Mount Tambuyukon are isolated remnants of a Holocene upland population and
  face contrasting risks from climate-driven habitat loss.

# Purpose: Search keywords.
keywords:
  - Rattus baluensis
  - summit rat
  - Borneo
  - Mount Kinabalu
  - Mount Tambuyukon
  - interglacial refugia
  - tropical mountains
  - sky islands
  - phylogeography
  - population genetics
  - genetic isolation
  - approximate Bayesian computation
  - mitochondrial genome
  - nuclear introns
  - climate change
  - elevational range shift
  - mountain endemism
  - conservation genetics
  - Holocene fragmentation

# Purpose: Social sharing metadata.
social:
  title: "Interglacial Refugia and the Borneo Summit Rat"
  description: >-
    Camacho-Sanchez and colleagues reveal genetically isolated summit rat
    populations on two Bornean mountains and their vulnerability to
    climate-driven habitat contraction.
  image: "images/images_publications/Interglacial-refugia-summit-rat_Camacho-Sanchez-2018.png"
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
  The article is subject to the publisher's copyright and reuse conditions.
  Reuse of article text or figures requires compliance with the licence and
  permissions stated by the publisher.

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
  source_url: "https://doi.org/10.1111/ddi.12761"

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
