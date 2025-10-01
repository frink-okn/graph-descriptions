

# Slot: Identifier (dct_identifier)


_Recommended practice is to identify the resource by means of a string conforming to an identification system. Examples include International Standard Book Number (ISBN), Digital Object Identifier (DOI), and Uniform Resource Name (URN).  Persistent identifiers should be provided as HTTP URIs._






This slot occurs 4880 times.


URI: [dct:identifier](http://purl.org/dc/terms/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit](../classes/HttpsIdir.uta.eduSockg-ontology#ExperimentalUnit.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#JournalArticle](../classes/HttpsIdir.uta.eduSockg-ontology#JournalArticle.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Site](../classes/HttpsIdir.uta.eduSockg-ontology#Site.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |  |  no  |







## Properties

* Range: [RdfsLiteral](../classes/RdfsLiteral.md)





## Comments

* description: An unambiguous reference to the resource within a given context.



## LinkML Source

<details>

```yaml
name: dct_identifier
description: Recommended practice is to identify the resource by means of a string
  conforming to an identification system. Examples include International Standard
  Book Number (ISBN), Digital Object Identifier (DOI), and Uniform Resource Name (URN).  Persistent
  identifiers should be provided as HTTP URIs.
title: Identifier
notes:
- No occurrences of this slot in the graph.
comments:
- 'description: An unambiguous reference to the resource within a given context.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:identifier
domain_of:
- https___idir.uta.edu_sockg-ontology#ExperimentalUnit
- https___idir.uta.edu_sockg-ontology#JournalArticle
- https___idir.uta.edu_sockg-ontology#Location
- https___idir.uta.edu_sockg-ontology#Site
- https___idir.uta.edu_sockg-ontology#Treatment
subproperty_of: dc_identifier
range: rdfs_Literal

```
</details>