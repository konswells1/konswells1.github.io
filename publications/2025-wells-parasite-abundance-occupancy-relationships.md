---
# =======
# Publication object identity
# =======

id: 2025-wells-et-al-parasite-abundance-occupancy
title: "Parasite Abundance-Occupancy Relationships Across Biogeographic Regions: Joint Effects of Niche Breadth, Host Availability and Climate"
short_title: "Parasite Abundance-Occupancy Relationships"

object_type: publication
type: research-article
status: published

schema_version: "BKOS-1.0"
profile_version: "BPAS-2.0"

year_published: 2025
date: "2024-09-24"

# =====
# Authors
# =====

authors:
  - Konstans Wells
  - Jeffrey A. Bell
  - Alan Fecchio
  - Serguei Drovetski
  - Spencer Galen
  - Shannon Hackett
  - Holly Lutz
  - Heather R. Skeen
  - Gary Voelker
  - Wanyoike Wamiti
  - Jason D. Weckstein
  - Nicholas J. Clark

bahe_authors:
  - konstans-wells


# =====
# Bibliographic metadata
# =====

journal_name: "Journal of Biogeography"
volume: "52"
pages: "55-65"

publisher: "John Wiley & Sons"
open_access: true
license: "CC BY"

citation_full: >
  Wells, K., Bell, J. A., Fecchio, A., Drovetski, S.,
  Galen, S., Hackett, S., Lutz, H., Skeen, H. R.,
  Voelker, G., Wamiti, W., Weckstein, J. D., & Clark,
  N. J. (2025). Parasite abundance-occupancy
  relationships across biogeographic regions:
  Joint effects of niche breadth, host availability
  and climate. Journal of Biogeography, 52, 55-65.

identifiers:
  doi: "10.1111/jbi.15015"
  publisher_url: "https://onlinelibrary.wiley.com/doi/full/10.1111/jbi.15015"
  pmid: ""
  arxiv: ""
  openalex: ""
  semantic_scholar: ""
  
canonical_source_url: "https://doi.org/10.1111/jbi.15015"
pdf: "https://onlinelibrary.wiley.com/doi/pdf/10.1111/jbi.15015"

# =====
# Abstract
# =====

abstract_original: |-
  Aim: Changing biodiversity and environmental conditions may allow multi-host pathogens to spread among host species and
  affect prevalence. There are several widely acknowledged theories about mechanisms that may influence variation in pathogen
  prevalence, including the controversially debated dilution effect and abundance-occupancy relationship hypotheses. Here, we
  explore such abundance-occupancy relationships for unique lineages of three vector-borne avian blood parasite genera (the avian
  malaria parasite Plasmodium and the related haemosporidian parasites Parahaemoproteus and Leucocytozoon) across biogeo-
  graphical regions.
  Location: Nearctic-Neotropical and Palearctic-Afrotropical regions.
  Methods: We compiled a cross-continental dataset of 17,116 bird individuals surveyed from 46 bird assemblages across the
  Nearctic-Neotropical and Palearctic-Afrotropical regions and explored relationships between local parasite lineage prevalence
  and host assemblage metrics in a Bayesian random regression framework.
  Results: Most lineages from these three genera infected ≥ 5 host species and exhibited clear phylogenetic or functional host
  specificity. Lineage prevalence from all three genera increased with host range, but also with higher degrees of specialisa-
  tion to phylogenetically or functionally related host species. Local avian community features were also found to be important
  drivers of prevalence. For example, bird species richness was positively correlated with lineage prevalence for Plasmodium
  and Leucocytozoon, whereas higher relative abundances of the main host species were associated with lower prevalence for
  Plasmodium and Parahaemoproteus but higher prevalence for Leucocytozoon.

# =====
# Funding
# =====

project_funders:
  - Australian Research Council
  - The Royal Society

project_grants:
  - ARC DECRA Fellowship DE210101439
  - Royal Society Research Grant RGS/R2/222152

# =======
# BAHE display controls
# =======

featured: true
show_on_publications_page: true
show_on_homepage: true

order: 20250101

# =======
# Image
# =======

image: "images/images_publications/haemosporidia-abundance-occupancy.png"

image_alt: >
  Relationship between lineage prevalence within all locally recorded host species and regional bird species richness for three different haemosporidian genera.



# =====
# Research classification
# =====

research_themes:
  - wildlife-health-one-health
  - biodiversity-global-change
  - ecological-interactions-system-dynamics

concepts:
  - abundance-occupancy-relationships
  - niche-breadth
  - niche-breadth-hypothesis
  - trade-off-hypothesis
  - host-specificity
  - parasite-prevalence
  - host-availability
  - biodiversity
  - dilution-effect
  - climate-gradients
  - avian-malaria
  - multi-host-pathogens

