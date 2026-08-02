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
id: 2018-clark-changing-interspecific-interactions

# Purpose: Official publication title.
title: "Unravelling changing interspecific interactions across environmental gradients using Markov random fields"

# Purpose: Short display title.
short_title: "Changing interspecific interactions with Markov random fields"

# Purpose: BAHE object class.
# Values: publication
object_type: publication

# Purpose: Publication category.
# Values: research-article, review, methods, perspective, commentary
publication_type: methods

# Purpose: Publication subtype.
# Values: empirical-study, systematic-review, scoping-review, topical-review, meta-analysis, simulation-study, conceptual-framework, protocol
publication_subtype: empirical-study

# Purpose: Publication workflow status.
# Values: draft, submitted, accepted, published, archived
status: published

# Purpose: Publication year. # Format: YYYY
year_published: 2018

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2018-06-01

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
- Nicholas J. Clark
- Konstans Wells
- Oscar Lindberg

# Purpose: Canonical BAHE author ids.
bahe_authors:
  - konstans-wells

# Purpose: Structured author metadata.
author_entities:
  # Purpose: Citation order.
  - position: 1
    # Purpose: Full author name.
    name: "Nicholas J. Clark"
    # Purpose: Canonical BAHE person id.
    person_id: nicholas-j-clark
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated canonical organisation objects.
    affiliation_ids:
      - university-of-queensland

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Konstans Wells"
    # Purpose: Canonical BAHE person id.
    person_id: konstans-wells
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - griffith-university

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Oscar Lindberg"
    # Purpose: Canonical BAHE person id.
    person_id: oscar-lindberg
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-turku

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  nicholas-j-clark:
    - conceptualization
    - methodology
    - software
    - formal-analysis
    - visualization
    - writing-original-draft
    - writing-review-editing

  konstans-wells:
    - conceptualization
    - methodology
    - interpretation
    - writing-review-editing

  oscar-lindberg:
    - methodology
    - software
    - interpretation
    - writing-review-editing

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "National Geographic Society"
    # Purpose: Canonical funder identifier.
    funder_id: national-geographic-society
    # Purpose: Grant identifier.
    grant_number: "9383-13"
    # Purpose: Official grant title.
    grant_title: ""

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Ecology"

# Purpose: Journal volume.
volume: "99"

# Purpose: Journal issue.
issue: "6"

# Purpose: Article pages or article number.
pages: "1277-1283"

# Purpose: Publisher.
publisher: "Wiley"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Clark, N. J., Wells, K., & Lindberg, O. (2018). Unravelling changing
  interspecific interactions across environmental gradients using Markov
  random fields. Ecology, 99(6), 1277-1283.
  https://doi.org/10.1002/ecy.2221

# Purpose: Short citation.
citation_short: >-
  Clark et al. (2018), Ecology, 99(6), 1277-1283.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1002/ecy.2221"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1002/ecy.2221"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1002/ecy.2221"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Inferring interactions between co-occurring species is key to identify processes governing community assembly. Incorporating interspecific interactions in predictive models is common in ecology, yet most methods do not adequately account for indirect interactions (where an interaction between two species is masked by their shared interactions with a third) and assume interactions do not vary along environmental gradients. Markov random fields (MRF) overcome these limitations by estimating interspecific interactions, while controlling for indirect interactions, from multispecies occurrence data. We illustrate the utility of MRFs for ecologists interested in interspecific interactions, and demonstrate how covariates can be included (a set of models known as Conditional Random Fields, CRF) to infer how interactions vary along environmental gradients. We apply CRFs to two data sets of presence–absence data. The first illustrates how blood parasite (Haemoproteus, Plasmodium, and nematode microfilaria spp.) co-infection probabilities covary with relative abundance of their avian hosts. The second shows that co-occurrences between mosquito larvae and predatory insects vary along water temperature gradients. Other applications are discussed, including the potential to identify replacement or shifting impacts of highly connected species along climate or land-use gradients. We provide tools for building CRFs and plotting/interpreting results as an R package.

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
    github: "https://github.com/nicholasjclark/MRFcov"
    MRFcov_R_package: "https://cran.r-project.org/web/packages/MRFcov/index.html"
  data:
    zenodo: "https://doi.org/10.5281/zenodo.1199673"
    figshare: ""
    dryad: ""
  preprint: ""
  supplementary_material: "https://onlinelibrary.wiley.com/doi/10.1002/ecy.2221/suppinfo"

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
image: "/images/images_publications/Changing-interspecific-interactions_Markov-random-fields_Clark-2018.jpg"

