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
id: 2008-wells-leopoldamys-movement-ranging-logging

# Purpose: Official publication title.
title: "Movement and ranging patterns of a tropical rat (Leopoldamys sabanus) in logged and unlogged rain forests"

# Purpose: Short display title.
short_title: "Movement and ranging of Leopoldamys sabanus"

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
year_published: 2008

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2008-06-05

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

authors:
- Konstans Wells
- Elisabeth K. V. Kalko
- Maklarin B. Lakim
- Martin Pfeiffer

bahe_authors:
  - konstans-wells

author_entities:
  - position: 1
    name: "Konstans Wells"
    person_id: konstans-wells
    orcid: "0000-0003-0377-2463"
    affiliation_ids:
      - university-of-ulm

  - position: 2
    name: "Elisabeth K. V. Kalko"
    person_id: elisabeth-k-v-kalko
    orcid: ""
    affiliation_ids:
      - university-of-ulm
      - smithsonian-tropical-research-institute

  - position: 3
    name: "Maklarin B. Lakim"
    person_id: maklarin-b-lakim
    orcid: ""
    affiliation_ids:
      - sabah-parks

  - position: 4
    name: "Martin Pfeiffer"
    person_id: martin-pfeiffer
    orcid: ""
    affiliation_ids:
      - university-of-ulm

# =======
# Author contributions
# =======

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
  elisabeth-k-v-kalko:
    - conceptualization
    - methodology
    - supervision
    - resources
    - interpretation
    - writing-review-editing
  maklarin-b-lakim:
    - investigation
    - resources
    - field-logistics
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

project_funding:
  - funder_name: "German Academic Exchange Service"
    funder_id: daad
    grant_number: ""
    grant_title: ""

# =======
# Bibliographic metadata
# =======

journal_name: "Journal of Mammalogy"
volume: "89"
issue: "3"
pages: "712-720"
publisher: "American Society of Mammalogists"
open_access: false
license: "All rights reserved"

citation_full: >-
  Wells, K., Kalko, E. K. V., Lakim, M. B., & Pfeiffer, M. (2008).
  Movement and ranging patterns of a tropical rat (Leopoldamys sabanus)
  in logged and unlogged rain forests. Journal of Mammalogy, 89(3),
  712-720. https://doi.org/10.1644/07-MAMM-A-074R2.1

citation_short: >-
  Wells et al. (2008), Journal of Mammalogy, 89(3), 712-720.

identifiers:
  doi: "10.1644/07-MAMM-A-074R2.1"
  publisher_url: "https://doi.org/10.1644/07-MAMM-A-074R2.1"
  pmid: ""
  arxiv: ""
  openalex: ""
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1644/07-MAMM-A-074R2.1"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
# The original abstract is intentionally excluded because it is copyrighted.
abstract_original: ""
abstract_source: publisher
abstract_verbatim: false
abstract_public_display: false

# =======
# Resources and media
# =======

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

image: "/images/images_publications/leopoldamys-sabanus.png"

image_alt: >-
  Long-tailed giant rat (Leopoldamys sabanus) climbing along a tree branch in
  lowland Bornean rainforest. The species is an agile, scansorial forest rodent
  used to investigate movement behaviour across logged and old-growth forests.
  
image_caption: >-
  Long-tailed giant rat (Leopoldamys sabanus) photographed while climbing in
  Bornean rainforest. This common forest rodent was the focal species for
  quantifying fine-scale movement paths and home-ranging behaviour in logged
  and unlogged tropical forests, providing insights into how forest
  disturbance influences animal movement and habitat connectivity. Photograph
  © Konstans Wells.

image_license: "All rights reserved"
image_credit: "Konstans Wells"
image_license_verified: true

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false
order: 20080605

# =======
# Knowledge statements
# =======

