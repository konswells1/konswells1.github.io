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
id: 2011-bohm-top-down-herbivory-control

# Purpose: Official publication title.
title: "Top-down control of herbivory by birds and bats in the canopy of temperate broad-leaved oaks (Quercus robur)"

# Purpose: Short display title.
short_title: "Bird and bat control of oak herbivory"

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
date: 2011-04-04

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
- Stefan M. Böhm
- Konstans Wells
- Elisabeth K. V. Kalko

# Purpose: Canonical BAHE author ids.
bahe_authors:
  - konstans-wells

# Purpose: Structured author metadata.
author_entities:
  # Purpose: Citation order.
  - position: 1
    # Purpose: Full author name.
    name: "Stefan M. Böhm"
    # Purpose: Canonical BAHE person id.
    person_id: stefan-m-bohm
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated canonical organisation objects.
    affiliation_ids:
      - university-of-ulm

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Konstans Wells"
    # Purpose: Canonical BAHE person id.
    person_id: konstans-wells
    # Purpose: ORCID identifier.
    orcid: "0000-0003-0377-2463"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-ulm
      - biodiversity-and-climate-research-centre

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Elisabeth K. V. Kalko"
    # Purpose: Canonical BAHE person id.
    person_id: elisabeth-k-v-kalko
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - smithsonian-tropical-research-institute
      - university-of-ulm

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  stefan-m-bohm:
    - conceptualization
    - methodology
    - investigation
    - data-curation
    - formal-analysis
    - visualization
    - writing-original-draft
    - writing-review-editing

  konstans-wells:
    - conceptualization
    - methodology
    - formal-analysis
    - interpretation
    - writing-original-draft
    - writing-review-editing

  elisabeth-k-v-kalko:
    - conceptualization
    - methodology
    - resources
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

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "PLOS ONE"

# Purpose: Journal volume.
volume: "6"

# Purpose: Journal issue.
issue: "4"

# Purpose: Article pages or article number.
pages: "e17857"

# Purpose: Publisher.
publisher: "Public Library of Science"

# Purpose: Open-access availability. # Values: true, false
open_access: true

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "CC BY 4.0"

# Purpose: Complete citation.
citation_full: >-
  Böhm, S. M., Wells, K., & Kalko, E. K. V. (2011). Top-Down Control
  of Herbivory by Birds and Bats in the Canopy of Temperate Broad-Leaved
  Oaks (Quercus robur). PLOS ONE, 6(4), e17857.
  https://doi.org/10.1371/journal.pone.0017857

# Purpose: Short citation.
citation_short: >-
  Böhm et al. (2011), PLOS ONE, 6(4), e17857.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1371/journal.pone.0017857"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1371/journal.pone.0017857"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1371/journal.pone.0017857"
pdf: "https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0017857&type=printable"

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  The intensive foraging of insectivorous birds and bats is well known to reduce the density of arboreal herbivorous arthropods but quantification of collateral leaf damage remains limited for temperate forest canopies. We conducted exclusion experiments with nets in the crowns of young and mature oaks, Quercus robur, in south and central Germany to investigate the extent to which aerial vertebrates reduce herbivory through predation. We repeatedly estimated leaf damage throughout the vegetation period. Exclusion of birds and bats led to a distinct increase in arthropod herbivory, emphasizing the prominent role of vertebrate predators in controlling arthropods. Leaf damage (e.g., number of holes) differed strongly between sites and was 59% higher in south Germany, where species richness of vertebrate predators and relative oak density were lower compared with our other study site in central Germany. The effects of bird and bat exclusion on herbivory were 19% greater on young than on mature trees in south Germany. Our results support previous studies that have demonstrated clear effects of insectivorous vertebrates on leaf damage through the control of herbivorous arthropods. Moreover, our comparative approach on quantification of leaf damage highlights the importance of local attributes such as tree age, forest composition and species richness of vertebrate predators for control of arthropod herbivory.

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
  supplementary_material: "https://doi.org/10.1371/journal.pone.0017857"

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
image: "/images/images_publications/boehm_2011_oak_herbivory.png"

image_alt: >-
  Differences in mean damage of leaf area (A) and mean number of holes (B) per leaf for exclusions (shaded bars) and controls (open bars) at the two study sites and for young and mature oaks on the Schwäbische Alb. Significant differences in variables are indicated by “*”. Error bars indicate one SE; variables are presented as square-root transformed values..

