
---
id: 2021-giles-optimizing-noninvasive-sampling-zoonotic-bat-virus
title: "Optimizing noninvasive sampling of a zoonotic bat virus"
short_title: "Optimizing noninvasive bat virus sampling"
object_type: publication
publication_type: research-article
publication_subtype: methodological-study
status: published
year_published: 2021
date: 2021-08-21
journal_name: Ecology and Evolution
volume: "11"
pages: "12307–12321"
doi: "10.1002/ece3.7830"

authors:
  - John R. Giles
  - Alison J. Peel
  - Konstans Wells
  - Raina K. Plowright
  - Hamish McCallum
  - Olivier Restif

bahe_authors:
  - konstans-wells

# =======
# Image
# =======

# Relative image path.
image: "images/images_publications/Giles_Figure.jpg"

image_alt: >-
  Conceptual illustration comparing three approaches for estimating viral
  prevalence in bat colonies. The figure contrasts individual bat sampling
  with two under-roost urine sampling methods that collect pooled samples from
  plastic sheets. Example prevalence calculations demonstrate how pooling
  samples from multiple bats can overestimate true colony-level viral
  prevalence compared with individual-level sampling.

# Image caption
image_caption: >-
  Comparison of sampling strategies used to estimate viral prevalence in bat
  roosts. Panel (a) illustrates individual-level sampling, where captured bats
  each contribute a single sample to estimate prevalence. Panels (b) and (c)
  show under-roost urine collection methods in which samples are pooled within
  sheet quadrants or across entire plastic sheets placed beneath the colony.
  Because pooled samples may contain urine from multiple bats, the apparent
  prevalence of infection can exceed the true proportion of infected
  individuals. The conceptual example highlights how sampling design
  influences prevalence estimates and demonstrates the importance of
  accounting for pooled sampling when inferring pathogen dynamics in wildlife
  populations.



# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: true

order: 20210821



research_themes:
  - health-environment-interactions
  - ecological-interactions-system-dynamics
  - biodiversity-global-change

concepts:
  - bat-virus
  - hendra-virus
  - noninvasive-sampling
  - under-roost-sampling
  - sampling-bias
  - spatial-statistics
  - disease-ecology
  - prevalence-estimation
  - zoonotic-spillover

methods:
  - generalized-additive-model
  - spatial-simulation
  - poisson-cluster-process
  - sensitivity-analysis
  - boosted-regression-trees
  - latin-hypercube-sampling

knowledge_statements:
  - id: statement-01
    knowledge_type: empirical-result
    attributed_to: source-publication
    text: Conventional under-roost pooled sampling substantially overestimates bat-virus prevalence because samples receive excreta from multiple individuals.
  - id: statement-02
    knowledge_type: empirical-result
    attributed_to: source-publication
    text: The commonly used quadrant-sheet design estimated viral prevalence approximately 3.2 times higher than individual-level estimates.
  - id: statement-03
    knowledge_type: empirical-result
    attributed_to: source-publication
    text: Spatial autocorrelation among sampling sheets and clustering of bats are primary drivers of positive estimation bias.
  - id: statement-04
    knowledge_type: methodological-proposition
    attributed_to: source-publication
    text: Smaller, more numerous, spatially dispersed sampling sheets substantially reduce prevalence-estimation bias.
  - id: statement-05
    knowledge_type: recommendation
    attributed_to: source-publication
    text: A stratified random sampling design using approximately 80–100 sheets of 0.75–1 m² provides a practical balance between estimation bias and false negatives.
  - id: statement-06
    knowledge_type: interpretation
    attributed_to: source-publication
    text: Under-roost sampling is highly sensitive for pathogen detection but less suitable for unbiased prevalence estimation unless sampling design is optimized.
  - id: statement-07
    knowledge_type: conceptual-proposition
    attributed_to: source-publication
    text: Spatial sample pooling creates an ecological aggregation bias that affects many wildlife disease surveillance systems.
  - id: statement-08
    knowledge_type: policy-implication
    attributed_to: source-publication
    text: Optimized noninvasive surveillance can improve monitoring of zoonotic spillover risk while minimizing disturbance to wildlife.

summary: >
  The study combines empirical Hendra virus field data with spatial simulation
  models to quantify bias introduced by pooled under-roost sampling of bats.
  Large sampling sheets consistently overestimate viral prevalence because
  multiple bats contribute to pooled samples. Simulation analyses demonstrate
  that reducing sheet size, increasing sheet number and spatially dispersing
  sheets markedly improve prevalence estimation while maintaining detection
  probability.

knowledge_summary: >
  This publication provides one of the first quantitative evaluations of bias
  arising from noninvasive pooled wildlife sampling and offers a general
  framework for optimizing surveillance designs for bat-borne zoonotic viruses.

relationships:
  - predicate: authored_by
    object_type: person
    object_id: konstans-wells
  - predicate: addresses
    object_type: concept
    object_id: sampling-bias
  - predicate: addresses
    object_type: concept
    object_id: disease-ecology
  - predicate: addresses
    object_type: concept
    object_id: zoonotic-spillover

provenance:
  source_type:
    - publisher-pdf
  source_doi: 10.1002/ece3.7830
  ai_generated: true
  human_verified: false
---
