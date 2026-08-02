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
id: 2007-wells-rainforest-logging-helminths-borneo

# Purpose: Official publication title.
title: "Impact of rain-forest logging on helminth assemblages in small mammals (Muridae, Tupaiidae) from Borneo"

# Purpose: Short display title.
short_title: "Rain-forest logging and helminths in Bornean small mammals"

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
date: 2007-01-01

# Purpose: BAHE object creation date. # Format: YYYY-MM-DD
date_created: 2026-07-26

# Purpose: BAHE object modification date.
# Format: YYYY-MM-DD
date_modified: 2026-07-26

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
- Lesley R. Smales
- Elisabeth K. V. Kalko
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
    orcid: ""
    # Purpose: Affiliated canonical organisation objects.
    affiliation_ids:
      - ulm-university

  # Author position.
  - position: 2
    # Purpose: Full author name.
    name: "Lesley R. Smales"
    # Purpose: Canonical BAHE person id.
    person_id: lesley-r-smales
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - central-queensland-university

  # Author position.
  - position: 3
    # Purpose: Full author name.
    name: "Elisabeth K. V. Kalko"
    # Purpose: Canonical BAHE person id.
    person_id: elisabeth-k-v-kalko
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - ulm-university
      - smithsonian-tropical-research-institute

  # Author position.
  - position: 4
    # Purpose: Full author name.
    name: "Martin Pfeiffer"
    # Purpose: Canonical BAHE person id.
    person_id: martin-pfeiffer
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - ulm-university

# =======
# Author contributions
# =======

# CRediT-style author roles.
author_contributions:
  konstans-wells:
    - conceptualization
    - methodology
    - data-curation
    - writing-original-draft
    - writing-review-editing
    - visualization

  menna-brown:
    - conceptualization
    - data-curation
    - writing-review-editing
  
  carmen-jochem:
    - writing-review-editing
  
  brian-garrod:  
    - conceptualization
    - data-curation
    - writing-review-editing
    
# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "German Academic Exchange Service"
    # Purpose: Canonical funder identifier.
    funder_id: german-academic-exchange-service
    # Purpose: Grant identifier.
    grant_number: ""
    # Purpose: Official grant title.
    grant_title: ""

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Journal of Tropical Ecology"

# Purpose: Journal volume.
volume: "23"

# Purpose: Journal issue.
issue: ""

# Purpose: Article pages or article number.
pages: "35-43"

# Purpose: Publisher.
publisher: "Cambridge University Press"

# Purpose: Open-access availability. # Values: true, false
open_access: false

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Smales, L. R., Kalko, E. K. V., & Pfeiffer, M. (2007).
  Impact of rain-forest logging on helminth assemblages in small mammals
  (Muridae, Tupaiidae) from Borneo. Journal of Tropical Ecology, 23, 35-43.
  https://doi.org/10.1017/S0266467406003804

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2007), Journal of Tropical Ecology, 23, 35-43.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: "10.1017/S0266467406003804"
  
  # Purpose: Publisher landing page.
  publisher_url: "https://doi.org/10.1017/S0266467406003804"
  
  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.  
  arxiv: ""

  # Purpose: OpenAlex identifier.  
  openalex: ""
  
  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://doi.org/10.1017/S0266467406003804"
pdf: "Wells_etal_2007_JTropEcol.pdf"

# =====
# Abstract
# =====

