---
# =======
# Publication object identity
# =======

id: 2020-wells-distinct-spread-dna-rna-viruses
title: "Distinct Spread of DNA and RNA Viruses among Mammals amid Prominent Role of Domestic Species"
short_title: "Distinct Spread of DNA and RNA Viruses among Mammals"

object_type: publication 
publication_type: research-article
publication_subtype: empirical-study 
status: published

schema_version: BKOS-1.0
profile_version: BPubAS-1.0

year_published: 2020
date: "2020-02-09"
date_created: 2026-07-11
date_modified: 2026-07-11

# ==========================================================
# Authors
# ==========================================================

authors:
  - Konstans Wells
  - Serge Morand
  - Maya Wardeh
  - Matthew Baylis

bahe_authors:
  - konstans-wells

author_entities:
  - position: 1
    name: "Konstans Wells"
    person_id: "konstans-wells"
    orcid: "0000-0003-0377-2463"
    affiliation_ids:
      - swansea-university

  - position: 2
    name: "Serge Morand"
    person_id: "serge-morand"
    orcid: "0000-0003-3986-7659"

  - position: 3
    name: "Maya Wardeh"
    person_id: "maya-wardeh"
    orcid: "0000-0002-2316-5460"

  - position: 4
    name: "Matthew Baylis"
    person_id: "matthew-baylis"
    orcid: "0000-0003-0335-187X"

organisations:
  - swansea-university
  - cirad
  - kasetsart-university
  - university-of-liverpool
  - public-health-england

# ==========================================================
# Bibliographic metadata
# ==========================================================

journal_name: "Global Ecology and Biogeography"
volume: "29"
issue: "3"
pages: "470-481"

publisher: "John Wiley & Sons"
open_access: true
license: "CC BY"

citation_full: >
  Wells, K., Morand, S., Wardeh, M., & Baylis, M. (2020).
  Distinct spread of DNA and RNA viruses among mammals amid
  prominent role of domestic species.
  Global Ecology and Biogeography, 29, 470–481.

identifiers:
  doi: "10.1111/geb.13045"

canonical_source_url: "https://doi.org/10.1111/geb.13045"

# =======
# Funding
# =======

project_funders:
  - Biotechnology and Biological Sciences Research Council
  - Natural Environment Research Council
  - National Institute for Health Research
  - Public Health England
  - Agence Nationale de la Recherche

project_grants:
  - NE/G002827/1
  - BB/K003798/1
  - BB/N02320X/1
  - MR/R024898/1
  - ANR-17-CE35-0003


# =======
# Abstract
# =======

abstract_original: |-
  Aim: Emerging infectious diseases arising from pathogen spillover from mammals to
  humans constitute a substantial health threat. Tracing virus origin and predicting the
  most likely host species for future spillover events are major objectives in One Health
  disciplines.
  We assessed patterns of virus sharing among a large diversity of mammals, including
  humans and domestic species.
  Location: Global.
  Time period: Current.
  Major taxa studied: Mammals and associated viruses.
  Methods: We used network centrality analysis and trait-based Bayesian hierarchical
  models to explore patterns of virus sharing among mammals. We analysed a global
  database that compiled the associations between 1,785 virus species and 725 mammalian host species as sourced from automatic screening of meta-data accompanying
  published nucleotide sequences between 1950 and 2019.
  Results: We show that based on current evidence, domesticated mammals hold the
  most central positions in networks of known mammal–virus associations. Among en-
  tire host–virus networks, Carnivora and Chiroptera hold central positions for mainly
  sharing RNA viruses, whereas ungulates hold central positions for sharing both RNA
  and DNA viruses with other host species. We revealed strong evidence that DNA
  viruses were phylogenetically more host specific than RNA viruses. RNA viruses ex-
  hibited low functional host specificity despite an overall tendency to infect phyloge-
  netically related species, signifying high potential to shift across hosts with different
  ecological niches. The frequencies of sharing viruses among hosts and the proportion
  of zoonotic viruses in hosts were larger for RNA than for DNA viruses.
  Main conclusions: Acknowledging the role of domestic species in addition to host
  and virus traits in patterns of virus sharing is necessary to improve our understand-
  ing of virus spread and spillover in times of global change. Understanding multi-host
  virus-sharing pathways adds focus to curtail disease spread


