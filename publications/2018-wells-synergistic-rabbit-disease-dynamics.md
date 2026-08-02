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
id: 2018-wells-synergistic-rabbit-disease-dynamics

# Purpose: Official publication title.
title: "Disentangling synergistic disease dynamics: Implications for the viral biocontrol of rabbits"

# Purpose: Short display title.
short_title: "Synergistic viral disease dynamics in rabbits"

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
year_published: 2018

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2018-09-01

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
- Damien A. Fordham
- Barry W. Brook
- Phillip Cassey
- Tarnya Cox
- Robert B. O’Hara
- Nina I. Schwensow

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
    name: "Damien A. Fordham"
    # Purpose: Canonical BAHE person id.
    person_id: damien-a-fordham
    # Purpose: ORCID identifier.
    orcid: "0000-0003-2137-5592"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-adelaide
      - university-of-copenhagen

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Barry W. Brook"
    # Purpose: Canonical BAHE person id.
    person_id: barry-w-brook
    # Purpose: ORCID identifier.
    orcid: "0000-0002-2491-1517"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-adelaide
      - university-of-tasmania

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "Phillip Cassey"
    # Purpose: Canonical BAHE person id.
    person_id: phillip-cassey
    # Purpose: ORCID identifier.
    orcid: "0000-0002-2626-0172"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-adelaide

  # Auhor position.
  - position: 5
    # Purpose: Full author name.
    name: "Tarnya Cox"
    # Purpose: Canonical BAHE person id.
    person_id: tarnya-cox
    # Purpose: ORCID identifier.
    orcid: "0000-0001-9581-9227"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - nsw-department-of-primary-industries

  # Auhor position.
  - position: 6
    # Purpose: Full author name.
    name: "Robert B. O’Hara"
    # Purpose: Canonical BAHE person id.
    person_id: robert-b-ohara
    # Purpose: ORCID identifier.
    orcid: "0000-0001-9737-3724"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - norwegian-university-of-science-and-technology

  # Auhor position.
  - position: 7
    # Purpose: Full author name.
    name: "Nina I. Schwensow"
    # Purpose: Canonical BAHE person id.
    person_id: nina-i-schwensow
    # Purpose: ORCID identifier.
    orcid: "0000-0003-3453-5823"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-adelaide
      - university-of-ulm

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  konstans-wells:
    - conceptualization
    - methodology
    - software
    - formal-analysis
    - visualization
    - writing-original-draft
    - writing-review-editing

  damien-a-fordham:
    - methodology
    - interpretation
    - writing-review-editing

  barry-w-brook:
    - methodology
    - interpretation
    - writing-review-editing

  phillip-cassey:
    - interpretation
    - writing-review-editing

  tarnya-cox:
    - resources
    - investigation
    - writing-review-editing

  robert-b-ohara:
    - methodology
    - interpretation
    - writing-review-editing

  nina-i-schwensow:
    - conceptualization
    - investigation
    - resources
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
    grant_number: "LP-1202002A"
    # Purpose: Official grant title.
    grant_title: "Linkage Project"

  - funder_name: "Australian Research Council"
    funder_id: australian-research-council
    grant_number: "DE120102821"
    grant_title: "Discovery Early Career Researcher Award"

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Journal of Animal Ecology"

# Purpose: Journal volume.
volume: "87"

# Purpose: Journal issue.
issue: "5"

# Purpose: Article pages or article number.
pages: "1418-1428"

# Purpose: Publisher.
publisher: "Wiley"

# Purpose: Open-access availability. # Values: true, false
open_access: true

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "CC BY 4.0"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Fordham, D. A., Brook, B. W., Cassey, P., Cox, T.,
  O’Hara, R. B., & Schwensow, N. I. (2018). Disentangling
  synergistic disease dynamics: Implications for the viral biocontrol
  of rabbits. Journal of Animal Ecology, 87(5), 1418-1428.
  https://doi.org/10.1111/1365-2656.12871

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2018), Journal of Animal Ecology, 87(5), 1418-1428.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1111/1365-2656.12871"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1111/1365-2656.12871"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1111/1365-2656.12871"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  1. European rabbits (Oryctolagus cuniculus) have been exposed to rabbit haemorrhagic disease virus (RHDV) and myxoma virus (MYXV) in their native and invasive ranges for decades. Yet, the long-term effects of these viruses on rabbit population dynamics remain poorly understood.
  2. In this context, we analysed 17 years of detailed capture–mark–recapture data (2000–2016) from Turretfield, South Australia, using a probabilistic state-space hierarchical modelling framework to estimate rabbit survival and epidemiological dynamics.
  3. While RHDV infection and disease-induced death were most prominent during annual epidemics in winter and spring, we found evidence for continuous infection of susceptible individuals with RHDV throughout the year. RHDV-susceptible rabbits had, on average, 25% lower monthly survival rates compared to immune individuals, while the average monthly force of infection in winter and spring was ~38%. These combined to result in an average infection-induced mortality rate of 69% in winter and spring.
  4. Individuals susceptible to MYXV and immune to RHDV had similar survival probabilities to those having survived infections from both viruses, whereas individuals susceptible to both RHDV and MYXV had higher survival probabilities than those susceptible to RHDV and immune to MYXV. This suggests that MYXV may reduce the future survival rates of individuals that endure initial MYXV infection.
  5. There was no evidence for long-term changes in disease-induced mortality and infection rates for either RHDV or MYXV.
  6. We conclude that continuous, year-round virus perpetuation (and perhaps heterogeneity in modes of transmission and infectious doses during and after epidemics) acts to reduce the efficiency of RHDV and MYXV as biocontrol agents of rabbits in their invasive range. However, if virulence can be maintained as relatively constant through time, RHDV and MYXV will likely continue realizing strong benefits as biocontrol agents.

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
    dryad: "https://doi.org/10.5061/dryad.3hd6sb6"
  preprint: ""
  supplementary_material: "https://besjournals.onlinelibrary.wiley.com/doi/10.1111/1365-2656.12871/suppinfo"

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
image: "/images/images_publications/Synergistic-rabbit-disease-dynamics_Wells-2018.jpg"

