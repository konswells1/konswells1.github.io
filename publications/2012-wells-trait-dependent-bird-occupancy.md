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
id: 2012-wells-trait-dependent-bird-occupancy

# Purpose: Official publication title.
title: "Trait-dependent occupancy dynamics of birds in temperate forest landscapes: fine-scale observations in a hierarchical multi-species framework"

# Purpose: Short display title.
short_title: "Trait-dependent bird occupancy in temperate forests"

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
year_published: 2012

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2012-11-01

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
- Robert B. O’Hara
- Stefan M. Böhm
- Sonja Gockel
- Andreas Hemp
- Swen C. Renner
- Simone Pfeiffer
- Katrin Böhning-Gaese
- Elisabeth K. V. Kalko

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
      - university-of-ulm
      - biodiversity-and-climate-research-centre

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Robert B. O’Hara"
    # Purpose: Canonical BAHE person id.
    person_id: robert-b-ohara
    # Purpose: ORCID identifier.
    orcid: "0000-0001-9737-3724"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - biodiversity-and-climate-research-centre

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Stefan M. Böhm"
    # Purpose: Canonical BAHE person id.
    person_id: stefan-m-bohm
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-ulm

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "Sonja Gockel"
    # Purpose: Canonical BAHE person id.
    person_id: sonja-gockel
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - friedrich-schiller-university-jena

  # Auhor position.
  - position: 5
    # Purpose: Full author name.
    name: "Andreas Hemp"
    # Purpose: Canonical BAHE person id.
    person_id: andreas-hemp
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-potsdam

  # Auhor position.
  - position: 6
    # Purpose: Full author name.
    name: "Swen C. Renner"
    # Purpose: Canonical BAHE person id.
    person_id: swen-c-renner
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-ulm

  # Auhor position.
  - position: 7
    # Purpose: Full author name.
    name: "Simone Pfeiffer"
    # Purpose: Canonical BAHE person id.
    person_id: simone-pfeiffer
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-potsdam

  # Auhor position.
  - position: 8
    # Purpose: Full author name.
    name: "Katrin Böhning-Gaese"
    # Purpose: Canonical BAHE person id.
    person_id: katrin-bohning-gaese
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - biodiversity-and-climate-research-centre

  # Auhor position.
  - position: 9
    # Purpose: Full author name.
    name: "Elisabeth K. V. Kalko"
    # Purpose: Canonical BAHE person id.
    person_id: elisabeth-k-v-kalko
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-ulm
      - smithsonian-tropical-research-institute

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  konstans-wells:
    - conceptualization
    - methodology
    - formal-analysis
    - visualization
    - writing-original-draft
    - writing-review-editing

  robert-b-ohara:
    - methodology
    - formal-analysis
    - interpretation
    - writing-review-editing

  stefan-m-bohm:
    - investigation
    - data-curation
    - writing-review-editing

  sonja-gockel:
    - investigation
    - resources
    - writing-review-editing

  andreas-hemp:
    - investigation
    - resources
    - writing-review-editing

  swen-c-renner:
    - investigation
    - data-curation
    - writing-review-editing

  simone-pfeiffer:
    - investigation
    - resources
    - writing-review-editing

  katrin-bohning-gaese:
    - conceptualization
    - supervision
    - interpretation
    - writing-review-editing

  elisabeth-k-v-kalko:
    - conceptualization
    - supervision
    - funding-acquisition
    - interpretation
    - writing-review-editing

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "German Research Foundation"
    # Purpose: Canonical funder identifier.
    funder_id: german-research-foundation
    # Purpose: Grant identifier.
    grant_number: "KA 1241/15-1"
    # Purpose: Official grant title.
    grant_title: "Priority Programme 1374 Infrastructure-Biodiversity-Exploratories"

  - funder_name: "Landesoffensive zur Entwicklung wissenschaftlich-ökonomischer Exzellenz"
    funder_id: loewe-hesse
    grant_number: ""
    grant_title: "Biodiversity and Climate Research Centre"

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Animal Conservation"

# Purpose: Journal volume.
volume: "15"

# Purpose: Journal issue.
issue: "6"

# Purpose: Article pages or article number.
pages: "626-637"

