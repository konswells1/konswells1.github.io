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
id: 2012-wells-dog-ectoparasites-borneo

# Purpose: Official publication title.
title: "Ectoparasite infestation patterns of domestic dogs in suburban and rural areas in Borneo"

# Purpose: Short display title.
short_title: "Dog ectoparasites across rural–suburban Borneo"

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
date: 2012-04-18

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
- Jean-Claude Beaucournu
- Lance A. Durden
- Trevor N. Petney
- Maklarin B. Lakim
- Robert B. O’Hara

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
      - university-of-ulm
      - sabah-parks

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Jean-Claude Beaucournu"
    # Purpose: Canonical BAHE person id.
    person_id: jean-claude-beaucournu
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - universite-de-rennes

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Lance A. Durden"
    # Purpose: Canonical BAHE person id.
    person_id: lance-a-durden
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - georgia-southern-university

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "Trevor N. Petney"
    # Purpose: Canonical BAHE person id.
    person_id: trevor-n-petney
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - karlsruhe-institute-of-technology

  # Auhor position.
  - position: 5
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
  - position: 6
    # Purpose: Full author name.
    name: "Robert B. O’Hara"
    # Purpose: Canonical BAHE person id.
    person_id: robert-b-ohara
    # Purpose: ORCID identifier.
    orcid: "0000-0001-9737-3724"
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - biodiversity-and-climate-research-centre

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

  jean-claude-beaucournu:
    - taxonomic-identification
    - resources
    - interpretation
    - writing-review-editing

  lance-a-durden:
    - taxonomic-identification
    - resources
    - interpretation
    - writing-review-editing

  trevor-n-petney:
    - taxonomic-identification
    - resources
    - interpretation
    - writing-review-editing

  maklarin-b-lakim:
    - investigation
    - resources
    - field-logistics
    - writing-review-editing

  robert-b-ohara:
    - methodology
    - formal-analysis
    - supervision
    - interpretation
    - writing-review-editing

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "Landesoffensive zur Entwicklung wissenschaftlich-ökonomischer Exzellenz"
    # Purpose: Canonical funder identifier.
    funder_id: loewe-hesse
    # Purpose: Grant identifier.
    grant_number: ""
    # Purpose: Official grant title.
    grant_title: "Biodiversity and Climate Research Centre"

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Parasitology Research"

# Purpose: Journal volume.
volume: "111"

# Purpose: Journal issue.
issue: "2"

# Purpose: Article pages or article number.
pages: "909-919"

# Purpose: Publisher.
publisher: "Springer"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Beaucournu, J.-C., Durden, L. A., Petney, T. N.,
  Lakim, M. B., & O’Hara, R. B. (2012). Ectoparasite infestation
  patterns of domestic dogs in suburban and rural areas in Borneo.
  Parasitology Research, 111(2), 909-919.
  https://doi.org/10.1007/s00436-012-2917-7

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2012), Parasitology Research, 111(2), 909-919.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1007/s00436-012-2917-7"

  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1007/s00436-012-2917-7"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1007/s00436-012-2917-7"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Domestic dogs, Canis lupus, have been one of the longest companions of humans and have introduced their own menagerie of parasites and pathogens into this relationship. Here, we investigate the parasitic load of 212 domestic dogs with fleas (Siphonaptera), chewing lice (Phthiraptera), and ticks (Acarina) along a gradient from rural areas with near-natural forest cover to suburban areas in Northern Borneo (Sabah, Malaysia). We used a spatially-explicit hierarchical Bayesian model that allowed us to impute missing data and to consider spatial structure in modelling dog infestation probability and parasite density. We collected a total of 1,968 fleas of two species, Ctenocephalides orientis and Ctenocephalides felis felis, from 195 dogs (prevalence, 92%). Flea density was higher on dogs residing in houses made of bamboo or corrugated metal (increase of 40% from the average) compared to timber or stone/compound houses. Host-dependent and landscape-level environmental variables and spatial structure only had a weak explanatory power. We found adults of the invasive chewing louse Heterodoxus spiniger on 42 dogs (20%). The effect of housing conditions was opposite to those for fleas; lice were only found on dogs residing in stone or timber houses. We found ticks of the species Rhipicephalus sanguineus as well as Haemaphysalis bispinosa group, Haemaphysalis cornigera, Haemaphysalis koenigsbergi, and Haemaphysalis semermis on 36 dogs (17%). The most common tick species was R. sanguineus, recorded from 23 dogs. Tick infestations were highest on dogs using both plantation and forest areas (282% increase in overall tick density of dogs using all habitat types). The infestation probability of dogs with lice and ticks decreased with elevation, most infestations occurred below 800 m above sea level. However, the density of lice and ticks revealed no spatial structure; infestation probability of dogs with these two groups revealed considerable autocorrelation. Our study shows that environmental conditions on the house level appeared to be more influential on flea and lice density whereas tick density was also influenced by habitat use. Infestation of dogs with Haemaphysalis ticks identified an important link between dogs and forest wildlife for potential pathogen transmission.

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
  supplementary_material: "https://doi.org/10.1007/s00436-012-2917-7"

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
image: "/images/images_publications/Dog-ectoparasites-borneo_Wells-2012.jpg"