image_alt: >-
  State-space diagram showing how capture–mark–recapture observations,
  rabbit age and antibody status are used to infer transitions among maternal
  protection, susceptibility, immunity and death for rabbit haemorrhagic
  disease virus and myxoma virus.

# Image caption  
image_caption: >-
  State-space inference framework for estimating disease-specific survival
  and infection dynamics in European rabbits. Observed and unobserved capture
  histories are linked to age, maternal antibodies, susceptibility, immunity
  and death, allowing latent disease states and transitions to be estimated
  throughout each individual's life.

image_license: "CC BY 4.0"
image_credit: "Wells et al. (2018); illustration prepared by David Sargent"
image_license_verified: true  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20180901

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
      Rabbit haemorrhagic disease virus infection was strongly seasonal but susceptible rabbits were likely exposed throughout most of the year.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Rabbits susceptible to rabbit haemorrhagic disease virus had monthly survival probabilities approximately 25% lower than immune rabbits.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      The average monthly force of rabbit haemorrhagic disease virus infection in winter and spring was approximately 38%, producing an estimated infection-induced mortality rate of about 69%.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Individuals susceptible to both rabbit haemorrhagic disease virus and myxoma virus had higher survival than rabbits susceptible to rabbit haemorrhagic disease virus but immune to myxoma virus.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      The lower survival of rabbits that had survived myxoma virus infection suggests that myxomatosis can impose delayed demographic costs beyond the acute infection period.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-06
    text: >
      Forces of infection for rabbit haemorrhagic disease virus and myxoma virus were strongly correlated, indicating synchrony in the epidemiological dynamics of the two diseases.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      No long-term trend was detected in infection rates or disease-induced mortality for either rabbit haemorrhagic disease virus or myxoma virus during the 17-year study.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Continuous low-level transmission, heterogeneous transmission routes and variation in infectious dose may reduce the population-level efficacy of rabbit haemorrhagic disease virus as a biocontrol agent.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-09
    text: >
      Bayesian multistate capture–mark–recapture models can jointly estimate latent disease states, survival, seroconversion and force of infection when infection histories are only partially observed.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-10
    text: >
      Improving rabbit biocontrol requires attention to transmission timing, routes and infectious dose in addition to the virulence of released viral strains.
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
  This study used 17 years of capture–mark–recapture and serology data from
  2,200 European rabbits in South Australia to estimate the interacting
  demographic and epidemiological effects of rabbit haemorrhagic disease virus
  and myxoma virus using a Bayesian state-space model.

# Knowledge-network summary.
knowledge_summary: >
  The study demonstrates that rabbit viral biocontrol dynamics are shaped by
  persistent transmission, seasonal variation in force of infection and
  delayed effects of prior infection on survival. Rabbit haemorrhagic disease
  virus produced immediate survival costs, whereas myxoma virus appeared to
  reduce later survival among individuals that survived initial infection.
  Despite strong annual fluctuations, no long-term decline in infection rates
  or disease-induced mortality was detected.

# Scientific or societal significance.
impact_statement: >
  Viral biocontrol efficacy depends not only on pathogen virulence but also on
  year-round transmission, infectious dose and interactions between
  co-circulating diseases.

