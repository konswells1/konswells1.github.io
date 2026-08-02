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
id: 2005-wells-rat-seed-predation-removal

# Purpose: Official publication title.
title: "Eat in or take away – seed predation and removal by rats (Muridae) during a fruiting event in a dipterocarp rainforest"

# Purpose: Short display title.
short_title: "Rat seed predation and removal in dipterocarp rainforest"

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
date: 2005-12-31

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
- Robert Bagchi

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
    name: "Robert Bagchi"
    # Purpose: Canonical BAHE person id.
    person_id: robert-bagchi
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-sheffield

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

  robert-bagchi:
    - conceptualization
    - methodology
    - investigation
    - data-curation
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

  - funder_name: "Natural Environment Research Council"
    funder_id: nerc
    grant_number: ""
    grant_title: ""

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "The Raffles Bulletin of Zoology"

# Purpose: Journal volume.
volume: "53"

# Purpose: Journal issue.
issue: "2"

# Purpose: Article pages or article number.
pages: "281-286"

# Purpose: Publisher.
publisher: "National University of Singapore"

# Purpose: Open-access availability. # Values: true, false
open_access: true

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., & Bagchi, R. (2005). Eat in or take away – seed predation
  and removal by rats (Muridae) during a fruiting event in a dipterocarp
  rainforest. The Raffles Bulletin of Zoology, 53(2), 281-286.

# Purpose: Short citation.
citation_short: >-
  Wells and Bagchi (2005), The Raffles Bulletin of Zoology, 53(2), 281-286.

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
pdf: "https://lkcnhm.nus.edu.sg/wp-content/uploads/sites/11/app/uploads/2017/06/53rbz281-286.pdf"

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Seed predators are considered important in the evolution of mast fruiting. Mast events in turn
  provide an abundant food resource for consumers, but only for a limited period of time. In this study seed
  removal experiments, feeding trials and small mammal trapping were used to determine the potential of
  forest rats (Muridae) as predators and dispersers of two tree species, Lithocarpus gracilis (Fagaceae) and
  Parashorea malaanonan (Dipterocarpaceae) during a minor fruiting event in a dipterocarp rainforest at Danum
  Valley (Sabah, Malaysia) in Sept/Oct 2004. Seeds of both species were exploited by rodents at similar
  frequencies. Nearly all seeds exploited were removed from the feeding stations. Seeds placed near burrows
  of Maxomys rajah were moved into the burrows. Gnawed seeds collected in fruit fall traps (8% of total
  collected) indicated that Parashorea seeds were also exploited in the canopy. Partially eaten seeds often
  retained their ability to germinate. Captive rats ate a range of dipterocarp and other hard-shelled seed and
  feeding on an individual seed could take up to 27 minutes. Trap success for rats, but not tree shrews (Tupaiidae)
  and civets (Viverridae), decreased during the fruiting season. This supports the idea that this group benefits
  from mast fruiting. Rats are evidently important predators of the seeds of these tree species, both before and
  after dispersal. However, due to the removal of seeds before eating, long consumption times and the ability
  of partially consumed seeds to germinate, they may also function as secondary dispersal agents.


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
  pdf: "https://lkcnhm.nus.edu.sg/wp-content/uploads/sites/11/app/uploads/2017/06/53rbz281-286.pdf"
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
image: "/images/images_publications/rats-borneo_seed-removal.png"
image_alt: >-
  Composite image illustrating seed predation and removal by forest rats during a dipterocarp mast-fruiting event in Borneo. Shown are Lithocarpus sp. seeds, a Whitehead's spiny rat (Maxomys whiteheadi) feeding on a fresh dipterocarp seed, a spool-line experiment tracing seed removal into the concealed burrow of a Rajah spiny rat (Maxomys rajah/M. surifer), falling dipterocarp seeds during mast fruiting, and newly germinated dipterocarp seedlings. The sequence illustrates the ecological pathways linking seed production, rodent foraging, seed movement and forest regeneration.

