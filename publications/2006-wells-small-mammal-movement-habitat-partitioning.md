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
id: 2006-wells-small-mammal-movement-habitat-partitioning

# Purpose: Official publication title.
title: "Movement trajectories and habitat partitioning of small mammals in logged and unlogged rain forests on Borneo"

# Purpose: Short display title.
short_title: "Small-mammal movement and habitat partitioning in Borneo"

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
date: 2006-09-01

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
- Elisabeth K. V. Kalko

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
    name: "Elisabeth K. V. Kalko"
    # Purpose: Canonical BAHE person id.
    person_id: elisabeth-k-v-kalko
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-ulm
      - smithsonian-tropical-research-institute

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

  elisabeth-k-v-kalko:
    - conceptualization
    - methodology
    - supervision
    - resources
    - funding-acquisition
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
journal_name: "Journal of Animal Ecology"

# Purpose: Journal volume.
volume: "75"

# Purpose: Journal issue.
issue: "5"

# Purpose: Article pages or article number.
pages: "1212-1223"

# Purpose: Publisher.
publisher: "British Ecological Society / Blackwell Publishing"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Pfeiffer, M., Lakim, M. B., & Kalko, E. K. V. (2006).
  Movement trajectories and habitat partitioning of small mammals in logged
  and unlogged rain forests on Borneo. Journal of Animal Ecology, 75(5),
  1212-1223. https://doi.org/10.1111/j.1365-2656.2006.01144.x

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2006), Journal of Animal Ecology, 75(5), 1212-1223.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1111/j.1365-2656.2006.01144.x"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1111/j.1365-2656.2006.01144.x"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1111/j.1365-2656.2006.01144.x"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  1. Non-volant animals in tropical rain forests differ in their ability to exploit the habitat above the forest floor and also in their response to habitat variability. It is predicted that specific movement trajectories are determined both by intrinsic factors such as ecological specialization, morphology and body size and by structural features of the surrounding habitat such as undergrowth and availability of supportive structures.
  2. We applied spool-and-line tracking in order to describe movement trajectories and habitat segregation of eight species of small mammals from an assemblage of Muridae, Tupaiidae and Sciuridae in the rain forest of Borneo where we followed a total of 13 525 m path. We also analysed specific changes in the movement patterns of the small mammals in relation to habitat stratification between logged and unlogged forests. Variables related to climbing activity of the tracked species as well as the supportive structures of the vegetation and undergrowth density were measured along their tracks.
  3. Movement patterns of the small mammals differed significantly between species. Most similarities were found in congeneric species that converged strongly in body size and morphology. All species were affected in their movement patterns by the altered forest structure in logged forests with most differences found in Leopoldamys sabanus. However, the large proportions of short step lengths found in all species for both forest types and similar path tortuosity suggest that the main movement strategies of the small mammals were not influenced by logging but comprised generally a response to the heterogeneous habitat as opposed to random movement strategies predicted for homogeneous environments.
  4. Overall shifts in microhabitat use showed no coherent trend among species. Multivariate principal component analysis revealed contrasting trends for convergent species, in particular for Maxomys rajah and M. surifer as well as for Tupaia longipes and T. tana, suggesting that each species was uniquely affected in its movement trajectories by a multiple set of environmental and intrinsic features.

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
image: "/images/images_publications/Small-mammal-movement-habitat-partitioning_Wells-2006.png"

image_alt: >-
  Principal-components plots and species illustrations comparing vertical
  habitat use and movement trajectories of eight Bornean small-mammal species
  in logged and unlogged rain forest. The figures summarize climbing,
  above-ground movement, maximum height, log use, support diameter,
  undergrowth density, step length and turning-angle patterns.

# Image caption  
image_caption: >-
  Movement and habitat partitioning of eight small-mammal species in Bornean
  rain forest. Species differed in vertical activity and substrate use, while
  comparison of logged and unlogged forests showed species-specific shifts
  rather than a uniform response to forest disturbance. Congeneric species
  with similar morphology often occupied nearby regions of multivariate
  movement space but changed in contrasting directions after logging.

