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
id: 2013-wells-tick-mammal-host-specificity

# Purpose: Official publication title.
title: "Inferring host specificity and network formation through agent-based models: tick–mammal interactions in Borneo"

# Purpose: Short display title.
short_title: "Tick–mammal host specificity in Borneo"

# Purpose: BAHE object class.
# Values: publication
object_type: publication

# Purpose: Publication category.
# Values: research-article, review, methods, perspective, commentary
publication_type: methods

# Purpose: Publication subtype.
# Values: empirical-study, systematic-review, scoping-review, topical-review, meta-analysis, simulation-study, conceptual-framework, protocol
publication_subtype: empirical-study

# Purpose: Publication workflow status.
# Values: draft, submitted, accepted, published, archived
status: published

# Purpose: Publication year. # Format: YYYY
year_published: 2013

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2013-05-01

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
- Robert B. O’Hara
- Martin Pfeiffer
- Maklarin B. Lakim
- Trevor N. Petney
- Lance A. Durden

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
      - sabah-parks

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Robert B. O’Hara"
    # Purpose: Canonical BAHE person id.
    person_id: robert-b-ohara
    # Purpose: ORCID identifier.
    orcid: "0000-0001-9737-3724"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - biodiversity-and-climate-research-centre

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Martin Pfeiffer"
    # Purpose: Canonical BAHE person id.
    person_id: martin-pfeiffer
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-ulm
      - national-university-of-mongolia

  # Auhor position.
  - position: 4
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
  - position: 5
    # Purpose: Full author name.
    name: "Trevor N. Petney"
    # Purpose: Canonical BAHE person id.
    person_id: trevor-n-petney
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - karlsruhe-institute-of-technology

  # Auhor position.
  - position: 6
    # Purpose: Full author name.
    name: "Lance A. Durden"
    # Purpose: Canonical BAHE person id.
    person_id: lance-a-durden
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - georgia-southern-university

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
    - software
    - visualization
    - writing-original-draft
    - writing-review-editing

  robert-b-ohara:
    - methodology
    - formal-analysis
    - supervision
    - interpretation
    - writing-review-editing

  martin-pfeiffer:
    - conceptualization
    - investigation
    - resources
    - interpretation
    - writing-review-editing

  maklarin-b-lakim:
    - investigation
    - resources
    - field-logistics
    - writing-review-editing

  trevor-n-petney:
    - investigation
    - taxonomic-identification
    - resources
    - writing-review-editing

  lance-a-durden:
    - investigation
    - taxonomic-identification
    - resources
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
journal_name: "Oecologia"

# Purpose: Journal volume.
volume: "172"

# Purpose: Journal issue.
issue: "1"

# Purpose: Article pages or article number.
pages: "307-316"

# Purpose: Publisher.
publisher: "Springer"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., O’Hara, R. B., Pfeiffer, M., Lakim, M. B., Petney, T. N.,
  & Durden, L. A. (2013). Inferring host specificity and network
  formation through agent-based models: tick–mammal interactions in
  Borneo. Oecologia, 172(1), 307-316.
  https://doi.org/10.1007/s00442-012-2511-9

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2013), Oecologia, 172(1), 307-316.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1007/s00442-012-2511-9"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1007/s00442-012-2511-9"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1007/s00442-012-2511-9"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Patterns of host–parasite association are poorly understood in tropical forests. While we typically observe only snapshots of the diverse assemblages and interactions under variable conditions, there is a desire to make inferences about prevalence and host-specificity patterns. We studied the interaction of ticks with non-volant small mammals in forests of Borneo. We inferred the probability of species interactions from individual-level data in a multi-level Bayesian model that incorporated environmental covariates and advanced estimates for rarely observed species through model averaging. We estimated the likelihood of observing particular interaction frequencies under field conditions and a scenario of exhaustive sampling and examined the consequences for inferring host specificity. We recorded a total of 13 different tick species belonging to the five genera Amblyomma, Dermacentor, Haemaphysalis, Ixodes, and Rhipicephalus from a total of 37 different host species (Rodentia, Scandentia, Carnivora, Soricidae) on 237 out of 1,444 host individuals. Infestation probabilities revealed most variation across host species but less variation across tick species with three common rat and two tree shrew species being most heavily infested. Host species identity explained ca. 75 % of the variation in infestation probability and another 8–10 % was explained by local host abundance. Host traits and site-specific attributes had little explanatory power. Host specificity was estimated to be similarly low for all tick species, which were all likely to infest 34–37 host species if exhaustively sampled. By taking into consideration the hierarchical organization of individual interactions that may take place under variable conditions and that shape host–parasite networks, we can discern uncertainty and sampling bias from true interaction frequencies, whereas network attributes derived from observed values may lead to highly misleading results. Multi-level approaches may help to move this field towards inferential approaches for understanding mechanisms that shape the strength and dynamics in ecological networks.

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
  supplementary_material: "https://doi.org/10.1007/s00442-012-2511-9"

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
image: "/images/images_publications/Tick-mammal-host-specificity_Wells-2013.jpg"

