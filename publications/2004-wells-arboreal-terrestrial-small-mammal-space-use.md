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
id: 2004-wells-arboreal-terrestrial-small-mammal-space-use

# Purpose: Official publication title.
title: "Use of arboreal and terrestrial space by a small mammal community in a tropical rain forest in Borneo, Malaysia"

# Purpose: Short display title.
short_title: "Arboreal and terrestrial space use by Bornean small mammals"

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
year_published: 2004

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2004-04-01

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
- Martin Pfeiffer
- Maklarin B. Lakim
- K. Eduard Linsenmair

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
      - university-of-wurzburg
      - university-of-ulm

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Martin Pfeiffer"
    # Purpose: Canonical BAHE person id.
    person_id: martin-pfeiffer
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-ulm

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Maklarin B. Lakim"
    # Purpose: Canonical BAHE person id.
    person_id: maklarin-b-lakim
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - sabah-parks

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "K. Eduard Linsenmair"
    # Purpose: Canonical BAHE person id.
    person_id: k-eduard-linsenmair
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-wurzburg

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
    - formal-analysis
    - visualization
    - writing-original-draft
    - writing-review-editing

  martin-pfeiffer:
    - conceptualization
    - methodology
    - supervision
    - interpretation
    - writing-review-editing

  maklarin-b-lakim:
    - investigation
    - resources
    - field-logistics
    - taxonomic-identification
    - writing-review-editing

  k-eduard-linsenmair:
    - conceptualization
    - supervision
    - resources
    - interpretation
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
    grant_title: ""

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Journal of Biogeography"

# Purpose: Journal volume.
volume: "31"

# Purpose: Journal issue.
issue: "4"

# Purpose: Article pages or article number.
pages: "641-652"

# Purpose: Publisher.
publisher: "Blackwell Publishing"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Pfeiffer, M., Lakim, M. B., & Linsenmair, K. E. (2004).
  Use of arboreal and terrestrial space by a small mammal community in a
  tropical rain forest in Borneo, Malaysia. Journal of Biogeography, 31(4),
  641-652. https://doi.org/10.1046/j.1365-2699.2003.01032.x

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2004), Journal of Biogeography, 31(4), 641-652.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1046/j.1365-2699.2003.01032.x"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1046/j.1365-2699.2003.01032.x"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.
  arxiv: ""

  # Purpose: OpenAlex identifier.
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1046/j.1365-2699.2003.01032.x"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
# The original abstract is intentionally excluded because it is copyrighted.
abstract_original: ""

# Purpose: Source of abstract. # Values: publisher, author-manuscript
abstract_source: publisher

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
##/images/images_publications/Arboreal-terrestrial-small-mammal-space-use_Wells-2004.png

image_alt: >-
  Multivariate habitat-space plots comparing trap locations used by common
  arboreal small mammals, terrestrial murids and terrestrial tree shrews in
  lowland rainforest at Kinabalu National Park. The plots show extensive
  overlap among species along gradients of tree size distribution, tree
  spacing, branch connectivity and liana abundance.

# Image caption
image_caption: >-
  Microhabitat use by common arboreal and terrestrial small mammals in
  lowland Bornean rainforest. Species occupied broadly overlapping portions
  of the measured habitat space, although capture probabilities of several
  taxa were associated with tree size distribution, branch connectivity,
  lianas, gaps and other fine-scale vegetation attributes.

