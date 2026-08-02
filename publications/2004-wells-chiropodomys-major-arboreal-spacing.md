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
id: 2004-wells-chiropodomys-major-arboreal-spacing

# Purpose: Official publication title.
title: "Arboreal spacing patterns of the large pencil-tailed tree mouse, Chiropodomys major (Muridae), in a rainforest in Sabah, Malaysia"

# Purpose: Short display title.
short_title: "Arboreal spacing of Chiropodomys major"

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
year_published: 2004

# Purpose: Official publication date. # Format: YYYY-MM-DD
date: 2004-01-01

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
- Martin Pfeiffer
- Maklarin Bin Lakim
- Karl Eduard Linsenmair

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
      - university-of-wurzburg

  # Auhor position.
  - position: 2
    # Purpose: Full author name.
    name: "Martin Pfeiffer"
    # Purpose: Canonical BAHE person id.
    person_id: martin-pfeiffer
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-ulm

  # Auhor position.
  - position: 3
    # Purpose: Full author name.
    name: "Maklarin Bin Lakim"
    # Purpose: Canonical BAHE person id.
    person_id: maklarin-bin-lakim
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - sabah-parks

  # Auhor position.
  - position: 4
    # Purpose: Full author name.
    name: "Karl Eduard Linsenmair"
    # Purpose: Canonical BAHE person id.
    person_id: karl-eduard-linsenmair
    # Purpose: ORCID identifier.
    orcid: ""
    # Purpose: Affiliated organisation ids.
    affiliation_ids:
      - university-of-wurzburg

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

  martin-pfeiffer:
    - conceptualization
    - methodology
    - supervision
    - interpretation
    - writing-review-editing

  maklarin-bin-lakim:
    - investigation
    - resources
    - field-logistics
    - taxonomic-identification
    - writing-review-editing

  karl-eduard-linsenmair:
    - conceptualization
    - supervision
    - resources
    - interpretation
    - writing-review-editing

# =======
# Funding
# =======

# Purpose: Funding information.
project_funding:
  # Purpose: Funding organisation.
  - funder_name: "Arthur-von-Gwinner Stiftung"
    # Purpose: Canonical funder identifier.
    funder_id: arthur-von-gwinner-stiftung
    # Purpose: Grant identifier.
    grant_number: ""
    # Purpose: Official grant title.
    grant_title: ""

  - funder_name: "Deutsche Forschungsgemeinschaft"
    funder_id: dfg
    grant_number: ""
    grant_title: ""

# =======
# Bibliographic metadata
# =======

# Purpose: Journal or publication source.
journal_name: "Ecotropica"

# Purpose: Journal volume.
volume: "10"

# Purpose: Journal issue.
issue: "1"

# Purpose: Article pages or article number.
pages: "15-22"

# Purpose: Publisher.
publisher: "Society for Tropical Ecology"

# Purpose: Open-access availability. # Values: true, false
open_access: true

# Purpose: Publication licence. # Values: CC BY 4.0, CC BY-SA 4.0, CC0, All rights reserved
license: "All rights reserved"

# Purpose: Complete citation.
citation_full: >-
  Wells, K., Pfeiffer, M., Lakim, M. B., & Linsenmair, K. E. (2004).
  Arboreal spacing patterns of the large pencil-tailed tree mouse,
  Chiropodomys major (Muridae), in a rainforest in Sabah, Malaysia.
  Ecotropica, 10(1), 15-22.

# Purpose: Short citation.
citation_short: >-
  Wells et al. (2004), Ecotropica, 10(1), 15-22.

# Purpose: Persistent identifiers.
identifiers:
  # Purpose: Digital Object Identifier. # Format: 10.xxxx/xxxxx
  doi: ""

  # Purpose: Publisher landing page.
  publisher_url: "https://www.soctropecol.eu/publications/pdf/10-1/Wells%20et%20al.%20Ecotropica%202004.pdf"

  # Purpose: PubMed identifier.
  pmid: ""

  # Purpose: arXiv identifier.
  arxiv: ""

  # Purpose: OpenAlex identifier.
  openalex: ""

  # Purpose: Semantic Scholar identifier.
  semantic_scholar: ""

canonical_source_url: "https://www.soctropecol.eu/publications/pdf/10-1/Wells%20et%20al.%20Ecotropica%202004.pdf"
pdf: ""

# =====
# Abstract
# =====

# Purpose: Original published abstract.
# The original abstract is intentionally excluded because it is copyrighted.
abstract_original: ""

# Purpose: Source of abstract. # Values: publisher, author-manuscript
abstract_source: publisher