# Image caption  
image_caption: >-
  Differences in mean damage of leaf area (A) and mean number of holes (B) per leaf for exclusions (shaded bars) and controls (open bars) at the two study sites and for young and mature oaks on the Schwäbische Alb. Significant differences in variables are indicated by “*”. Error bars indicate one SE; variables are presented as square-root transformed values..

image_license: "CC BY 4.0"
image_credit: "Böhm, Wells and Kalko (2011)"
image_license_verified: true  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20110404

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
      Excluding birds and bats from Quercus robur crowns significantly increased both leaf-area damage and the number of arthropod feeding holes.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      On young oaks in the Schwäbische Alb, vertebrate exclusion increased mean leaf-area damage by approximately 40% and the number of holes per leaf by approximately 29%.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      On mature oaks, vertebrate exclusion increased mean leaf-area damage by approximately 23% in the Schwäbische Alb and 44% in Hainich-Dün.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      On mature oaks, vertebrate exclusion increased the number of feeding holes per leaf by approximately 16% in the Schwäbische Alb and 39% in Hainich-Dün.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Leaf damage was greater on young than on mature oaks in the Schwäbische Alb, indicating that tree age modifies herbivory and predator effects.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Mature oaks in the Schwäbische Alb experienced substantially greater herbivory than mature oaks in Hainich-Dün.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Higher bird species richness, higher bird abundance and greater foliage-gleaning bat activity in Hainich-Dün coincided with lower herbivory than in the Schwäbische Alb.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Birds and bats provide a measurable ecosystem service by suppressing herbivorous arthropods and reducing canopy leaf damage in temperate oak forests.
    knowledge_type: conceptual-proposition
    attributed_to: source-publication

  - id: statement-09
    text: >
      The strength of top-down herbivory control depends on local forest composition, tree age and the richness and abundance of vertebrate predators.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-10
    text: >
      Exclosure experiments combined with repeated phytometric measurements can quantify cascading effects of vertebrate predation on herbivory in forest canopies.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-11
    text: >
      Declines in insectivorous bird and bat diversity may increase arthropod herbivory and reduce forest productivity.
    knowledge_type: policy-implication
    attributed_to: source-publication

  - id: statement-12
    text: >
      Forest management should retain structurally diverse stands, dead wood, oaks, cavity-bearing trees and refuge habitats that support insectivorous birds and bats.
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
  This canopy-exclosure experiment compared leaf herbivory on young and mature
  common oaks in the Schwäbische Alb and Hainich-Dün regions of Germany.
  Repeated leaf measurements quantified how exclusion of insectivorous birds
  and bats changed leaf-area loss and feeding-hole abundance.

# Knowledge-network summary.
knowledge_summary: >
  The study provides experimental evidence for a trophic cascade in temperate
  forest canopies. Birds and bats suppress herbivorous arthropods, thereby
  reducing damage to Quercus robur leaves. The magnitude of this ecosystem
  service varies with tree age, stand composition and regional predator
  diversity, linking biodiversity directly to forest function.

# Scientific or societal significance.
impact_statement: >
  Conserving diverse insectivorous bird and bat assemblages can reduce canopy
  herbivory and help maintain forest productivity and resilience.

