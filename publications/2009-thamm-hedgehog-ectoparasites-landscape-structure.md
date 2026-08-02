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
id: 2009-thamm-hedgehog-ectoparasites-landscape-structure

# Purpose: Official publication title.
title: "Ectoparasite Infestations of Hedgehogs (Erinaceus europaeus) are Associated with Small-Scale Landscape Structures in an Urban–Suburban Environment"

# Purpose: Short display title.
short_title: "Landscape structure and hedgehog ectoparasites"

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
year_published: 2009

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2010-01-30

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
- Sven Thamm
- Elisabeth K. V. Kalko
- Konstans Wells

# Purpose: Canonical BAHE author ids.
bahe_authors:
  - konstans-wells

# Purpose: Structured author metadata.
author_entities:
  # Purpose: Citation order.
  - position: 1
    # Purpose: Full author name.
    name: "Sven Thamm"
    # Purpose: Canonical BAHE person id.
    person_id: sven-thamm
    # Purpose: ORCID identifier.
    orcid: ""
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
    name: "Konstans Wells"
    # Purpose: Canonical BAHE person id.
    person_id: konstans-wells
    # Purpose: ORCID identifier.
    orcid: "0000-0003-0377-2463"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-ulm

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  sven-thamm:
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
    - interpretation
    - writing-review-editing

  konstans-wells:
    - conceptualization
    - methodology
    - formal-analysis
    - interpretation
    - writing-original-draft
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
journal_name: "EcoHealth"

# Purpose: Journal volume.
volume: "6"

# Purpose: Journal issue.
issue: "3"

# Purpose: Article pages or article number.
pages: "404-413"

# Purpose: Publisher.
publisher: "Springer"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Thamm, S., Kalko, E. K. V., & Wells, K. (2009). Ectoparasite
  Infestations of Hedgehogs (Erinaceus europaeus) are Associated with
  Small-Scale Landscape Structures in an Urban–Suburban Environment.
  EcoHealth, 6(3), 404-413.
  https://doi.org/10.1007/s10393-009-0268-3

# Purpose: Short citation.
citation_short: >-
  Thamm et al. (2009), EcoHealth, 6(3), 404-413.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1007/s10393-009-0268-3"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1007/s10393-009-0268-3"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1007/s10393-009-0268-3"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Animals that exploit heterogeneous and patchy environments encounter different local habitat conditions that influence their interaction with the environment, such as the acquisition of parasites. How and at which scales interaction processes between parasites, hosts, and the environment are realized remains largely unknown. We examined the infestation patterns of 56 hedgehogs (Erinaceus europaeus) with fleas and ticks at a small spatial scale within a 12 km2 area along a suburban–urban gradient in southwestern Germany. The structure and type of habitats surrounding hedgehog capture locations were estimated from digital land cover data within radii of 20, 50, and 100 m. These were assumed to match the ranging area and underlying heterogeneous landscape matrix in which host–parasite interactions take place. Landscape-based models suggested that flea burdens significantly decreased with the diversity and heterogeneity of land cover, as well as with the areal coverage of roads within radii of 50 and 100 m. Overall tick infestation levels were mostly explained by the number of arable patches and the areal coverage of roads within radii of 50 and 100 m, as well as date of capture. Examination of the semivariance in model residuals revealed no evident spatial structure in any of the models with flea or tick infestation patterns as response variables. Our results, which are based on a sampling scheme within a relatively small spatio-temporal window, suggest that heterogeneous landscape matrices affect parasitization rates of animals in urban environments, with clear differences at the individual level.

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
image: "/images/images_publications/Hedgehog-ectoparasites-landscape-structure_Thamm-2009.png"

image_alt: >-
  Map of the urban–suburban study landscape around Ulm, Germany, showing
  hedgehog capture sites across built-up areas, roads, arable fields,
  grasslands and forest patches, together with example 20, 50 and 100 metre
  buffers used to quantify local landscape structure around each capture
  location.

# Image caption  
image_caption: >-
  Urban–suburban landscape context of hedgehog sampling around Ulm,
  southwestern Germany. Capture locations were embedded within a fine-grained
  mosaic of built-up land, roads, arable fields, grassland and forest.
  Landscape composition and heterogeneity were quantified within 20, 50 and
  100 metre buffers to test their associations with flea and tick burdens.

