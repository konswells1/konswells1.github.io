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
id: 2007-wells-rainforest-logging-small-mammals

# Purpose: Official publication title.
title: "Effects of rain forest logging on species richness and assemblage composition of small mammals in Southeast Asia"

# Purpose: Short display title.
short_title: "Rainforest logging and Bornean small mammals"

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
year_published: 2007

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2007-06-01

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
- Elisabeth K. V. Kalko
- Maklarin B. Lakim
- Martin Pfeiffer

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

  # Auhor position.
  - position: 2
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

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Maklarin B. Lakim"
    # Purpose: Canonical BAHE person id.
    person_id: maklarin-b-lakim
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - sabah-parks

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "Martin Pfeiffer"
    # Purpose: Canonical BAHE person id.
    person_id: martin-pfeiffer
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-ulm

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  konstans-wells:
    - conceptualization
    - methodology
    - investigation
    - data-curation
    - formal-analysis
    - visualization
    - writing-original-draft
    - writing-review-editing

  elisabeth-k-v-kalko:
    - conceptualization
    - methodology
    - supervision
    - resources
    - funding-acquisition
    - interpretation
    - writing-review-editing

  maklarin-b-lakim:
    - investigation
    - resources
    - field-logistics
    - taxonomic-identification
    - writing-review-editing

  martin-pfeiffer:
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
journal_name: "Journal of Biogeography"

# Purpose: Journal volume.
volume: "34"

# Purpose: Journal issue.
issue: "6"

# Purpose: Article pages or article number.
pages: "1087-1099"

# Purpose: Publisher.
publisher: "Blackwell Publishing"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Kalko, E. K. V., Lakim, M. B., & Pfeiffer, M. (2007).
  Effects of rain forest logging on species richness and assemblage
  composition of small mammals in Southeast Asia. Journal of Biogeography,
  34(6), 1087-1099.
  https://doi.org/10.1111/j.1365-2699.2006.01677.x

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2007), Journal of Biogeography, 34(6), 1087-1099.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1111/j.1365-2699.2006.01677.x"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1111/j.1365-2699.2006.01677.x"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1111/j.1365-2699.2006.01677.x"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Aim The effects of logging and habitat degradation on the richness and abundance of small mammals in Asian rain forests are largely unknown. This work compares the species richness, dominance and evenness of small non-volant mammals between logged and unlogged forests, and assesses whether assemblage variability (β-diversity) is similar between forest types.
  Location Southeast Asia, northern Borneo (Sabah, Malaysia), Sunda-shelf.
  Methods We surveyed species-rich assemblages of small non-volant mammals in three unlogged and three logged forests for 2 years. At each forest site, we sampled a permanently marked transect and two additional sites in three trapping sessions. All analyses were performed at both levels to include the effects of local abundances and point estimates, separately from the relative abundances of species on a more regional scale.
  Results We trapped a total of 1218 individuals of 28 species. Eleven common species accounted for 95% of all captures. Species richness and diversity were significantly higher in unlogged forest (27 species) than in logged forest (17 species). This was mainly attributable to the smaller number of rarely recorded species in logged forest (five compared with 16 in unlogged forest, with a total of fewer than 10 captures). However, all common species were present in both logged and unlogged forests, and our analyses revealed similar patterns of dominance, evenness and fluctuations in abundance. Hence overall assemblage composition in multivariate space did not differ greatly between forest types. Assemblages of Muridae and Tupaiidae showed similar population fluctuations in space and time, indicating that the ecology of these taxa may be partially driven by the same environmental factors.
  Main conclusions Although species were distributed patchily within sites, analyses at local and regional scales revealed similar patterns in diversity and assemblage variability, suggesting that effects of forest modification did not differ extensively locally and regionally, but had a profound effect on rare species. Our results emphasize the importance and conservation value of logged forest stands that are able to hold a large proportion of the small mammals also found in unlogged forests. Rare and more specialized species are more vulnerable to forest degradation than commonly caught species, resulting in the complete loss, or a decrease in numbers, of certain groups, such as arboreal small mammals and Viverridae.

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
  supplementary_material: ""

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
image: "/images/images_publications/Rainforest-logging-small-mammals_Wells-2007.png"

image_alt: >-
  Rarefied species-accumulation curves comparing small-mammal richness in
  unlogged and logged forests in Sabah, Borneo, together with rank-abundance
  curves and a multidimensional-scaling plot of assemblage composition across
  six forest sites.