# Image caption
image_caption: >-
  Seed predation, seed removal and forest regeneration during a Bornean mast-fruiting event. Clockwise from upper left: fruits of the stone oak Lithocarpus sp.; the spectacular rain of dipterocarp seeds during a mast-fruiting event in Danum Valley Conservation Area; newly germinated dipterocarp seedlings emerging after seed fall; a spool-line experiment showing a seed removed into the concealed burrow of a spiny rat (Maxomys rajah/M. surifer), whose entrance was sealed with leaf litter after the animal entered; and a Whitehead's spiny rat (Maxomys whiteheadi) consuming a fresh dipterocarp seed. Together, these images illustrate how tropical forest rodents influence seed fate through predation, transport and temporary storage, processes that can simultaneously reduce seed survival while contributing to secondary seed dispersal and subsequent forest regeneration.

image_license: "All rights reserved"
image_credit: "Konstans Wells"
image_license_verified: true

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20051231

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
      Rats exploited Parashorea malaanonan and Lithocarpus gracilis seeds at similar frequencies during a partial fruiting event in lowland dipterocarp rainforest.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Nine of 55 Parashorea malaanonan seeds and 11 of 55 Lithocarpus gracilis seeds were exploited at experimental feeding stations.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Most exploited seeds were removed from their feeding stations rather than consumed at the point of encounter.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Seeds placed near Maxomys rajah burrows were moved into the burrows, demonstrating directed transport to protected locations.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Lithocarpus gracilis seeds were more frequently displaced than Parashorea malaanonan seeds, and two displaced Lithocarpus seeds were found buried.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Eight percent of Parashorea malaanonan seeds collected in seed traps showed rodent damage, indicating that seed exploitation also occurred in the canopy.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Some partially consumed Parashorea malaanonan seeds retained the capacity to germinate.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Captive Maxomys rats consumed several dipterocarp and other hard-shelled seed species but rejected the tested Ficus, Aglaia and Tetrastigma fruits.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-09
    text: >
      Feeding on a single Parashorea malaanonan seed lasted for as long as 27 minutes.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-10
    text: >
      Captive rats commonly moved seeds before feeding and sometimes concealed Lithocarpus gracilis seeds under leaves or in cage corners.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-11
    text: >
      Rat capture rates declined significantly during the fruiting period, whereas capture rates of tree shrews and civets did not show the same decline.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-12
    text: >
      Reduced rat trap success during fruiting is consistent with abundant natural seeds reducing attraction to banana-baited traps.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-13
    text: >
      Rapidly germinating dipterocarp seeds are more likely to be moved for protected consumption, whereas slowly germinating Lithocarpus seeds are more suitable for caching.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-14
    text: >
      Rats can function simultaneously as seed predators and secondary seed dispersers because they transport seeds, cache some seeds and may leave partially consumed seeds viable.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-15
    text: >
      Rodent seed exploitation extends across forest strata and may operate over longer periods through caching than seed predation by larger, more mobile mammals.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-16
    text: >
      Future studies should track removed seeds to their final fate and quantify caching, seed survival and seedling recruitment under contrasting levels of forest disturbance.
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
  This study combined seed-removal experiments, captive feeding trials,
  canopy seed traps and small-mammal trapping to assess how rats handled
  Parashorea malaanonan and Lithocarpus gracilis seeds during a partial
  fruiting event at Danum Valley, Sabah.

# Knowledge-network summary.
knowledge_summary: >
  The study demonstrates that Bornean rats are important consumers of both
  dipterocarp and stone-oak seeds, but seed removal does not always lead to
  immediate destruction. Transport to burrows, burial of Lithocarpus seeds,
  long handling times and survival of some partially eaten seeds create
  pathways through which rats may also contribute to secondary dispersal.

# Scientific or societal significance.
impact_statement: >
  Rodents can influence tropical tree recruitment through a context-dependent
  balance of seed predation, transport, caching and incomplete consumption.