image_license: "All rights reserved"
image_credit: "Wells et al. (2006)"
image_license_verified: false  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20060901

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
      Spool-and-line tracking produced 212 movement tracks totalling 13,525 metres from at least 188 individuals of eight small-mammal species in Borneo.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Movement trajectories differed significantly among species in climbing activity, above-ground movement, maximum height, support use, undergrowth use, step length and turning angle.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Congeneric species with similar body size and morphology, including Maxomys rajah and Maxomys surifer and Tupaia longipes and Tupaia tana, showed the strongest similarities in movement and habitat use.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Principal component analysis identified above-ground activity as the dominant axis of interspecific movement differentiation, explaining 54% of total variation.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Body mass was positively associated with step length but not with climbing activity or the diameter of supportive structures used.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Relative hind-foot and tail dimensions were associated with above-ground movement and support use, indicating that morphology rather than body size alone structures vertical habitat exploitation.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      All focal species changed at least some aspects of their movement trajectories between logged and unlogged forests.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Leopoldamys sabanus exhibited the largest number of movement changes between forest types, including shifts in above-ground activity, log use, support diameter, undergrowth use, step length and turning angle.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-09
    text: >
      Tupaia longipes and Leopoldamys sabanus increased above-ground movement in logged forest, whereas Maxomys rajah reduced above-ground activity.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-10
    text: >
      Species pairs with similar morphology changed in contrasting directions between logged and unlogged forest, showing that convergent body form did not produce uniform disturbance responses.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-11
    text: >
      The frequency distributions of step lengths and overall path tortuosity were similar between logged and unlogged forests despite significant changes in specific habitat-use variables.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-12
    text: >
      The prevalence of short steps and stable path tortuosity across species and forest types indicates movement adapted to heterogeneous habitat rather than simple random-walk behaviour.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-13
    text: >
      Bornean small mammals can be partitioned into terrestrial, scansorial and arboreal movement guilds, but these categories form a continuum rather than a strict ground–canopy dichotomy.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-14
    text: >
      Forest logging alters the structural context of movement but does not necessarily replace the fundamental small-scale movement strategy used by a species.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-15
    text: >
      Movement ecology studies of tropical small mammals should measure both trajectory geometry and the structural substrates used along paths rather than relying solely on trapping locations.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-16
    text: >
      Species-specific responses to altered forest structure limit the reliability of broad functional-group generalisations for predicting persistence in logged tropical forests.
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
  This study used spool-and-line tracking to quantify 13.5 kilometres of
  movement by eight small-mammal species across three logged and three
  unlogged forests in Sabah, Borneo. Vertical habitat use, substrate
  characteristics, undergrowth density, step lengths and turning angles were
  compared among species and forest types.

# Knowledge-network summary.
knowledge_summary: >
  The study demonstrates that fine-scale movement trajectories reveal
  ecological differentiation not captured by trapping records alone.
  Species segregated along gradients of vertical activity, support use and
  undergrowth structure, with morphology contributing more strongly than body
  size to climbing behaviour. Logging changed movement in every focal species,
  but responses were idiosyncratic and did not alter the shared underlying
  strategy of short, tortuous movement through heterogeneous forest habitat.

# Scientific or societal significance.
impact_statement: >
  Predicting small-mammal persistence in logged forests requires
  species-specific movement and substrate-use data because structurally
  similar species can respond in opposite ways to habitat alteration.