knowledge_statements:
  - id: statement-01
    text: >
      Fine-scale movements of Leopoldamys sabanus were quantified from 49 spool-and-line tracks, while larger-scale ranging was measured by radiotracking 16 individuals for at least four consecutive nights.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-02
    text: >
      Step-length distributions followed a power-law pattern and did not differ significantly between logged and unlogged forests.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-03
    text: >
      Mean turning angles and the frequency of persistent, relatively straight fine-scale paths did not differ between forest types.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-04
    text: >
      Approximately two thirds of spool-and-line tracks showed directional persistence rather than random turning.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-05
    text: >
      Radiotracked rats were active for an average of approximately 485 minutes per night and travelled about 1,443 metres per night.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-06
    text: >
      Nightly activity duration, total distance travelled and movement speed did not differ significantly between logged and unlogged forests or between sexes.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-07
    text: >
      Movement-speed distributions resembled Lévy-walk patterns, with many short movements interspersed with occasional long movements.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-08
    text: >
      Consecutive movement speeds were serially correlated, indicating that rats often made clusters of short, slow movements within local areas.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-09
    text: >
      Nocturnal home ranges varied from approximately 2,083 to 9,829 square metres, while core ranges varied from 594 to 1,535 square metres.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-10
    text: >
      Home-range and core-range sizes did not differ significantly between logged and unlogged forests or between sexes.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-11
    text: >
      Individual variation in movement speed, activity duration, nightly path length and range size was substantially greater than variation explained by forest type or sex.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-12
    text: >
      Local habitat structure and patchy resource distributions are more plausible drivers of movement variation than the broad classification of forest as logged or unlogged.
    knowledge_type: interpretation
    attributed_to: source-publication
  - id: statement-13
    text: >
      Logging-related changes in vegetation structure do not necessarily translate into detectable movement or ranging changes for a common habitat-generalist rat.
    knowledge_type: interpretation
    attributed_to: source-publication
  - id: statement-14
    text: >
      Plasticity in movement and search behaviour may allow common small mammals to persist in logged forests when sufficient environmental heterogeneity and resources remain.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication
  - id: statement-15
    text: >
      Movement responses to habitat modification should be studied at multiple spatial scales because fine-scale trajectories and larger-scale ranging may respond to different ecological drivers.
    knowledge_type: methodological-proposition
    attributed_to: source-publication
  - id: statement-16
    text: >
      Conservation assessments should avoid assuming that broad structural differences between logged and unlogged forests predict movement responses for all small-mammal species.
    knowledge_type: recommendation
    attributed_to: source-publication

# =======
# Summaries
# =======

summary: >
  This study compared fine-scale movement trajectories and larger-scale
  nocturnal ranging of the long-tailed giant rat Leopoldamys sabanus in three
  logged and three unlogged forests in Sabah, Malaysia. Spool-and-line
  tracking quantified step lengths and turning angles, while radiotelemetry
  measured movement speed, nightly activity and home-range size.

knowledge_summary: >
  The study found no strong effect of logging on movement geometry, activity,
  speed or home-range size. Instead, substantial differences among
  individuals dominated the data. Movement paths combined clusters of short,
  slow moves with occasional long movements, consistent with searching in a
  patchy rainforest resource landscape.

impact_statement: >
  Broad forest categories were poor predictors of movement in a common
  generalist rat, highlighting the importance of local habitat heterogeneity
  and species-specific behavioural plasticity.

plain_language_summary: >-
  Researchers tracked giant rats in logged and intact Bornean forests using
  thread spools and radio collars. The rats moved similar distances, at
  similar speeds and across similar-sized areas in both forest types.
  Differences among individual rats were much larger than differences between
  logged and unlogged forest.

# =======
# BAHE knowledge-network relationships
# =======

research_themes:
  - ecological-interactions-system-dynamics
  - biodiversity-global-change
  - conservation-ecology

concepts:
  - animal-movement
  - movement-trajectories
  - home-range
  - radiotelemetry
  - spool-and-line-tracking
  - logged-forest
  - habitat-heterogeneity
  - resource-patchiness
  - movement-plasticity
  - levy-walk
  - path-persistence
  - step-length-distribution
  - movement-speed
  - individual-variation
  - multiscale-movement-ecology

display_concepts:
  - animal-movement
  - home-range
  - logged-forest
  - movement-plasticity
  - resource-patchiness
  - multiscale-movement-ecology

study_systems:
  - borneo-leopoldamys-movement-system
  - sabah-logged-unlogged-forest-comparison
  - southeast-asian-dipterocarp-rainforest
  - tropical-small-mammal-ranging

focal_species:
  - leopoldamys-sabanus

