---
# =======
# Publication object identity
# =======

id: 2023-clark-wells-dynamic-generalized-additive-models
title: "Dynamic Generalised Additive Models (DGAMs) for Forecasting Discrete Ecological Time Series"
short_title: "Dynamic GAMs for Ecological Forecasting"

object_type: publication
type: research-article
status: published

schema_version: "BKOS-1.0"
profile_version: "BPAS-2.0"

year_published: 2023
date: "2023-03-01"
date_created: 2026-07-11
date_modified: 2026-07-11

# =======
# Authorship
# =======

authors:
  - Nicholas J. Clark
  - Konstans Wells

bahe_authors:
  - konstans-wells

author_entities:
  - position: 1
    name: "Nicholas J. Clark"
    person_id: ""
    orcid: ""
    affiliation_ids:
      - university-of-queensland

  - position: 2
    name: "Konstans Wells"
    person_id: "konstans-wells"
    orcid: "0000-0003-0377-2463"
    affiliation_ids:
      - swansea-university

organisations:
  - university-of-queensland
  - swansea-university

# =======
# Bibliographic metadata
# =======

journal_name: "Methods in Ecology and Evolution"
volume: "14"
issue: "3"
pages: "771-784"

publisher: "British Ecological Society / John Wiley & Sons"
open_access: true
license: "CC BY 4.0"

citation_full: "Clark, N.J., & Wells, K. (2023). Dynamic Generalised Additive Models (DGAMs) for forecasting discrete ecological time series. Methods in Ecology and Evolution, 14, 771–784."

identifiers:
  doi: "10.1111/2041-210X.13974"
  publisher_url: "https://doi.org/10.1111/2041-210X.13974"
  pmid: ""
  arxiv: ""
  openalex: ""
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1111/2041-210X.13974"
pdf: ""

abstract_original: |-
  Generalised additive models (GAMs) are powerful tools for modelling nonlinear ecological relationships but often perform poorly for forecasting because smooth functions extrapolate unrealistically beyond observed data. This paper introduces Dynamic Generalised Additive Models (DGAMs), which augment GAMs with latent dynamic processes to jointly model nonlinear predictor effects and temporal dependence. The framework is implemented in the open-source R package mvgam and supports Bayesian estimation of hierarchical smooth functions, dynamic latent factors and probabilistic forecasts for discrete ecological time series. Simulation studies and empirical applications demonstrate improved forecasting accuracy and uncertainty quantification relative to conventional GAMs.

abstract_source: publisher
abstract_verbatim: false
abstract_public_display: true

# =======
# Funding and contributions
# =======

project_funding:
  project_funders:
    - Australian Research Council
  project_grants:
    - DE210101439

author_contributions:
  nicholas-j-clark:
    - conceptualization
    - methodology
    - software
    - formal-analysis
    - writing-original-draft
    - visualization
    - supervision

  konstans-wells:
    - conceptualization
    - methodology
    - writing-review-editing
    - validation


# =======
# Resources and media
# =======

resource_links:
  bahe_context: ""
  code: "https://github.com/nicholasjclark/mvgam"
  data:
    zenodo: "https://doi.org/10.5281/zenodo.6918047"
    other_repository: "https://data.neonscience.org"
  software: "https://cran.r-project.org/web/packages/mvgam/index.html"
  preprint: ""
  supplementary_material: ""
  news:
    university_story: ""
  media: {}
  teaching: {}


# =======
# Display controls
# =======

featured: true
show_on_publications_page: true
show_on_homepage: true

order: 20230301

# =======
# Image
# =======

image: "images/images_publications/mvgam-splines_NickClark.gif"

image_alt: >
  Dynamic generalised additive models splines.



# =======
# Knowledge statements
# =======

knowledge_statements:
  - id: statement-01
    text: >
      Dynamic Generalised Additive Models (DGAMs) integrate nonlinear ecological
      relationships with latent temporal processes within a unified Bayesian
      framework, enabling simultaneous inference and forecasting for discrete
      ecological time series.
    knowledge_type: methodological-framework
    attributed_to: source-publication

  - id: statement-02
    text: >
      Explicitly modelling latent temporal dynamics produces more robust and
      realistic ecological forecasts than extrapolating smooth functions beyond
      the range of observed data using conventional Generalised Additive Models.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-03
    text: >
      Hierarchical dynamic factor models provide an efficient approach for
      forecasting multiple ecological time series by representing shared
      temporal dynamics through a reduced set of latent processes.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-04
    text: >
      Bayesian probabilistic inference enables ecological forecasts to quantify
      uncertainty arising from nonlinear predictor effects, latent ecological
      dynamics and observation processes within a single coherent modelling
      framework.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-05
    text: >
      Ecological forecasting models should accommodate incomplete observations,
      irregular sampling and discrete response distributions because these are
      fundamental characteristics of ecological time-series data rather than
      exceptional cases.
    knowledge_type: methodological-principle
    attributed_to: source-publication

  - id: statement-06
    text: >
      Reliable ecological forecasting requires integrating mechanistic ecological
      knowledge with dynamic statistical models that represent both biological
      processes and their associated uncertainties through time.
    knowledge_type: conceptual-synthesis
    attributed_to: source-publication