# Non-technical summary.
plain_language_summary: >-
  Rats in a Bornean rainforest often carried seeds away before eating them.
  Some seeds were taken into burrows, and a few stone-oak seeds were buried.
  Although many seeds were destroyed, some partly eaten seeds still
  germinated. Rats therefore acted not only as seed predators but also as
  possible seed dispersers.

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
  - seed-predation
  - seed-removal
  - secondary-seed-dispersal
  - scatter-hoarding
  - mast-fruiting
  - predator-satiation
  - rodent-plant-interactions
  - seed-fate
  - seed-caching
  - partial-seed-consumption
  - germination-after-predation
  - canopy-seed-predation
  - fruiting-season
  - dipterocarp-regeneration
  - resource-pulses

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - seed-predation
  - seed-removal
  - secondary-seed-dispersal
  - scatter-hoarding
  - mast-fruiting
  - predator-satiation

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - danum-valley-seed-consumer-system
  - borneo-rat-seed-interaction-system
  - dipterocarp-fruiting-event
  - southeast-asian-lowland-rainforest

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species:
  - parashorea-malaanonan
  - lithocarpus-gracilis
  - maxomys-rajah
  - maxomys-surifer
  - maxomys-whiteheadi
  - leopoldamys-sabanus
  - niviventer-cremoriventer
  - muridae

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - seed-removal-experiment
  - seed-choice-experiment
  - captive-feeding-trial
  - canopy-seed-trap
  - seed-germination-assay
  - live-trapping
  - seasonal-trap-success-comparison
  - shannon-wiener-diversity
  - seed-fate-classification
  - burrow-proximity-experiment

# Input environmental database/ data sources
data_products:
  - danum-valley-seed-removal-data
  - captive-rat-feeding-observations
  - parashorea-seed-trap-data
  - seasonal-small-mammal-trapping-data

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
    object_id: robert-bagchi

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-ulm

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-sheffield

  - predicate: addresses
    object_type: concept
    object_id: seed-predation

  - predicate: addresses
    object_type: concept
    object_id: seed-removal

  - predicate: addresses
    object_type: concept
    object_id: secondary-seed-dispersal

  - predicate: addresses
    object_type: concept
    object_id: scatter-hoarding

  - predicate: involves
    object_type: taxon
    object_id: parashorea-malaanonan

  - predicate: involves
    object_type: taxon
    object_id: lithocarpus-gracilis

  - predicate: involves
    object_type: taxon
    object_id: maxomys-rajah

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - tropical-forest-ecology
  - seed-dispersal-ecology
  - plant-animal-interactions
  - mammalogy
  - mast-fruiting
  - predator-satiation
  - disturbance-ecology
  - forest-regeneration
  - field-experimental-design

# Purpose: Suggested discussion questions.
discussion_questions:
  - "When should seed removal be interpreted as predation, dispersal or an unresolved seed fate?"
  - "Why might Lithocarpus seeds be more suitable for scatter-hoarding than dipterocarp seeds?"
  - "How can long seed-handling times alter where rats consume seeds?"
  - "What does lower rat trap success during fruiting imply about resource availability and trapping bias?"
  - "How might rodent seed predation differ from predation by bearded pigs during mast and non-mast years?"
  - "What evidence would be needed to demonstrate that rat-mediated seed movement improves plant recruitment?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Rat Seed Predation and Removal in Bornean Rainforest | Wells & Bagchi 2005"

# Purpose: Search description.
seo_description: >-
  Seed-removal and feeding experiments showing that Bornean rats act as both
  seed predators and potential secondary dispersers of Parashorea and
  Lithocarpus seeds.

# Purpose: Search keywords.
keywords:
  - Borneo
  - Danum Valley
  - seed predation
  - seed removal
  - seed dispersal
  - scatter hoarding
  - mast fruiting
  - predator satiation
  - Parashorea malaanonan
  - Lithocarpus gracilis
  - Maxomys rajah
  - Leopoldamys sabanus
  - Muridae
  - dipterocarp rainforest
  - seed caching
  - tropical forest regeneration
  - rodent plant interactions
  - seed fate

# Purpose: Social sharing metadata.
social:
  title: "Rat Seed Predation and Removal in Bornean Rainforest"
  description: >-
    Wells and Bagchi show that rainforest rats both destroy and transport tree
    seeds, creating potential pathways for secondary dispersal.
  image: "images/images_publications/Rat-seed-predation-removal_Wells-Bagchi-2005.png"
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
    claims: needs-verification
    summaries: needs-verification
    concept_classification: unreviewed

---
