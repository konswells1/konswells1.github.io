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
id: 2011-wells-forest-attributes-bird-assemblages

# Purpose: Official publication title.
title: "Local and landscape-scale forest attributes differ in their impact on bird assemblages across years in forest production landscapes"

# Purpose: Short display title.
short_title: "Forest attributes and annual bird assemblage dynamics"

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
year_published: 2011

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2011-03-01

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
- Stefan M. Böhm
- Steffen Boch
- Markus Fischer
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
    name: "Stefan M. Böhm"
    # Purpose: Canonical BAHE person id.
    person_id: stefan-m-bohm
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-ulm

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Steffen Boch"
    # Purpose: Canonical BAHE person id.
    person_id: steffen-boch
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-bern

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "Markus Fischer"
    # Purpose: Canonical BAHE person id.
    person_id: markus-fischer
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-bern

  # Auhor position.
  - position: 5
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

  stefan-m-bohm:
    - investigation
    - data-curation
    - field-surveys
    - writing-review-editing

  steffen-boch:
    - investigation
    - vegetation-data
    - writing-review-editing

  markus-fischer:
    - conceptualization
    - resources
    - project-administration
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
    grant_number: ""
    # Purpose: Official grant title.
    grant_title: "Priority Programme 1374 Exploratories for large-scale and long-term functional biodiversity research"

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Basic and Applied Ecology"

# Purpose: Journal volume.
volume: "12"

# Purpose: Journal issue.
issue: "2"

# Purpose: Article pages or article number.
pages: "97-106"

# Purpose: Publisher.
publisher: "Elsevier"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Böhm, S. M., Boch, S., Fischer, M., & Kalko, E. K. V.
  (2011). Local and landscape-scale forest attributes differ in their
  impact on bird assemblages across years in forest production landscapes.
  Basic and Applied Ecology, 12(2), 97-106.
  https://doi.org/10.1016/j.baae.2011.01.002

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2011), Basic and Applied Ecology, 12(2), 97-106.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1016/j.baae.2011.01.002"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1016/j.baae.2011.01.002"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1016/j.baae.2011.01.002"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Forest management practices and forest fragmentation are commonly recognised as factors influencing species distribution and diversity, but it remains largely unknown how species turnover and fluctuations across years might affect generalisations from short-term predictions. There is also much uncertainty about how compositional heterogeneity within forests, through their partitioning into differently managed stands, influences species occurrence and diversity. We aimed to investigate bird species richness in different forest stands in a heterogeneous landscape and asked whether short-term studies commonly used are sufficient to describe diversity–habitat relationships.
  Breeding birds were monitored in 50 stands of differing forest types and management regimes in 2008 and 2009 in the heterogeneous forest production landscape of the Schwäbische Alb in SW Germany. Based on a database of 25 and 21 species observed in 2008 and 2009, respectively, we estimated local species richness and species turnover with Bayesian hierarchical multi-species occupancy models to account for imperfect detection. A suite of forest attributes at stand level and landscape level, between 100 and 2000 m in extent, were screened for their explanatory power regarding bird species richness.
  Bird species richness in 2008 was mostly explained by stand composition heterogeneity over a distance of 800 m around sample locations, whereas in 2009 local stand features such as stand succession type and stand age mostly explained species richness. Species turnover was significantly higher in young forest stands of thicket and pole-wood stages compared with old forest stands of timber stages.
  Variable multi-scale impacts of forest attributes on local species richness and turnover, together with year-to-year fluctuations in the regional species pool, emphasise that the relative importance of local versus landscape-scale factors in determining bird species richness may vary across years. Long-term and multiple-scale investigations that take structural and compositional forest heterogeneity into account are necessary for improved prediction of species–habitat relationships.

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
  supplementary_material: "https://doi.org/10.1016/j.baae.2011.01.002"

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
  xx.

# Image caption  
image_caption: >-
  xx.

image_license: "All rights reserved"
image_credit: "Wells et al. (2011)"
image_license_verified: false  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20110301

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
      Estimated regional bird species richness declined from 28 species in 2008 to 22 species in 2009, demonstrating substantial annual fluctuation in the regional species pool.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Most bird species occupied fewer forest plots in 2009 than in 2008.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Bird species turnover between years declined significantly with forest stand age.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Species turnover was significantly higher in thicket and pole-wood stands than in young and old timber stands.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Stand-area heterogeneity within an 800-metre radius was the strongest predictor of bird species richness in 2008.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Local stand succession stage and stand age were the most influential predictors of bird species richness in 2009.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      The scale at which landscape variables correlated with species richness differed among variables and between years.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Landscape-scale conclusions based on only two or three arbitrarily selected spatial extents can be unreliable because nearby scales are strongly collinear and variable importance changes continuously with scale.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-09
    text: >
      Hierarchical multi-species occupancy models can estimate species richness and turnover while accounting jointly for imperfect detection and unobserved species.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-10
    text: >
      Short-term studies can produce non-transferable species–habitat relationships when the relative importance of local and landscape forest attributes changes between years.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-11
    text: >
      Compositional heterogeneity among managed forest stands may partly buffer the loss of structural complexity within individual production stands.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-12
    text: >
      Sustainable forest management should integrate local stand characteristics, landscape heterogeneity and multi-year variation in bird occupancy.
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
  This study monitored breeding birds on 50 forest plots in the Schwäbische
  Alb during 2008 and 2009. Bayesian hierarchical multi-species occupancy
  models estimated species richness and turnover, while random forests and
  Bayesian model averaging compared local stand attributes with landscape
  variables measured across radii from 100 to 2,000 metres.