# Purpose: Indicates verbatim reproduction of original published abstract. # Values: true, false
abstract_verbatim: false

# Purpose: Display publicly. # Values: true, false
abstract_public_display: false

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
image: "/images/images_publications/Chiropodomys-major-arboreal-spacing_Wells-2004.png"

image_alt: >-
  Overlapping 90 percent core convex polygon home ranges of male and female
  Chiropodomys major in two subcanopy trapping areas in lowland rainforest at
  Kinabalu National Park, Sabah.

# Image caption
image_caption: >-
  Estimated home ranges of adult male and female Chiropodomys major in two
  rainforest subcanopy grids. Male ranges were larger on average than female
  ranges, and both sexes showed substantial overlap with same-sex and
  opposite-sex individuals.

image_license: "All rights reserved"
image_credit: "Wells et al. (2004)"
image_license_verified: false

# =======
# BAHE display controls
# =======

featured: false
show_on_publications_page: true
show_on_homepage: false

order: 20040101

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
      Chiropodomys major was the most frequently captured small-mammal species in the sampled subcanopy, with 275 captures of 40 individuals.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-02
    text: >
      Only two individuals of Chiropodomys major were captured in ground traps, confirming that the species was predominantly arboreal at the study site.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-03
    text: >
      Home-range estimates were calculated for 18 resident individuals with at least five captures using 90 percent core convex polygons.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-04
    text: >
      Male Chiropodomys major had significantly larger home ranges than females, averaging approximately 2,971 square metres compared with 1,580 square metres.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-05
    text: >
      Male home ranges varied from about 1,600 to 4,600 square metres, whereas female ranges varied from about 200 to 2,600 square metres.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-06
    text: >
      Home ranges of both sexes overlapped with those of same-sex and opposite-sex individuals, indicating that exclusive territories were not maintained.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-07
    text: >
      Male home ranges overlapped with more same-sex individuals than female home ranges did.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-08
    text: >
      Adult individuals persisted in the study area for longer than immature individuals.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-09
    text: >
      Chiropodomys major was recorded at 56 of 62 arboreal trap stations, demonstrating use of nearly the entire sampled subcanopy habitat.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-10
    text: >
      Capture frequency was positively associated with the presence of canopy gaps and lianas.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-11
    text: >
      Trap height was not correlated with the number of captured individuals or total captures.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-12
    text: >
      Some individuals used nesting or refuge sites near the ground, including tree hollows, dead stumps and holes near roots or logs.
    knowledge_type: empirical-result
    attributed_to: source-publication

  - id: statement-13
    text: >
      The broad overlap of adult ranges is consistent with a nonterritorial spacing system and permits a promiscuous mating structure.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-14
    text: >
      Scattered and unpredictable canopy resources may make exclusive territorial defence inefficient for Chiropodomys major.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-15
    text: >
      Branch connections, lianas and the ability to descend through vegetation likely facilitate agile movement through the structurally heterogeneous canopy.
    knowledge_type: interpretation
    attributed_to: source-publication

  - id: statement-16
    text: >
      More extensive telemetry and year-round sampling are needed to quantify three-dimensional home ranges, seasonal changes and vertical space use in arboreal small mammals.
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
  This study examined demography, home ranges and microhabitat use of the
  Bornean endemic tree mouse Chiropodomys major in the subcanopy of primary
  lowland rainforest at Kinabalu National Park. Individuals were live-trapped
  across two paired ground-and-canopy grids during seven trapping sessions.

# Knowledge-network summary.
knowledge_summary: >
  The study provides one of the first quantitative descriptions of spacing in
  a small arboreal tropical rodent. Males occupied larger ranges than females,
  but ranges of both sexes overlapped broadly, arguing against territoriality.
  The species used nearly all sampled arboreal habitat and was associated
  particularly with lianas and canopy gaps.

# Scientific or societal significance.
impact_statement: >
  Arboreal rodent spacing cannot be inferred reliably from terrestrial models
  because three-dimensional canopy structure and dispersed resources shape
  movement, overlap and social organisation.

# Non-technical summary.
plain_language_summary: >-
  The large pencil-tailed tree mouse was abundant in the rainforest canopy and
  rarely caught on the ground. Males used larger areas than females, but both
  sexes shared space with several other individuals. The mice were most often
  found where lianas and canopy gaps created connected pathways through the
  trees.

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
  - arboreal-spacing-patterns
  - home-range
  - canopy-microhabitat
  - territoriality
  - range-overlap
  - mating-system
  - liana-connectivity
  - canopy-gaps
  - vertical-habitat-use
  - persistence
  - rainforest-canopy
  - resource-dispersion
  - nonterritorial-space-use
  - arboreal-locomotion
  - tropical-rodent-ecology