image_license: "All rights reserved"
image_credit: "Wells et al. (2004)"
image_license_verified: false

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20040401

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
      Seven trapping sessions across paired terrestrial and lower-canopy grids recorded 644 captures of 118 individuals representing 20 small-mammal species from six families.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Sixteen species were recorded on the ground and 11 species in the lower canopy, with terrestrial species diversity significantly exceeding arboreal diversity.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Murid rodents dominated both habitat layers and accounted for approximately 82% of all captures.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Chiropodomys major dominated the canopy assemblage, whereas Maxomys whiteheadi and Maxomys surifer were the most abundant terrestrial species.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Niviventer cremoriventer and Tupaia minor were common in both terrestrial and arboreal traps, demonstrating that vertical habitat use formed a continuum rather than a strict ground–canopy division.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Most common small-mammal species occupied broadly overlapping portions of measured microhabitat space rather than being confined to distinct habitat types.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Tree size distribution was among the strongest fine-scale habitat correlates of capture probability for both arboreal and terrestrial species.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Branch connectivity, liana presence, canopy gaps, bark structure and crown density influenced the occurrence of particular species and local assemblages.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-09
    text: >
      Microhabitat variation explained more compositional variation in terrestrial assemblages than in arboreal assemblages.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-10
    text: >
      Most species pairs showed neither strong spatial avoidance nor greater-than-expected overlap in trap use.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-11
    text: >
      Marked individuals showed low persistence across trapping sessions, with lower persistence in males and immature individuals than in females.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-12
    text: >
      Species turnover between trapping sessions was similarly high in terrestrial and arboreal assemblages.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-13
    text: >
      Ecological segregation in this small-mammal community was driven more by concentrated activity within preferred parts of broadly shared habitat than by strict habitat-layer specialization.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-14
    text: >
      The structurally complex canopy may constrain foraging efficiency and thereby reduce differentiation in microhabitat use among common arboreal species.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-15
    text: >
      Studies of tropical small-mammal communities should sample both ground and canopy layers because terrestrial trapping alone underrepresents vertical habitat use and arboreal diversity.
    knowledge_type: recommendation
    attributed_to: source-publication

  - id: statement-16
    text: >
      Fine-scale habitat measurements should be combined with repeated demographic sampling because local assemblages vary through both habitat associations and rapid individual turnover.
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
  This study compared ground and lower-canopy small-mammal assemblages in
  lowland rainforest at Kinabalu National Park using paired live traps,
  permanent individual marking and detailed measurements of vegetation
  structure. Diversity, microhabitat use, species co-occurrence, persistence
  and temporal turnover were analysed across seven trapping sessions.

# Knowledge-network summary.
knowledge_summary: >
  The study shows that tropical small-mammal communities are vertically
  structured without forming sharply separated terrestrial and arboreal
  assemblages. Terrestrial diversity was higher, but several common species
  used both habitat layers. Species shared much of the available
  microhabitat, and differentiation arose mainly through variation in the
  intensity of use of tree structure, connectivity, lianas, gaps and other
  local habitat attributes.

# Scientific or societal significance.
impact_statement: >
  Understanding tropical small-mammal diversity requires three-dimensional
  sampling and explicit consideration of both microhabitat variation and
  rapid community turnover.

# Non-technical summary.
plain_language_summary: >-
  Small mammals in Borneo did not divide neatly into ground-dwelling and
  tree-dwelling groups. Some species strongly preferred one layer, but many
  used both the forest floor and lower canopy. The ground community contained
  more species, while local combinations of animals changed frequently over
  time. Fine-scale tree and vegetation structure influenced where several
  species were found.

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - biodiversity-global-change
  - ecological-interactions-system-dynamics
  - conservation-ecology
  - quantitative-ecology-modelling

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - vertical-habitat-partitioning
  - arboreal-terrestrial-continuum
  - tropical-small-mammal-diversity
  - microhabitat-use
  - habitat-segregation
  - species-coexistence
  - canopy-ecology
  - community-turnover
  - individual-persistence
  - niche-overlap
  - tree-connectivity
  - liana-use
  - forest-structure
  - local-assemblage-variability
  - three-dimensional-habitat-use

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - vertical-habitat-partitioning
  - arboreal-terrestrial-continuum
  - microhabitat-use
  - canopy-ecology
  - community-turnover
  - niche-overlap

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - kinabalu-lowland-rainforest
  - poring-hot-spring-small-mammal-community
  - borneo-arboreal-terrestrial-mammal-system
  - southeast-asian-dipterocarp-rainforest

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species:
  - chiropodomys-major
  - maxomys-whiteheadi
  - maxomys-surifer
  - niviventer-cremoriventer
  - lenothrix-canus
  - leopoldamys-sabanus
  - maxomys-baeodon
  - sundasciurus-lowii
  - sundasciurus-hippurus
  - sundasciurus-brookei
  - callosciurus-notatus
  - hylopetes-spadiceus
  - trichys-fasciculata
  - tupaia-minor
  - tupaia-gracilis
  - tupaia-longipes
  - tupaia-tana
  - ptilocercus-lowii
  - herpestes-brachyurus
  - nycticebus-coucang

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - paired-ground-canopy-live-trapping
  - repeated-trapping-sessions
  - pit-tagging
  - microhabitat-characterisation
  - profile-board-understorey-measurement
  - tree-size-distribution-assessment
  - factor-analysis
  - multiple-logistic-regression
  - habitat-profile-analysis
  - discriminant-analysis
  - detrended-correspondence-analysis
  - species-co-occurrence-analysis
  - diversity-index-analysis
  - persistence-rate-estimation
  - sorensen-turnover-analysis

