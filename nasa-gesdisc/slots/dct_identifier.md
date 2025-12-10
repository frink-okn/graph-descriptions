

# Slot: Identifier (dct_identifier)


_Recommended practice is to identify the resource by means of a string conforming to an identification system. Examples include International Standard Book Number (ISBN), Digital Object Identifier (DOI), and Uniform Resource Name (URN).  Persistent identifiers should be provided as HTTP URIs._






This slot occurs 142173 times.


URI: [dct:identifier](http://purl.org/dc/terms/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset.md) |  |  no  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication.md) |  |  no  |







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
- https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
- https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
subproperty_of: dc_identifier
range: rdfs_Literal

```
</details>