# Knowledge-network summary.
knowledge_summary: >
  The study shows that bird assemblage responses to managed forest structure
  are both scale dependent and temporally unstable. Landscape compositional
  heterogeneity best explained richness in one year, whereas local stand age
  and succession stage were more important in the next. Young stands also
  supported greater temporal turnover, linking forest development stage to
  dynamic occupancy processes.

# Scientific or societal significance.
impact_statement: >
  Forest-bird conservation strategies based on single-year or single-scale
  studies may be unreliable; robust management requires multi-year and
  multi-scale evidence.

# Non-technical summary.  
plain_language_summary: >-
  Bird communities in managed forests changed noticeably between 2008 and
  2009. In one year, the mix of different forest stands across the surrounding
  landscape mattered most, while in the next year local stand age and
  development stage were more important. This means forest management plans
  should not rely on observations from only one year or one spatial scale.  

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
  - multi-scale-habitat-associations
  - bird-species-richness
  - species-turnover
  - forest-management
  - forest-production-landscapes
  - landscape-heterogeneity
  - stand-composition
  - stand-succession
  - temporal-variability
  - imperfect-detection
  - multi-species-occupancy
  - spatial-scale-dependence
  - habitat-fragmentation
  - biodiversity-monitoring
  - short-term-study-bias

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - multi-scale-habitat-associations
  - bird-species-richness
  - species-turnover
  - landscape-heterogeneity
  - temporal-variability
  - multi-species-occupancy

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - schwabische-alb-forest-production-landscape
  - german-biodiversity-exploratories
  - temperate-forest-bird-assemblage
  - managed-forest-landscape-mosaic

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - aves
  - erithacus-rubecula
  - turdus-merula
  - fringilla-coelebs
  - turdus-philomelos
  - cyanistes-caeruleus
  - phylloscopus-bonelli
  - chloris-chloris
  - turdus-pilaris
  - loxia-curvirostra

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - repeated-point-count-surveys
  - multi-species-occupancy-modelling
  - hierarchical-bayesian-modelling
  - imperfect-detection-modelling
  - data-augmentation
  - species-turnover-analysis
  - jaccard-dissimilarity
  - random-forest-variable-selection
  - bayesian-model-averaging
  - poisson-regression
  - scale-of-effect-analysis
  - morans-i
  - mantel-test
  - gis-landscape-analysis

# Input environmental database/ data sources
data_products:
  - biodiversity-exploratories-forest-plot-data
  - regional-digital-forest-management-maps
  - forest-vegetation-inventory
  - breeding-bird-point-count-data

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
    object_id: stefan-m-bohm

  - predicate: authored_by
    object_type: person
    object_id: steffen-boch

  - predicate: authored_by
    object_type: person
    object_id: markus-fischer

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
    object_id: university-of-bern

  - predicate: authored_by
    object_type: organisation
    object_id: smithsonian-tropical-research-institute

  - predicate: contributes_to
    object_type: project
    object_id: biodiversity-exploratories

  - predicate: uses
    object_type: data-product
    object_id: regional-digital-forest-management-maps

  - predicate: addresses
    object_type: concept
    object_id: multi-scale-habitat-associations

  - predicate: addresses
    object_type: concept
    object_id: species-turnover

  - predicate: addresses
    object_type: concept
    object_id: landscape-heterogeneity

  - predicate: addresses
    object_type: concept
    object_id: temporal-variability

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - landscape-ecology
  - forest-ecology
  - avian-ecology
  - conservation-biology
  - occupancy-modelling
  - hierarchical-bayesian-modelling
  - spatial-scale-analysis
  - biodiversity-monitoring
  - forest-management

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why did landscape heterogeneity explain bird richness in 2008 but not in 2009?"
  - "How does imperfect detection affect estimates of species richness and turnover?"
  - "Why was species turnover greater in thicket and pole-wood stands?"
  - "What problems arise when landscape analyses test only a few arbitrarily chosen spatial scales?"
  - "How can compositional heterogeneity among forest stands buffer biodiversity loss within intensively managed stands?"
  - "What length of monitoring programme would be sufficient to separate natural annual fluctuations from management effects?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Forest Attributes and Bird Assemblages Across Years | Wells et al. 2011"

# Purpose: Search description.
seo_description: >-
  Multi-year, multi-scale analysis showing that local and landscape forest
  attributes differ in their effects on bird richness and turnover across
  years in a managed German forest landscape.

# Purpose: Search keywords.
keywords:
  - forest bird assemblages
  - species richness
  - species turnover
  - forest management
  - landscape heterogeneity
  - stand succession
  - stand age
  - multi-species occupancy
  - imperfect detection
  - scale of effect
  - random forest
  - Bayesian model averaging
  - habitat fragmentation
  - Schwäbische Alb
  - Biodiversity Exploratories
  - production forest
  - landscape ecology
  - temporal variability

# Purpose: Social sharing metadata.
social:
  title: "Forest Attributes and Bird Assemblages Across Years"
  description: >-
    Wells and colleagues show that local and landscape forest predictors of
    bird richness change between years in production landscapes.
  image: "images/images_publications/Forest-attributes-bird-assemblages_Wells-2011.png"
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
  source_url: "https://doi.org/10.1016/j.baae.2011.01.002"

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
