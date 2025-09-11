

# Class: Bibliographic Resource (dct_BibliographicResource)


_A book, article, or other documentary resource._






This class occurs 14 times.


URI: [dct:BibliographicResource](http://purl.org/dc/terms/BibliographicResource)






```mermaid
 classDiagram
    class DctBibliographicResource
    click DctBibliographicResource href "../DctBibliographicResource"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontologyDocs#Abstract
        click HttpsIdir.uta.eduSockg-ontologyDocs#Abstract href "../HttpsIdir.uta.eduSockg-ontologyDocs#Abstract"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontologyDocs#BookChapter
        click HttpsIdir.uta.eduSockg-ontologyDocs#BookChapter href "../HttpsIdir.uta.eduSockg-ontologyDocs#BookChapter"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontologyDocs#JournalArticle
        click HttpsIdir.uta.eduSockg-ontologyDocs#JournalArticle href "../HttpsIdir.uta.eduSockg-ontologyDocs#JournalArticle"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontologyDocs#PopularArticle
        click HttpsIdir.uta.eduSockg-ontologyDocs#PopularArticle href "../HttpsIdir.uta.eduSockg-ontologyDocs#PopularArticle"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontologyDocs#Proceedings
        click HttpsIdir.uta.eduSockg-ontologyDocs#Proceedings href "../HttpsIdir.uta.eduSockg-ontologyDocs#Proceedings"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontologyDocs#Report
        click HttpsIdir.uta.eduSockg-ontologyDocs#Report href "../HttpsIdir.uta.eduSockg-ontologyDocs#Report"
      DctBibliographicResource <|-- HttpsIdir.uta.eduSockg-ontologyDocs#Thesis
        click HttpsIdir.uta.eduSockg-ontologyDocs#Thesis href "../HttpsIdir.uta.eduSockg-ontologyDocs#Thesis"
      
      
```





## Inheritance
* **DctBibliographicResource**
    * [HttpsIdir.uta.eduSockg-ontologyDocs#Abstract](../classes/HttpsIdir.uta.eduSockg-ontologyDocs#Abstract.md)
    * [HttpsIdir.uta.eduSockg-ontologyDocs#BookChapter](../classes/HttpsIdir.uta.eduSockg-ontologyDocs#BookChapter.md)
    * [HttpsIdir.uta.eduSockg-ontologyDocs#JournalArticle](../classes/HttpsIdir.uta.eduSockg-ontologyDocs#JournalArticle.md)
    * [HttpsIdir.uta.eduSockg-ontologyDocs#PopularArticle](../classes/HttpsIdir.uta.eduSockg-ontologyDocs#PopularArticle.md)
    * [HttpsIdir.uta.eduSockg-ontologyDocs#Proceedings](../classes/HttpsIdir.uta.eduSockg-ontologyDocs#Proceedings.md)
    * [HttpsIdir.uta.eduSockg-ontologyDocs#Report](../classes/HttpsIdir.uta.eduSockg-ontologyDocs#Report.md)
    * [HttpsIdir.uta.eduSockg-ontologyDocs#Thesis](../classes/HttpsIdir.uta.eduSockg-ontologyDocs#Thesis.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location.md) | [http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_cites](../slots/http___www.semanticweb.org_trash_ontologies_2025_5_untitled_ontology_278_cites.md) | any_of[range] | [DctBibliographicResource](../classes/DctBibliographicResource.md) |











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