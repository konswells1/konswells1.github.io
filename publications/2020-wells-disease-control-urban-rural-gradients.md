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
id: 2020-wells-disease-control-urban-rural-gradients

# Purpose: Official publication title.
title: "Disease control across urban–rural gradients"

# Purpose: Short display title.
short_title: "Disease control across urban–rural gradients"

# Purpose: BAHE object class.
# Values: publication
object_type: publication

# Purpose: Publication category.
# Values: research-article, review, methods, perspective, commentary
publication_type: research-article

# Purpose: Publication subtype.
# Values: empirical-study, systematic-review, scoping-review, topical-review, meta-analysis, simulation-study, conceptual-framework, protocol
publication_subtype: simulation-study

# Purpose: Publication workflow status.
# Values: draft, submitted, accepted, published, archived
status: published

# Purpose: Publication year. # Format: YYYY
year_published: 2020

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2020-12-09

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
- Miguel Lurgi
- Brendan Collins
- Biagio Lucini
- Rowland R. Kao
- Alun L. Lloyd
- Simon D. W. Frost
- Mike B. Gravenor

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
      - swansea-university

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Miguel Lurgi"
    # Purpose: Canonical BAHE person id.
    person_id: miguel-lurgi
    # Purpose: ORCID identifier.
    orcid: "0000-0001-9891-895X"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - swansea-university

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Brendan Collins"
    # Purpose: Canonical BAHE person id.
    person_id: brendan-collins
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-liverpool
      - welsh-government

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "Biagio Lucini"
    # Purpose: Canonical BAHE person id.
    person_id: biagio-lucini
    # Purpose: ORCID identifier.
    orcid: "0000-0001-8974-8266"
    # Purpose: Affiliated organisation ids.    
    affiliation_ids:
      - swansea-university

  # Auhor position.
  - position: 5
    # Purpose: Full author name.
    name: "Rowland R. Kao"
    # Purpose: Canonical BAHE person id.
    person_id: rowland-r-kao
    # Purpose: ORCID identifier.
    orcid: "0000-0003-0919-6401"
    # Purpose: Affiliated organisation ids.    
    affiliation_ids:
      - university-of-edinburgh

  # Auhor position.
  - position: 6
    # Purpose: Full author name.
    name: "Alun L. Lloyd"
    # Purpose: Canonical BAHE person id.
    person_id: alun-l-lloyd
    # Purpose: ORCID identifier.
    orcid: "0000-0002-6389-6321"
    # Purpose: Affiliated organisation ids.    
    affiliation_ids:
      - north-carolina-state-university

  # Auhor position.
  - position: 7
    # Purpose: Full author name.
    name: "Simon D. W. Frost"
    # Purpose: Canonical BAHE person id.
    person_id: simon-d-w-frost
    # Purpose: ORCID identifier.
    orcid: "0000-0002-5207-9879"
    # Purpose: Affiliated organisation ids.    
    affiliation_ids:
      - microsoft-research
      - london-school-of-hygiene-and-tropical-medicine

  # Auhor position.
  - position: 8
    # Purpose: Full author name.
    name: "Mike B. Gravenor"
    # Purpose: Canonical BAHE person id.
    person_id: mike-b-gravenor
    # Purpose: ORCID identifier.
    orcid: "0000-0003-0710-0947"
    # Purpose: Affiliated organisation ids.    
    affiliation_ids:
      - swansea-university

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

  miguel-lurgi:
    - conceptualization
    - methodology
    - software
    - writing-review-editing

  brendan-collins:
    - conceptualization
    - interpretation
    - writing-review-editing

  biagio-lucini:  
    - methodology
    - interpretation
    - writing-review-editing

  rowland-r-kao:
    - conceptualization
    - methodology
    - interpretation
    - writing-review-editing

  alun-l-lloyd:
    - methodology
    - interpretation
    - writing-review-editing

  simon-d-w-frost:
    - methodology
    - interpretation
    - writing-review-editing

  mike-b-gravenor:
    - conceptualization
    - methodology
    - supervision
    - interpretation
    - writing-review-editing

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: ""
    # Purpose: Canonical funder identifier.
    funder_id: ""
    # Purpose: Grant identifier.
    grant_number: ""
    # Purpose: Official grant title.
    grant_title: ""

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Journal of the Royal Society Interface"

