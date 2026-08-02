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
id: 2011-wells-flea-small-mammal-host-specificity

# Purpose: Official publication title.
title: "Host specificity and niche partitioning in flea–small mammal networks in Bornean rainforests"

# Purpose: Short display title.
short_title: "Flea–small mammal networks in Borneo"

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
date: 2011-01-10

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
- Maklarin B. Lakim
- Jean-Claude Beaucournu

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
      - biodiversity-and-climate-research-centre
      - sabah-parks
      - university-of-ulm

  # Auhor position.
  - position: 2
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
  - position: 3
    # Purpose: Full author name.
    name: "Jean-Claude Beaucournu"
    # Purpose: Canonical BAHE person id.
    person_id: jean-claude-beaucournu
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-rennes

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

  maklarin-b-lakim:
    - investigation
    - resources
    - field-logistics
    - writing-review-editing

  jean-claude-beaucournu:
    - taxonomic-identification
    - resources
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
journal_name: "Medical and Veterinary Entomology"

# Purpose: Journal volume.
volume: "25"

# Purpose: Journal issue.
issue: "3"

# Purpose: Article pages or article number.
pages: "311-319"

# Purpose: Publisher.
publisher: "Wiley"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Lakim, M. B., & Beaucournu, J.-C. (2011). Host specificity
  and niche partitioning in flea–small mammal networks in Bornean
  rainforests. Medical and Veterinary Entomology, 25(3), 311-319.
  https://doi.org/10.1111/j.1365-2915.2010.00940.x

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2011), Medical and Veterinary Entomology, 25(3), 311-319.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1111/j.1365-2915.2010.00940.x"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1111/j.1365-2915.2010.00940.x"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1111/j.1365-2915.2010.00940.x"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  The diversity of ectoparasites in Southeast Asia and flea–host associations remain largely understudied. We explore specialization and interaction patterns of fleas infesting non-volant small mammals in Bornean rainforests, using material from a field survey carried out in two montane localities in northwestern Borneo (Sabah, Malaysia) and from a literature database of all available interactions in both lowland and montane forests. A total of 234 flea individuals collected during our field survey resulted in an interaction network of eight flea species on seven live-captured small mammal species. The interaction network from all compiled studies currently includes 15 flea species and 16 small mammal species. Host specificity and niche partitioning of fleas infesting diurnal treeshrews and squirrels were low, with little difference in specialization among taxa, but host specificity in lowland forests was found to be higher than in montane forests. By contrast, Sigmactenus alticola exhibited low host specificity by infesting various montane and lowland nocturnal rats. However, this species exhibited low niche partitioning as it was the only commonly recorded flea from rats on Borneo. Overall complementary specialization was of intermediate intensity for both networks and differed significantly from random association; this has important implications for specific interactions that are also relevant to the potential spread of vector-borne diseases.

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
image: "/images/images_publications/Flea-small-mammal-networks-borneo_Wells-2011.png"

image_alt: >-
  Bipartite interaction network linking 16 non-volant small mammal host
  species on the left with 15 flea species on the right using all published
  records available from Bornean forests. Grey host nodes represent squirrels
  and treeshrews, black host nodes represent rats and Hylomys suillus, and
  connecting lines show recorded flea–host associations.

# Image caption  
image_caption: >-
  Compiled flea–small mammal interaction network for Bornean rainforests.
  The network includes 45 recorded associations among 15 flea species and
  16 mammal species. Tree shrews and squirrels share several flea taxa,
  whereas Sigmactenus alticola is the main flea associated with multiple
  nocturnal rat species across lowland and montane forests.