# Non-technical summary.  
plain_language_summary: >-
  Researchers followed the paths of small mammals through intact and logged
  Bornean forests using lightweight thread spools. Different species used the
  ground, logs, vines and low vegetation in distinct ways. Logging changed
  these details for every species, but there was no single shared response:
  some animals climbed more, while others climbed less.  

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
  - animal-movement
  - movement-trajectories
  - habitat-partitioning
  - vertical-habitat-use
  - forest-logging
  - habitat-heterogeneity
  - microhabitat-selection
  - scansoriality
  - arboreality
  - substrate-use
  - step-length-distribution
  - path-tortuosity
  - morphological-adaptation
  - species-specific-disturbance-response
  - tropical-forest-degradation

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - animal-movement
  - habitat-partitioning
  - vertical-habitat-use
  - forest-logging
  - morphological-adaptation
  - species-specific-disturbance-response

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - borneo-small-mammal-movement-system
  - sabah-logged-unlogged-forest-comparison
  - southeast-asian-dipterocarp-rainforest
  - tropical-small-mammal-habitat-partitioning

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - leopoldamys-sabanus
  - maxomys-rajah
  - maxomys-surifer
  - niviventer-cremoriventer
  - sundasciurus-lowii
  - tupaia-longipes
  - tupaia-tana
  - tupaia-gracilis
  - tupaia-minor

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - spool-and-line-tracking
  - live-trapping
  - mark-recapture
  - pit-tagging
  - movement-path-reconstruction
  - step-length-analysis
  - turning-angle-analysis
  - path-tortuosity-analysis
  - vertical-habitat-classification
  - support-diameter-measurement
  - undergrowth-density-classification
  - principal-components-analysis
  - nonparametric-comparative-analysis
  - log-log-regression
  - multivariate-habitat-use-analysis

# Input environmental database/ data sources
data_products:
  - borneo-small-mammal-spool-tracking-data
  - six-site-logged-unlogged-forest-survey
  - sabah-parks-small-mammal-reference-data

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
    object_id: elisabeth-k-v-kalko

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-ulm

  - predicate: authored_by
    object_type: organisation
    object_id: sabah-parks

  - predicate: authored_by
    object_type: organisation
    object_id: smithsonian-tropical-research-institute

  - predicate: addresses
    object_type: concept
    object_id: animal-movement

  - predicate: addresses
    object_type: concept
    object_id: habitat-partitioning

  - predicate: addresses
    object_type: concept
    object_id: forest-logging

  - predicate: addresses
    object_type: concept
    object_id: species-specific-disturbance-response

  - predicate: involves
    object_type: taxon
    object_id: leopoldamys-sabanus

  - predicate: involves
    object_type: taxon
    object_id: tupaia-longipes

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - movement-ecology
  - tropical-forest-ecology
  - mammalogy
  - habitat-selection
  - disturbance-ecology
  - conservation-biology
  - multivariate-ecology
  - field-tracking-methods
  - functional-morphology

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why does spool-and-line tracking reveal habitat use that conventional live trapping cannot?"
  - "How do morphology and body size differ in their relationships with climbing and step length?"
  - "Why did congeneric species with similar morphology sometimes respond differently to logging?"
  - "What does the persistence of similar path tortuosity across forest types imply about movement strategy?"
  - "How does fine-scale structural complexity in logged forest alter opportunities for scansorial movement?"
  - "What limitations arise when tracking animals that move into the upper canopy?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Small-Mammal Movement in Logged and Unlogged Borneo | Wells et al. 2006"

# Purpose: Search description.
seo_description: >-
  Spool-and-line study showing species-specific movement and habitat
  partitioning among eight small mammals across logged and unlogged Bornean
  rain forests.

# Purpose: Search keywords.
keywords:
  - Borneo
  - small mammals
  - movement trajectories
  - habitat partitioning
  - spool-and-line tracking
  - logged forest
  - unlogged forest
  - vertical habitat use
  - scansorial mammals
  - arboreal mammals
  - step length
  - path tortuosity
  - undergrowth density
  - support diameter
  - Leopoldamys sabanus
  - Maxomys rajah
  - Tupaia longipes
  - forest degradation
  - movement ecology

# Purpose: Social sharing metadata.
social:
  title: "Small-Mammal Movement in Logged and Unlogged Borneo"
  description: >-
    Wells and colleagues reveal species-specific movement and habitat-use
    responses to logging in Bornean small mammals.
  image: "images/images_publications/Small-mammal-movement-habitat-partitioning_Wells-2006.png"
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
  source_url: "https://doi.org/10.1111/j.1365-2656.2006.01144.x"

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
