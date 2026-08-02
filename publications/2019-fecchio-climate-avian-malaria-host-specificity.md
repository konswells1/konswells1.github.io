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
id: 2019-fecchio-climate-avian-malaria-host-specificity

# Purpose: Official publication title.
title: "Climate variation influences host specificity in avian malaria parasites"

# Purpose: Short display title.
short_title: "Climate and host specificity in avian malaria parasites"

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
year_published: 2019

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2019-03-01

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
- Alan Fecchio
- Konstans Wells
- Jeffrey A. Bell
- Vasyl V. Tkach
- Holly L. Lutz
- Jason D. Weckstein
- Sonya M. Clegg
- Nicholas J. Clark

# Purpose: Canonical BAHE author ids.
bahe_authors:
  - konstans-wells

# Purpose: Structured author metadata.
author_entities:
  # Purpose: Citation order.
  - position: 1
    # Purpose: Full author name.
    name: "Alan Fecchio"
    # Purpose: Canonical BAHE person id.
    person_id: alan-fecchio
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated canonical organisation objects.
    affiliation_ids:
      - universidade-federal-da-bahia

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
      - swansea-university

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Jeffrey A. Bell"
    # Purpose: Canonical BAHE person id.
    person_id: jeffrey-a-bell
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-north-dakota

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "Vasyl V. Tkach"
    # Purpose: Canonical BAHE person id.
    person_id: vasyl-v-tkach
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-north-dakota

  # Auhor position.
  - position: 5
    # Purpose: Full author name.
    name: "Holly L. Lutz"
    # Purpose: Canonical BAHE person id.
    person_id: holly-l-lutz
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-chicago
      - field-museum-of-natural-history

  # Auhor position.
  - position: 6
    # Purpose: Full author name.
    name: "Jason D. Weckstein"
    # Purpose: Canonical BAHE person id.
    person_id: jason-d-weckstein
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - academy-of-natural-sciences-of-drexel-university
      - drexel-university

  # Auhor position.
  - position: 7
    # Purpose: Full author name.
    name: "Sonya M. Clegg"
    # Purpose: Canonical BAHE person id.
    person_id: sonya-m-clegg
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-oxford

  # Auhor position.
  - position: 8
    # Purpose: Full author name.
    name: "Nicholas J. Clark"
    # Purpose: Canonical BAHE person id.
    person_id: nicholas-j-clark
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-queensland

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  alan-fecchio:
    - conceptualization
    - investigation
    - data-curation
    - writing-original-draft
    - writing-review-editing

  konstans-wells:
    - formal-analysis
    - methodology
    - visualization
    - interpretation
    - writing-review-editing

  jeffrey-a-bell:
    - investigation
    - resources
    - writing-review-editing

  vasyl-v-tkach:
    - investigation
    - resources
    - writing-review-editing

  holly-l-lutz:
    - investigation
    - resources
    - writing-review-editing

  jason-d-weckstein:
    - investigation
    - resources
    - writing-review-editing

  sonya-m-clegg:
    - investigation
    - resources
    - writing-review-editing

  nicholas-j-clark:
    - conceptualization
    - methodology
    - formal-analysis
    - writing-original-draft
    - writing-review-editing

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "U.S. National Science Foundation"
    # Purpose: Canonical funder identifier.
    funder_id: us-national-science-foundation
    # Purpose: Grant identifier.
    grant_number: "DEB-1503804; DEB-1120734"
    # Purpose: Official grant title.
    grant_title: ""

  - funder_name: "National Geographic Society"
    funder_id: national-geographic-society
    grant_number: "9383-13"
    grant_title: ""

  - funder_name: "Coordenação de Aperfeiçoamento de Pessoal de Nível Superior"
    funder_id: capes
    grant_number: ""
    grant_title: "PNPD postdoctoral scholarship"

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Ecology Letters"

# Purpose: Journal volume.
volume: "22"

# Purpose: Journal issue.
issue: "3"

# Purpose: Article pages or article number.
pages: "547-557"

# Purpose: Publisher.
publisher: "Wiley"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Fecchio, A., Wells, K., Bell, J. A., Tkach, V. V., Lutz, H. L.,
  Weckstein, J. D., Clegg, S. M., & Clark, N. J. (2019).
  Climate variation influences host specificity in avian malaria parasites.
  Ecology Letters, 22(3), 547-557.
  https://doi.org/10.1111/ele.13215

