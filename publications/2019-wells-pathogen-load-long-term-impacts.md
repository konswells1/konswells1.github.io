
---
id: 2019-wells-pathogen-load-long-term-impacts
title: "Individual and temporal variation in pathogen load predicts long-term impacts of an emerging infectious disease"
short_title: "Pathogen load predicts long-term disease impacts"

object_type: publication
publication_type: research-article
status: published

year_published: 2019
date: 2019-03-01

authors:
  - Konstans Wells
  - Rodrigo K. Hamede
  - Menna E. Jones
  - Paul A. Hohenlohe
  - Andrew Storfer
  - Hamish I. McCallum

bahe_authors:
  - konstans-wells

journal_name: Ecology
volume: "100"
issue: "3"
pages: "e02613"
publisher: Ecological Society of America

identifiers:
  doi: "10.1002/ecy.2613"

citation_full: >-
  Wells K., Hamede R.K., Jones M.E., Hohenlohe P.A., Storfer A.,
  McCallum H.I. (2019). Individual and temporal variation in pathogen
  load predicts long-term impacts of an emerging infectious disease.
  Ecology 100(3):e02613. https://doi.org/10.1002/ecy.2613


# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Emerging infectious diseases increasingly threaten wildlife populations. Most studies focus on managing short-term epidemic properties, such as controlling early outbreaks. Predicting long-term endemic characteristics with limited retrospective data is more challenging. We used individual-based modeling informed by individual variation in pathogen load and transmissibility to predict long-term impacts of a lethal, transmissible cancer on Tasmanian devil (Sarcophilus harrisii) populations. For this, we employed approximate Bayesian computation to identify model scenarios that best matched known epidemiological and demographic system properties derived from 10 yr of data after disease emergence, enabling us to forecast future system dynamics. We show that the dramatic devil population declines observed thus far are likely attributable to transient dynamics (initial dynamics after disease emergence). Only 21% of matching scenarios led to devil extinction within 100 yr following devil facial tumor disease (DFTD) introduction, whereas DFTD faded out in 57% of simulations. In the remaining 22% of simulations, disease and host coexisted for at least 100 yr, usually with long-period oscillations. Our findings show that pathogen extirpation or host–pathogen coexistence are much more likely than the DFTD-induced devil extinction, with crucial management ramifications. Accounting for individual-level disease progression and the long-term outcome of devil–DFTD interactions at the population-level, our findings suggest that immediate management interventions are unlikely to be necessary to ensure the persistence of Tasmanian devil populations. This is because strong population declines of devils after disease emergence do not necessarily translate into long-term population declines at equilibria. Our modeling approach is widely applicable to other host–pathogen systems to predict disease impact beyond transient dynamics.

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
  code:
    github: "https://konswells1.github.io/publication/2019_Wells_Ecology"
  data:
    zenodo: ""
    figshare: ""
    dryad: ""
  preprint: "https://www.biorxiv.org/content/10.1101/392324v1"
  supplementary_material: "https://doi.org/10.1088/1748-9326/ae803f/data1"

  news:
    university_story: "https://www-2018.swansea.ac.uk/press-office/news-archive/2019/tasmaniandevilcancerunlikelytocauseextinctionsayexperts.php"
    phys_org: "https://phys.org/news/2019-01-tasmanian-devil-cancer-extinction-experts.html"
    bbc: "https://www.bbc.co.uk/news/science-environment-47659640"

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
image: "images/images_publications/dftd_longterm_scenarios.jpg"

image_alt: >-
  Multi-panel figure comparing two simulated long-term outcomes of devil
  facial tumour disease in Tasmanian devils. The left column shows disease
  extirpation and the right column shows long-term host–pathogen coexistence.
  Each scenario includes a population time series, a wavelet power spectrum
  illustrating changes in population periodicity through time, and a disease
  prevalence time series over a 100-year simulation.

# Image caption
image_caption: >-
  Simulated long-term dynamics of Tasmanian devil populations following the
  introduction of devil facial tumour disease (DFTD). Scenario 1 illustrates
  disease extirpation, whereas Scenario 2 demonstrates stable coexistence
  between host and pathogen. Upper panels show changes in devil population
  size over 100 years of simulation, middle panels present Morlet wavelet
  power spectra identifying shifts in the strength and periodicity of
  population cycles through time, and lower panels show the prevalence of
  DFTD. Together, the simulations demonstrate how epidemiological processes
  can generate contrasting long-term outcomes ranging from pathogen loss to
  persistent endemic disease accompanied by characteristic oscillations in
  host abundance.

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: true

