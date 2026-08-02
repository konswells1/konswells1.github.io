---
# =======
# Publication object identity
# =======

id: 2024-karunarathna-desert-rodent-dynamic-gam
title: "Modelling nonlinear responses of a desert rodent species to environmental change with hierarchical dynamic generalized additive models"
short_title: "Desert rodent dynamic GAMs"

object_type: publication
type: research-article
status: published

schema_version: "BKOS-1.0"
profile_version: "BPAS-2.0"

year_published: 2024
date: "2024-04-01"
date_created: 2026-07-11
date_modified: 2026-07-11

# =======
# Authorship
# =======

authors:
  - K.A.N.K. Karunarathna
  - Konstans Wells
  - Nicholas J. Clark

bahe_authors:
  - konstans-wells

author_entities:
  - position: 1
    name: "K.A.N.K. Karunarathna"
    person_id: ""
    orcid: ""
    affiliation_ids: []

  - position: 2
    name: "Konstans Wells"
    person_id: "konstans-wells"
    orcid: "0000-0003-0377-2463"
    affiliation_ids:
      - swansea-university

  - position: 3
    name: "Nicholas J. Clark"
    person_id: ""
    orcid: ""
    affiliation_ids: []

organisations:
  - swansea-university

# =======
# Bibliographic metadata
# =======

journal_name: "Ecological Modelling"
volume: "490"
issue: ""
pages: "110648"

publisher: "Elsevier B.V."
open_access: true
license: "CC BY 4.0"

citation_full: "Karunarathna, K.A.N.K., Wells, K., & Clark, N.J. (2024). Modelling nonlinear responses of a desert rodent species to environmental change with hierarchical dynamic generalized additive models. Ecological Modelling, 490, 110648."

identifiers:
  doi: "10.1016/j.ecolmodel.2024.110648"
  publisher_url: "https://doi.org/10.1016/j.ecolmodel.2024.110648"
  pmid: ""
  arxiv: ""
  openalex: ""
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1016/j.ecolmodel.2024.110648"
pdf: ""

abstract_original: |-
  Modelling abundance fluctuations of species is a crucial first step for understanding and forecasting system dynamics under future conditions. This study used hierarchical Dynamic Generalized Additive Models in a Bayesian framework to model 23 years of monthly Desert Pocket Mouse captures from the Portal Project in Arizona. Nonlinear and distributed lag effects of environmental predictors substantially improved model fit and forecasting performance, demonstrating the value of hierarchical dynamic models for ecological forecasting.

abstract_source: publisher
abstract_verbatim: false
abstract_public_display: true

# =======
# Funding and contributions
# =======

project_funding:
  project_funders:
    - Australian Research Council
    - National Science Foundation
  project_grants:
    - DE210101439
    - DEB-1929730
    - DEB-1622425

author_contributions:
  karunarathna:
    - conceptualization
    - data-curation
    - formal-analysis
    - methodology
    - validation
    - visualization
    - software
    - writing-original-draft
  konstans-wells:
    - methodology
    - writing-review-editing
  nicholas-j-clark:
    - funding-acquisition
    - resources
    - supervision
    - conceptualization
    - data-curation
    - formal-analysis
    - methodology
    - validation
    - visualization
    - software
    - writing-original-draft
    - writing-review-editing

# =======
# Display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: true
order: 20240401

# =======
# Image
# =======

image: "images/images_publications/karunarathna_gam.jpg"
image_alt: >
  ""

# =======
# Knowledge-network relationships
# =======

research_themes:
  - ecological-forecasting
  - population-ecology
  - biodiversity-global-change

concepts:
  - species-abundance
  - ecological-time-series
  - nonlinear-responses
  - hierarchical-models
  - generalized-additive-models
  - dyanmic-generalized-additive-models
  - bayesian-modelling
  - distributed-lag-effects
  - ecological-forecasting
  - environmental-change
  - desert-ecology

study_systems:
  - desert-rodents

focal_species:
  - chaetodipus-penicillatus

regions:
  - arizona-usa

methods:
  - hierarchical-dynamic-generalized-additive-models
  - bayesian-modelling
  - generalized-additive-models
  - gaussian-process
  - negative-binomial-modelling
  - ecological-time-series-analysis
  - forecasting

data_products: []
research_datasets: []
projects: DGAM

relationships: []

# =======
# Study design and scope
# =======

study_design:
  design_type: longitudinal-observational-modelling-study
  evidence_synthesis_type:
  spatial_scope: "Portal Project, Arizona, USA"
  temporal_scope: "1996–2018"
  observational_units:
    - monthly rodent captures
    - experimental plots
  sample_size: []

population:
  focal_group: "Desert Pocket Mouse (Chaetodipus penicillatus)"
  associated_group:

outcomes:
  - species-abundance
  - forecasting-performance