image_license: "All rights reserved"
image_credit: "Wells, Lakim and Beaucournu (2011)"
image_license_verified: false  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20110110

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
      The montane field survey recorded 234 individual fleas representing eight flea species on seven non-volant small mammal species.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Fleas were detected on 74 of 90 sampled small mammals, corresponding to an overall infestation prevalence of approximately 82%.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Up to three flea species co-occurred on individual treeshrews and squirrels, with a mean of 1.3 flea species per infested host.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      The field-survey network showed intermediate complementary specialization and differed significantly from random flea–host association.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      The three most commonly recorded flea species, Gryphopsylla mjoebergi, Macrostylophora traubi and Lentistivalius vomerus, exhibited low host specificity across treeshrews and squirrels.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      The compiled Bornean network contained 45 recorded associations among 15 flea species and 16 small mammal species.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Tupaia montana had the largest known flea assemblage in the compiled network, with nine flea species recorded.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Host specificity was higher among lowland flea–host associations than among montane associations.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-09
    text: >
      Sigmactenus alticola was recorded on five of six rat species and on Tupaia montana, indicating broad host use across lowland and montane habitats.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-10
    text: >
      Flea–host network structure differed among functional host groups, with diurnal treeshrews and squirrels sharing several flea species while nocturnal rats were dominated by one common flea taxon.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-11
    text: >
      Complementary specialization indices provided broadly consistent community-level patterns between the short-term field survey and the literature-derived network despite incomplete sampling.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-12
    text: >
      Incomplete sampling particularly biases inference for rarely encountered species, singleton interactions, network connectivity and modularity.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-13
    text: >
      Differences in flea host specificity between lowland and montane forests may reflect climatic constraints, host nesting ecology and the availability of suitable microhabitats for flea development.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-14
    text: >
      Changes in forest use and wildlife–commensal rodent contact may alter vector-borne disease transmission through shifts in flea abundance, host sharing and habitat tolerance.
    knowledge_type: policy-implication
    attributed_to: source-publication

  - id: statement-15
    text: >
      Future research should combine repeated field sampling, environmental covariates and both host and parasite perspectives to explain variation in flea–host interaction intensity.
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
  This study combined a short-term flea survey in two montane forests of
  Sabah with a compilation of all available Bornean flea–small mammal records.
  Bipartite network analysis, null models and specialization indices were used
  to compare host specificity and niche partitioning across taxa and habitats.

# Knowledge-network summary.
knowledge_summary: >
  The study provides one of the first community-level analyses of tropical
  flea–mammal networks in Southeast Asia. It shows intermediate but
  non-random complementary specialization, broad flea sharing among
  treeshrews and squirrels, and a distinctive rat-associated network
  dominated by Sigmactenus alticola. Host specificity also varied between
  lowland and montane forests, linking network structure to environmental and
  functional differences among host groups.

# Scientific or societal significance.
impact_statement: >
  Flea host sharing and habitat-dependent specialization shape potential
  pathways for vector-borne disease transmission across diverse tropical
  mammal communities.

# Non-technical summary.  
plain_language_summary: >-
  Fleas in Bornean rainforests do not all use hosts in the same way.
  Tree shrews and squirrels shared several flea species, while rats were
  mainly linked by one widespread flea. Associations also differed between
  lowland and mountain forests. These patterns may influence how flea-borne
  pathogens move among wildlife species.  

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
  - flea-host-specificity
  - niche-partitioning
  - flea-small-mammal-networks
  - parasite-sharing
  - complementary-specialization
  - bipartite-ecological-networks
  - ectoparasite-community
  - vector-borne-disease
  - host-functional-groups
  - montane-lowland-comparison
  - parasite-generalism
  - network-asymmetry
  - sampling-bias
  - wildlife-disease-transmission
  - tropical-parasitology

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - flea-host-specificity
  - niche-partitioning
  - flea-small-mammal-networks
  - parasite-sharing
  - complementary-specialization
  - vector-borne-disease

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - borneo-flea-small-mammal-network
  - mesilou-montane-forest
  - mount-alap-montane-forest
  - borneo-lowland-montane-parasite-system

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - cratynius-audyi
  - dasypsyllus-gallinulae-klossi
  - macrostylophora-borneensis
  - macrostylophora-durdeni
  - macrostylophora-kinabaluae
  - macrostylophora-traubi
  - neopsylla-luma
  - sigmactenus-alticola
  - gryphopsylla-hopkinsi
  - gryphopsylla-jacobsoni-segregata
  - gryphopsylla-mjoebergi
  - lentistivalius-vomerus
  - medwayella-pfeifferi
  - medwayella-sabahae
  - medwayella-traubiana
  - hylomys-suillus
  - maxomys-alticola
  - maxomys-rajah
  - maxomys-whiteheadi
  - niviventer-cremoriventer
  - rattus-baluensis
  - rattus-rattus
  - sundamys-infraluteus
  - callosciurus-prevostii
  - dremomys-everetti
  - sundasciurus-jentinki
  - sundasciurus-lowii
  - tupaia-gracilis
  - tupaia-longipes
  - tupaia-montana
  - tupaia-tana

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - live-trapping
  - ectoparasite-collection
  - flea-taxonomic-identification
  - literature-data-compilation
  - bipartite-network-analysis
  - null-model-randomization
  - patefield-randomization
  - complementary-specialization-analysis
  - kullback-leibler-specialisation
  - host-specificity-analysis
  - niche-partitioning-analysis
  - bray-curtis-dissimilarity
  - permutational-multivariate-analysis
  - network-visualization