order: 20190301

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
      Individual-based epidemiological models that explicitly represent temporal changes in pathogen burden and transmission can predict long-term disease outcomes that differ substantially from predictions produced by homogeneous compartmental models.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-02
    text: >
      Model scenarios calibrated to ten years of empirical Tasmanian devil data predicted that devil facial tumour disease is more likely to fade out locally or persist through long-term coexistence than to drive Tasmanian devil populations to extinction.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Progressive tumour growth creates temporal variation in host mortality and infectiousness that slows epidemic spread and increases the likelihood of long-term host–pathogen coexistence through delayed disease dynamics.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-04
    text: >
      Long-term persistence of devil facial tumour disease is predicted to produce multi-year oscillations in host abundance and disease prevalence rather than stable equilibrium dynamics or inevitable host extinction.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Combining individual-based simulation with approximate Bayesian computation enables estimation of plausible epidemiological parameters and selection of model structures that best reproduce observed host demographic and disease patterns.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-06
    text: >
      Early severe population declines following emergence of devil facial tumour disease should not be interpreted as evidence of inevitable long-term extinction, and intensive management interventions may be unnecessary unless supported by long-term epidemiological forecasts.
    knowledge_type: recommendation
    attributed_to: source-publication

  - id: statement-07
    text: >
      Severe population declines observed during the early stages of an emerging infectious disease do not necessarily predict long-term population collapse because transient epidemic dynamics may differ fundamentally from long-term endemic dynamics.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-08
    text: >
      Reliable assessment of disease impacts on wildlife populations requires models that capture long-term eco-epidemiological processes, as conclusions based solely on short-term observations of emerging epidemics can lead to misleading forecasts and inappropriate management decisions.
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

summary: >
  This study combines a stochastic individual-based epidemiological model with
  approximate Bayesian computation and ten years of field observations to
  investigate the long-term dynamics of devil facial tumour disease in
  Tasmanian devils. By explicitly modelling individual variation in tumour
  growth, pathogen burden, transmission and mortality, the study shows that
  local disease fade-out and long-term host–pathogen coexistence are more
  probable outcomes than host extinction, demonstrating that transient epidemic
  declines can differ fundamentally from long-term disease dynamics.

knowledge_summary: >
  The study provides a major conceptual advance in wildlife disease ecology by
  demonstrating that realistic representation of within-host disease
  progression and individual heterogeneity can fundamentally alter predictions
  of long-term epidemic outcomes. It challenges conclusions drawn from earlier
  compartmental models by showing that severe initial population declines do
  not necessarily imply eventual host extinction, highlighting the importance
  of distinguishing transient epidemic dynamics from long-term eco-
  epidemiological processes when forecasting disease impacts and evaluating
  conservation interventions.

impact_statement: >
  The findings demonstrate that long-term disease forecasts require
  mechanistic models linking within-host processes to population dynamics,
  cautioning against conservation decisions based solely on short-term epidemic
  observations and providing a more robust framework for assessing emerging
  wildlife diseases.

plain_language_summary: >
  When a new disease first appears, wildlife populations can decline rapidly,
  making extinction seem inevitable. This study shows that these dramatic early
  declines do not necessarily predict what will happen in the long term. By
  combining long-term field data with realistic computer simulations, the
  authors found that Tasmanian devils are more likely to coexist with devil
  facial tumour disease—or for the disease to disappear locally—than to become
  extinct. The study highlights why conservation decisions should be based on
  long-term ecological understanding rather than short-term observations alone.


# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - ecological-interactions-system-dynamics
  - wildlife-ecology-health-and-one-health


methods:
  - individual-based modelling
  - approximate Bayesian computation
  - stochastic simulation
  - spatial epidemiological modelling
  - wavelet analysis
  - boosted regression trees

study_systems:
  - Tasmanian devil
  - devil facial tumour disease

focal_species:
  - Sarcophilus harrisii

concepts:
  - pathogen load
  - transmissible cancer
  - disease emergence
  - within-host dynamics
  - host-pathogen coexistence
  - transient dynamics
  - population viability
  - spatial transmission
  - disease burden
  - wildlife disease


management_implications:
  - Immediate large-scale intervention is unlikely to be necessary solely to prevent Tasmanian devil persistence loss.
  - Management should be evaluated using long-term forecasts rather than short-term epidemic trajectories.
  - Conservation decisions should incorporate within-host disease progression and spatial structure.

keywords:
  - Tasmanian devil
  - devil facial tumour disease
  - transmissible cancer
  - individual-based model
  - approximate Bayesian computation
  - pathogen load
  - disease burden
  - wildlife epidemiology
  - host-pathogen dynamics
  - transient dynamics
  
  

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
  The article is published under the Creative Commons Attribution 4.0
  licence. Reuse must preserve attribution to the authors, article title,
  journal citation and DOI.

# =======
# Provenance and curation
# =======

# Purpose: Editorial review metadata.
curation:
  # Purpose: curation status. # Values: unreviewed, in-review, reviewed, revision-required
  status: reviewed
  reviewed_by: konstans-wells
  reviewed_on: 2026-07-22

# Purpose: Source provenance.
provenance:
  # Purpose: Original source type. # Values: publisher-pdf, publisher-html, repository, author, 
  source_type:
    - publisher-pdf
    - author
    
  # Purpose: Original source URL.
  source_url: "https://doi.org/10.1002/ecy.2613"

  # Purpose: AI assistance metadata.
  ai_assistance:
    system: ChatGPT
    roles:
      - metadata-extraction
      - draft-summary
      - concept-classification
    outputs_human_verified: true

  confidence:
    bibliographic_metadata: verified
    claims: verified
    summaries: verified
    concept_classification: reviewed  
---
