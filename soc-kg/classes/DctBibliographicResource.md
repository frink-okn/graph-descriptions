

# Class: Bibliographic Resource (dct_BibliographicResource)


_A book, article, or other documentary resource._






This class occurs 14 times.


URI: [dct:BibliographicResource](http://purl.org/dc/terms/BibliographicResource)






```mermaid
 classDiagram
    class DctBibliographicResource
    click DctBibliographicResource href "../DctBibliographicResource"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontology#Abstract
        click HttpsIdir.uta.eduSockg-ontology#Abstract href "../HttpsIdir.uta.eduSockg-ontology#Abstract"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontology#BookChapter
        click HttpsIdir.uta.eduSockg-ontology#BookChapter href "../HttpsIdir.uta.eduSockg-ontology#BookChapter"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontology#JournalArticle
        click HttpsIdir.uta.eduSockg-ontology#JournalArticle href "../HttpsIdir.uta.eduSockg-ontology#JournalArticle"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontology#PopularArticle
        click HttpsIdir.uta.eduSockg-ontology#PopularArticle href "../HttpsIdir.uta.eduSockg-ontology#PopularArticle"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontology#Proceedings
        click HttpsIdir.uta.eduSockg-ontology#Proceedings href "../HttpsIdir.uta.eduSockg-ontology#Proceedings"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontology#Report
        click HttpsIdir.uta.eduSockg-ontology#Report href "../HttpsIdir.uta.eduSockg-ontology#Report"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontology#Thesis
        click HttpsIdir.uta.eduSockg-ontology#Thesis href "../HttpsIdir.uta.eduSockg-ontology#Thesis"
      
      
```





## Inheritance
* **DctBibliographicResource**
    * [HttpsIdir.uta.eduSockg-ontology#Abstract](../classes/HttpsIdir.uta.eduSockg-ontology#Abstract.md)
    * [HttpsIdir.uta.eduSockg-ontology#BookChapter](../classes/HttpsIdir.uta.eduSockg-ontology#BookChapter.md)
    * [HttpsIdir.uta.eduSockg-ontology#JournalArticle](../classes/HttpsIdir.uta.eduSockg-ontology#JournalArticle.md)
    * [HttpsIdir.uta.eduSockg-ontology#PopularArticle](../classes/HttpsIdir.uta.eduSockg-ontology#PopularArticle.md)
    * [HttpsIdir.uta.eduSockg-ontology#Proceedings](../classes/HttpsIdir.uta.eduSockg-ontology#Proceedings.md)
    * [HttpsIdir.uta.eduSockg-ontology#Report](../classes/HttpsIdir.uta.eduSockg-ontology#Report.md)
    * [HttpsIdir.uta.eduSockg-ontology#Thesis](../classes/HttpsIdir.uta.eduSockg-ontology#Thesis.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#Abstract](../classes/HttpsIdir.uta.eduSockg-ontology#Abstract.md) | [https___idir.uta.edu_sockg_ontology#correspondingAuthor](../slots/https___idir.uta.edu_sockg_ontology#correspondingAuthor.md) | domain | [DctBibliographicResource](../classes/DctBibliographicResource.md) |
| [HttpsIdir.uta.eduSockg-ontology#BookChapter](../classes/HttpsIdir.uta.eduSockg-ontology#BookChapter.md) | [https___idir.uta.edu_sockg_ontology#correspondingAuthor](../slots/https___idir.uta.edu_sockg_ontology#correspondingAuthor.md) | domain | [DctBibliographicResource](../classes/DctBibliographicResource.md) |
| [HttpsIdir.uta.eduSockg-ontology#JournalArticle](../classes/HttpsIdir.uta.eduSockg-ontology#JournalArticle.md) | [https___idir.uta.edu_sockg_ontology#correspondingAuthor](../slots/https___idir.uta.edu_sockg_ontology#correspondingAuthor.md) | domain | [DctBibliographicResource](../classes/DctBibliographicResource.md) |
| [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) | [https___idir.uta.edu_sockg_ontology#cites](../slots/https___idir.uta.edu_sockg_ontology#cites.md) | any_of[range] | [DctBibliographicResource](../classes/DctBibliographicResource.md) |
| [HttpsIdir.uta.eduSockg-ontology#PopularArticle](../classes/HttpsIdir.uta.eduSockg-ontology#PopularArticle.md) | [https___idir.uta.edu_sockg_ontology#correspondingAuthor](../slots/https___idir.uta.edu_sockg_ontology#correspondingAuthor.md) | domain | [DctBibliographicResource](../classes/DctBibliographicResource.md) |
| [HttpsIdir.uta.eduSockg-ontology#Proceedings](../classes/HttpsIdir.uta.eduSockg-ontology#Proceedings.md) | [https___idir.uta.edu_sockg_ontology#correspondingAuthor](../slots/https___idir.uta.edu_sockg_ontology#correspondingAuthor.md) | domain | [DctBibliographicResource](../classes/DctBibliographicResource.md) |
| [HttpsIdir.uta.eduSockg-ontology#Report](../classes/HttpsIdir.uta.eduSockg-ontology#Report.md) | [https___idir.uta.edu_sockg_ontology#correspondingAuthor](../slots/https___idir.uta.edu_sockg_ontology#correspondingAuthor.md) | domain | [DctBibliographicResource](../classes/DctBibliographicResource.md) |
| [HttpsIdir.uta.eduSockg-ontology#Thesis](../classes/HttpsIdir.uta.eduSockg-ontology#Thesis.md) | [https___idir.uta.edu_sockg_ontology#correspondingAuthor](../slots/https___idir.uta.edu_sockg_ontology#correspondingAuthor.md) | domain | [DctBibliographicResource](../classes/DctBibliographicResource.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: dct_BibliographicResource
description: A book, article, or other documentary resource.
title: Bibliographic Resource
from_schema: okns:dc
source: http://purl.org/dc/terms/
class_uri: dct:BibliographicResource

```
</details>

### Induced

<details>

```yaml
name: dct_BibliographicResource
description: A book, article, or other documentary resource.
title: Bibliographic Resource
from_schema: okns:dc
source: http://purl.org/dc/terms/
class_uri: dct:BibliographicResource

```
</details>