image_alt: >-
  Heat map of modelled infestation probabilities for 13 tick species across
  37 small mammal host species in Borneo, accompanied by distributions
  comparing observed host ranges with field-based and exhaustive-sampling
  estimates.

# Image caption  
image_caption: >-
  Model-based tick–mammal interaction probabilities and inferred host ranges
  in Bornean forests. The heat map shows posterior infestation probabilities
  for each tick–host combination, while the accompanying distributions
  demonstrate how limited field sampling can underestimate the number of host
  species used by ticks. Under exhaustive sampling, all focal tick species
  were predicted to infest broad and similar host ranges.

image_license: "All rights reserved"
image_credit: "Wells et al. (2013)"
image_license_verified: false  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20130501

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
      Thirteen hard tick species were recorded from 37 mammalian host species in Bornean forests, with ticks detected on 237 of 1,444 examined host individuals.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Host species identity explained approximately 75% of variation in tick infestation probability, whereas tick species identity explained only about 4%.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Local host abundance explained an additional 8–10% of variation in infestation probability and was positively associated with tick occurrence.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Leopoldamys sabanus, Maxomys rajah, Maxomys alticola, Tupaia longipes and Tupaia gracilis had the highest estimated infestation probabilities among sampled mammals.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Forest type, sampling site, host body mass, habitat use, year and month had comparatively little explanatory power for infestation probability.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Observed interaction matrices substantially underestimated tick host breadth because rare associations were frequently missed under finite field sampling.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Under equal exhaustive sampling, all 13 tick species were predicted to infest 34–37 of the 37 available host species.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Host-specificity indices derived directly from observed interaction counts created spurious differences among tick species that largely disappeared after accounting for sampling uncertainty.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-09
    text: >
      Multi-level Bayesian models can infer species-level ecological network properties from individual-level observations while incorporating zero encounters, covariates and uncertainty.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-10
    text: >
      Ecological network analyses based only on aggregated adjacency matrices risk overestimating specialisation when species are unevenly sampled.
    knowledge_type: recommendation
    attributed_to: source-publication

  - id: statement-11
    text: >
      Host availability, abundance and space use are likely to be more important determinants of tick survival and reproduction than rigid host specialisation in this Bornean system.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-12
    text: >
      Comparative network studies should retain disaggregated individual-level observations so that differences in sampling intensity and false zero interactions can be modelled explicitly.
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
  This study analysed 13 tick species and 37 small mammal host species sampled
  across lowland and montane forests in Sabah, Borneo. A multi-level Bayesian
  model estimated individual infestation probabilities, partitioned host and
  environmental effects, and compared observed with exhaustive-sampling
  scenarios.

# Knowledge-network summary.
knowledge_summary: >
  The study demonstrates that apparent host specificity can emerge from
  uneven sampling rather than true biological specialisation. Host identity
  and local abundance dominated variation in infestation probability, whereas
  environmental covariates had weak effects. By modelling individual
  encounters and propagating uncertainty to species-level network indices, the
  analysis revealed that all focal tick species were broad host generalists.

# Scientific or societal significance.
impact_statement: >
  Reliable inference about parasite host range and disease-network structure
  requires models that separate true ecological interactions from sampling
  bias and false absences.

