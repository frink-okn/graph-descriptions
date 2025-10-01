

# Slot: Creator (dct_creator)


_Recommended practice is to identify the creator with a URI.  If this is not possible or feasible, a literal value that identifies the creator may be provided._






This slot occurs 173 times.


URI: [dct:creator](http://purl.org/dc/terms/creator)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#Abstract](../classes/HttpsIdir.uta.eduSockg-ontology#Abstract.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#PopularArticle](../classes/HttpsIdir.uta.eduSockg-ontology#PopularArticle.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#JournalArticle](../classes/HttpsIdir.uta.eduSockg-ontology#JournalArticle.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Thesis](../classes/HttpsIdir.uta.eduSockg-ontology#Thesis.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#BookChapter](../classes/HttpsIdir.uta.eduSockg-ontology#BookChapter.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Proceedings](../classes/HttpsIdir.uta.eduSockg-ontology#Proceedings.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Report](../classes/HttpsIdir.uta.eduSockg-ontology#Report.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)





## Comments

* description: An entity responsible for making the resource.



## LinkML Source

<details>

```yaml
name: dct_creator
description: Recommended practice is to identify the creator with a URI.  If this
  is not possible or feasible, a literal value that identifies the creator may be
  provided.
title: Creator
notes:
- No occurrences of this slot in the graph.
comments:
- 'description: An entity responsible for making the resource.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
exact_mappings:
- http://xmlns.com/foaf/0.1/maker
slot_uri: dct:creator
domain_of:
- https___idir.uta.edu_sockg-ontology#Abstract
- https___idir.uta.edu_sockg-ontology#BookChapter
- https___idir.uta.edu_sockg-ontology#JournalArticle
- https___idir.uta.edu_sockg-ontology#PopularArticle
- https___idir.uta.edu_sockg-ontology#Proceedings
- https___idir.uta.edu_sockg-ontology#Report
- https___idir.uta.edu_sockg-ontology#Thesis
subproperty_of: dct_contributor
range: Any

```
</details>