image_alt: >-
  Three ecological interaction networks showing predicted changes in
  associations among mosquito larvae and other marsh-dwelling organisms along
  an increasing water-temperature gradient. Red links indicate positive
  associations, blue links indicate negative associations, and thicker links
  represent stronger conditional interactions.

# Image caption  
image_caption: >-
  Conditional random field predictions of how interactions among mosquito
  larvae, aquatic predators and other marsh organisms change with increasing
  water temperature. Network edges represent conditional associations after
  accounting for the remaining species and environmental covariates. Positive
  interactions are shown in red, negative interactions in blue, and line
  thickness indicates interaction strength. The sequence demonstrates that
  both the direction and magnitude of ecological associations can vary across
  environmental gradients.

image_license: "All rights reserved"
image_credit: "Clark, Wells and Lindberg (2018)"
image_license_verified: false  


# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20180601

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
      Markov random fields can estimate direct conditional dependencies among species from multispecies presence–absence data while controlling for indirect associations mediated through other species.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-02
    text: >
      Conditional random fields extend Markov random fields by incorporating environmental covariates, allowing the direction and strength of interspecific associations to vary across environmental gradients.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-03
    text: >
      In avian blood-parasite communities, Plasmodium and microfilaria showed a positive conditional association, whereas the two focal Haemoproteus complexes showed a strong negative association.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Associations between both Haemoproteus complexes and Plasmodium became more positive as the relative abundance of Zosterops hosts increased, while the association between Haemoproteus zosteropis and microfilaria became more negative.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Interspecific parasite associations were stronger predictors of Haemoproteus zosteropis occurrence than host relative abundance, demonstrating that conditional random fields permit direct comparison between biotic and environmental effect sizes.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Culex modestus and Culex pipiens showed a strong positive association, consistent with shared larval habitat requirements.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Negative associations between predatory aquatic insects and mosquito larvae changed across water-temperature gradients, indicating that potential predator effects are environmentally context dependent.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      L1 regularisation and cross-validation enable conditional random fields to estimate sparse ecological interaction networks while reducing overfitting in datasets containing many species and covariates.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-09
    text: >
      Conditional random fields provide a complementary approach to joint species distribution models when the research objective is to identify interpretable, environmentally varying conditional associations among species.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-10
    text: >
      The MRFcov R package provides tools for fitting, visualising and interpreting Markov and conditional random fields for ecological presence–absence data.
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
  This methods paper adapts conditional random fields for ecological
  presence–absence data to estimate direct interspecific associations and how
  they change across environmental gradients. Applications to avian blood
  parasites and aquatic mosquito communities demonstrate environmentally
  varying co-infection and co-occurrence patterns.

# Knowledge-network summary.
knowledge_summary: >
  The study presents Markov random fields as graphical network models that
  distinguish direct conditional dependencies from associations generated
  indirectly through other species. By adding covariates, conditional random
  fields estimate how interaction coefficients change with environmental
  conditions and allow their effect sizes to be compared directly with abiotic
  predictors. Case studies show that parasite co-infections vary with host
  abundance and that mosquito–predator associations shift with water
  temperature and other habitat gradients. The accompanying MRFcov R package
  makes the framework accessible for applied ecological analyses.

# Scientific or societal significance.
impact_statement: >
  Conditional random fields provide an interpretable framework for detecting
  non-stationary species interactions, improving inference about community
  assembly, disease ecology and ecological responses to climate or land-use
  change.