# Input environmental database/ data sources
data_products:
  - borneo-flea-host-literature-database
  - mesilou-small-mammal-survey
  - mount-alap-small-mammal-survey

# Data produced or archived by this study  
research_datasets: []

projects:
  - borneo-small-mammal-ectoparasite-ecology

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
    object_id: maklarin-b-lakim

  - predicate: authored_by
    object_type: person
    object_id: jean-claude-beaucournu

  - predicate: authored_by
    object_type: organisation
    object_id: biodiversity-and-climate-research-centre

  - predicate: authored_by
    object_type: organisation
    object_id: sabah-parks

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-ulm

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-rennes

  - predicate: addresses
    object_type: concept
    object_id: flea-host-specificity

  - predicate: addresses
    object_type: concept
    object_id: niche-partitioning

  - predicate: addresses
    object_type: concept
    object_id: parasite-sharing

  - predicate: addresses
    object_type: concept
    object_id: complementary-specialization

  - predicate: addresses
    object_type: concept
    object_id: vector-borne-disease

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - parasite-ecology
  - disease-ecology
  - ecological-network-analysis
  - tropical-ecology
  - medical-entomology
  - veterinary-entomology
  - host-specificity
  - niche-partitioning
  - wildlife-epidemiology

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why can a flea species exhibit low host specificity but low niche partitioning at the same time?"
  - "How do treeshrew–squirrel flea networks differ from rat-associated flea networks?"
  - "What mechanisms could explain higher host specificity in lowland than montane forests?"
  - "Why are singleton interaction records difficult to interpret in ecological networks?"
  - "How do complementary specialization indices reduce, but not eliminate, sampling bias?"
  - "How might forest degradation alter flea-mediated pathogen transmission among wildlife and commensal mammals?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Flea–Small Mammal Host Specificity in Borneo | Wells et al. 2011"

# Purpose: Search description.
seo_description: >-
  Network analysis of Bornean flea–small mammal associations showing
  non-random specialization, broad host sharing among tree shrews and
  squirrels, and habitat-dependent differences in host specificity.

# Purpose: Search keywords.
keywords:
  - Borneo fleas
  - small mammals
  - host specificity
  - niche partitioning
  - flea–host network
  - Siphonaptera
  - ectoparasites
  - parasite sharing
  - complementary specialization
  - bipartite networks
  - treeshrews
  - squirrels
  - rats
  - Sigmactenus alticola
  - Tupaia montana
  - montane forest
  - lowland forest
  - vector-borne disease
  - wildlife epidemiology

# Purpose: Social sharing metadata.
social:
  title: "Flea–Small Mammal Networks in Bornean Rainforests"
  description: >-
    Wells and colleagues reveal non-random flea host sharing and contrasting
    network structure among rats, squirrels and tree shrews in Borneo.
  image: "images/images_publications/Flea-small-mammal-networks-borneo_Wells-2011.png"
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
  source_url: "https://doi.org/10.1111/j.1365-2915.2010.00940.x"

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