# Non-technical summary.  
plain_language_summary: >-
  Long-term monitoring showed that rabbit haemorrhagic disease virus and
  myxoma virus continue to affect wild rabbits in different ways. Rabbit
  haemorrhagic disease caused immediate mortality, while surviving myxoma
  infection appeared to carry longer-term survival costs. Both viruses
  continued circulating over many years, but low-level transmission outside
  major outbreaks may reduce their overall effectiveness as rabbit
  biocontrol agents.  

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
  - rabbit-haemorrhagic-disease-virus
  - myxoma-virus
  - viral-biocontrol
  - disease-synergy
  - force-of-infection
  - infection-induced-mortality
  - host-survival
  - co-circulating-pathogens
  - latent-disease-states
  - capture-mark-recapture
  - state-space-modelling
  - infectious-dose
  - transmission-heterogeneity
  - invasive-species-management
  - host-pathogen-coevolution

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - viral-biocontrol
  - rabbit-haemorrhagic-disease-virus
  - myxoma-virus
  - disease-synergy
  - force-of-infection
  - state-space-modelling

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - turretfield-rabbit-population
  - australian-invasive-rabbit-system
  - rabbit-viral-biocontrol-system
  - co-circulating-rabbit-viruses

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - oryctolagus-cuniculus
  - rabbit-haemorrhagic-disease-virus
  - myxoma-virus

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - capture-mark-recapture
  - longitudinal-field-monitoring
  - serological-testing
  - competition-elisa
  - enzyme-linked-immunosorbent-assay
  - bayesian-state-space-modelling
  - multistate-capture-mark-recapture
  - latent-markov-process
  - markov-chain-monte-carlo
  - ontogenetic-growth-modelling
  - force-of-infection-estimation
  - survival-analysis

# Input environmental database/ data sources
data_products:
  - turretfield-rabbit-monitoring-data
  - rabbit-serology-data

# Data produced or archived by this study  
research_datasets:
  - dryad-3hd6sb6

projects:
  - australian-rabbit-biocontrol

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
    object_id: damien-a-fordham

  - predicate: authored_by
    object_type: person
    object_id: barry-w-brook

  - predicate: authored_by
    object_type: person
    object_id: phillip-cassey

  - predicate: authored_by
    object_type: person
    object_id: tarnya-cox

  - predicate: authored_by
    object_type: person
    object_id: robert-b-ohara

  - predicate: authored_by
    object_type: person
    object_id: nina-i-schwensow

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-adelaide

  - predicate: authored_by
    object_type: organisation
    object_id: griffith-university

  - predicate: authored_by
    object_type: organisation
    object_id: nsw-department-of-primary-industries

  - predicate: produces
    object_type: dataset
    object_id: dryad-3hd6sb6

  - predicate: addresses
    object_type: concept
    object_id: viral-biocontrol

  - predicate: addresses
    object_type: concept
    object_id: disease-synergy

  - predicate: addresses
    object_type: concept
    object_id: force-of-infection

  - predicate: addresses
    object_type: concept
    object_id: transmission-heterogeneity

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - disease-ecology
  - wildlife-epidemiology
  - invasive-species-management
  - biological-control
  - capture-mark-recapture
  - bayesian-state-space-modelling
  - host-pathogen-coevolution
  - co-infection
  - population-ecology

# Purpose: Suggested discussion questions.
discussion_questions:
  - "How does year-round low-level transmission alter the effectiveness of a strongly seasonal viral biocontrol agent?"
  - "Why can survival comparisons between susceptible and immune hosts differ from direct estimates of infection-induced mortality?"
  - "What mechanisms could explain delayed survival costs after myxoma virus infection?"
  - "How can transmission dose and route influence population-level disease mortality?"
  - "What advantages do Bayesian state-space capture–mark–recapture models offer for partially observed disease histories?"
  - "How should rabbit biocontrol programmes balance viral virulence with transmission ecology?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Synergistic Rabbit Disease Dynamics and Viral Biocontrol | Wells et al. 2018"

# Purpose: Search description.
seo_description: >-
  Seventeen-year study of rabbit haemorrhagic disease virus and myxoma virus
  showing persistent transmission, contrasting survival effects and
  implications for viral biocontrol of invasive rabbits.

# Purpose: Search keywords.
keywords:
  - European rabbit
  - rabbit haemorrhagic disease virus
  - myxoma virus
  - viral biocontrol
  - disease synergy
  - force of infection
  - infection-induced mortality
  - capture–mark–recapture
  - Bayesian state-space model
  - wildlife disease
  - invasive species management
  - rabbit epidemiology
  - transmission heterogeneity
  - infectious dose
  - host survival
  - co-circulating viruses
  - Australia

# Purpose: Social sharing metadata.
social:
  title: "Synergistic Rabbit Disease Dynamics and Viral Biocontrol"
  description: >-
    Wells and colleagues show how persistent transmission and contrasting
    effects of RHDV and myxoma virus shape long-term rabbit biocontrol.
  image: "images/images_publications/Synergistic-rabbit-disease-dynamics_Wells-2018.png"
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
  The article is published under the Creative Commons Attribution 4.0
  licence. Reuse must preserve attribution to the authors, article title,
  journal citation and DOI.

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
  source_url: "https://doi.org/10.1111/1365-2656.12871"

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