# Purpose: Original published abstract.
abstract_original: |-
  Parasites are ubiquitous in wild animals, with host-specific life histories considered as major determinants of prevalence and parasite assemblage patterns. It is predicted that habitat differences in logged rain forests influence population performances of small mammals and consequently may change the infection patterns of local animal populations with regard to endo- and ectoparasites. We investigated patterns of helminth species assemblages (Nematoda, Platyhelminthes) in two rat species (Leopoldamys sabanus, Niviventer cremoriventer) and two tree shrew species (Tupaia tana, T. longipes) in three logged and three unlogged rain forests in Borneo by examining 337 faecal samples with non-invasive faecal egg count (FEC). Nematode eggs prevailed in 95% of all samples with up to five (mean 1.9 ± 1.1) morphotypes. Whereas members of Strongylida were most prevalent in L. sabanus, T. tana and T. longipes, Spirurida dominated in N. cremoriventer that revealed at the same time the lowest average nematode prevalence and FEC. Cestode eggs were only found in L. sabanus and T. tana. Composition and abundance patterns of the parasitic helminth assemblages were influenced by logging. As hypothesized, species richness of nematode morphotypes and mean number of infections per host of T. longipes were larger in logged than in unlogged forest. In contrast, L. sabanus was more heavily infected with cestodes in unlogged than in logged forest and also revealed larger egg counts for strongylids and spirurids in unlogged forest. Our results suggest that forest degradation and altered environmental conditions influence helminth diversity and infection patterns of small mammals with contrasting trends among host species. The inconsistent logging-induced changes in helminth assemblages from different hosts indicate that specific sets of habitat-host-parasite interactions are uniquely influenced by the effects of logging. Consequently, predictions on changes of parasite diversity and prevalence with regard to habitat disturbance need to be based on the individual life histories of the hosts (and the parasites).

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
    news_source_1: ""
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

image_alt: ""

# Image caption  
image_caption: ""
  
image_license: "All rights reserved"
image_credit: ""
image_license_verified: false  
  

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20070101

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
      Rain-forest logging altered the composition and abundance of helminth assemblages in Bornean small mammals, but the direction and magnitude of change differed among host species.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Nematode eggs occurred in 95% of the 337 faecal samples, with Strongylida most prevalent in Leopoldamys sabanus, Tupaia tana and Tupaia longipes, while Spirurida dominated in Niviventer cremoriventer.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Tupaia longipes had greater nematode morphotype richness and more infections per host in logged than in unlogged forest.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Leopoldamys sabanus showed higher cestode prevalence and egg counts, and higher strongylid and spirurid egg counts, in unlogged than in logged forest.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Host habitat use, diet, mobility and exposure to intermediate hosts can mediate how forest disturbance affects parasite transmission and assemblage structure.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-06
    text: >
      Predictions about parasite diversity and infection under habitat disturbance should be based on the individual life histories of both hosts and parasites rather than assuming a uniform response.
    knowledge_type: recommendation
    attributed_to: source-publication

  - id: statement-07
    text: >
      Broader comparative research across more host species is needed to determine whether general patterns emerge in parasite responses to anthropogenic habitat disturbance.
    knowledge_type: knowledge-gap
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
  This empirical study compared gastrointestinal helminth assemblages in four small-mammal species across three logged and three unlogged rain forests in Sabah, Borneo, using non-invasive faecal egg counts from 337 samples. Logging effects were host-specific and multidirectional rather than uniform.

# Knowledge-network summary.
knowledge_summary: >
  The study demonstrates that anthropogenic forest disturbance can restructure host-parasite interactions through changes in habitat, microclimate, host performance, diet and transmission opportunities. Its central contribution is evidence that parasite responses to logging cannot be inferred from habitat disturbance alone because different host-parasite systems respond in contrasting ways.

# Scientific or societal significance.
impact_statement: >
  Forest degradation changes parasite diversity and infection risk in wildlife, but effects vary by host and parasite ecology. Conservation and disease-ecology assessments therefore require species-specific host-parasite evidence.

# Non-technical summary.  
plain_language_summary: >-
  The researchers compared parasitic worms in rats and tree shrews from logged and unlogged forests in Borneo. Logging did not produce one simple pattern: one tree-shrew species carried a richer set of nematodes in logged forest, while a rat species had heavier infections in unlogged forest. The results show that habitat disturbance affects each host-parasite combination differently.
  
# =======
# BAHE knowledge-network relationships
# =======

# Purpose: Canonical research themes. # Values: Canonical BAHE theme ids
research_themes:
  - ecological-interactions-system-dynamics
  - biodiversity-global-change
  - nature-society-sustainable-futures


