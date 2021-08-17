## Identification
- Title: The MELITE metadata specification
- Creator: Brett G. Olivier (https://orcid.org/0000-0002-5293-5321)
- CreatorAffiliation: Systems Biology Lab, AIMMS, VU (https://doi.org/10.13039/501100001833)
- Date: 2021-07-28 
- Publisher: Vrije Universiteit Amsterdam (https://ror.org/008xxew50)
- ResourceType: Dataset
- Rights: CC0 1.0 Universal
- Version: 0.5 alpha

## Description
### More about the description
 A general description of a data collection. Be as detailed as you want, you may use almost all Markdown **with the exception of the H1 (# Heading 1) or H2 (## Heading 2)** elements in your *Description*. 

### More about MELITE
MELITE uses a restricted set of Markdown syntax: H2, unordered list and link (`## - (URI)`) to define metadata in a human writable way. Furthermore:

- Sections are defined as a single line of text beginning with `## `. All MELITE metadata files must, at least, include:
  - `## Identification`
  - `## Description`
- Optional section that is required for data publication or archiving:
  - `## Required for publication`
- Optional section(s) that are highly recomended:
  - `## Contributors`
  - `## Related identiers`
  - `## Optional information`
- Optional file end token indicating the end of the MELITE metadata definition, which allows arbitrary information to be stored after the end token.
  - `## End`
- Key-value pairs are defined as a line that begins with a bullet point ` - ` the key and a ` : ` with everything to the right until the end of the line  interpreted as the value (`- Key: value`):
  - `- Title: The MELITE metadata specification`
- Where a *value* has a related identifier (DOI, ORCID, ROR, etc.) that can be linked to a *value*, in a key-value pair, this should follow the *value* text:
  - `- CreatorAffiliation: Systems Biology Lab, AIMMS, VU (https://doi.org/10.13039/501100001833)`
- Optional external identifiers can be linked to a person or organisation using the link syntax `(link URI)`. Note an **is** relationship is implied between the subject text and the object URI/hyperlink. For example, in the case we are stating the **Vrije Universiteit Amsterdam is https://ror.org/008xxew50**.
  - `- Publisher: Vrije Universiteit Amsterdam (https://ror.org/008xxew50)`
- Some sections such as *Contributors* and *Related Identifiers* use a nested unordered list, where a subitem is defined using two spaces before bullet point `  -`:
``` 
- ContributorName: Brett Olivier (https://orcid.org/0000-0002-5293-5321) 
  - ContributorType: Researcher
```

All values in *Identifaction* and *Description* are required to be filled in for every dataset or data collection. The section *Required for publication* is optional except if the data collection is being submitted for archiving and/or publication, in which case it is required. The remaining sections are optional, albeit, highly recommended. The *Description* ends with the definition of one of the optional sections or `## End`.

See the detailed description of the minimal metadata specification on which MELITE is [based](https://yoda.vu.nl).

### Defined value sets
Certain keys such as *ResourceType*  and *ContributorType* have a defined set of values that they can take:

**ResourceType**: 
```text
Audiovisual, Book, BookChapter, Collection, ComputationalNotebook, ConferencePaper, ConferenceProceeding, DataPaper, Dataset, Dissertation, Event, Image, InteractiveResource, Model, OutputManagementPlan, PeerReview, PhysicalObject, Preprint, Report, Service, Software, Sound, Standard, Text, Workflow, Other
```
**ContributorType**
```text
ContactPerson, DataCollector, DataCurator, DataManager, Distributor, Editor, HostingInstitution, Producer, ProjectLeader, ProjectManager, ProjectMember, RegistrationAgency, RegistrationAuthority, RelatedPerson, Researcher, ResearchGroup, RightsHolder, Sponsor, Supervisor, WorkPackageLeader, Other
```
**RelatedIdentifierType**
```text
ARK, arXiv, bibcode, DOI, EAN13, EISSN, Handle, IGSN, ISBN, ISSN, ISTC, LISSN, LSID, PMID, PURL, UPC, URL, URN, w3id,
```

**RelationType**
```text
IsCitedBy, Cites, IsSupplementTo, IsSupplementedBy, IsContinuedBy, Continues, Describes, IsDescribedBy, HasMetadata, IsMetadataFor, HasVersion, IsVersionOf, IsNewVersionOf, IsPreviousVersionOf, IsPartOf, HasPart, IsPublishedIn, IsReferencedBy, References, IsDocumentedBy, Documents, IsCompiledBy, Compiles, IsVariantFormOf, IsOriginalFormOf, IsIdenticalTo, IsReviewedBy, Reviews, IsDerivedFrom, IsSourceOf, IsRequiredBy, Requires, Obsoletes, IsObsoletedBy
```

## Required for publication
- PublicationYear: 2022
- Size: 20 kB
- Subject: metadata datacite "VU minimal metadata"
- Identifier: DOI (URI)

## Contributors
- ContributorName: Brett G. Olivier (https://orcid.org/0000-0002-5293-5321)
  - ContributorType: Researcher
  - ContributorAffiliation: Vrije Universiteit Amsterdam (https://ror.org/008xxew50)
- ContributorName: Peter Vos
  - ContributorType: ProjectMember
  - ContributorAffiliation: Vrije Universiteit Amsterdam

## Related identiers
- RelatedIdentifier: 10.14454/3w3z-sa82 (https://doi.org/10.14454/3w3z-sa82)
  - relatedIdentifierType: DOI
  - relationType: IsDerivedFrom
- RelatedIdentifier: 10.14454/3w3z-sa82
  - relatedIdentifierType: DOI
  - relationType: IsVariantFormOf
- RelatedIdentifier: Document URL (https://github.com/vu-rdm-tech/melite-metadata/blob/main/melite-proposed.md)
  - relatedIdentifierType: URL
  - relationType: IsIdenticalTo

## Optional information
- AlternateIdentifier: GitHub project (https://github.com/vu-rdm-tech/melite-metadata/)
- Format: UTF-8
- FundingReference: NWO DCC (https://www.nwo.nl/en/calls/local-digital-compentence-centres)
- GeoLocation: 52.335169, 4.861827
- Language: en

## End

(C) Brett G. Olivier, Vrije Universiteit Amsterdam, Amsterdam, The Netherlands, 2021.