# =======
# Summaries
# =======

summary: >
  This study introduces Dynamic Generalised Additive Models (DGAMs), a Bayesian
  modelling framework that combines the flexibility of generalised additive
  models with latent dynamic processes to forecast discrete ecological time
  series. The framework accommodates nonlinear ecological relationships,
  temporal dependence, missing observations and multivariate hierarchical data,
  and is implemented in the open-source R package mvgam.

knowledge_summary: >
  The study advances ecological forecasting by demonstrating that nonlinear
  ecological processes and temporal dynamics can be modelled simultaneously
  within a unified probabilistic framework. By integrating hierarchical smooth
  functions with latent dynamic processes, DGAMs provide more accurate forecasts,
  improved uncertainty quantification and greater flexibility for analysing
  complex ecological time series than conventional generalised additive models.

impact_statement: >
  Dynamic Generalised Additive Models provide a general framework for
  forecasting discrete ecological time series while explicitly quantifying
  uncertainty, improving the reliability of ecological predictions needed for
  biodiversity conservation, ecosystem management and environmental
  decision-making under global change.

plain_language_summary: >
  Predicting how animal populations and ecosystems will change over time is
  difficult because ecological data are often noisy, incomplete and influenced
  by many interacting factors. This study introduces a new statistical approach
  that combines flexible models of ecological relationships with methods that
  account for how systems change through time. The approach produces more
  reliable forecasts and better estimates of uncertainty, helping scientists and
  managers make more informed decisions about future environmental change.


# =======
# Study design and scope
# =======

study_design:
  design_type: methodological-development
  evidence_synthesis_type:
  spatial_scope: "Simulation studies and NEON ecological monitoring data (USA)"
  temporal_scope: "Simulated time series and 2015–2019 NEON observations"
  observational_units:
    - ecological time series
    - tick abundance observations

population:
  focal_group: "Discrete ecological time series"
  associated_group: "Tick abundance monitoring"

outcomes:
  - forecasting-accuracy
  - probabilistic-forecasting
  - uncertainty-estimation


# =======
# Knowledge-network relationships
# =======

research_themes:
  - wildlife-ecology-health-one-health
  - ecological-interactions-system-dynamics
  - biodiversity-global-change

concepts:
  - generalized-additive-models
  - dynamic-generalized-additive-models
  - ecological-time-series
  - bayesian-inference
  - latent-factor-models
  - probabilistic-forecasting
  - nonlinear-modelling
  - state-space-models
  - hierarchical-models
  - uncertainty-quantification

study_systems:
  - simulated-ecological-time-series
  - tick-population-monitoring

focal_species:
  - amblyomma-americanum
  - ixodes-scapularis

regions:
  - united-states

methods:
  - dynamic-generalized-additive-models
  - bayesian-hierarchical-modelling
  - generalized-additive-models
  - latent-factor-analysis
  - state-space-modelling
  - hamiltonian-monte-carlo
  - markov-chain-monte-carlo
  - ecological-forecasting

data_products:
  - mvgam-r-package

research_datasets:
  - neon-tick-monitoring

projects: []

relationships:
  - develops: mvgam-r-package

# =======
# Teaching and discussion
# =======

teaching_uses:
  - ecological-forecasting
  - bayesian-statistics
  - generalized-additive-models
  - time-series-analysis
  - state-space-models

discussion_questions:
  - "Why do standard GAMs extrapolate poorly beyond observed data?"
  - "How do latent dynamic processes improve ecological forecasts?"
  - "What are the advantages of Bayesian hierarchical forecasting for ecological monitoring?"


seo_description: >
  Dynamic Generalised Additive Models (DGAMs) for Bayesian ecological forecasting of nonlinear discrete time series using the mvgam R package.

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
  reviewed_on: 2026-07-19

# Purpose: Source provenance.
provenance:
  # Purpose: Original source type. # Values: publisher-pdf, publisher-html, repository, author, 
  source_type:
    - publisher-pdf
    - author
    
  # Purpose: Original source URL.
  source_url: "https://besjournals.onlinelibrary.wiley.com/doi/epdf/10.1111/2041-210X.13974"

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