# Purpose: Short citation.
citation_short: >-
  Fecchio et al. (2019), Ecology Letters, 22(3), 547-557.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1111/ele.13215"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1111/ele.13215"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1111/ele.13215"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Parasites with low host specificity (e.g. infecting a large diversity of host species) are of special interest in disease ecology, as they are likely more capable of circumventing ecological or evolutionary barriers to infect new hosts than are specialist parasites. Yet for many parasites, host specificity is not fixed and can vary in response to environmental conditions. Using data on host associations for avian malaria parasites (Apicomplexa: Haemosporida), we develop a hierarchical model that quantifies this environmental dependency by partitioning host specificity variation into region- and parasite-level effects. Parasites were generally phylogenetic host specialists, infecting phylogenetically clustered subsets of available avian hosts. However, the magnitude of this specialisation varied biogeographically, with parasites exhibiting higher host specificity in regions with more pronounced rainfall seasonality and wetter dry seasons. Recognising the environmental dependency of parasite specialisation can provide useful leverage for improving predictions of infection risk in response to global climate change.

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
    figshare: "10.6084/m9.figshare.7464617.v1"
    dryad: ""
  preprint: ""
  supplementary_material: "https://onlinelibrary.wiley.com/doi/10.1111/ele.13215/suppinfo"

  news:
    university_story: ""
    science_daily: "https://www.sciencedaily.com/releases/2019/05/190501114619.html"
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
image: "/images/images_publications/Climate-host-specificity-avian-malaria_Fecchio-2019.png"

image_alt: >-
  Density plots of regional host-specificity estimates for avian malaria
  parasites arranged by decreasing minimum rainfall during the driest
  quarter, alongside parasite-level ecological and phylogenetic specificity
  estimates for Plasmodium and Haemoproteus lineages.

# Image caption  
image_caption: >-
  Regional and parasite-level variation in avian malaria host specificity.
  Lower regional coefficients indicate that infected host species are more
  similar than expected from local host pools and therefore represent greater
  host specialisation. Parasites were generally phylogenetic specialists, and
  regions with wetter dry seasons and stronger rainfall seasonality supported
  more specialised parasite communities.

image_license: "All rights reserved"
image_credit: "Fecchio et al. (2019)"
image_license_verified: false  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20190301


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
      Realised host specificity in avian malaria parasites varies among biogeographical regions and is therefore not a fixed parasite trait.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Most Plasmodium and Haemoproteus lineages infected phylogenetically clustered subsets of the avian hosts available within regional host pools.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Rainfall seasonality explained the largest proportion of regional variation in realised host specificity, with stronger seasonality associated with greater parasite specialisation.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Avian malaria parasites were more specialised in regions with wetter dry seasons, indicating that precipitation during climatically limiting periods influences host-range structure.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Regional variation in host specificity was robust to differences in sampling effort, host diversity and parasite richness.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Parasite-level specialisation was driven more strongly by host phylogenetic relatedness than by ecological similarity in diet and foraging habitat.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Parasite communities in Brazilian Amazonia, Peru, Malaysia and Melanesia were among the least specialised, whereas those in New Zealand, the Philippines and south-eastern Australia were more specialised relative to local host pools.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Seasonal rainfall may concentrate vectors and breeding birds in time and space, increasing transmission among a narrower subset of hosts and selecting for greater host specialisation.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-09
    text: >
      Hierarchical models that partition parasite- and region-level effects provide a framework for estimating geographically variable host specificity from observed host-association data.
    knowledge_type: methodological-proposition
    attributed_to: source-publication

  - id: statement-10
    text: >
      Climate-dependent host specificity should be incorporated into predictions of parasite host shifting and infectious disease emergence under global climate change.
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
  This study analysed host associations for 154 multi-host avian malaria
  parasite lineages sampled from 15,541 birds across ten biogeographical
  regions in South America and the Australia-Pacific. Hierarchical Bayesian
  models partitioned host-specificity variation into parasite- and
  region-level components and tested climatic predictors.

# Knowledge-network summary.
knowledge_summary: >
  The study establishes that realised host specificity is environmentally
  contingent rather than an invariant parasite property. Most avian malaria
  parasites infected phylogenetically clustered subsets of available hosts,
  but the strength of this specialisation varied geographically. Rainfall
  seasonality and minimum rainfall during the driest quarter were the dominant
  regional predictors, suggesting that climate-mediated variation in vector
  activity, host aggregation and encounter opportunity shapes parasite host
  ranges.

# Scientific or societal significance.
impact_statement: >
  Climate-sensitive variation in parasite host specificity changes the
  likelihood of host shifting and should be incorporated into forecasts of
  disease emergence under future environmental change.