# Purpose: Journal volume.
volume: "17"

# Purpose: Journal issue.
issue: ""

# Purpose: Article pages or article number.
pages: "20200775"

# Purpose: Publisher.
publisher: "The Royal Society"

# Purpose: Open-access availability. # Values: true, false
open_access: true

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "CC BY 4.0"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Lurgi, M., Collins, B., Lucini, B., Kao, R. R., Lloyd, A. L.,
  Frost, S. D. W., & Gravenor, M. B. (2020). Disease control across
  urban–rural gradients. Journal of the Royal Society Interface, 17,
  20200775. https://doi.org/10.1098/rsif.2020.0775

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2020), Journal of the Royal Society Interface, 17, 20200775.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1098/rsif.2020.0775"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1098/rsif.2020.0775"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1098/rsif.2020.0775"
pdf: "https://royalsocietypublishing.org/doi/pdf/10.1098/rsif.2020.0775"

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Controlling the regional re-emergence of severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2) after its initial spread in ever-changing personal contact networks and disease landscapes is a challenging task. In a landscape context, contact opportunities within and between populations are changing rapidly as lockdown measures are relaxed and a number of social activities re-activated. Using an individual-based metapopulation model, we explored the efficacy of different control strategies across an urban–rural gradient in Wales, UK. Our model shows that isolation of symptomatic cases or regional lockdowns in response to local outbreaks have limited efficacy unless the overall transmission rate is kept persistently low. Additional isolation of non-symptomatic infected individuals, who may be detected by effective test-and-trace strategies, is pivotal to reducing the overall epidemic size over a wider range of transmission scenarios. We define an ‘urban–rural gradient in epidemic size’ as a correlation between regional epidemic size and connectivity within the region, with more highly connected urban populations experiencing relatively larger outbreaks. For interventions focused on regional lockdowns, the strength of such gradients in epidemic size increased with higher travel frequencies, indicating a reduced efficacy of the control measure in the urban regions under these conditions. When both non-symptomatic and symptomatic individuals are isolated or regional lockdown strategies are enforced, we further found the strongest urban–rural epidemic gradients at high transmission rates. This effect was reversed for strategies targeted at symptomatic individuals only. Our results emphasize the importance of test-and-trace strategies and maintaining low transmission rates for efficiently controlling SARS-CoV-2 spread, both at landscape scale and in urban areas.

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
    figshare: "https://doi.org/10.6084/m9.figshare.c.5227967"
    dryad: ""
  preprint: ""
  supplementary_material: "https://doi.org/10.6084/m9.figshare.c.5227967"

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
image: "/images/images_publications/Disease-control-urban-rural-gradients_Wells-2020.png"

image_alt: >-
  Conceptual diagram of SARS-CoV-2 transmission and control in an
  urban–rural metapopulation. The figure combines an individual-level
  susceptible–exposed–asymptomatic–infectious–removed model, movement among
  connected rural and urban populations, and three interventions: tracing all
  infected individuals, isolating symptomatic cases only, and regional
  lockdowns.

# Image caption  
image_caption: >-
  Conceptual framework for SARS-CoV-2 spread and control across an urban–rural
  metapopulation. Epidemiological transitions are represented with a
  stochastic susceptible–exposed–asymptomatic–infectious–removed model.
  Connected rural and urban populations exchange commuter travellers, creating
  changing source–sink dynamics as outbreaks alter local pools of susceptible
  individuals. The lower panels compare isolation of all infected people,
  isolation of symptomatic cases only, and regional lockdowns that reduce
  local transmission and travel.

image_license: "CC BY 4.0"
image_credit: "Wells et al. (2020)"
image_license_verified: true  


# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20201209

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
      Isolation of symptomatic SARS-CoV-2 cases alone has limited capacity to reduce total epidemic size unless the overall transmission rate remains persistently low.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Regional lockdowns triggered by local outbreaks have limited long-term efficacy when transmission rates are high and are most effective when introduced at low outbreak thresholds.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Detecting and isolating non-symptomatic infected individuals through effective testing and contact tracing substantially reduces epidemic size across a wider range of transmission conditions than symptom-based isolation.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      In the simulations, isolating at least 47% of all infected individuals reduced epidemic size to less than 5% of the corresponding uncontrolled scenario.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Urban–rural gradients in epidemic size arise because highly connected urban populations can experience larger outbreaks than less connected rural populations.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Higher commuter travel frequencies strengthen urban–rural differences in epidemic size under regional lockdown strategies, indicating reduced lockdown efficacy in highly connected urban populations.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      High transmission rates produce the strongest urban–rural gradients when all infected individuals are isolated or regional lockdowns are used, whereas symptom-only isolation produces the opposite pattern.
    knowledge_type: simulation-based-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Maintaining low background transmission is more important for limiting total epidemic size than repeatedly adjusting short-term regional control measures in response to observed case numbers.
    knowledge_type: policy-implication
    attributed_to: source-publication

  - id: statement-09
    text: >
      Strategic individual-based metapopulation models can reveal how intervention efficacy depends on interactions among transmission, mobility, population connectivity and spatial variation in susceptibility.
    knowledge_type: methodological-proposition
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
  This simulation study used an individual-based metapopulation model of
  SARS-CoV-2 transmission across 422 communities in an urban–rural landscape
  in south-west Wales. It compared isolation of all infected individuals,
  isolation of symptomatic cases only, and regional lockdowns across 40,000
  epidemiological and intervention scenarios.

# Knowledge-network summary.
knowledge_summary: >
  The study links individual infection dynamics with population connectivity,
  commuting and spatial variation in urban and rural communities. It shows
  that intervention efficacy depends strongly on the background transmission
  rate and on whether non-symptomatic infections are detected. Symptom-based
  isolation and reactive regional lockdowns usually provide limited control,
  whereas tracing and isolating infected individuals across exposed,
  asymptomatic and symptomatic states can greatly suppress epidemic size.
  The analysis also introduces an urban–rural epidemic gradient to quantify
  how regional outbreak size changes with population connectivity.

# Scientific or societal significance.
impact_statement: >
  Effective test-and-trace systems that identify non-symptomatic infections,
  combined with persistently low transmission, are more reliable for
  landscape-scale epidemic control than symptom-only isolation or reactive
  regional lockdowns.

# Non-technical summary.  
plain_language_summary: >-
  Computer simulations of COVID-19 spread across urban and rural communities
  in south-west Wales showed that isolating only people with symptoms or
  locking down areas after outbreaks had begun often failed to prevent large
  epidemics. Control improved substantially when testing and contact tracing
  also found infected people without symptoms. The results show that keeping
  transmission consistently low is especially important in highly connected
  urban areas.  

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - one-health-disease-ecology
  - quantitative-ecology-modelling
  - ecological-interactions-system-dynamics
  - nature-society-sustainable-futures

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - infectious-disease-control
  - sars-cov-2
  - covid-19
  - urban-rural-gradients
  - metapopulation-dynamics
  - source-sink-dynamics
  - epidemic-size
  - test-and-trace
  - asymptomatic-transmission
  - symptomatic-isolation
  - regional-lockdown
  - transmission-rate
  - commuter-mobility
  - population-connectivity
  - spatial-epidemiology
  - non-pharmaceutical-interventions

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - infectious-disease-control
  - urban-rural-gradients
  - metapopulation-dynamics
  - test-and-trace
  - asymptomatic-transmission
  - regional-lockdown

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - human-urban-rural-metapopulation
  - south-west-wales
  - sars-cov-2-transmission-system
  - connected-human-communities

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - homo-sapiens
  - severe-acute-respiratory-syndrome-coronavirus-2

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - individual-based-modelling
  - stochastic-simulation
  - metapopulation-modelling
  - seair-compartmental-modelling
  - gravity-model
  - latin-hypercube-sampling
  - generalised-linear-modelling
  - boosted-regression-trees
  - sensitivity-analysis
  - scenario-analysis
  - spearman-rank-correlation

