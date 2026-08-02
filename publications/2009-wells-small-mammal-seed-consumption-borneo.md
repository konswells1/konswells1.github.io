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
id: 2009-wells-small-mammal-seed-consumption-borneo

# Purpose: Official publication title.
title: "Seed consumption by small mammals from Borneo"

# Purpose: Short display title.
short_title: "Seed consumption by Bornean small mammals"

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
year_published: 2009

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2009-09-01

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
- Richard T. Corlett
- Maklarin B. Lakim
- Elisabeth K. V. Kalko
- Martin Pfeiffer

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
      - university-of-ulm

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Richard T. Corlett"
    # Purpose: Canonical BAHE person id.
    person_id: richard-t-corlett
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - national-university-of-singapore

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
    name: "Elisabeth K. V. Kalko"
    # Purpose: Canonical BAHE person id.
    person_id: elisabeth-k-v-kalko
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-ulm
      - smithsonian-tropical-research-institute

  # Auhor position.
  - position: 5
    # Purpose: Full author name.
    name: "Martin Pfeiffer"
    # Purpose: Canonical BAHE person id.
    person_id: martin-pfeiffer
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-ulm

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

  richard-t-corlett:
    - conceptualization
    - interpretation
    - writing-review-editing

  maklarin-b-lakim:
    - investigation
    - resources
    - field-logistics
    - writing-review-editing

  elisabeth-k-v-kalko:
    - conceptualization
    - supervision
    - resources
    - interpretation
    - writing-review-editing

  martin-pfeiffer:
    - conceptualization
    - methodology
    - supervision
    - interpretation
    - writing-review-editing

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "German Academic Exchange Service"
    # Purpose: Canonical funder identifier.
    funder_id: daad
    # Purpose: Grant identifier.
    grant_number: ""
    # Purpose: Official grant title.
    grant_title: ""

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Journal of Tropical Ecology"

# Purpose: Journal volume.
volume: "25"

# Purpose: Journal issue.
issue: "5"

# Purpose: Article pages or article number.
pages: "555-558"

# Purpose: Publisher.
publisher: "Cambridge University Press"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Corlett, R. T., Lakim, M. B., Kalko, E. K. V., &
  Pfeiffer, M. (2009). Seed consumption by small mammals from Borneo.
  Journal of Tropical Ecology, 25(5), 555-558.
  https://doi.org/10.1017/S0266467409990058

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2009), Journal of Tropical Ecology, 25(5), 555-558.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1017/S0266467409990058"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1017/S0266467409990058"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.
  arxiv: ""

  # Purpose: OpenAlex identifier.
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1017/S0266467409990058"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
# This short communication does not contain a separately labelled abstract.
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
image: "/images/images_publications/small-mammal-borneo_seed-consumption.png"

image_alt: >-
  Composite illustration showing the Bornean spiny rat Maxomys rajah alongside seeds recovered from faecal samples, including intact fig (Ficus) seeds that survived gut passage and fragmented remains of larger seeds damaged during consumption. The image represents contrasting outcomes of small mammal–seed interactions in tropical rain forests.

# Image caption
image_caption: >-
  Small mammals as seed consumers and potential seed dispersers in Bornean rain forests. The Bornean spiny rat (Maxomys rajah) is shown alongside examples of seeds recovered from faecal samples. Numerous intact fig (Ficus) seeds demonstrate that very small seeds can survive passage through the digestive tract and may subsequently be dispersed, whereas fragments of larger unidentified seeds illustrate seed predation. The study revealed that seed consumption is widespread among tropical rats and tree shrews, highlighting their diverse roles in seed dispersal and seed predation within forest regeneration processes.