# Non-technical summary.  
plain_language_summary: >-
  Species do not interact in the same way under all environmental conditions.
  This study shows how network models can separate direct associations from
  indirect ones and measure how those associations change along gradients such
  as host abundance or water temperature. Examples involving bird parasites
  and mosquito larvae demonstrate that interactions can strengthen, weaken or
  reverse as environmental conditions change.  

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - quantitative-ecology-modelling
  - ecological-interactions-system-dynamics
  - biodiversity-global-change
  - one-health-disease-ecology

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - markov-random-fields
  - conditional-random-fields
  - interspecific-interactions
  - conditional-dependence
  - species-co-occurrence
  - environmental-gradients
  - non-stationary-interactions
  - ecological-networks
  - community-assembly
  - joint-species-distribution-models
  - parasite-co-infection
  - host-relative-abundance
  - mosquito-predator-interactions
  - regularisation
  - graphical-network-models

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - markov-random-fields
  - conditional-random-fields
  - interspecific-interactions
  - environmental-gradients
  - non-stationary-interactions
  - ecological-networks

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - new-caledonian-avian-blood-parasite-community
  - uk-marsh-mosquito-community
  - multispecies-presence-absence-networks
  - aquatic-predator-prey-communities

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - haemoproteus-zosteropis-species-complex
  - haemoproteus-killangoi-species-complex
  - plasmodium
  - nematode-microfilaria
  - zosterops
  - culex-modestus
  - culex-pipiens
  - culiseta-annulata
  - anopheles-maculipennis
  - ilyocoris
  - palaemonetes

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - markov-random-fields
  - conditional-random-fields
  - logistic-regression
  - lasso-regularisation
  - ten-fold-cross-validation
  - bootstrap-resampling
  - presence-absence-modelling
  - graphical-network-analysis
  - partial-correlation-analysis
  - joint-species-distribution-modelling
  - model-sensitivity-assessment

# Input environmental database/ data sources
data_products:
  - clark-et-al-2016-avian-blood-parasite-data
  - golding-et-al-2015-mosquito-community-data

# Data produced or archived by this study  
research_datasets:
  - zenodo-1199673  

projects: []

# =======
# Typed graph relationships
# =======

# Purpose: Explicit knowledge graph relationships.
relationships:
  - predicate: authored_by
    object_type: person
    object_id: nicholas-j-clark

  - predicate: authored_by
    object_type: person
    object_id: konstans-wells

  - predicate: authored_by
    object_type: person
    object_id: oscar-lindberg

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-queensland

  - predicate: authored_by
    object_type: organisation
    object_id: griffith-university

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-turku

  - predicate: produces
    object_type: dataset
    object_id: zenodo-1199673

  - predicate: produces
    object_type: software
    object_id: mrfcov-r-package

  - predicate: addresses
    object_type: concept
    object_id: markov-random-fields

  - predicate: addresses
    object_type: concept
    object_id: conditional-random-fields

  - predicate: addresses
    object_type: concept
    object_id: interspecific-interactions

  - predicate: addresses
    object_type: concept
    object_id: environmental-gradients

  - predicate: addresses
    object_type: concept
    object_id: non-stationary-interactions

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - quantitative-ecology
  - community-ecology
  - ecological-network-analysis
  - species-distribution-modelling
  - disease-ecology
  - statistical-ecology
  - regularisation
  - environmental-gradient-analysis
  - reproducible-research

# Purpose: Suggested discussion questions.
discussion_questions:
  - "How do Markov random fields distinguish direct conditional associations from indirect species associations?"
  - "Why is it biologically unrealistic to assume that interspecific interactions remain constant across environmental gradients?"
  - "What advantages do conditional random fields offer over conventional joint species distribution models?"
  - "How does regularisation reduce overfitting when many species and environmental covariates are included?"
  - "How should conditional associations inferred from co-occurrence data be interpreted without experimental evidence of causal interaction?"
  - "Which ecological questions are best addressed by modelling interaction coefficients as functions of environmental covariates?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Changing Species Interactions with Markov Random Fields | Clark et al. 2018"

# Purpose: Search description.
seo_description: >-
  Methods study applying Markov and conditional random fields to detect direct
  species associations and quantify how ecological interactions change along
  host-abundance and environmental gradients.

# Purpose: Search keywords.
keywords:
  - Markov random fields
  - conditional random fields
  - interspecific interactions
  - ecological networks
  - species co-occurrence
  - environmental gradients
  - community assembly
  - joint species distribution models
  - non-stationary interactions
  - graphical network models
  - parasite co-infection
  - avian blood parasites
  - mosquito larvae
  - predator interactions
  - LASSO regularisation
  - presence–absence data
  - MRFcov
  - statistical ecology

# Purpose: Social sharing metadata.
social:
  title: "Changing Species Interactions with Markov Random Fields"
  description: >-
    Clark, Wells and Lindberg show how conditional random fields can detect
    direct ecological associations and reveal how interactions change across
    environmental gradients.
  image: "images/images_publications/Changing-interspecific-interactions_Markov-random-fields_Clark-2018.png"
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
  The article is subject to the publisher's copyright and reuse conditions.
  Reuse of article text or figures requires compliance with the licence and
  permissions stated by the publisher.

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
  source_url: "https://doi.org/10.1002/ecy.2221"

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
