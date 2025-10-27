

# Slot: Date Issued (dct_issued)


_Recommended practice is to describe the date, date/time, or period of time as recommended for the property Date, of which this is a subproperty._






This slot occurs 177 times.


URI: [dct:issued](http://purl.org/dc/terms/issued)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#Report](../classes/HttpsIdir.uta.eduSockg-ontology#Report.md) |  |  no  |
| [DcamVocabularyEncodingScheme](../classes/DcamVocabularyEncodingScheme.md) | An enumerated set of resources |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Abstract](../classes/HttpsIdir.uta.eduSockg-ontology#Abstract.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#PopularArticle](../classes/HttpsIdir.uta.eduSockg-ontology#PopularArticle.md) |  |  no  |
| [DctAgentClass](../classes/DctAgentClass.md) | A group of agents |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Proceedings](../classes/HttpsIdir.uta.eduSockg-ontology#Proceedings.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Thesis](../classes/HttpsIdir.uta.eduSockg-ontology#Thesis.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#BookChapter](../classes/HttpsIdir.uta.eduSockg-ontology#BookChapter.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#JournalArticle](../classes/HttpsIdir.uta.eduSockg-ontology#JournalArticle.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:date](http://www.w3.org/2001/XMLSchema#date)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)





## Comments

* description: Date of formal issuance of the resource.



## LinkML Source

<details>

```yaml
name: dct_issued
description: Recommended practice is to describe the date, date/time, or period of
  time as recommended for the property Date, of which this is a subproperty.
title: Date Issued
comments:
- 'description: Date of formal issuance of the resource.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:issued
domain_of:
- dcam_VocabularyEncodingScheme
- dct_AgentClass
- https___idir.uta.edu_sockg-ontology#Abstract
- https___idir.uta.edu_sockg-ontology#BookChapter
- https___idir.uta.edu_sockg-ontology#JournalArticle
- https___idir.uta.edu_sockg-ontology#PopularArticle
- https___idir.uta.edu_sockg-ontology#Proceedings
- https___idir.uta.edu_sockg-ontology#Report
- https___idir.uta.edu_sockg-ontology#Thesis
subproperty_of: dct_date
range: Any
any_of:
- range: date
- range: rdfs_Literal

```
</details>