# Purpose: Publisher.
publisher: "Wiley"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., O’Hara, R. B., Böhm, S. M., Gockel, S., Hemp, A.,
  Renner, S. C., Pfeiffer, S., Böhning-Gaese, K., & Kalko, E. K. V.
  (2012). Trait-dependent occupancy dynamics of birds in temperate
  forest landscapes: fine-scale observations in a hierarchical
  multi-species framework. Animal Conservation, 15(6), 626-637.
  https://doi.org/10.1111/j.1469-1795.2012.00560.x

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2012), Animal Conservation, 15(6), 626-637.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1111/j.1469-1795.2012.00560.x"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1111/j.1469-1795.2012.00560.x"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1111/j.1469-1795.2012.00560.x"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Silvicultural practices lead to changes in forest composition and structure and may impact species diversity from the overall regional species pool to stand-level species occurrence. We explored to what extent fine-scale occupancy patterns in differently managed forest stands are driven by environment and ecological traits in three regions in Germany using a multi-species hierarchical model. We tested for the possible impact of environmental variables and ecological traits on occupancy dynamics in a joint modelling exercise while taking possible variation in coefficient estimates over years and plots into account. Bird species richness differed across regions and years, and trends in species richness across years were different in the three regions. On the species level, forest management affected occupancy of species in all regions, but only 3–5% of the total assemblage-level variation in occurrence probability was explained by either forest type and successional stage and <1% by forest edge. On the assemblage level, bird occurrence decreased with body mass in all regions. Species with smaller breeding ranges had lower occurrence probabilities in one region, while later spring arrival decreased occurrence probabilities in the two other regions. Spatial variation in the effect size of trait covariates such as species phylogeny and breeding strata showed that variation in patch occupancy due to fine-scale differences in forest management is, to some extent, predictable from ecological traits. Our results show that environmental factors and ecological traits jointly predict variation in bird occupancy patterns and their response to forest management. Observations at the fine scale of forest stands, at which conservation efforts can be arranged along with forest management practices in heterogeneous environments, have been shown to provide meaningful insights despite the difficulties involved in monitoring mobile organisms such as birds at the plot level.

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
    dryad: ""
  preprint: ""
  supplementary_material: "https://doi.org/10.1111/j.1469-1795.2012.00560.x"

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
image: ""

image_alt: >-
  xx

# Image caption  
image_caption: >-
  xx

image_license: "All rights reserved"
image_credit: "Wells et al. (2012)"
image_license_verified: false  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20121101

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
      Bird species richness and year-to-year changes in regional prevalence differed among the Swabian Alb, Hainich and Schorfheide forest regions.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Forest type and forest successional stage each explained approximately 3–5% of assemblage-level variation in bird occurrence probability, while distance to forest edge explained less than 1%.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Species-level responses to forest type and stand development were evident even though forest management variables explained a relatively small share of total assemblage-level variation.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Ecological traits explained between approximately 16% and 83% of variation in assemblage-level bird occurrence probability across the three regions.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Bird occurrence probability declined by approximately 13% for every 100 g increase in body mass across all three regions.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Species with more northerly southern breeding-range limits had lower occurrence probabilities, especially in the Swabian Alb.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Later spring arrival was associated with lower occurrence probability, with the strongest effect in the Hainich region.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Effects of breeding strata, foraging strata, diet and phylogenetic order varied among years and forest plots, showing that trait–occupancy relationships are context dependent.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-09
    text: >
      Traits linked to local resource use and vertical forest structure were more informative for fine-scale occupancy variation than broad life-history traits alone.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-10
    text: >
      Hierarchical multi-species occupancy models can jointly estimate detectability, species richness, environmental responses and trait-dependent assemblage patterns while borrowing information across species.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-11
    text: >
      Conservation strategies optimised for one forest region may not transfer directly to another because ecological trait effects and occupancy responses vary regionally.
    knowledge_type: recommendation
    attributed_to: source-publication

  - id: statement-12
    text: >
      Maintaining tree-species diversity, structural heterogeneity, old trees and dead wood within managed stands can help buffer adverse effects of silviculture on bird communities.
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
  This study analysed repeated point-count data from 150 forest plots across
  three German regions between 2008 and 2010. Hierarchical multi-species
  occupancy models linked detection, forest management, stand structure and
  eight ecological traits to species- and assemblage-level occurrence.

# Knowledge-network summary.
knowledge_summary: >
  The study integrates fine-scale environmental variation with trait-based
  community ecology in a single occupancy framework. Although forest type and
  stand development explained modest proportions of total assemblage
  variation, species-specific responses were substantial. Body mass,
  breeding-range limits and spring arrival structured regional occupancy,
  while breeding and foraging strata varied more strongly across plots and
  years, linking local forest structure to functional community responses.

# Scientific or societal significance.
impact_statement: >
  Forest-bird conservation benefits from fine-scale, trait-informed management
  because species responses to silviculture differ among regions, years and
  stand conditions.