# =======
# Scientific claims and findings
# =======

claims:
  - Hierarchical dynamic generalized additive models improve ecological forecasting for multivariate count time series.
  - Nonlinear and distributed lag environmental effects substantially improve model fit.
  - Accounting for temporal dependence improves forecasting performance.
  - Bayesian iterative model development provides an effective framework for ecological forecasting.

key_findings:
  - Environmental effects with lags up to 12 months improved predictive performance.
  - Dynamic latent trends captured unexplained temporal autocorrelation.
  - Negative binomial hierarchical models outperformed simpler alternatives.
  - The final model produced the strongest forecasting performance among the candidate models.

scope_and_limitations:
  - Study focused on a single rodent species.
  - Results are based on one long-term ecological monitoring site.
  - Additional environmental and biotic predictors may improve forecasts.
  - Generalisation to other ecosystems requires further validation.

future_directions:
  - Evaluate the modelling framework for additional species.
  - Incorporate species interactions.
  - Extend forecasting horizons.
  - Apply the workflow across different ecosystems.

broader_implications:
  - Demonstrates the value of flexible Bayesian hierarchical models for ecological forecasting.
  - Supports improved prediction of ecological responses to environmental change.
  - Provides a reproducible workflow for long-term ecological monitoring analyses.

# =======
# Teaching and discussion
# =======

teaching_uses:
  - ecological-modelling
  - bayesian-statistics
  - generalized-additive-models
  - population-ecology
  - ecological-forecasting

discussion_questions:
  - "Why do distributed lag effects improve ecological forecasting?"
  - "What advantages do hierarchical Bayesian models provide for ecological time series?"
  - "How can latent temporal trends improve predictive performance?"

# =======
# Resources and media
# =======

resource_links:
  bahe_context: ""
  code: "https://github.com/kankkarunarathna/PortalAnalysis"
  data:
    figshare: ""
    dryad: ""
    zenodo: "https://zenodo.org/records/1217619"
    other_repository: "https://github.com/weecology/PortalData"
  software: ""
  preprint: ""
  supplementary_material: ""
  news:
    university_story: ""
    news_source_1: ""
    news_source_2: ""
    news_source_3: ""
  media:
    podcast: ""
    video: ""
  teaching:
    lecture_notes: ""
    discussion_guide: ""

# =======
# Related publications
# =======

related_publications:
  extends: []
  companion: []
  methodology: []
  review: []
  dataset: []
  precursor: []

# =======
# Summaries
# =======

summary: >
  This study develops hierarchical dynamic generalized additive models to forecast long-term abundance dynamics of the Desert Pocket Mouse using 23 years of ecological monitoring data. Incorporating nonlinear environmental responses, distributed lag effects and latent temporal trends substantially improved model performance and forecasting accuracy.

knowledge_summary: >
  The paper demonstrates how Bayesian hierarchical dynamic generalized additive models can accommodate nonlinear relationships, delayed environmental effects and temporal dependence in ecological count data. Using long-term monitoring from the Portal Project, it provides a practical workflow for ecological forecasting that balances model flexibility with rigorous evaluation and iterative model development.

impact_statement: >
  The study advances ecological forecasting by providing a flexible Bayesian modelling framework capable of capturing complex environmental responses in long-term ecological monitoring data, improving predictions relevant to conservation and ecosystem management.

seo_description: >
  Bayesian hierarchical dynamic generalized additive models improve ecological forecasting of long-term desert rodent population dynamics under environmental change.

attribution_note: >
  This BAHE knowledge object summarises and contextualises the published research. Scientific findings remain attributable to the original publication.

license_note: >
  Bibliographic metadata and BAHE-authored annotations are provided separately from the original publication. Copyright remains with the authors and publisher.

# =======
# Curation, provenance, review and validation
# =======

curation:
  status: awaiting-review
  completion:
    bibliography: verified
    scientific_annotation: high
    graph_links: partial
    external_resources: partial
    review: pending
  remaining_tasks:
    - verify-publication-date
    - verify-author-orcids
    - add-image
    - resolve-bahe-ids

provenance:
  source_documents:
    - type: publisher-pdf
      url: ""
  ai_support_by: "ChatGPT"
  human_creator: ""
  generated_date: ""

review:
  human_reviewed: false
  reviewed_by: ""
  review_date: ""
  next_review_date: ""

confidence:
  bibliographic: verified
  authorship: verified
  classification: high
  claims: high
  summaries: high
  resources: high

validation:
  yaml_valid: true
  links_checked: false
  ids_resolved: false
  validation_status: pending-review
  unresolved_ids:
    - karunarathna-person-id
    - nicholas-clark-person-id
  proposed_object_ids: []
  warnings: []

manual_fields_required:
  - publication_date
  - image
  - bahe_author_ids
  - ORCID identifiers
  - PDF URL
---