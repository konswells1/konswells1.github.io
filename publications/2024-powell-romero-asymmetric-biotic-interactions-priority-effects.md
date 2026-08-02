---

# =======
# Publication object identity
# =======

id: 2024-powell-romero-priority-effects-asymmetric-interactions
title: "Asymmetric biotic interactions cannot be inferred Without accounting for priority effects"
short_title: "Priority effects and asymmetric biotic interactions"

object_type: publication
type: perspective
status: published

schema_version: "BKOS-1.0"
profile_version: "BPAS-2.0"

year_published: 2024
date: 2024-09-01
date_created: 2026-07-11
date_modified: 2026-07-11

# =======
# Authorship
# =======

# Preserve the official published author order and spelling.
authors:
  - Francisca Powell-Romero
  - Konstans Wells
  - Nicholas J. Clark

bahe_authors:
  - konstans-wells

author_entities:
  - position: 1
    name: "Francisca Powell-Romero"
    affiliation_ids:
      - university-of-queensland

  - position: 2
    name: "Konstans Wells"
    person_id: konstans-wells
    orcid: "0000-0003-0377-2463"
    affiliation_ids:
      - swansea-university

  - position: 3
    name: "Nicholas J. Clark"
    affiliation_ids:
      - university-of-queensland

organisations:
  - university-of-queensland
  - swansea-university

journal_name: "Ecology Letters"
volume: 27
issue: 9
pages: "e14509"
publisher: "Wiley"
open_access: true
license: "CC BY-NC 4.0"

citation_full: "Powell-Romero, F., Wells, K., & Clark, N. J. (2024). Asymmetric Biotic Interactions Cannot Be Inferred Without Accounting for Priority Effects. Ecology Letters, 27, e14509. https://doi.org/10.1111/ele.14509"

identifiers:
  doi: "10.1111/ele.14509"
  publisher_url: "https://onlinelibrary.wiley.com/doi/10.1111/ele.14509"
  pmid: null
  arxiv: null
  openalex: null
  semantic_scholar: null

canonical_source_url: "https://doi.org/10.1111/ele.14509"
pdf: "https://doi.org/10.1111/ele.14509"



project_funding:
  project_funders:
    - "The Royal Society"
    - "Australian Research Council"
  project_grants:
    - 'RGS\R2\222152'
    - 'DE210101439'

author_contributions:
  francisca-powell-romero:
    - study-design
    - coding
    - analysis
    - visualisation
    - writing
  konstans-wells:
    - conceptualisation
    - study-design
    - coding
    - analysis
    - writing
  nicholas-j-clark:
    - conceptualisation
    - coding
    - analysis
    - writing



# =====
# Abstract
# =====

abstract_original: |-
  Understanding biotic interactions is a crucial goal in community ecology and
  species distribution modelling, and large strides have been made towards
  improving multivariate computational methods with the aim of quantifying
  biotic interactions and improving predictions of species occurrence. Yet,
  while considerable attention has been given to computational approaches and
  the interpretation of these quantitative tools, the importance of sampling
  design to reveal these biotic interactions has received little consideration.
  This study explores the influential role of priority effects, that is, the
  order of habitat colonisation, in shaping our ability to detect biotic
  interactions. Using a simple set of simulations, we demonstrate that
  commonly used cross-sectional co-occurrence data alone cannot be used to
  make reliable inferences on asymmetric biotic interactions, even if they
  perform well in predicting the occurrence of species. We then show how
  sampling designs that consider priority effects can recover the asymmetric
  effects that are lost when priority effects are ignored. Based on these findings, we urge for caution when drawing inferences on biotic interactions from cross-sectional binary co-occurrence data, and provide guidance on sampling designs that may provide the necessary data to tackle this longstanding challenge.

abstract_source: publisher
abstract_public_display: true


# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20240901

# =======
# Image
# =======

image: "images/images_publications/mele14509-fig-0001-m.jpg"
image_alt: >
  Diagram illustrating how priority effects influence inference of
  asymmetric biotic interactions.


# =======
# BAHE knowledge-network relationships
# =======

research_themes:
  - community-ecology
  - biodiversity-global-change
  - ecological-modelling

concepts:
  - biotic-interactions
  - priority-effects
  - asymmetric-interactions
  - species-cooccurrence
  - community-assembly
  - species-distribution-modelling
  - joint-species-distribution-modelling
  - sampling-design
  - ecological-inference
  - colonisation-history

study_systems:
  - simulated-species-communities

focal_species: []

regions:
  - global

methods:
  - simulation-modelling
  - generalised-linear-models
  - binary-occurrence-modelling
  - cooccurrence-analysis

data_products: []

research_datasets:
  - zenodo.13363723

projects: coinfections

relationships:
  - predicate: challenges
    object: cooccurrence-based-inference-of-biotic-interactions

  - predicate: introduces
    object: priority-effect-aware-sampling-design