# Image caption  
image_caption: >-
  Diversity and assemblage structure of small non-volant mammals in three
  unlogged and three logged forests in Sabah. Species-accumulation curves show
  substantially greater richness in unlogged forests, whereas rank-abundance
  distributions and ordination patterns indicate that common-species
  dominance and overall assemblage dynamics remained comparatively similar
  between forest types.

image_license: "All rights reserved"
image_credit: "Wells et al. (2007)"
image_license_verified: false  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20070601

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
      Two years of trapping across six Bornean forest sites recorded 1,218 individuals representing 28 species of small non-volant mammals.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Unlogged forests supported 27 recorded species, whereas logged forests supported 17 species.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Estimated species richness was consistently higher in unlogged forests than in logged forests across Chao2, first-order jackknife and rarefaction analyses.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      The difference in richness between forest types was driven primarily by the loss or reduced detection of rare species rather than by the disappearance of common species.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Eleven common species accounted for approximately 95% of all captures and nearly all occurred in both logged and unlogged forests.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Overall Shannon diversity was lower in logged forests even though single-site diversity estimates did not differ consistently between forest types.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Dominance patterns, rank-abundance distributions and fluctuations in common-species abundance were broadly similar between logged and unlogged forests.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Niviventer cremoriventer and Tupaia tana were significantly more abundant in logged forests than in unlogged forests.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-09
    text: >
      Local and regional changes in small-mammal assemblage structure were strongly correlated, indicating similar ecological patterns across spatial scales.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-10
    text: >
      Murid and tupaiid assemblages showed correlated fluctuations in space and time, suggesting partial responses to shared environmental drivers.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-11
    text: >
      Geographic distance among forest sites explained more variation in assemblage similarity than seasonal or chronological differences among trapping sessions.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-12
    text: >
      Rare endemic, arboreal and more specialised mammals were disproportionately absent or reduced in logged forest.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-13
    text: >
      Logged forests retained a large proportion of the common small-mammal fauna found in unlogged forests and therefore have substantial conservation value.
    knowledge_type: policy-implication
    attributed_to: source-publication

  - id: statement-14
    text: >
      Community-level stability in common species can mask substantial biodiversity loss among rare and specialised taxa.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-15
    text: >
      Assessments of logging effects should combine replicated sites, multi-year sampling and both local and regional analyses to distinguish habitat effects from spatial heterogeneity.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-16
    text: >
      Conservation planning in production landscapes should protect remaining unlogged forests while recognising logged forests as important secondary habitat for disturbance-tolerant species.
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
  This replicated two-year field study compared small non-volant mammal
  assemblages in three unlogged and three selectively logged lowland forests
  in Sabah, Malaysia. More than 40,000 trap-nights and 18 trapping sessions
  were analysed using rarefaction, richness estimators, diversity indices,
  ordination and spatial–temporal similarity tests.

# Knowledge-network summary.
knowledge_summary: >
  The study shows that logging strongly reduces small-mammal species richness
  by disproportionately affecting rare, endemic, arboreal and specialised
  taxa, while leaving many common murids and tree shrews comparatively
  resilient. Similar dominance and abundance dynamics across forest types
  demonstrate that community-level stability can coexist with substantial
  biodiversity loss.

# Scientific or societal significance.
impact_statement: >
  Logged tropical forests retain important conservation value, but they do
  not replace unlogged forests for maintaining rare and specialised mammal
  diversity.