image_license: "All rights reserved"
image_credit: "Thamm, Kalko and Wells (2009)"
image_license_verified: false  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20090901

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
      Fleas were recorded on 50 of 56 European hedgehogs sampled across the urban–suburban study landscape.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      The flea Archeopsylla erinacei reached burdens of up to 100 individuals per hedgehog, with 907 fleas collected in total.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Tick infestations were recorded on 49 of 56 hedgehogs, including both Ixodes hexagonus and Ixodes ricinus.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Of the identified ticks, approximately 65% were Ixodes hexagonus and 35% were Ixodes ricinus.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Flea burdens declined as land-cover diversity and heterogeneity increased within 50 and 100 metre buffers around hedgehog capture locations.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Greater road coverage within 50 and 100 metre buffers was associated with lower flea burdens on hedgehogs.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Patch richness and the Shannon diversity of patch numbers within 20 metres were negatively associated with flea burden but had less explanatory power than landscape variables measured at 50 and 100 metres.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Tick infestation levels declined with increasing arable land cover and with increasing numbers of arable patches across the analysed spatial scales.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-09
    text: >
      Tick infestation increased with built-up land cover within 50 and 100 metre buffers and with the number of roads within 50 metres.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-10
    text: >
      Tick infestation intensity declined through the April-to-August sampling period.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-11
    text: >
      Flea and tick burdens were not correlated with geographic distance among hedgehog capture locations.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-12
    text: >
      Residual variograms showed little evidence of spatial autocorrelation after landscape variables were included in the infestation models.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-13
    text: >
      Small-scale landscape heterogeneity can influence parasite acquisition by neighbouring hosts even when infestation patterns show no simple spatial clustering.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-14
    text: >
      Flea burdens may respond indirectly to landscape structure through effects on hedgehog movement, aggregation, density and use of resting sites.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-15
    text: >
      Tick responses to built-up and arable land should be interpreted cautiously because Ixodes hexagonus and Ixodes ricinus differ substantially in off-host ecology and questing strategy.
    knowledge_type: recommendation
    attributed_to: source-publication

  - id: statement-16
    text: >
      Host–parasite models in urban environments should incorporate fine-scale landscape composition and heterogeneity rather than assuming homogeneous habitat matrices.
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
  This study examined flea and tick burdens on 56 European hedgehogs sampled
  along an urban–suburban gradient around Ulm, Germany. Digital land-cover
  data were summarized within 20, 50 and 100 metre buffers, and infestation
  patterns were analysed using negative binomial and ordinal logistic models.

# Knowledge-network summary.
knowledge_summary: >
  The study demonstrates that parasite burdens can respond to landscape
  structure at spatial scales comparable to individual host movement.
  Flea burdens were lower in more heterogeneous landscapes and where road
  coverage was greater, whereas tick burdens were associated with arable,
  built-up and road features and with seasonal timing. These results connect
  urban landscape ecology, host movement and parasite acquisition at the
  individual level.

# Scientific or societal significance.
impact_statement: >
  Urban wildlife disease risk cannot be inferred from host presence alone;
  fine-scale landscape composition and host-specific movement contexts also
  shape ectoparasite exposure.

# Non-technical summary.  
plain_language_summary: >-
  Hedgehogs living only short distances apart carried very different numbers
  of fleas and ticks. These differences were linked to the mix of roads,
  fields, buildings, grassland and forest around where each animal was found.
  The study shows that urban landscape structure can influence parasite
  exposure over surprisingly small distances.  

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - one-health-disease-ecology
  - biodiversity-global-change
  - quantitative-ecology-modelling
  - ecological-interactions-system-dynamics

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - urban-wildlife-parasitism
  - hedgehog-ectoparasites
  - landscape-heterogeneity
  - small-scale-landscape-structure
  - flea-burden
  - tick-infestation
  - host-parasite-interactions
  - urban-suburban-gradient
  - spatial-epidemiology
  - habitat-matrix
  - road-effects
  - arable-land-effects
  - built-up-land-effects
  - host-movement
  - parasite-acquisition

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - urban-wildlife-parasitism
  - landscape-heterogeneity
  - flea-burden
  - tick-infestation
  - spatial-epidemiology
  - host-movement

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - ulm-urban-suburban-landscape
  - european-hedgehog-ectoparasite-system
  - urban-wildlife-parasite-interface
  - small-scale-host-landscape-matrix

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - erinaceus-europaeus
  - archeopsylla-erinacei
  - ixodes-hexagonus
  - ixodes-ricinus

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - nocturnal-spotlight-capture
  - pit-tagging
  - ectoparasite-collection
  - flea-counting
  - tick-infestation-scoring
  - morphological-ectoparasite-identification
  - gis-buffer-analysis
  - landscape-metric-analysis
  - shannon-diversity-index
  - negative-binomial-regression
  - ordinal-logistic-regression
  - akaike-information-criterion
  - mantel-test
  - variogram-analysis
  - spatial-residual-analysis