methods:
  - live-trapping
  - pit-tagging
  - spool-and-line-tracking
  - radiotelemetry
  - radio-triangulation
  - step-length-analysis
  - turning-angle-analysis
  - rayleigh-circular-statistics
  - power-law-analysis
  - mantel-correlogram
  - fixed-kernel-home-range
  - linear-mixed-effects-model
  - movement-speed-analysis
  - multiscale-movement-analysis

data_products:
  - leopoldamys-spool-track-data
  - leopoldamys-radiotelemetry-data
  - six-site-logged-unlogged-forest-survey

research_datasets: []

projects:
  - borneo-small-mammal-forest-ecology

# =======
# Typed graph relationships
# =======

relationships:
  - predicate: authored_by
    object_type: person
    object_id: konstans-wells
  - predicate: authored_by
    object_type: person
    object_id: elisabeth-k-v-kalko
  - predicate: authored_by
    object_type: person
    object_id: maklarin-b-lakim
  - predicate: authored_by
    object_type: person
    object_id: martin-pfeiffer
  - predicate: authored_by
    object_type: organisation
    object_id: university-of-ulm
  - predicate: authored_by
    object_type: organisation
    object_id: smithsonian-tropical-research-institute
  - predicate: authored_by
    object_type: organisation
    object_id: sabah-parks
  - predicate: addresses
    object_type: concept
    object_id: animal-movement
  - predicate: addresses
    object_type: concept
    object_id: home-range
  - predicate: addresses
    object_type: concept
    object_id: movement-plasticity
  - predicate: addresses
    object_type: concept
    object_id: logged-forest
  - predicate: involves
    object_type: taxon
    object_id: leopoldamys-sabanus

# =======
# Teaching and discussion
# =======

teaching_uses:
  - movement-ecology
  - mammalogy
  - tropical-forest-ecology
  - radiotelemetry
  - home-range-analysis
  - disturbance-ecology
  - conservation-biology
  - behavioural-ecology
  - mixed-effects-modelling

discussion_questions:
  - "Why might individual variation exceed the effect of forest type on movement and ranging?"
  - "What ecological processes could produce clusters of short moves interrupted by occasional long movements?"
  - "How do spool-and-line tracking and radiotelemetry capture different spatial scales of movement?"
  - "Why does the absence of a logging effect in Leopoldamys sabanus not imply that logging is harmless to all small mammals?"
  - "What limitations arise from telemetry error and short tracking duration when estimating home ranges?"
  - "How might behavioural plasticity contribute to persistence in logged forests?"

# =======
# Search and discovery metadata
# =======

seo_title: "Movement and Ranging of Leopoldamys sabanus in Logged Forests | Wells et al. 2008"
seo_description: >-
  Multiscale tracking study showing similar movement speed, activity and
  home-range size of Leopoldamys sabanus in logged and unlogged Bornean rain
  forests.

keywords:
  - Leopoldamys sabanus
  - long-tailed giant rat
  - Borneo
  - animal movement
  - home range
  - radiotelemetry
  - spool-and-line tracking
  - logged forest
  - unlogged forest
  - movement trajectories
  - movement speed
  - Levy walk
  - habitat heterogeneity
  - individual variation
  - Sabah
  - tropical rainforest
  - behavioural plasticity

social:
  title: "Movement and Ranging of Leopoldamys sabanus"
  description: >-
    Wells and colleagues show that movement and home-range patterns of a
    common Bornean rat were similar in logged and unlogged forests.
  image: "images/images_publications/Leopoldamys-movement-ranging-logging_Wells-2008.png"
  card: summary_large_image

# =======
# Attribution and reuse
# =======

attribution_note: >
  This BAHE knowledge object summarises and contextualises the peer-reviewed
  publication for research, teaching and interdisciplinary synthesis.
  Scientific arguments and findings should be attributed to and cited from
  the original publication.

license_note: >
  The original abstract is intentionally excluded. The article is subject to
  the publisher's copyright and reuse conditions. Reuse of article text or
  figures requires compliance with the licence and permissions stated by the
  publisher.

# =======
# Provenance and curation
# =======

curation:
  status: unreviewed
  reviewed_by: ""
  reviewed_on: ""

provenance:
  source_type:
    - publisher-pdf
  source_url: "https://doi.org/10.1644/07-MAMM-A-074R2.1"
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
