---
# ============================================================================
# BAHE publication knowledge object
#
# Generated following the BPubAS publication annotation standard.
# Structure, ordering and comments preserved from the canonical template.
# ============================================================================

id: 2014-wells-population-fluctuations-ecological-networks
title: "Population fluctuations affect inference in ecological networks of multi-species interactions"
short_title: "Population fluctuations and ecological networks"
object_type: publication
publication_type: research-article
publication_subtype: empirical-study
status: published
year_published: 2014
date: 2014-05-01
date_created: 2026-07-25
date_modified: 2026-07-25
publication_language: en-GB
schema_version: BKOS-1.0
profile_version: BPubAS-1.0

authors:
  - Konstans Wells
  - Heike Feldhaar
  - Robert B. O'Hara

bahe_authors:
  - konstans-wells

journal_name: "Oikos"
volume: "123"
issue: "5"
pages: "589-598"
publisher: "Nordic Society Oikos / Wiley"
open_access: false
license: "All rights reserved"

citation_full: >-
  Wells, K., Feldhaar, H. & O'Hara, R.B. (2014). Population fluctuations
  affect inference in ecological networks of multi-species interactions.
  Oikos 123, 589-598. https://doi.org/10.1111/oik.01149

citation_short: "Wells et al. (2014) Oikos"

identifiers:
  doi: "10.1111/oik.01149"
  publisher_url: "https://doi.org/10.1111/oik.01149"
  pmid: ""
  arxiv: ""
  openalex: ""
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1111/oik.01149"
pdf: ""

abstract_original: |-
  Local abundance and population fluctuations are key factors affecting the realized interaction frequencies in biotic interactions, but they are commonly ignored when network metrics are calculated over aggregated sets of observations. Here we studied how abundance fluctuations may affect network-level inference in bipartite ecological networks using simulation models. Variation in specialization, dependence, diversity and H2′ was strongly correlated with abundance fluctuations, whereas connectance was comparatively robust. We conclude that ecological network inference should account for underlying population dynamics and uncertainty in observed interaction frequencies by modelling lower-level processes rather than relying solely on aggregated interaction matrices.

abstract_source: publisher
abstract_verbatim: false
abstract_public_display: true

image: "/images/images_publications/Population-fluctuations-ecological-networks_Wells-2014.png"
image_alt: "Conceptual illustration of simulated ecological interaction networks under fluctuating population dynamics."
image_caption: "Simulation framework linking stochastic population dynamics with ecological network inference."
image_license: "All rights reserved"
image_credit: "Wells, Feldhaar & O'Hara (2014)"
image_license_verified: false

featured: false
show_on_publications_page: true
show_on_homepage: false
order: 20140501

knowledge_statements:
  - id: statement-01
    text: Population fluctuations substantially alter quantitative ecological network metrics even when underlying interaction probabilities remain unchanged.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-02
    text: Environmental stochasticity explained most variation in specialization and diversity metrics.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-03
    text: Weighted NODF was influenced primarily by differences in carrying capacity among consumer species.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-04
    text: Binary connectance remained comparatively robust because it does not depend directly on interaction frequency.
    knowledge_type: empirical-result
    attributed_to: source-publication
  - id: statement-05
    text: Population-dynamic models provide a stronger basis for ecological network inference than analyses based only on aggregated interaction matrices.
    knowledge_type: methodological-proposition
    attributed_to: source-publication
  - id: statement-06
    text: Quantifying uncertainty in interaction frequencies improves comparison among ecological networks.
    knowledge_type: recommendation
    attributed_to: source-publication

summary: >
  Simulation analyses demonstrated that stochastic population dynamics can
  strongly bias inference from quantitative ecological networks.

knowledge_summary: >
  The paper links population ecology with ecological network analysis by
  showing that many widely used network metrics partly reflect demographic
  and environmental variability rather than intrinsic interaction structure.

impact_statement: >
  Reliable inference about ecological networks requires explicit modelling of
  population dynamics and uncertainty.

plain_language_summary: >
  Changes in animal numbers alone can make ecological networks appear to
  change even when species interact in the same way. Accounting for population
  fluctuations leads to more reliable ecological conclusions.

research_themes:
  - quantitative-ecology-modelling
  - ecological-interactions-system-dynamics

concepts:
  - ecological-networks
  - population-dynamics
  - environmental-stochasticity
  - demographic-stochasticity
  - bipartite-networks
  - uncertainty
  - interaction-strength

methods:
  - simulation-modelling
  - ricker-population-model
  - bayesian-analysis
  - ecological-network-analysis

curation:
  status: unreviewed
  reviewed_by: ""
  reviewed_on: ""

provenance:
  source_type:
    - publisher-pdf
  source_url: "https://doi.org/10.1111/oik.01149"
  ai_assistance:
    system: ChatGPT
    roles:
      - metadata-extraction
      - concept-classification
      - draft-summary
    outputs_human_verified: false
  confidence:
    bibliographic_metadata: verified
    claims: needs-verification
    summaries: needs-verification
    concept_classification: unreviewed
---