# Input environmental database/ data sources
data_products:
  - baden-wurttemberg-digital-land-cover-data
  - ulm-field-parcel-database
  - hedgehog-capture-location-data

# Data produced or archived by this study  
research_datasets: []

projects:
  - ulm-urban-hedgehog-ecology

# =======
# Typed graph relationships
# =======

# Purpose: Explicit knowledge graph relationships.
relationships:
  - predicate: authored_by
    object_type: person
    object_id: sven-thamm

  - predicate: authored_by
    object_type: person
    object_id: elisabeth-k-v-kalko

  - predicate: authored_by
    object_type: person
    object_id: konstans-wells

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-ulm

  - predicate: authored_by
    object_type: organisation
    object_id: smithsonian-tropical-research-institute

  - predicate: uses
    object_type: data-product
    object_id: baden-wurttemberg-digital-land-cover-data

  - predicate: uses
    object_type: data-product
    object_id: ulm-field-parcel-database

  - predicate: addresses
    object_type: concept
    object_id: urban-wildlife-parasitism

  - predicate: addresses
    object_type: concept
    object_id: landscape-heterogeneity

  - predicate: addresses
    object_type: concept
    object_id: tick-infestation

  - predicate: addresses
    object_type: concept
    object_id: flea-burden

  - predicate: involves
    object_type: taxon
    object_id: erinaceus-europaeus

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - disease-ecology
  - urban-ecology
  - landscape-ecology
  - wildlife-parasitology
  - spatial-epidemiology
  - veterinary-ecology
  - generalized-linear-modelling
  - gis-in-ecology
  - one-health

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why might landscape heterogeneity reduce flea burdens on hedgehogs?"
  - "How do the life histories of Ixodes hexagonus and Ixodes ricinus complicate interpretation of pooled tick burdens?"
  - "Why were 20, 50 and 100 metre buffers used rather than full estimated hedgehog home ranges?"
  - "How can parasite burdens vary among neighbouring animals without showing spatial autocorrelation?"
  - "Why might built-up land increase tick burdens while arable land decreases them?"
  - "What additional data on hedgehog movement and density would strengthen causal inference?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Hedgehog Ectoparasites and Urban Landscape Structure | Thamm et al. 2009"

# Purpose: Search description.
seo_description: >-
  Study showing that flea and tick burdens on European hedgehogs vary with
  small-scale landscape heterogeneity, roads, arable land and built-up cover
  across an urban–suburban gradient in Germany.

# Purpose: Search keywords.
keywords:
  - European hedgehog
  - Erinaceus europaeus
  - ectoparasites
  - fleas
  - ticks
  - Archeopsylla erinacei
  - Ixodes hexagonus
  - Ixodes ricinus
  - urban ecology
  - suburban landscape
  - landscape heterogeneity
  - spatial epidemiology
  - road cover
  - arable land
  - built-up land
  - parasite burden
  - host movement
  - EcoHealth
  - Ulm Germany

# Purpose: Social sharing metadata.
social:
  title: "Hedgehog Ectoparasites and Urban Landscape Structure"
  description: >-
    Thamm, Kalko and Wells show that flea and tick burdens on hedgehogs vary
    with landscape structure across an urban–suburban gradient.
  image: "images/images_publications/Hedgehog-ectoparasites-landscape-structure_Thamm-2009.png"
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
  source_url: "https://doi.org/10.1007/s10393-009-0268-3"

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
