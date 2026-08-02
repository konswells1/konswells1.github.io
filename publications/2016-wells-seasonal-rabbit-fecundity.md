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
id: 2016-wells-seasonal-rabbit-fecundity

# Purpose: Official publication title.
title: "Environmental effects and individual body condition drive seasonal fecundity of rabbits: identifying acute and lagged processes"

# Purpose: Short display title.
short_title: "Seasonal fecundity of rabbits"

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
year_published: 2016

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2016-03-30

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
- Brian D. Cooke
- Greg J. Mutze
- Thomas A. A. Prowse
- Damien A. Fordham

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
      - university-of-adelaide
      - griffith-university

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
    name: "Brian D. Cooke"
    # Purpose: Canonical BAHE person id.
    person_id: brian-d-cooke
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - invasive-animals-cooperative-research-centre
      - university-of-canberra

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "Greg J. Mutze"
    # Purpose: Canonical BAHE person id.
    person_id: greg-j-mutze
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - biosecurity-south-australia

  # Auhor position.
  - position: 5
    # Purpose: Full author name.
    name: "Thomas A. A. Prowse"
    # Purpose: Canonical BAHE person id.
    person_id: thomas-a-a-prowse
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-adelaide

  # Auhor position.
  - position: 6
    # Purpose: Full author name.
    name: "Damien A. Fordham"
    # Purpose: Canonical BAHE person id.
    person_id: damien-a-fordham
    # Purpose: ORCID identifier.
    orcid: "0000-0003-2137-5592"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-adelaide

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  konstans-wells:
    - conceptualization
    - methodology
    - formal-analysis
    - visualization
    - writing-original-draft
    - writing-review-editing

  robert-b-ohara:
    - methodology
    - formal-analysis
    - interpretation
    - writing-review-editing

  brian-d-cooke:
    - conceptualization
    - investigation
    - resources
    - writing-review-editing

  greg-j-mutze:
    - investigation
    - resources
    - interpretation
    - writing-review-editing

  thomas-a-a-prowse:
    - formal-analysis
    - methodology
    - writing-review-editing

  damien-a-fordham:
    - methodology
    - formal-analysis
    - supervision
    - funding-acquisition
    - writing-review-editing

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "Australian Research Council"
    # Purpose: Canonical funder identifier.
    funder_id: australian-research-council
    # Purpose: Grant identifier.
    grant_number: "LP12020024"
    # Purpose: Official grant title.
    grant_title: "Linkage Project"

  - funder_name: "Australian Research Council"
    funder_id: australian-research-council
    grant_number: "FT140101192"
    grant_title: "Future Fellowship"

  - funder_name: "Biodiversity and Climate Research Centre"
    funder_id: biodiversity-and-climate-research-centre
    grant_number: ""
    grant_title: ""

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Oecologia"

# Purpose: Journal volume.
volume: "181"

# Purpose: Journal issue.
issue: "3"

# Purpose: Article pages or article number.
pages: "853-864"

# Purpose: Publisher.
publisher: "Springer"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., O’Hara, R. B., Cooke, B. D., Mutze, G. J., Prowse, T. A. A.,
  & Fordham, D. A. (2016). Environmental effects and individual body
  condition drive seasonal fecundity of rabbits: identifying acute and lagged
  processes. Oecologia, 181(3), 853-864.
  https://doi.org/10.1007/s00442-016-3617-2

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2016), Oecologia, 181(3), 853-864.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1007/s00442-016-3617-2"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1007/s00442-016-3617-2"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1007/s00442-016-3617-2"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  The reproduction of many species is determined by seasonally-driven resource supply. But it is difficult to quantify whether the fecundity is sensitive to short- or long-term exposure to environmental conditions such as rainfall that drive resource supply. Using 25 years of data on individual fecundity of European female rabbits, Oryctolagus cuniculus, from semiarid Australia, we investigate the role of individual body condition, rainfall and temperature as drivers of seasonal and long-term and population-level changes in fecundity (breeding probability, ovulation rate, embryo survival). We built distributed lag models in a hierarchical Bayesian framework to account for both immediate and time-lagged effects of climate and other environmental drivers, and possible shifts in reproduction over consecutive seasons. We show that rainfall during summer, when rabbits typically breed only rarely, increased breeding probability immediately and with time lags of up to 10 weeks. However, an earlier onset of the yearly breeding period did not result in more overall reproductive output. Better body condition was associated with an earlier onset of breeding and higher embryo survival. Breeding probability in the main breeding season declined with increased breeding activity in the preceding season and only individuals in good body condition were able to breed late in the season. Higher temperatures reduce breeding success across seasons. We conclude that a better understanding of seasonal dynamics and plasticity (and their interplay) in reproduction will provide crucial insights into how lagomorphs are likely to respond and potentially adapt to the influence of future climate and other environmental change.

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
  supplementary_material: "https://doi.org/10.1007/s00442-016-3617-2"

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
image: "/images/images_publications/Seasonal-rabbit-fecundity_Wells-2016.png"