# Purpose: Featured concepts. # Values: Concepts object ids in lowercase kebab-case
display_concepts:
  - arboreal-spacing-patterns
  - home-range
  - range-overlap
  - canopy-microhabitat
  - liana-connectivity
  - nonterritorial-space-use

# Purpose: Biological, ecological, social, or coupled systems studied. # Values: Study-system object ids in lowercase kebab-case
study_systems:
  - kinabalu-subcanopy-small-mammal-system
  - poring-hot-spring-rainforest
  - borneo-arboreal-rodent-community
  - southeast-asian-dipterocarp-rainforest

# Purpose: Biological taxa studied. # Values: Taxon object ids in lowercase kebab-case
focal_species:
  - chiropodomys-major

# Purpose: Research methods. # Values: Research methods object ids in lowercase kebab-case
methods:
  - arboreal-live-trapping
  - ground-live-trapping
  - pit-tagging
  - repeated-trapping-sessions
  - core-convex-polygon-home-range
  - microhabitat-profile-analysis
  - persistence-rate-estimation
  - spool-and-line-tracking
  - univariate-habitat-association
  - range-overlap-analysis

# Input environmental database/ data sources
data_products:
  - chiropodomys-major-capture-data
  - kinabalu-canopy-microhabitat-data
  - poring-arboreal-trapping-grid

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
    object_id: martin-pfeiffer

  - predicate: authored_by
    object_type: person
    object_id: maklarin-bin-lakim

  - predicate: authored_by
    object_type: person
    object_id: karl-eduard-linsenmair

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-ulm

  - predicate: authored_by
    object_type: organisation
    object_id: university-of-wurzburg

  - predicate: authored_by
    object_type: organisation
    object_id: sabah-parks

  - predicate: addresses
    object_type: concept
    object_id: arboreal-spacing-patterns

  - predicate: addresses
    object_type: concept
    object_id: home-range

  - predicate: addresses
    object_type: concept
    object_id: range-overlap

  - predicate: addresses
    object_type: concept
    object_id: canopy-microhabitat

  - predicate: involves
    object_type: taxon
    object_id: chiropodomys-major

# =======
# Teaching and discussion
# =======

# Purpose: Teaching applications.
teaching_uses:
  - mammalogy
  - canopy-ecology
  - behavioural-ecology
  - home-range-analysis
  - tropical-forest-ecology
  - mating-systems
  - microhabitat-selection
  - field-methods
  - spatial-ecology

# Purpose: Suggested discussion questions.
discussion_questions:
  - "Why might male Chiropodomys major have larger home ranges than females?"
  - "What evidence indicates that this species does not defend exclusive territories?"
  - "How could scattered canopy resources favour overlapping home ranges?"
  - "Why are lianas and canopy gaps important to an arboreal rodent?"
  - "What biases can arise when estimating home ranges from live-trapping grids?"
  - "How could radiotelemetry improve estimates of three-dimensional space use?"

# =======
# Search and discovery metadata
# =======

# Purpose: Search title.
seo_title: "Arboreal Spacing of Chiropodomys major in Sabah | Wells et al. 2004"

# Purpose: Search description.
seo_description: >-
  Canopy live-trapping study showing larger male home ranges, extensive range
  overlap and associations with lianas and gaps in the Bornean tree mouse
  Chiropodomys major.

# Purpose: Search keywords.
keywords:
  - Chiropodomys major
  - pencil-tailed tree mouse
  - Borneo
  - Sabah
  - canopy ecology
  - home range
  - arboreal rodent
  - spacing patterns
  - range overlap
  - territoriality
  - mating system
  - lianas
  - canopy gaps
  - Kinabalu National Park
  - tropical rainforest
  - live trapping
  - microhabitat use
  - persistence

# Purpose: Social sharing metadata.
social:
  title: "Arboreal Spacing of Chiropodomys major"
  description: >-
    Wells and colleagues show that the Bornean pencil-tailed tree mouse uses
    overlapping home ranges and favours connected canopy habitat with lianas
    and gaps.
  image: "images/images_publications/Chiropodomys-major-arboreal-spacing_Wells-2004.png"
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
  The original abstract is intentionally excluded. The article is subject to
  the publisher's copyright and reuse conditions. Reuse of article text or
  figures requires compliance with the licence and permissions stated by the
  publisher.

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
  source_url: "https://www.soctropecol.eu/publications/pdf/10-1/Wells%20et%20al.%20Ecotropica%202004.pdf"

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