# Non-technical summary.  
plain_language_summary: >-
  Avian malaria parasites do not infect the same breadth of bird species
  everywhere. Most were restricted to related groups of birds, but this
  restriction was stronger in regions with more seasonal rainfall and wetter
  dry seasons. The findings show that climate can alter how specialised a
  parasite appears and may therefore influence its capacity to infect new
  host species.  

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
  - host-specificity
  - realised-host-specificity
  - parasite-host-shifting
  - avian-malaria
  - climate-variation
  - rainfall-seasonality
  - dry-season-rainfall
  - phylogenetic-host-specialisation
  - ecological-host-specialisation
  - ecological-fitting
  - parasite-emergence
  - biogeographical-variation
  - vector-borne-disease
  - host-range-expansion
  - climate-change-disease-risk

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - host-specificity
  - avian-malaria
  - climate-variation
  - rainfall-seasonality
  - phylogenetic-host-specialisation
  - parasite-host-shifting

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - avian-malaria-host-parasite-system
  - south-american-bird-communities
  - australia-pacific-bird-communities
  - vector-borne-wildlife-disease

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - aves
  - plasmodium
  - haemoproteus

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - hierarchical-bayesian-modelling
  - markov-chain-monte-carlo
  - gibbs-variable-selection
  - host-association-analysis
  - phylogenetic-distance-analysis
  - ecological-distance-analysis
  - gower-distance
  - biogeographical-clustering
  - lasso-variable-selection
  - leave-one-out-cross-validation
  - polymerase-chain-reaction
  - cytochrome-b-barcoding

# Input environmental database/ data sources
data_products:
  - worldclim
  - birdlife-international-range-maps
  - birdtree
  - eltontraits
  - malavi
  - genbank

# Data produced or archived by this study  
research_datasets: []

projects: []

# =======
# Typed graph relationships
# =======

# Purpose: Explicit knowledge graph relationships.
relationships:
  - predicate: authored_by
    object_type: person
    object_id: alan-fecchio

  - predicate: authored_by
    object_type: person
    object_id: konstans-wells

  - predicate: authored_by
    object_type: person
    object_id: jeffrey-a-bell

  - predicate: authored_by
    object_type: person
    object_id: vasyl-v-tkach

  - predicate: authored_by
    object_type: person
    object_id: holly-l-lutz

  - predicate: authored_by
    object_type: person
    object_id: jason-d-weckstein

  - predicate: authored_by
    object_type: person
    object_id: sonya-m-clegg

  - predicate: authored_by
    object_type: person
    object_id: nicholas-j-clark

  - predicate: authored_by
    object_type: organisation
    object_id: swansea-university

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-queensland

  - predicate: uses
    object_type: data-product
    object_id: worldclim

  - predicate: uses
    object_type: data-product
    object_id: birdlife-international-range-maps

  - predicate: uses
    object_type: data-product
    object_id: birdtree

  - predicate: addresses
    object_type: concept
    object_id: host-specificity

  - predicate: addresses
    object_type: concept
    object_id: parasite-host-shifting

  - predicate: addresses
    object_type: concept
    object_id: rainfall-seasonality

  - predicate: addresses
    object_type: concept
    object_id: phylogenetic-host-specialisation

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - disease-ecology
  - parasite-ecology
  - avian-malaria
  - climate-change-biology
  - host-parasite-interactions
  - biogeography
  - phylogenetic-comparative-methods
  - hierarchical-bayesian-modelling
  - ecological-fitting

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why should realised host specificity be treated as geographically variable rather than as a fixed parasite trait?"
  - "How can rainfall seasonality alter encounter rates among vectors, parasites and potential avian hosts?"
  - "Why might phylogenetic relatedness constrain host range more strongly than ecological similarity?"
  - "How does comparison with regional potential-host pools change interpretation of parasite specialisation?"
  - "What mechanisms could explain greater host specialisation in regions with wetter dry seasons?"
  - "How might climate change alter the emergence potential of multi-host avian malaria parasites?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Climate Variation and Avian Malaria Host Specificity | Fecchio et al. 2019"

# Purpose: Search description.
seo_description: >-
  Study showing that avian malaria parasites are generally phylogenetic host
  specialists and that rainfall seasonality and dry-season rainfall influence
  regional variation in realised host specificity.

# Purpose: Search keywords.
keywords:
  - avian malaria
  - host specificity
  - realised host specificity
  - parasite specialisation
  - parasite host shifting
  - rainfall seasonality
  - dry-season rainfall
  - climate change
  - Plasmodium
  - Haemoproteus
  - phylogenetic host specificity
  - ecological host specificity
  - ecological fitting
  - vector-borne disease
  - disease emergence
  - hierarchical Bayesian model
  - biogeography
  - host range expansion

# Purpose: Social sharing metadata.
social:
  title: "Climate Variation Influences Avian Malaria Host Specificity"
  description: >-
    Fecchio and colleagues show that rainfall seasonality and dry-season
    rainfall shape regional variation in avian malaria parasite specialisation.
  image: "images/images_publications/Climate-host-specificity-avian-malaria_Fecchio-2019.png"
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
  source_url: "https://doi.org/10.1111/ele.13215"

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