study_design:
  design_type: simulation-study
  evidence_synthesis_type: ""
  spatial_scope: ""
  temporal_scope: ""
  observational_units:
    - simulated-species-pairs
    - simulated-community-sites
  sample_size:
    simulated_records: 1000
    simulation_replicates: 1000

population:
  focal_group: species-interactions
  associated_group: ecological-communities

outcomes:
  - detection-of-asymmetric-interactions
  - prediction-of-species-occurrence
  - interaction-effect-estimation

claims:
  - Cross-sectional binary co-occurrence data cannot reliably infer asymmetric biotic interactions when priority effects influence community assembly.
  - Models that account for colonisation order can recover asymmetric interaction effects that are obscured when priority effects are ignored.
  - Good predictive performance of species occurrence models does not guarantee accurate inference of underlying ecological mechanisms.
  - Sampling designs that record colonisation history are required to investigate asymmetric species interactions.

key_findings:
  - Priority-effect-aware models accurately estimated simulated interaction effects across symmetric and asymmetric interaction scenarios.
  - Co-occurrence models without colonisation history inferred interactions as symmetric and failed to detect asymmetric effects.
  - Including priority effects improved predictive performance of simulated species occurrence models.
  - Longitudinal or experimental sampling designs can provide information needed to infer colonisation order.

scope_and_limitations:
  - The study uses simplified simulations of pairwise species interactions rather than empirical communities.
  - Simulated interaction strengths and environmental effects may not capture all complexity of natural systems.
  - Priority effects may vary in strength and importance across ecological contexts.
  - The study focuses on direct asymmetric interactions and does not fully model all indirect community assembly processes.

future_directions:
  - Develop empirical sampling designs that record colonisation history.
  - Apply priority-effect-aware approaches to experimental studies of species interactions.
  - Integrate longitudinal ecological datasets with models that account for arrival order.
  - Investigate how spatial and temporal scales influence detection of asymmetric interactions.

broader_implications:
  - Ecological models of species distributions should consider whether observed associations represent true interactions or historical assembly processes.
  - Improved sampling designs may strengthen predictions of community responses to environmental change.
  - Accurate inference of biotic interactions is important for biodiversity forecasting and ecological management.

teaching_uses:
  - community-ecology
  - species-distribution-modelling
  - ecological-statistics
  - simulation-modelling
  - ecological-inference

discussion_questions:
  - "Why can strong predictive performance fail to reveal the mechanisms underlying species co-occurrence?"
  - "How does colonisation order influence interpretation of asymmetric species interactions?"
  - "What sampling designs would provide better evidence for causal ecological interactions?"
  - "When might cross-sectional co-occurrence data still be useful?"

resource_links:
  bahe_context: ""
  code: ""
  data:
    figshare: ""
    dryad: ""
    zenodo: "https://doi.org/10.5281/zenodo.13363723"
    other_repository: ""
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

related_publications:
  extends: []
  companion: []
  methodology: []
  review: []
  dataset: []
  precursor: []

summary: >
  This perspective demonstrates through simulation modelling that asymmetric
  biotic interactions cannot be reliably inferred from binary cross-sectional
  co-occurrence data when priority effects influence community assembly. The
  authors show that recording colonisation order enables more accurate
  estimation of interaction effects and recommend sampling designs that capture
  ecological history.

knowledge_summary: >
  The study highlights a fundamental limitation in ecological inference: species
  co-occurrence patterns do not necessarily reveal the direction or strength of
  underlying interactions. By simulating alternative interaction scenarios and
  comparing models with and without priority effects, the authors show that
  colonisation history is essential for detecting asymmetric relationships.
  The work links community ecology, species distribution modelling and
  ecological statistics by emphasising the importance of study design alongside
  computational methods.

impact_statement: >
  This work provides guidance for improving inference of species interactions
  by demonstrating that sampling design and ecological history are critical
  components of reliable biodiversity modelling.

seo_description: >
  Simulation study showing why priority effects are essential for detecting asymmetric species interactions.

attribution_note: >
  This BAHE knowledge object summarises and contextualises the published
  research for knowledge discovery and teaching. Original findings remain
  attributed to Powell-Romero, Wells and Clark.



# =======
# Provenance and curation
# =======

curation:
  status: awaiting-review
  created: 2026-07-11
  modified: 2026-07-11

  completion:
    bibliography: verified
    scientific_annotation: verified
    graph_links: verified
    external_resources: partial
    review: pending

  remaining_tasks:
    - add-bahe-url
    - verify-funding
    - add-author-orcids
    - verify-image-license

provenance:
  source_type: publisher-pdf
  source_url: ""
  AI_support_by: "ChatGPT"
  human_creator: konstans-wells

  review:
    human_reviewed: false
    reviewed_by: konstans-wells
    review_date: 2026-07-14

  confidence:
    bibliographic: verified
    authorship: verified
    classification: high
    claims: high
    summaries: high
    resources: verified

  unresolved_ids: ""
  proposed_object_ids: ""

  validation_status: pending-review

---