# Input environmental database/ data sources
data_products:
  - kinabalu-small-mammal-trapping-data
  - poring-microhabitat-data
  - sabah-parks-museum-reference-collection

# Data produced or archived by this study
research_datasets: []

projects:
  - borneo-small-mammal-forest-ecology

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
    object_id: martin-pfeiffer

  - predicate: authored_by
    object_type: person
    object_id: maklarin-b-lakim

  - predicate: authored_by
    object_type: person
    object_id: k-eduard-linsenmair

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-wurzburg

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-ulm

  - predicate: authored_by
    object_type: organisation
    object_id: sabah-parks

  - predicate: addresses
    object_type: concept
    object_id: vertical-habitat-partitioning

  - predicate: addresses
    object_type: concept
    object_id: microhabitat-use

  - predicate: addresses
    object_type: concept
    object_id: community-turnover

  - predicate: addresses
    object_type: concept
    object_id: niche-overlap

  - predicate: involves
    object_type: taxon
    object_id: chiropodomys-major

  - predicate: involves
    object_type: taxon
    object_id: maxomys-whiteheadi

  - predicate: involves
    object_type: taxon
    object_id: tupaia-minor

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - tropical-forest-ecology
  - mammalogy
  - canopy-ecology
  - community-ecology
  - habitat-selection
  - niche-partitioning
  - biodiversity-monitoring
  - multivariate-ecology
  - field-methods

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why did the terrestrial assemblage contain more species than the lower-canopy assemblage?"
  - "What evidence argues against a strict separation between arboreal and terrestrial small mammals?"
  - "Why might microhabitat variation explain more community structure on the ground than in the canopy?"
  - "How can broadly overlapping habitat use coexist with ecological differentiation among species?"
  - "What are the limitations of sampling only the lower canopy rather than the full vertical forest profile?"
  - "How do low individual persistence and high species turnover affect interpretation of short-term trapping surveys?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Arboreal and Terrestrial Space Use by Bornean Small Mammals | Wells et al. 2004"

# Purpose: Search description.
seo_description: >-
  Ground-and-canopy trapping study showing high small-mammal diversity,
  overlapping microhabitat use and rapid assemblage turnover in lowland
  rainforest at Kinabalu National Park, Borneo.

# Purpose: Search keywords.
keywords:
  - Borneo small mammals
  - Kinabalu National Park
  - canopy ecology
  - arboreal mammals
  - terrestrial mammals
  - habitat partitioning
  - microhabitat use
  - community turnover
  - niche overlap
  - tropical rainforest
  - Chiropodomys major
  - Maxomys whiteheadi
  - Maxomys surifer
  - Niviventer cremoriventer
  - Tupaia minor
  - live trapping
  - lower canopy
  - species diversity
  - forest structure

# Purpose: Social sharing metadata.
social:
  title: "Arboreal and Terrestrial Space Use by Bornean Small Mammals"
  description: >-
    Wells and colleagues show that Bornean small mammals partition vertical
    forest space without forming sharply separated ground and canopy
    communities.
  image: "images/images_publications/Arboreal-terrestrial-small-mammal-space-use_Wells-2004.png"
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
  The original abstract is intentionally excluded. The article is subject to
  the publisher's copyright and reuse conditions. Reuse of article text or
  figures requires compliance with the licence and permissions stated by the
  publisher.

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
  source_url: "https://doi.org/10.1046/j.1365-2699.2003.01032.x"

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