methods:
  - Bayesian-hierarchical-modelling
  - Bayesian random regression
  - Hamiltonian-Monte-Carlo
  - phylogenetic-analysis
  - functional-trait-analysis
  - host-specificity-metrics
  - macroecological-comparative-analysis

study_systems:
  - avian-haemosporidian-parasites
  - wild-bird-communities

regions:
  - global
  - Nearctic
  - Neotropics
  - Palearctic
  - Afrotropics

# =====
# Study design
# =====

study_design:
  design_type: comparative macroecological observational study
  spatial_scope: intercontinental
  temporal_scope: compiled published datasets

population:
  focal_group: avian haemosporidian parasites

sample_size:
  bird_individuals: 17116
  infected_individuals: 2830
  bird_assemblages: 46
  parasite_lineage_records: 144
  functional_lineages_available: 1983

parasite_genera:
  - Plasmodium
  - Parahaemoproteus
  - Haemoproteus
  - Leucocytozoon

# =====
# Variables
# =====

predictor_variables:
  - host range
  - phylogenetic host specificity
  - functional host specificity
  - bird species richness
  - main host availability
  - climate principal component 1
  - climate principal component 2

response_variables:
  - parasite lineage prevalence
  - local parasite occupancy


# =======
# Knowledge statements
# =======

knowledge_statements:
  - id: statement-01
    text: >
      Parasite abundance-occupancy relationships emerge from the joint effects of host niche breadth, host availability and climate rather than from any single ecological mechanism.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-02
    text: >
      Broader host ranges and more diverse host communities generally amplify parasite prevalence by increasing ecological opportunities for transmission, providing broad empirical support for the niche breadth hypothesis.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      High parasite prevalence is also associated with specialization on phylogenetically or functionally similar host species, demonstrating that ecological specialization and broad host ranges are complementary rather than competing strategies.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Different parasite genera exhibit contrasting abundance-occupancy relationships with host availability and climate, indicating that no single general rule explains parasite prevalence across vector-borne parasite systems.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Cross-biogeographic analyses of individual parasite lineages provide a powerful empirical framework for testing competing ecological hypotheses governing parasite prevalence and distribution.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-06
    text: >
      Predicting parasite spread under global environmental change requires integrating parasite life-history traits, host community composition and climatic conditions within a common ecological framework.
    knowledge_type: interpretation
    attributed_to: source-publication

# =====
# Ecological significance
# =====

ecological_contributions:
  - Reconciles niche breadth and specialization hypotheses for parasite abundance-occupancy relationships.
  - Demonstrates that biodiversity can amplify infection risk for vector-borne parasites.
  - Provides one of the largest comparative analyses of avian haemosporidian prevalence across continents.
  - Highlights the importance of host community assembly in disease biogeography.

# =====
# Teaching
# =====

teaching_uses:
  - disease ecology
  - parasite ecology
  - macroecology
  - community ecology
  - Bayesian statistics
  - biogeography

discussion_questions:
  - Why can broader host ranges and stronger specialization both increase parasite prevalence?
  - Why do different parasite genera respond differently to climate gradients?
  - Under what ecological conditions does biodiversity amplify rather than dilute disease risk?
  - How might vector ecology modify abundance-occupancy relationships?

# =====
# Summaries
# =====

summary: >
  Wells et al. analysed avian haemosporidian parasites across four
  major biogeographic regions using data from more than 17,000 birds.
  Parasite prevalence increased with broader host ranges but also with
  specialization on phylogenetically or functionally similar hosts.
  Host diversity generally amplified infection risk, while climate and
  host availability produced genus-specific responses. The study
  demonstrates that parasite abundance-occupancy relationships emerge
  from interacting effects of ecological opportunity, host
  specialization and environmental conditions rather than from any
  single mechanism.

knowledge_summary: >
  This study integrates ecological theory on niche breadth,
  specialization and biodiversity-disease relationships into a unified
  macroecological framework. It shows that parasite prevalence is best
  explained by joint effects of host range, host specialization,
  community composition and climate, helping reconcile competing
  hypotheses about pathogen distribution and transmission.

impact_statement: >
  The paper advances understanding of global parasite ecology by
  demonstrating that ecological opportunity and host specialization
  jointly determine parasite prevalence, providing a stronger basis for
  forecasting infectious disease dynamics under biodiversity and
  climate change.

seo_description: >
  Macroecological study demonstrating how host niche breadth,
  specialization, biodiversity and climate jointly shape parasite
  prevalence across global bird communities.

# =======
# Provenance and curation
# =======

curation:
  # Purpose: curation status. # Values: unreviewed, in-review, reviewed, revision-required
  status: reviewed
  reviewed_by: konstans-wells
  reviewed_on: 2026-07-18

provenance:
  # Purpose: Original source type. # Values: publisher-pdf, publisher-html, repository, author, 
  source_type:
    - publisher-pdf
    - author
    
  # Purpose: Original source URL.
  source_url: "https://doi.org/10.1111/geb.70077"
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