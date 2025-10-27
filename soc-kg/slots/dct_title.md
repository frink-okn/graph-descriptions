

# Slot: Title (dct_title)


_A name given to the resource._






This slot occurs 148 times.


URI: [dct:title](http://purl.org/dc/terms/title)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#Report](../classes/HttpsIdir.uta.eduSockg-ontology#Report.md) |  |  no  |
| [VaemGraphMetaData](../classes/VaemGraphMetaData.md) | "vaem:GraphMetaData" defines basic metadata for the registration and publishi... |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Abstract](../classes/HttpsIdir.uta.eduSockg-ontology#Abstract.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#PopularArticle](../classes/HttpsIdir.uta.eduSockg-ontology#PopularArticle.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Proceedings](../classes/HttpsIdir.uta.eduSockg-ontology#Proceedings.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Thesis](../classes/HttpsIdir.uta.eduSockg-ontology#Thesis.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#BookChapter](../classes/HttpsIdir.uta.eduSockg-ontology#BookChapter.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#JournalArticle](../classes/HttpsIdir.uta.eduSockg-ontology#JournalArticle.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)







## LinkML Source

<details>

```yaml
name: dct_title
description: A name given to the resource.
title: Title
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:title
domain_of:
- vaem_GraphMetaData
- https___idir.uta.edu_sockg-ontology#Abstract
- https___idir.uta.edu_sockg-ontology#BookChapter
- https___idir.uta.edu_sockg-ontology#JournalArticle
- https___idir.uta.edu_sockg-ontology#PopularArticle
- https___idir.uta.edu_sockg-ontology#Proceedings
- https___idir.uta.edu_sockg-ontology#Report
- https___idir.uta.edu_sockg-ontology#Thesis
subproperty_of: dc_title
range: Any
any_of:
- range: string
- range: rdfs_Literal

```
</details>