abstract_source: publisher
abstract_verbatim: false

# =======
# Image
# =======

image: "images/images_publications/virus_networks.jpg"

image_alt: >-
  Paired network diagrams showing patterns of RNA virus sharing (left) and
  DNA virus sharing (right) among 725 mammalian species. Each node represents
  a mammal species, with node size indicating the number of shared virus
  species and edge thickness representing the number of viruses shared
  between host pairs. Node colours distinguish mammalian taxonomic orders,
  highlighting differences in the structure and connectivity of RNA and DNA
  virus sharing networks.

# Image caption
image_caption: >-
  Comparative host-sharing networks for RNA viruses (left) and DNA viruses
  (right) across 725 mammalian species. Each node represents a mammal
  species, with larger nodes indicating hosts that share viruses with more
  species. Edge widths are proportional to the number of virus species shared
  between pairs of hosts, while node colours denote mammalian orders. The
  networks illustrate contrasting patterns of viral connectivity among
  mammalian hosts and identify species that occupy central positions in the
  transmission network, providing insight into the ecological structure of
  virus sharing and the potential pathways for cross-species transmission.
  
# =======
# BAHE display controls
# =======

featured: true
show_on_publications_page: true
show_on_homepage: true

order: 20200209

# =======
# Knowledge statements
# =======

knowledge_statements:
  - id: statement-01
    text: >
      Domestic mammals occupy central positions in global mammal–virus sharing
      networks, facilitating pathogen transmission between wildlife and humans.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      RNA viruses exhibit broader host ranges and lower host specificity than
      DNA viruses, increasing their potential for cross-species transmission.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      DNA viruses are generally more phylogenetically host-specific than RNA
      viruses, reflecting contrasting evolutionary dynamics of host switching.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-04
    text: >
      Mammalian orders differ markedly in their contribution to virus-sharing
      networks, demonstrating that host taxonomy influences pathogen spread.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Network analyses integrating host and virus characteristics provide a
      powerful framework for understanding pathogen spillover across mammal
      communities.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-06
    text: >
      Predicting future zoonotic emergence requires jointly considering host
      traits, domestication status and viral characteristics.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-07
    text: >
      Reliable inference from global host–pathogen association networks requires
      probabilistic modelling that explicitly accounts for incomplete sampling
      and observation bias rather than treating observed interaction networks as
      complete representations of biological reality.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

# =======
# Summaries
# =======

# Concise publication summary.
summary: >
  This study analysed a global network of mammal–virus associations to
  investigate how host identity, domestication and viral genome type shape
  patterns of virus sharing and zoonotic spillover among mammals. Using
  Bayesian hierarchical network models, it quantified differences in host
  specificity and transmission pathways for DNA and RNA viruses while
  identifying domestic mammals as central connectors in global virus-sharing
  networks.

# Knowledge-network summary.
knowledge_summary: >
  The study advances understanding of pathogen spillover by demonstrating that
  virus sharing emerges from interactions between host ecology,
  domestication and viral evolutionary characteristics rather than from a single host
  species alone. It shows that domestic mammals disproportionately connect
  wildlife and humans within global virus-sharing networks, RNA viruses have
  greater capacity for host sharing than DNA viruses, and probabilistic network
  modelling provides a robust framework for inferring pathogen-sharing
  processes from incomplete host–pathogen association data.

# Scientific or societal significance.
impact_statement: >
  By revealing how domestication, host phylogeny and viral genome type jointly
  structure global virus-sharing networks, this study provides a stronger
  scientific basis for predicting pathogen spillover and prioritising One
  Health surveillance of emerging zoonotic diseases.