image_license: "All rights reserved"
image_credit: "Konstans Wells"
image_license_verified: true

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20090901

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
      Seeds were detected in 138 of 701 faecal samples collected from 13 non-volant small-mammal species in Bornean forests.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      At least 11 seed morphotypes were distinguished from the faecal samples using seed size, shape, colour and surface characteristics.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Rat faecal samples contained seeds significantly more often than tree-shrew samples, with seeds present in 23% of rat samples and 13% of tree-shrew samples.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Leopoldamys sabanus had the highest observed proportion of faecal samples containing seeds among commonly sampled species, with seeds recorded in 48 of 145 samples.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Maxomys whiteheadi had significantly fewer seed-containing samples than Leopoldamys sabanus.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Fig seeds occurred in 74 of 701 samples and were recorded from nearly all commonly captured small-mammal species.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      A larger seed morphotype measuring approximately 2.5–6 millimetres was found intact in faeces of Leopoldamys sabanus, Tupaia longipes and Tupaia tana but commonly fragmented in samples from smaller Maxomys species and Niviventer cremoriventer.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      The largest swallowed seed recorded in the study measured 5.8 millimetres and occurred in a sample from Tupaia longipes.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-09
    text: >
      Seed occurrence in faeces of Leopoldamys sabanus and Maxomys rajah was significantly higher in logged forests than in unlogged forests.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-10
    text: >
      No clear difference in the identity of seed morphotypes was detected between logged and unlogged forests.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-11
    text: >
      Rats may contribute more substantially to tropical forest seed dispersal than previously assumed because they are abundant, species rich and active across multiple forest strata.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-12
    text: >
      Seed fate after ingestion is likely to vary among small-mammal species because body size, jaw strength, feeding behaviour and digestive physiology affect whether seeds remain intact.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-13
    text: >
      Tree shrews may disperse seeds over relatively short distances because their simple digestive tract produces rapid food passage.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-14
    text: >
      Forest logging can alter seed-consumption patterns indirectly by changing both small-mammal assemblages and the availability of fruit resources.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-15
    text: >
      Faecal seed screening can reveal broad patterns of frugivory and seed consumption but cannot determine dispersal effectiveness without seed identification and viability testing.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-16
    text: >
      Future research should quantify species-specific interaction strength, seed viability and dispersal distance across different forest types.
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
  This short communication examined visible seeds in 701 faecal samples from
  13 small-mammal species captured in three old-growth and three logged
  forests in Sabah, Malaysia. Seed occurrence, morphotype diversity and
  differences among rodents, squirrels, tree shrews and forest types were
  compared.

# Knowledge-network summary.
knowledge_summary: >
  The study provides evidence that diverse Bornean small mammals consume and
  potentially disperse seeds. Rodents had a higher incidence of seeds in
  faeces than tree shrews, figs were the most frequent identifiable seed
  resource, and seed integrity varied among host species. Higher seed
  occurrence in two rat species from logged forests suggests that land-use
  change can alter mammal–plant interaction strength.

# Scientific or societal significance.
impact_statement: >
  Small mammals may make an underappreciated contribution to tropical forest
  seed dispersal, but their functional roles differ among species and may
  change after logging.

# Non-technical summary.
plain_language_summary: >-
  Researchers found seeds in about one fifth of faecal samples collected from
  rats, squirrels and tree shrews in Borneo. Rats carried seeds more often
  than tree shrews, and fig seeds were especially common. Some animals passed
  larger seeds intact, while smaller rodents often damaged them. These
  differences may affect which small mammals act as useful seed dispersers.

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - ecological-interactions-system-dynamics
  - biodiversity-global-change
  - conservation-ecology
  - quantitative-ecology-modelling

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - seed-consumption
  - seed-dispersal
  - seed-predation
  - frugivory
  - mammal-plant-interactions
  - faecal-seed-dispersal
  - tropical-forest-regeneration
  - logging-effects
  - seed-viability
  - seed-morphotypes
  - fig-consumption
  - body-size-effects
  - digestive-retention-time
  - functional-diversity
  - mutualistic-interactions

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - seed-consumption
  - seed-dispersal
  - frugivory
  - mammal-plant-interactions
  - logging-effects
  - tropical-forest-regeneration

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - borneo-small-mammal-seed-interaction-system
  - sabah-logged-unlogged-forest-comparison
  - southeast-asian-tropical-rainforest
  - mammal-mediated-seed-dispersal

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species:
  - leopoldamys-sabanus
  - sundamys-muelleri
  - maxomys-rajah
  - maxomys-surifer
  - rattus-rattus
  - niviventer-cremoriventer
  - maxomys-baeodon
  - maxomys-whiteheadi
  - sundasciurus-lowii
  - tupaia-tana
  - tupaia-longipes
  - tupaia-gracilis
  - tupaia-minor
  - ficus

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - live-trapping
  - mark-recapture
  - faecal-sample-collection
  - light-microscopy
  - seed-extraction
  - seed-morphotype-classification
  - seed-photography
  - chi-square-testing
  - logged-unlogged-forest-comparison
  - comparative-diet-analysis