# Non-technical summary.  
plain_language_summary: >-
  Logged forests in Borneo still supported many of the common small mammals
  found in intact forest, but they contained far fewer species overall.
  Most of the losses involved rare, specialised and tree-dwelling mammals.
  Protecting unlogged forest remains essential, while well-managed logged
  forests can still contribute meaningfully to biodiversity conservation.  

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - biodiversity-global-change
  - conservation-ecology
  - ecological-interactions-system-dynamics
  - quantitative-ecology-modelling

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - tropical-forest-logging
  - small-mammal-diversity
  - species-richness
  - assemblage-composition
  - rare-species-loss
  - disturbance-tolerance
  - logged-forest-conservation-value
  - beta-diversity
  - rank-abundance
  - species-turnover
  - spatial-scale
  - forest-degradation
  - arboreal-mammal-decline
  - community-stability
  - habitat-specialisation

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - tropical-forest-logging
  - small-mammal-diversity
  - rare-species-loss
  - logged-forest-conservation-value
  - assemblage-composition
  - habitat-specialisation

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - sabah-logged-unlogged-forest-comparison
  - borneo-small-mammal-assemblages
  - southeast-asian-dipterocarp-forest
  - tropical-production-forest-landscape

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - small-non-volant-mammals
  - muridae
  - tupaiidae
  - sciuridae
  - viverridae
  - leopoldamys-sabanus
  - maxomys-rajah
  - maxomys-surifer
  - maxomys-whiteheadi
  - niviventer-cremoriventer
  - sundamys-muelleri
  - tupaia-gracilis
  - tupaia-longipes
  - tupaia-minor
  - tupaia-tana
  - sundasciurus-lowii

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - live-trapping
  - repeated-trapping-sessions
  - pit-tagging
  - species-identification
  - sample-based-rarefaction
  - chao2-richness-estimation
  - first-order-jackknife
  - shannon-wiener-diversity
  - rank-abundance-analysis
  - bray-curtis-similarity
  - non-metric-multidimensional-scaling
  - mantel-test
  - coefficient-of-variation
  - persistence-rate-estimation
  - multiscale-community-analysis

# Input environmental database/ data sources
data_products:
  - sabah-small-mammal-trapping-data
  - sabah-parks-museum-reference-collection
  - six-site-logged-unlogged-forest-survey

# Data produced or archived by this study  
research_datasets: []

projects:
  - borneo-small-mammal-forest-ecology

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
    object_id: elisabeth-k-v-kalko

  - predicate: authored_by
    object_type: person
    object_id: maklarin-b-lakim

  - predicate: authored_by
    object_type: person
    object_id: martin-pfeiffer

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-ulm

  - predicate: authored_by
    object_type: organisation
    object_id: smithsonian-tropical-research-institute

  - predicate: authored_by
    object_type: organisation
    object_id: sabah-parks

  - predicate: addresses
    object_type: concept
    object_id: tropical-forest-logging

  - predicate: addresses
    object_type: concept
    object_id: rare-species-loss

  - predicate: addresses
    object_type: concept
    object_id: logged-forest-conservation-value

  - predicate: addresses
    object_type: concept
    object_id: assemblage-composition

  - predicate: involves
    object_type: taxon
    object_id: muridae

  - predicate: involves
    object_type: taxon
    object_id: tupaiidae

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - conservation-biology
  - tropical-forest-ecology
  - disturbance-ecology
  - mammalogy
  - community-ecology
  - biodiversity-monitoring
  - multivariate-ecology
  - species-richness-estimation
  - sustainable-forest-management

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why can common-species abundance remain stable while overall species richness declines?"
  - "Why were rare, arboreal and endemic species particularly vulnerable to logging?"
  - "How do local and regional analyses provide complementary information about assemblage responses?"
  - "What does the similarity of rank-abundance curves reveal about the effects of logging?"
  - "How should logged forests be valued relative to primary forests in conservation planning?"
  - "What additional information would be needed to identify the mechanisms driving rare-species loss?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Rainforest Logging and Small Mammal Diversity in Borneo | Wells et al. 2007"

# Purpose: Search description.
seo_description: >-
  Replicated study showing that logging reduces small-mammal richness in
  Borneo primarily through losses of rare, arboreal and specialised species,
  while many common species persist in logged forests.

# Purpose: Search keywords.
keywords:
  - Borneo
  - Sabah
  - rainforest logging
  - small mammals
  - species richness
  - community composition
  - logged forest
  - unlogged forest
  - rare species
  - Muridae
  - Tupaiidae
  - tropical forest conservation
  - beta diversity
  - rank abundance
  - habitat degradation
  - arboreal mammals
  - species accumulation
  - forest management
  - Southeast Asia

# Purpose: Social sharing metadata.
social:
  title: "Rainforest Logging and Small Mammal Diversity in Borneo"
  description: >-
    Wells and colleagues show that logged forests retain many common small
    mammals but lose substantial rare and specialised biodiversity.
  image: "images/images_publications/Rainforest-logging-small-mammals_Wells-2007.png"
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
  source_url: "https://doi.org/10.1111/j.1365-2699.2006.01677.x"

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