# Non-technical summary.
plain_language_summary: >
  Viruses move between animal species through networks of shared hosts rather
  than through isolated transmission events. This study shows that domestic
  animals such as cattle, pigs, sheep and dogs play particularly important
  roles in connecting wildlife and humans, while RNA viruses are generally more
  capable of infecting multiple host species than DNA viruses. Understanding
  these global patterns can help improve surveillance and reduce the risk of
  future diseases spreading from animals to people.


# =======
# Research classification
# =======

research_themes:
  - Wildlife ecology, health and One Health
  - Ecological interactions and system dynamics
  - Biodiversity under Global Change

concepts:
  - virus-sharing
  - host-pathogen-networks
  - host-specificity
  - phylogenetic-host-specificity
  - cross-species-transmission
  - zoonotic-viruses
  - domestication
  - mammal-virus-associations
  - dna-virus
  - rna-virus
  - network-centrality

methods:
  - ecological-network-analysis
  - eigenvector-centrality-analysis
  - bayesian-hierarchical-modelling
  - hierarchical-bayesian-inference
  - phylogenetic-comparative-analysis
  - host-trait-analysis
  - probabilistic-network-modelling

study_systems:
  - mammalian-virus-sharing-networks
  - mammalian-host-virus-associations

regions:
  - global
# ==========================================================
# Study design
# ==========================================================

study_design:
  design_type: comparative-macroecology
  spatial_scope: global
  temporal_scope: "Virus records 1950–2019"
  observational_units:
    - mammal species
    - virus species
    - host-virus associations

population:
  focal_group: Mammalian hosts and associated viruses

datasets:
  - Enhanced Infectious Diseases Database (EID2)

sample_size:
  host_species: 725
  virus_species: 1785

# =======
# Resources and media
# =======

# Related code, data and media.
resource_links:
  code: ""
  data:
    zenodo: ""
    figshare: ""
    dryad: "https://datadryad.org/stash/dataset/doi:10.5061/dryad.p2ngf1vmg"
    EID_database: "https://eid2.liverpool.ac.uk"
  preprint: ""
  supplementary_material: ""

  news:
    university_story: "https://www.swansea.ac.uk/press-office/news-events/news/2020/01/new-research-shows-domestic-animals-link-virus-spread-among-humans-and-wildlife.php"
    medical_Xpress: "https://medicalxpress.com/news/2019-12-domestic-animals-link-virus-humans.html?src_id=alt"
    news_source_2: ""

  media:
    podcast: ""


# ==========================================================
# Related publications
# ==========================================================

related_publications:
  precursor:
    - 2018-wells-helminth-sharing
  extends:
    - 2023-clark-dynamic-generalized-additive-models

# ==========================================================
# Educational material
# ==========================================================

teaching_uses:
  - disease-ecology
  - macroecology
  - zoonotic-disease
  - network-analysis
  - one-health

discussion_questions:
  - Why do domestic mammals occupy central positions in global virus-sharing networks?
  - Why are RNA viruses more broadly shared among mammals than DNA viruses?
  - How does phylogenetic host specificity influence zoonotic emergence?



seo_description: >
  Global analysis of mammal-virus sharing demonstrating the central
  role of domestic mammals and contrasting transmission patterns of
  DNA and RNA viruses.

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



# ==========================================================
# Curation
# ==========================================================

curation:
  # Purpose: curation status. # Values: unreviewed, in-review, reviewed, revision-required
  status: reviewed
  reviewed_by: konstans-wells
  reviewed_on: 2026-07-18

# Purpose: Source provenance.
provenance:
  # Purpose: Original source type. # Values: publisher-pdf, publisher-html, repository, author, 
  source_type:
    - publisher-pdf
    - author
    
  # Purpose: Original source URL.
  source_url: "https://doi.org/10.1111/geb.13045"

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