# Input environmental database/ data sources
data_products:
  - sabah-small-mammal-trapping-data
  - borneo-small-mammal-faecal-samples
  - seed-morphotype-photograph-collection

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
    object_id: richard-t-corlett

  - predicate: authored_by
    object_type: person
    object_id: maklarin-b-lakim

  - predicate: authored_by
    object_type: person
    object_id: elisabeth-k-v-kalko

  - predicate: authored_by
    object_type: person
    object_id: martin-pfeiffer

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-ulm

  - predicate: authored_by
    object_type: organisation
    object_id: national-university-of-singapore

  - predicate: authored_by
    object_type: organisation
    object_id: sabah-parks

  - predicate: authored_by
    object_type: organisation
    object_id: smithsonian-tropical-research-institute

  - predicate: addresses
    object_type: concept
    object_id: seed-consumption

  - predicate: addresses
    object_type: concept
    object_id: seed-dispersal

  - predicate: addresses
    object_type: concept
    object_id: frugivory

  - predicate: addresses
    object_type: concept
    object_id: logging-effects

  - predicate: involves
    object_type: taxon
    object_id: leopoldamys-sabanus

  - predicate: involves
    object_type: taxon
    object_id: tupaia-longipes

  - predicate: involves
    object_type: taxon
    object_id: ficus

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - tropical-forest-ecology
  - seed-dispersal-ecology
  - mammalogy
  - plant-animal-interactions
  - disturbance-ecology
  - conservation-biology
  - field-diet-analysis
  - functional-ecology
  - forest-regeneration

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why does the presence of intact seeds in faeces not by itself demonstrate effective seed dispersal?"
  - "What mechanisms could explain the higher frequency of seeds in rat faeces than in tree-shrew faeces?"
  - "How might body size and jaw strength influence whether swallowed seeds remain intact?"
  - "Why might seed consumption by Leopoldamys sabanus and Maxomys rajah increase in logged forests?"
  - "What ecological role do figs play in sustaining tropical small-mammal communities?"
  - "Which additional measurements are needed to quantify the contribution of each mammal species to plant recruitment?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Seed Consumption by Small Mammals from Borneo | Wells et al. 2009"

# Purpose: Search description.
seo_description: >-
  Faecal analysis of 13 Bornean small-mammal species showing frequent seed
  consumption, higher seed incidence in rats than tree shrews and altered
  patterns in logged forests.

# Purpose: Search keywords.
keywords:
  - Borneo
  - small mammals
  - seed consumption
  - seed dispersal
  - seed predation
  - frugivory
  - rodents
  - tree shrews
  - Muridae
  - Tupaiidae
  - figs
  - Ficus
  - faecal analysis
  - logged forest
  - unlogged forest
  - tropical forest regeneration
  - Leopoldamys sabanus
  - Tupaia longipes
  - Sabah

# Purpose: Social sharing metadata.
social:
  title: "Seed Consumption by Small Mammals from Borneo"
  description: >-
    Wells and colleagues show that Bornean rats and tree shrews frequently
    consume seeds and may differ substantially in their seed-dispersal roles.
  image: "images/images_publications/Seed-consumption-small-mammals-borneo_Wells-2009.png"
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
  source_url: "https://doi.org/10.1017/S0266467409990058"

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