# Non-technical summary.  
plain_language_summary: >-
  Field observations made some tick species appear highly specialised because
  they were found on only a few mammals. After accounting for unequal
  sampling, however, all tick species were predicted to use many host species.
  The findings show that incomplete observations can seriously distort
  ecological network conclusions.  

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - one-health-disease-ecology
  - ecological-interactions-system-dynamics
  - quantitative-ecology-modelling
  - biodiversity-global-change

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - host-specificity
  - tick-mammal-interactions
  - ecological-networks
  - sampling-bias
  - false-zero-interactions
  - infestation-probability
  - host-availability
  - host-abundance
  - parasite-generalism
  - hierarchical-modelling
  - network-formation
  - host-parasite-associations
  - individual-level-interactions
  - uncertainty-propagation
  - ecological-fallacy

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - host-specificity
  - tick-mammal-interactions
  - sampling-bias
  - parasite-generalism
  - hierarchical-modelling
  - ecological-networks

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - borneo-tick-mammal-network
  - sabah-small-mammal-community
  - tropical-forest-ectoparasite-system
  - host-parasite-interaction-network

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - ixodes-granulatus
  - amblyomma-testudinarium
  - dermacentor
  - rhipicephalus-haemaphysaloides
  - haemaphysalis-bispinosa
  - haemaphysalis-cornigera
  - haemaphysalis-koningsbergeri
  - haemaphysalis-papuana
  - haemaphysalis-semermis
  - haemaphysalis-traguli
  - leopoldamys-sabanus
  - maxomys-rajah
  - maxomys-alticola
  - tupaia-longipes
  - tupaia-gracilis

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - live-trapping
  - ectoparasite-screening
  - morphological-tick-identification
  - individual-level-logistic-regression
  - hierarchical-bayesian-modelling
  - markov-chain-monte-carlo
  - model-averaging
  - posterior-predictive-simulation
  - network-inference
  - host-specificity-indexing
  - rao-quadratic-entropy
  - kullback-leibler-specialisation
  - exhaustive-sampling-scenario

# Input environmental database/ data sources
data_products:
  - borneo-small-mammal-trapping-data
  - sabah-parks-tick-collection
  - us-national-tick-collection

# Data produced or archived by this study  
research_datasets: []

projects:
  - borneo-small-mammal-ecology

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
    object_id: robert-b-ohara

  - predicate: authored_by
    object_type: person
    object_id: martin-pfeiffer

  - predicate: authored_by
    object_type: person
    object_id: maklarin-b-lakim

  - predicate: authored_by
    object_type: person
    object_id: trevor-n-petney

  - predicate: authored_by
    object_type: person
    object_id: lance-a-durden

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-ulm

  - predicate: authored_by
    object_type: organisation
    object_id: sabah-parks

  - predicate: authored_by
    object_type: organisation
    object_id: biodiversity-and-climate-research-centre

  - predicate: authored_by
    object_type: organisation
    object_id: national-university-of-mongolia

  - predicate: authored_by
    object_type: organisation
    object_id: karlsruhe-institute-of-technology

  - predicate: authored_by
    object_type: organisation
    object_id: georgia-southern-university

  - predicate: addresses
    object_type: concept
    object_id: host-specificity

  - predicate: addresses
    object_type: concept
    object_id: sampling-bias

  - predicate: addresses
    object_type: concept
    object_id: parasite-generalism

  - predicate: addresses
    object_type: concept
    object_id: ecological-networks

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - disease-ecology
  - parasite-ecology
  - ecological-network-analysis
  - hierarchical-bayesian-modelling
  - sampling-theory
  - wildlife-epidemiology
  - tropical-ecology
  - host-specificity
  - uncertainty-analysis

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why can host specificity be overestimated when parasite records are sparse?"
  - "How does local host abundance influence tick infestation probability?"
  - "What information is lost when individual observations are aggregated into a species-by-species interaction matrix?"
  - "Why did exhaustive-sampling simulations produce broader and more similar host ranges across tick species?"
  - "How can hierarchical models distinguish false zero interactions from true host avoidance?"
  - "What additional data would be required to estimate environment-specific tick–mammal networks?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Tick–Mammal Host Specificity in Borneo | Wells et al. 2013"

# Purpose: Search description.
seo_description: >-
  Multi-level Bayesian analysis showing that Bornean tick species are broad
  mammal-host generalists and that observed network specialisation is strongly
  biased by uneven sampling.

# Purpose: Search keywords.
keywords:
  - tick host specificity
  - Borneo
  - tick–mammal interactions
  - ecological networks
  - sampling bias
  - false zeros
  - infestation probability
  - host abundance
  - host availability
  - hierarchical Bayesian model
  - parasite generalism
  - tropical forest
  - Ixodidae
  - small mammals
  - Rao quadratic entropy
  - specialization index
  - network inference
  - wildlife disease

# Purpose: Social sharing metadata.
social:
  title: "Tick–Mammal Host Specificity in Borneo"
  description: >-
    Wells and colleagues show that incomplete sampling can exaggerate tick
    host specialisation and distort ecological network structure.
  image: "images/images_publications/Tick-mammal-host-specificity_Wells-2013.png"
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
  source_url: "https://doi.org/10.1007/s00442-012-2511-9"

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
