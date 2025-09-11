

# Slot: Date Issued (dct_issued)


_Recommended practice is to describe the date, date/time, or period of time as recommended for the property Date, of which this is a subproperty._






This slot occurs 177 times.


URI: [dct:issued](http://purl.org/dc/terms/issued)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Report](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Report.md) |  |  no  |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BookChapter](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278BookChapter.md) |  |  no  |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278JournalArticle](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278JournalArticle.md) |  |  no  |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Abstract](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Abstract.md) |  |  no  |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Proceedings](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Proceedings.md) |  |  no  |
| [DctAgentClass](../classes/DctAgentClass.md) | A group of agents |  no  |
| [DcamVocabularyEncodingScheme](../classes/DcamVocabularyEncodingScheme.md) | An enumerated set of resources |  no  |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PopularArticle](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278PopularArticle.md) |  |  no  |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Thesis](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Thesis.md) |  |  no  |







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
- http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Abstract
- http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_BookChapter
- http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_JournalArticle
- http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_PopularArticle
- http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Proceedings
- http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Report
- http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Thesis
subproperty_of: dct_date
range: Any
any_of:
- range: date
- range: rdfs_Literal

```
</details>