# Purpose: Canonical concepts. # Values: concept ids
concepts:
  - rainforest-logging
  - habitat-disturbance
  - host-parasite-interactions
  - helminth-assemblages
  - parasite-diversity
  - infection-prevalence
  - faecal-egg-count
  - wildlife-disease-ecology
  - small-mammal-ecology
  - disturbance-ecology

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - rainforest-logging
  - host-parasite-interactions
  - helminth-assemblages
  - wildlife-disease-ecology

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - bornean-tropical-rainforest
  - logged-and-unlogged-rainforest
  - small-mammal-host-parasite-systems

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species: 
  - leopoldamys-sabanus
  - niviventer-cremoriventer
  - tupaia-tana
  - tupaia-longipes

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - live-trapping
  - non-invasive-faecal-sampling
  - faecal-egg-count
  - modified-flotation-method
  - mcmaster-method
  - parasite-morphotype-classification
  - species-accumulation-curves
  - chao2-richness-estimation
  - simpson-diversity-index
  - non-parametric-statistics

# Input environmental database/ data sources
data_products: []

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
    object_id: konstans-wells

  - predicate: authored_by
    object_type: person
    object_id: lesley-r-smales

  - predicate: authored_by
    object_type: person
    object_id: elisabeth-k-v-kalko

  - predicate: authored_by
    object_type: person
    object_id: martin-pfeiffer

  - predicate: addresses
    object_type: concept
    object_id: rainforest-logging

  - predicate: addresses
    object_type: concept
    object_id: host-parasite-interactions

  - predicate: studies
    object_type: study-system
    object_id: small-mammal-host-parasite-systems

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - disease-ecology
  - parasitology
  - tropical-ecology
  - disturbance-ecology
  - conservation-biology
  - wildlife-ecology
  - quantitative-ecology

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why did logging increase helminth richness in Tupaia longipes but reduce infection measures in Leopoldamys sabanus?"
  - "How might host habitat use and diet alter exposure to directly and indirectly transmitted helminths?"
  - "What are the strengths and limitations of using faecal egg counts and egg morphotypes to compare parasite assemblages?"
  - "How could changes in microclimate and arthropod communities after logging affect parasite transmission?"
  - "What additional sampling would be needed to identify general disturbance-response patterns across host species?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Rain-Forest Logging and Helminths in Bornean Small Mammals | Wells et al. 2007"

# Purpose: Search description.
seo_description: >-
  Empirical study of how rain-forest logging alters helminth diversity, prevalence and faecal egg counts in rats and tree shrews from Borneo.

# Purpose: Search keywords.
keywords:
  - rain-forest logging
  - Borneo
  - Sabah
  - helminths
  - parasite diversity
  - host-parasite interactions
  - small mammals
  - Muridae
  - Tupaiidae
  - faecal egg count
  - Strongylida
  - Spirurida
  - cestodes
  - habitat disturbance
  - wildlife disease ecology

# Purpose: Social sharing metadata.
social:
  title: "Rain-Forest Logging and Helminths in Bornean Small Mammals"
  description: >-
    Wells and colleagues show that logging alters helminth assemblages in Bornean rats and tree shrews through contrasting, host-specific responses.
  image: ""
  card: summary


# =======
# Attribution and reuse
# =======

# Purpose: Attribution guidance.
attribution_note: >
  This BAHE knowledge object summarises and contextualises the peer-reviewed publication for research, teaching and interdisciplinary synthesis. Scientific arguments and findings should be attributed to and cited from the original publication.

# Purpose: Reuse guidance.
license_note: >
  The article is copyrighted by Cambridge University Press. Reuse is subject to the publisher's terms and applicable copyright law.

# =======
# Provenance and curation
# =======

# Purpose: Editorial review metadata.
curation:
  # Purpose: curation status. # Values: unreviewed, in-review, reviewed, revision-required
  status: in-review
  reviewed_by: ""
  reviewed_on: ""

# Purpose: Source provenance.
provenance:
  # Purpose: Original source type. # Values: publisher-pdf, publisher-html, repository, author, 
  source_type:
    - publisher-pdf
  
  # Purpose: Original source URL.
  source_url: "https://doi.org/10.1017/S0266467406003804"

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
    claims: verified
    summaries: verified
    concept_classification: reviewed

---