# Non-technical summary.  
plain_language_summary: >-
  Bird communities differed among three managed forest regions in Germany.
  Larger birds and late-arriving migrants were generally less likely to occur,
  while species using different forest layers responded differently among
  stands and years. Local forest management had modest overall effects but
  mattered strongly for particular species, supporting region-specific
  conservation planning.  

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - biodiversity-global-change
  - quantitative-ecology-modelling
  - ecological-interactions-system-dynamics
  - conservation-ecology

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - multi-species-occupancy
  - trait-dependent-occupancy
  - forest-management
  - silviculture
  - bird-community-dynamics
  - functional-traits
  - imperfect-detection
  - forest-stand-structure
  - successional-stage
  - breeding-range-limits
  - migration-arrival-time
  - body-mass
  - breeding-strata
  - foraging-strata
  - regional-context-dependence

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - multi-species-occupancy
  - trait-dependent-occupancy
  - forest-management
  - functional-traits
  - imperfect-detection
  - regional-context-dependence

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - german-biodiversity-exploratories
  - swabian-alb-forest-landscape
  - hainich-dun-forest-landscape
  - schorfheide-chorin-forest-landscape
  - temperate-forest-bird-community

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - aves
  - fringilla-coelebs
  - turdus-merula
  - erithacus-rubecula
  - troglodytes-troglodytes
  - parus-major
  - regulus-ignicapilla
  - regulus-regulus
  - periparus-ater
  - lophophanes-cristatus
  - sitta-europaea
  - phylloscopus-collybita
  - sylvia-borin
  - ficedula-hypoleuca

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - repeated-point-count-surveys
  - multi-species-occupancy-modelling
  - hierarchical-bayesian-modelling
  - detection-probability-modelling
  - data-augmentation
  - trait-based-community-analysis
  - variance-partitioning
  - markov-chain-monte-carlo
  - posterior-richness-estimation
  - spatially-varying-coefficients
  - temporally-varying-coefficients
  - sensitivity-analysis

# Input environmental database/ data sources
data_products:
  - biodiversity-exploratories-forest-plot-data
  - european-bird-census-council
  - german-forest-bird-trait-data
  - aerial-photography-forest-edge-data

# Data produced or archived by this study  
research_datasets: []

projects:
  - biodiversity-exploratories

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
    object_id: robert-b-ohara

  - predicate: authored_by
    object_type: person
    object_id: stefan-m-bohm

  - predicate: authored_by
    object_type: person
    object_id: sonja-gockel

  - predicate: authored_by
    object_type: person
    object_id: andreas-hemp

  - predicate: authored_by
    object_type: person
    object_id: swen-c-renner

  - predicate: authored_by
    object_type: person
    object_id: simone-pfeiffer

  - predicate: authored_by
    object_type: person
    object_id: katrin-bohning-gaese

  - predicate: authored_by
    object_type: person
    object_id: elisabeth-k-v-kalko

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-ulm

  - predicate: authored_by
    object_type: organisation
    object_id: biodiversity-and-climate-research-centre

  - predicate: authored_by
    object_type: organisation
    object_id: friedrich-schiller-university-jena

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-potsdam

  - predicate: authored_by
    object_type: organisation
    object_id: smithsonian-tropical-research-institute

  - predicate: contributes_to
    object_type: project
    object_id: biodiversity-exploratories

  - predicate: addresses
    object_type: concept
    object_id: multi-species-occupancy

  - predicate: addresses
    object_type: concept
    object_id: trait-dependent-occupancy

  - predicate: addresses
    object_type: concept
    object_id: forest-management

  - predicate: addresses
    object_type: concept
    object_id: regional-context-dependence

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - conservation-biology
  - forest-ecology
  - avian-ecology
  - occupancy-modelling
  - hierarchical-bayesian-modelling
  - functional-trait-ecology
  - community-ecology
  - biodiversity-monitoring
  - silviculture

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why can forest management have strong species-specific effects while explaining little total assemblage-level variation?"
  - "How does a hierarchical multi-species model improve estimates for rarely detected species?"
  - "Why might body mass structure regional bird assemblages without strongly predicting responses to forest management?"
  - "How do breeding and foraging strata connect bird traits with fine-scale forest structure?"
  - "Why should conservation recommendations differ among the Swabian Alb, Hainich and Schorfheide regions?"
  - "What are the advantages and limitations of using 100 × 100 m plots for monitoring mobile bird species?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Trait-Dependent Bird Occupancy in Temperate Forests | Wells et al. 2012"

# Purpose: Search description.
seo_description: >-
  Hierarchical multi-species study showing how forest management, detection
  uncertainty and ecological traits shape fine-scale bird occupancy across
  three temperate forest regions in Germany.

# Purpose: Search keywords.
keywords:
  - bird occupancy
  - temperate forest
  - forest management
  - silviculture
  - multi-species occupancy model
  - hierarchical Bayesian model
  - functional traits
  - body mass
  - migration arrival
  - breeding range
  - breeding strata
  - foraging strata
  - imperfect detection
  - Biodiversity Exploratories
  - Germany
  - forest bird conservation
  - stand-level ecology
  - species richness

# Purpose: Social sharing metadata.
social:
  title: "Trait-Dependent Bird Occupancy in Temperate Forests"
  description: >-
    Wells and colleagues show how forest management and ecological traits
    jointly shape bird occupancy across German temperate forest landscapes.
  image: "images/images_publications/Trait-dependent-bird-occupancy_Wells-2012.png"
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
  source_url: "https://doi.org/10.1111/j.1469-1795.2012.00560.x"

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