# Non-technical summary.  
plain_language_summary: >-
  Oaks protected from birds and bats suffered more insect damage than
  unprotected trees. The effect occurred in both young and mature trees and
  was strongest where bird and bat communities were less diverse. The findings
  show that insect-eating vertebrates provide valuable natural pest control in
  temperate forests.  

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - ecological-interactions-system-dynamics
  - biodiversity-global-change
  - conservation-ecology
  - quantitative-ecology-modelling

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - top-down-control
  - trophic-cascades
  - herbivory
  - insectivorous-birds
  - insectivorous-bats
  - ecosystem-services
  - natural-pest-control
  - predator-diversity
  - forest-canopy-ecology
  - leaf-damage
  - tree-age-effects
  - forest-composition
  - functional-biodiversity
  - arthropod-suppression
  - forest-productivity

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - top-down-control
  - trophic-cascades
  - herbivory
  - insectivorous-birds
  - insectivorous-bats
  - ecosystem-services

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - temperate-oak-canopy-food-web
  - schwabische-alb-forest-landscape
  - hainich-dun-forest-landscape
  - german-biodiversity-exploratories

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - quercus-robur
  - aves
  - chiroptera
  - plecotus-auritus
  - plecotus-austriacus
  - myotis-bechsteinii
  - myotis-nattereri
  - myotis-emarginatus
  - myotis-mystacinus
  - eptesicus-serotinus

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - vertebrate-exclosure-experiment
  - canopy-netting
  - repeated-leaf-sampling
  - phytometric-analysis
  - digital-image-analysis
  - imagej-leaf-damage-measurement
  - winrhizopro-analysis
  - bird-point-counts
  - acoustic-bat-monitoring
  - generalised-linear-mixed-modelling
  - repeated-measures-analysis
  - model-comparison
  - variance-analysis

# Input environmental database/ data sources
data_products:
  - biodiversity-exploratories-forest-data
  - bird-survey-data
  - acoustic-bat-monitoring-data
  - oak-leaf-damage-data

# Data produced or archived by this study  
research_datasets:
  - plos-one-e17857-supporting-information

projects:
  - biodiversity-exploratories

# =======
# Typed graph relationships
# =======

# Purpose: Explicit knowledge graph relationships.
relationships:
  - predicate: authored_by
    object_type: person
    object_id: stefan-m-bohm

  - predicate: authored_by
    object_type: person
    object_id: konstans-wells

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
    object_id: smithsonian-tropical-research-institute

  - predicate: contributes_to
    object_type: project
    object_id: biodiversity-exploratories

  - predicate: produces
    object_type: dataset
    object_id: plos-one-e17857-supporting-information

  - predicate: addresses
    object_type: concept
    object_id: top-down-control

  - predicate: addresses
    object_type: concept
    object_id: trophic-cascades

  - predicate: addresses
    object_type: concept
    object_id: ecosystem-services

  - predicate: addresses
    object_type: concept
    object_id: predator-diversity

  - predicate: involves
    object_type: taxon
    object_id: quercus-robur

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - community-ecology
  - trophic-ecology
  - forest-ecology
  - ecosystem-services
  - experimental-ecology
  - conservation-biology
  - ornithology
  - bat-ecology
  - mixed-effects-modelling

# Purpose: Suggested discussion questions.
discussion_questions:
  - "How do exclosure experiments demonstrate top-down control in forest food webs?"
  - "Why might young oaks experience stronger herbivory than mature oaks?"
  - "How could predator species richness influence the magnitude of herbivore suppression?"
  - "Why is it difficult to separate the contributions of birds and bats in canopy exclosure experiments?"
  - "How might forest management alter the ecosystem service provided by insectivorous vertebrates?"
  - "What additional measurements would strengthen inference about arthropod abundance and tree fitness?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Bird and Bat Control of Oak Herbivory | Böhm et al. 2011"

# Purpose: Search description.
seo_description: >-
  Canopy-exclosure experiment showing that insectivorous birds and bats reduce
  arthropod herbivory on Quercus robur and that the effect varies with tree age,
  forest composition and predator diversity.

# Purpose: Search keywords.
keywords:
  - Quercus robur
  - common oak
  - top-down control
  - trophic cascade
  - herbivory
  - insectivorous birds
  - insectivorous bats
  - forest canopy
  - leaf damage
  - predator diversity
  - ecosystem services
  - natural pest control
  - Biodiversity Exploratories
  - Schwäbische Alb
  - Hainich-Dün
  - vertebrate exclosure
  - forest management
  - arthropod herbivores
  - temperate forest

# Purpose: Social sharing metadata.
social:
  title: "Bird and Bat Control of Oak Herbivory"
  description: >-
    Böhm, Wells and Kalko show that insectivorous birds and bats significantly
    reduce arthropod damage in temperate oak canopies.
  image: "images/images_publications/Top-down-control-oak-herbivory_Boehm-2011.png"
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
  The article is published under the Creative Commons Attribution licence.
  Reuse must preserve attribution to the authors, article title, journal
  citation and DOI.

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
  source_url: "https://doi.org/10.1371/journal.pone.0017857"

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