# Input environmental database/ data sources
data_products:
  - uk-2011-census
  - lower-layer-super-output-areas

# Data produced or archived by this study  
research_datasets:
  - figshare-5227967  

projects: []

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
    object_id: miguel-lurgi

  - predicate: authored_by
    object_type: person
    object_id: brendan-collins

  - predicate: authored_by
    object_type: person
    object_id: biagio-lucini

  - predicate: authored_by
    object_type: person
    object_id: rowland-r-kao

  - predicate: authored_by
    object_type: person
    object_id: alun-l-lloyd

  - predicate: authored_by
    object_type: person
    object_id: simon-d-w-frost

  - predicate: authored_by
    object_type: person
    object_id: mike-b-gravenor

  - predicate: authored_by
    object_type: organisation
    object_id: swansea-university

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-liverpool

  - predicate: authored_by
    object_type: organisation
    object_id: welsh-government

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-edinburgh

  - predicate: authored_by
    object_type: organisation
    object_id: north-carolina-state-university

  - predicate: authored_by
    object_type: organisation
    object_id: microsoft-research

  - predicate: authored_by
    object_type: organisation
    object_id: london-school-of-hygiene-and-tropical-medicine

  - predicate: produces
    object_type: dataset
    object_id: figshare-5227967

  - predicate: addresses
    object_type: concept
    object_id: infectious-disease-control

  - predicate: addresses
    object_type: concept
    object_id: urban-rural-gradients

  - predicate: addresses
    object_type: concept
    object_id: metapopulation-dynamics

  - predicate: addresses
    object_type: concept
    object_id: test-and-trace

  - predicate: addresses
    object_type: concept
    object_id: regional-lockdown

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - infectious-disease-epidemiology
  - mathematical-epidemiology
  - spatial-epidemiology
  - metapopulation-dynamics
  - individual-based-modelling
  - public-health-policy
  - non-pharmaceutical-interventions
  - urban-rural-health
  - sensitivity-analysis

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why does isolation of symptomatic cases alone provide limited control when asymptomatic transmission is common?"
  - "Under which combinations of transmission rate and outbreak threshold can regional lockdowns substantially reduce epidemic size?"
  - "How does population connectivity generate an urban–rural gradient in epidemic size?"
  - "Why might the same intervention differ in efficacy between highly connected urban populations and less connected rural populations?"
  - "What are the strengths and limitations of strategic simulation models compared with models designed to forecast a specific outbreak?"
  - "How should policymakers balance continuous transmission reduction against reactive local interventions?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Disease Control Across Urban–Rural Gradients | Wells et al. 2020"

# Purpose: Search description.
seo_description: >-
  Individual-based metapopulation study showing how SARS-CoV-2 control through
  test-and-trace, symptom isolation and regional lockdowns varies across
  connected urban and rural populations.

# Purpose: Search keywords.
keywords:
  - SARS-CoV-2
  - COVID-19
  - disease control
  - urban–rural gradient
  - metapopulation dynamics
  - source–sink dynamics
  - test and trace
  - asymptomatic transmission
  - symptomatic isolation
  - regional lockdown
  - transmission rate
  - commuter travel
  - population connectivity
  - epidemic size
  - individual-based model
  - stochastic simulation
  - spatial epidemiology
  - non-pharmaceutical interventions
  - Wales

# Purpose: Social sharing metadata.
social:
  title: "Disease Control Across Urban–Rural Gradients"
  description: >-
    Wells and colleagues model how test-and-trace, symptom isolation and
    regional lockdowns shape SARS-CoV-2 epidemic size across connected urban
    and rural populations.
  image: "images/images_publications/Disease-control-urban-rural-gradients_Wells-2020.png"
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
  source_url: "https://doi.org/10.1098/rsif.2020.0775"

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