image_alt: >-
  Conceptual diagram illustrating how seasonal breeding probability in European rabbits varies across years. The figure shows early and main breeding seasons, differences in seasonal fecundity, and how environmental conditions and previous reproductive investment can influence breeding through time.

# Image caption  
image_caption: >-
  Seasonal and interannual dynamics of rabbit fecundity. This conceptual framework illustrates how reproductive activity in European rabbits (Oryctolagus cuniculus) varies within and among years in response to environmental conditions. Seasonal breeding begins following autumn pasture growth, peaks during the main winter breeding season, and fluctuates between years according to changing resource availability. The framework highlights how lagged environmental effects and reproductive investment in preceding seasons can influence subsequent breeding probabilities and fecundity, providing the conceptual basis for analysing immediate and delayed drivers of reproduction using distributed lag models. The study demonstrates that rabbit fecundity is shaped not only by current rainfall, temperature and body condition, but also by the ecological history of individuals and populations, offering new insights into demographic responses to environmental variability and climate change.

image_license: "All rights reserved"
image_credit: "Wells et al. (2016)"
image_license_verified: true  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20160330

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
      Rabbit breeding probability was highly seasonal, peaking during July to October and remaining low during the dry summer months.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Summer rainfall increased rabbit breeding probability immediately and through lagged effects lasting up to approximately 10 weeks.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      An earlier onset of seasonal breeding did not increase total annual reproductive output because elevated early breeding reduced breeding probability in the subsequent main season.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Better kidney fat condition increased summer breeding probability and embryo survival, particularly when environmental conditions were marginal.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Higher body mass relative to age increased breeding probability during the main and late breeding seasons and increased ovulation rate across most of the breeding period.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Only females in good body condition were likely to continue breeding late in the annual reproductive cycle.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Higher temperatures reduced rabbit breeding probability across most seasons, although the estimated effect was modest.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Rainfall increased ovulation rate during the main breeding season with lagged effects extending to approximately 14 weeks.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-09
    text: >
      Rabbit fecundity was more strongly associated with individual body condition than with direct population-level environmental indices such as pasture growth, soil moisture or density.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-10
    text: >
      Distributed lag models improved inference about breeding probability by estimating the timescale over which environmental exposure affected reproduction.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-11
    text: >
      Seasonal reproductive plasticity can buffer short-term environmental stress without necessarily increasing annual fecundity.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-12
    text: >
      Forecasts of climate effects on highly fecund mammals should model both seasonal shifts in reproduction and delayed environmental effects rather than relying on annual averages.
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
  This study analysed 25 years of reproductive data from 2,563 female
  European rabbits in semi-arid South Australia. Hierarchical Bayesian
  distributed lag models quantified immediate and delayed effects of climate,
  body condition, age and prior breeding on breeding probability, ovulation
  and embryo survival.

# Knowledge-network summary.
knowledge_summary: >
  The study demonstrates that rabbit fecundity emerges from interactions among
  seasonal climate, individual condition and previous reproductive effort.
  Rainfall can trigger earlier breeding through effects lasting several weeks,
  but early reproduction may be offset by reduced later breeding. Body
  condition strongly determines which females reproduce under marginal or
  late-season conditions, showing that individual heterogeneity is central to
  population-level reproductive dynamics.

# Scientific or societal significance.
impact_statement: >
  Predicting rabbit population responses to climate change requires models
  that represent seasonal reproductive plasticity, body condition and
  time-lagged environmental effects.