image_alt: >-
  Three spatial maps showing modelled flea, louse and tick densities on
  domestic dogs sampled across Sabah, northern Borneo. Circle size represents
  posterior ectoparasite density at each location, while background points
  mark all dog sampling sites.

# Image caption  
image_caption: >-
  Spatial distribution of flea, louse and tick densities on domestic dogs
  across suburban and rural Sabah. Fleas were widespread, whereas lice and
  ticks were more spatially clustered. The maps illustrate contrasting
  infestation patterns among ectoparasite groups and provide the spatial
  context for analysing household, host and landscape drivers.

image_license: "All rights reserved"
image_credit: "Wells et al. (2012)"
image_license_verified: false  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20120418

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
      Fleas infested 92% of sampled domestic dogs in Sabah, making them the most prevalent ectoparasite group in the study.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Ctenocephalides orientis and Ctenocephalides felis felis were the two flea species identified from domestic dogs, and both species frequently co-occurred on the same hosts.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Flea density was higher on dogs living in bamboo or corrugated-metal housing and lower on dogs associated with stone or compound housing.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Smaller dogs carried higher flea densities, whereas forest cover, human population density and other landscape-scale variables had weak explanatory power.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      The invasive chewing louse Heterodoxus spiniger infested 20% of sampled dogs and was recorded only from dogs associated with stone or timber houses.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Tick infestation occurred on 17% of sampled dogs and included Rhipicephalus sanguineus and four Haemaphysalis taxa.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Dogs using both plantations and forests had an estimated 282% increase in overall tick density relative to the average dog.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Louse and tick infestation probabilities declined with elevation, with most infestations recorded below approximately 800 m above sea level.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-09
    text: >
      Spatial autocorrelation explained substantial variation in the probability of louse and tick infestation but little variation in ectoparasite density among infested dogs.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-10
    text: >
      Household-scale environmental conditions were more influential for flea and louse density than broad landscape-scale variables.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-11
    text: >
      Overlap between dog-associated Haemaphysalis ticks and ticks recorded from forest wildlife identifies domestic dogs as potential bridge hosts for tick-borne pathogen transmission.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-12
    text: >
      Studies of companion-animal ectoparasites in rapidly changing tropical landscapes should integrate host behaviour, housing, wildlife contact and land-use change.
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
  This field study examined fleas, lice and ticks on 212 domestic dogs across
  suburban and rural landscapes in Sabah, Malaysia. Spatially explicit
  hierarchical Bayesian models evaluated host, household, habitat and
  landscape predictors of infestation probability and parasite density.

# Knowledge-network summary.
knowledge_summary: >
  The study shows that different ectoparasite groups respond to distinct
  ecological scales. Flea and louse burdens were associated mainly with
  housing conditions, whereas tick density depended more strongly on dog
  habitat use and exposure to plantations and forests. Spatial clustering and
  elevational effects further shaped infestation probability, while the
  presence of wildlife-associated Haemaphysalis ticks highlighted possible
  transmission links across domestic-animal and wildlife systems.

# Scientific or societal significance.
impact_statement: >
  Domestic dogs can connect household, plantation and forest parasite cycles,
  making local housing, movement behaviour and wildlife contact important for
  ectoparasite management and zoonotic disease surveillance.

# Non-technical summary.  
plain_language_summary: >-
  Most dogs carried fleas, while fewer had lice or ticks. Flea and louse
  burdens differed with housing conditions, but dogs that entered plantations
  and forests carried more ticks. Some tick species also infest wild mammals,
  suggesting that dogs may help connect wildlife and human-associated disease
  cycles.  

# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - one-health-disease-ecology
  - ecological-interactions-system-dynamics
  - biodiversity-global-change
  - quantitative-ecology-modelling

# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - dog-ectoparasites
  - flea-infestation
  - louse-infestation
  - tick-infestation
  - domestic-animal-wildlife-interface
  - bridge-hosts
  - household-environment
  - habitat-use
  - spatial-epidemiology
  - elevational-gradients
  - companion-animal-health
  - zoonotic-pathogen-transmission
  - land-use-change
  - invasive-ectoparasites
  - one-health

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - dog-ectoparasites
  - domestic-animal-wildlife-interface
  - bridge-hosts
  - household-environment
  - habitat-use
  - zoonotic-pathogen-transmission

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - sabah-domestic-dog-ectoparasite-system
  - suburban-rural-borneo-gradient
  - domestic-dog-wildlife-interface
  - companion-animal-household-landscape-system

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - canis-lupus-familiaris
  - ctenocephalides-orientis
  - ctenocephalides-felis-felis
  - heterodoxus-spiniger
  - rhipicephalus-sanguineus
  - haemaphysalis-bispinosa-group
  - haemaphysalis-cornigera
  - haemaphysalis-koenigsbergi
  - haemaphysalis-semermis

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - domestic-dog-examination
  - standardized-flea-combing
  - ectoparasite-collection
  - morphological-taxonomic-identification
  - household-questionnaire
  - spatially-explicit-hierarchical-bayesian-modelling
  - poisson-regression
  - logistic-regression
  - missing-data-imputation
  - markov-chain-monte-carlo
  - spatial-random-effects
  - variance-partitioning
  - gis-landscape-analysis

# Input environmental database/ data sources
data_products:
  - globcover-2009
  - landscan-2007
  - handheld-gps-sampling-data
  - sabah-dog-ectoparasite-survey

# Data produced or archived by this study  
research_datasets: []

projects:
  - borneo-domestic-animal-wildlife-parasite-interface

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
    object_id: jean-claude-beaucournu

  - predicate: authored_by
    object_type: person
    object_id: lance-a-durden

  - predicate: authored_by
    object_type: person
    object_id: trevor-n-petney

  - predicate: authored_by
    object_type: person
    object_id: maklarin-b-lakim

  - predicate: authored_by
    object_type: person
    object_id: robert-b-ohara

  - predicate: authored_by
    object_type: organisation
    object_id: biodiversity-and-climate-research-centre

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-ulm

  - predicate: authored_by
    object_type: organisation
    object_id: sabah-parks

  - predicate: authored_by
    object_type: organisation
    object_id: georgia-southern-university

  - predicate: authored_by
    object_type: organisation
    object_id: karlsruhe-institute-of-technology

  - predicate: uses
    object_type: data-product
    object_id: globcover-2009

  - predicate: uses
    object_type: data-product
    object_id: landscan-2007

  - predicate: addresses
    object_type: concept
    object_id: dog-ectoparasites

  - predicate: addresses
    object_type: concept
    object_id: domestic-animal-wildlife-interface

  - predicate: addresses
    object_type: concept
    object_id: bridge-hosts

  - predicate: addresses
    object_type: concept
    object_id: zoonotic-pathogen-transmission

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - one-health
  - veterinary-parasitology
  - disease-ecology
  - companion-animal-health
  - spatial-epidemiology
  - tropical-parasitology
  - wildlife-domestic-animal-interfaces
  - hierarchical-bayesian-modelling
  - land-use-and-disease

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why did household conditions explain flea and louse densities better than landscape-scale variables?"
  - "How can dogs that use both plantation and forest habitats acquire more ticks?"
  - "What mechanisms could explain the decline in louse and tick infestation with elevation?"
  - "Why can infestation probability show strong spatial autocorrelation while parasite density does not?"
  - "How do shared Haemaphysalis ticks link domestic dogs with forest wildlife?"
  - "What additional sampling would be required to assess pathogen transmission rather than ectoparasite infestation alone?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Dog Ectoparasites Across Rural–Suburban Borneo | Wells et al. 2012"

# Purpose: Search description.
seo_description: >-
  Study of fleas, lice and ticks on domestic dogs in Sabah showing contrasting
  effects of housing, habitat use, elevation and spatial structure across a
  rural–suburban gradient.

# Purpose: Search keywords.
keywords:
  - domestic dogs
  - dog ectoparasites
  - Borneo
  - Sabah
  - fleas
  - chewing lice
  - ticks
  - Ctenocephalides orientis
  - Ctenocephalides felis
  - Heterodoxus spiniger
  - Rhipicephalus sanguineus
  - Haemaphysalis
  - household environment
  - habitat use
  - wildlife–domestic animal interface
  - bridge host
  - spatial epidemiology
  - zoonotic disease
  - One Health

# Purpose: Social sharing metadata.
social:
  title: "Dog Ectoparasites Across Rural–Suburban Borneo"
  description: >-
    Wells and colleagues show how housing, habitat use and elevation shape
    flea, louse and tick infestations of domestic dogs in Sabah.
  image: "images/images_publications/Dog-ectoparasites-borneo_Wells-2012.png"
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
  source_url: "https://doi.org/10.1007/s00436-012-2917-7"

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
