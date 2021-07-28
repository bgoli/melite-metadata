## Identification
- Title: The MELITE metadata specification
- Creator: Brett G. Olivier [https://orcid.org/0000-0002-5293-5321], Vrije Universiteit Amsterdam [https://ror.org/008xxew50]
- Date: 2021-07-28 
- Publisher: Vrije Universiteit Amsterdam [https://ror.org/008xxew50]
- ResourceType: Dataset
- Rights: CC0 1.0 Universal
- Version: 1.0 beta

## Description
### More about the description
 A general description of a data collection. Be as detailed as you want, you may use almost all Markdown **except the ## subsection** in your *Description*. 

### More about MELITE
MELITE uses a restricted set of Markdown as a syntax: the subsection, bullet point, comma and url (`## - , []`) to defined metadata in a human writable way. Furthermore:

- Sections are defined as a single line of text beginning with `## `. All MELITE metadata files must, at least, include:
  - `## Identification`
  - `## Description`
- Optional section that is required for data publication or archiving:
  - `## Required for publication`
- Optional section(s) that are highly recomended:
  - `## Contributors`
  - `## Related identiers`
  - `## Optional information`
- Optional file end token indicating the end of the MELITE metadata definition.
  - `## End`
- Key, value pairs are defined as a bullet point ` - ` and separated with a ` : `
  - `- Title: The MELITE metadata specification`
- A Key may sometime require a list of values, these are separated with a ` , `
  - `- Creator: Brett G. Olivier, Vrije Universiteit Amsterdam`
- Optional external identifiers can be linked to a person or organisation using the url syntax `[hyperlink]`. Note an **is** relationship is implied between the subject text and the object URI/hyperlink. For example, in the case we are stating the **Vrije Universiteit Amsterdam is https://ror.org/008xxew50**.
  - `- Publisher: Vrije Universiteit Amsterdam [https://ror.org/008xxew50]`

All values in *Identifaction* and *Description* are required to be filled in for every dataset or data collection. The section *Required for publication* is optional except if the data collection is being submitted for archiving and/or publication, when it becomes required. The remaining sections are optional, albeit highly recommended. The description ends with the definition of one (or more) of the optional sections or `## End`.

### Defined value sets
Some keys have defined lists of values that they can take, for example **ResourceType** must be one of: 

```text
Audiovisual, Book, BookChapter, Collection, ComputationalNotebook, ConferencePaper, ConferenceProceeding, DataPaper, Dataset, Dissertation, Event, Image, InteractiveResource, Model, OutputManagementPlan, PeerReview, PhysicalObject, Preprint, Report, Service, Software, Sound, Standard, Text, Workflow, Other
```

See the detailed description of the minimal metadata specification on which MELITE is based here (restricted access) [https://docs.google.com/spreadsheets/d/1YZvXfmtK8FWILDZnYAI2627MFRFGtsth/edit#gid=1666451278].

## Required for publication
- PublicationYear: 2022
- Size: 20 kB
- Subject: metadata, datacite, VU minimal metadata definitions
- Identifier: DOI [DOI]

## Contributors
TODO

## Related identiers
TODO

## Optional information
- AlternateIdentifier: GitHub project [https://github.com/vu-rdm-tech/melite-metadata/]
- Format: UTF-8
- FundingReference: NWO DCC [https://www.nwo.nl/en/calls/local-digital-compentence-centres]
- GeoLocation: 52.335169, 4.861827
- Language: en
- RelatedItem: This forms part of the documentation series written by Brett and Peter.
