

# Slot: Identifier (dct_identifier)


_Recommended practice is to identify the resource by means of a string conforming to an identification system. Examples include International Standard Book Number (ISBN), Digital Object Identifier (DOI), and Uniform Resource Name (URN).  Persistent identifiers should be provided as HTTP URIs._






This slot occurs 4880 times.


URI: [dct:identifier](http://purl.org/dc/terms/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278JournalArticle](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278JournalArticle.md) |  |  no  |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Site.md) |  |  no  |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278ExperimentalUnit.md) |  |  no  |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Treatment.md) |  |  no  |
| [HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location](../classes/HttpWww.semanticweb.orgTrashOntologies20255Untitled-ontology-278Location.md) |  |  no  |







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
- http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_ExperimentalUnit
- http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_JournalArticle
- http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Location
- http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Site
- http___www.semanticweb.org_trash_ontologies_2025_5_untitled-ontology-278_Treatment
subproperty_of: dc_identifier
range: rdfs_Literal

```
</details>