# Non-technical summary.  
plain_language_summary: >-
  Long-term data showed that rainfall can trigger rabbit breeding quickly and
  continue to influence reproduction for several weeks. However, starting
  breeding earlier did not necessarily produce more young over the whole year.
  Females in better condition were more likely to breed and successfully carry
  embryos, especially when conditions were poor.  

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - ecological-interactions-system-dynamics
  - biodiversity-global-change
  - quantitative-ecology-modelling
  - conservation-ecology

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - seasonal-fecundity
  - reproductive-plasticity
  - distributed-lag-effects
  - rainfall-driven-reproduction
  - temperature-effects
  - body-condition
  - breeding-probability
  - ovulation-rate
  - embryo-survival
  - reproductive-trade-offs
  - seasonal-autocorrelation
  - individual-heterogeneity
  - climate-demography
  - invasive-species-population-dynamics
  - phenology

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - seasonal-fecundity
  - reproductive-plasticity
  - distributed-lag-effects
  - body-condition
  - breeding-probability
  - climate-demography

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - belton-rabbit-population
  - semi-arid-south-australian-rabbit-system
  - seasonal-mammal-reproduction
  - invasive-rabbit-population-dynamics

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - oryctolagus-cuniculus

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - long-term-field-monitoring
  - necropsy-based-reproductive-assessment
  - spotlight-abundance-surveys
  - body-condition-indexing
  - kidney-fat-scoring
  - eye-lens-age-proxy
  - hierarchical-bayesian-modelling
  - distributed-lag-modelling
  - generalised-linear-modelling
  - markov-chain-monte-carlo
  - gibbs-variable-selection
  - posterior-predictive-checking
  - open-population-abundance-modelling

# Input environmental database/ data sources
data_products:
  - silo-australian-climate-database
  - aussiegrass
  - belton-rabbit-necropsy-data
  - belton-rabbit-spotlight-counts

# Data produced or archived by this study  
research_datasets: []

projects:
  - australian-rabbit-population-ecology

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
    object_id: brian-d-cooke

  - predicate: authored_by
    object_type: person
    object_id: greg-j-mutze

  - predicate: authored_by
    object_type: person
    object_id: thomas-a-a-prowse

  - predicate: authored_by
    object_type: person
    object_id: damien-a-fordham

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-adelaide

  - predicate: authored_by
    object_type: organisation
    object_id: griffith-university

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-canberra

  - predicate: uses
    object_type: data-product
    object_id: silo-australian-climate-database

  - predicate: uses
    object_type: data-product
    object_id: aussiegrass

  - predicate: addresses
    object_type: concept
    object_id: seasonal-fecundity

  - predicate: addresses
    object_type: concept
    object_id: distributed-lag-effects

  - predicate: addresses
    object_type: concept
    object_id: body-condition

  - predicate: addresses
    object_type: concept
    object_id: reproductive-plasticity

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - population-ecology
  - reproductive-ecology
  - climate-change-ecology
  - invasive-species-biology
  - hierarchical-bayesian-modelling
  - distributed-lag-models
  - phenology
  - long-term-ecological-data
  - demographic-analysis

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why did earlier breeding not necessarily increase annual reproductive output?"
  - "How do kidney fat and body mass index represent different dimensions of body condition?"
  - "Why are distributed lag models preferable to arbitrary moving averages for environmental covariates?"
  - "How can reproductive plasticity buffer short-term climate variability?"
  - "Why might body condition explain more variation in fecundity than population-level pasture or soil-moisture indices?"
  - "What additional demographic processes should be included when forecasting rabbit population responses to climate change?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Seasonal Rabbit Fecundity and Lagged Environmental Effects | Wells et al. 2016"

# Purpose: Search description.
seo_description: >-
  Twenty-five-year study showing how rainfall, temperature, body condition and
  previous breeding drive seasonal rabbit fecundity through immediate and
  delayed processes.

# Purpose: Search keywords.
keywords:
  - European rabbit
  - Oryctolagus cuniculus
  - seasonal fecundity
  - reproductive plasticity
  - distributed lag model
  - body condition
  - rainfall
  - temperature
  - breeding probability
  - ovulation rate
  - embryo survival
  - climate demography
  - phenology
  - long-term ecological data
  - semi-arid Australia
  - invasive species
  - Bayesian hierarchical model
  - reproductive trade-offs

# Purpose: Social sharing metadata.
social:
  title: "Seasonal Rabbit Fecundity and Environmental Time Lags"
  description: >-
    Wells and colleagues show how climate, body condition and prior breeding
    shape seasonal rabbit reproduction through immediate and delayed effects.
  image: "images/images_publications/Seasonal-rabbit-fecundity_Wells-2016.png"
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
  source_url: "https://doi.org/10.1007/s00442-016-3617-2"

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
