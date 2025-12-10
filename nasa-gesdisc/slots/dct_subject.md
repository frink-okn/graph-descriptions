

# Slot: Subject (dct_subject)


_Recommended practice is to refer to the subject with a URI. If this is not possible or feasible, a literal value that identifies the subject may be provided. Both should preferably refer to a subject in a controlled vocabulary._






This slot occurs 8521 times.


URI: [dct:subject](http://purl.org/dc/terms/subject)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument.md) |  |  no  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform.md) |  |  no  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaProject](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaProject.md) |  |  no  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset.md) |  |  no  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataCenter](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataCenter.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)





## Comments

* description: A topic of the resource.



## LinkML Source

<details>

```yaml
name: dct_subject
description: Recommended practice is to refer to the subject with a URI. If this is
  not possible or feasible, a literal value that identifies the subject may be provided.
  Both should preferably refer to a subject in a controlled vocabulary.
title: Subject
notes:
- No occurrences of this slot in the graph.
comments:
- 'description: A topic of the resource.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:subject
domain_of:
- https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
- https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
- https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
- https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
- https___nasa-gesdisc.proto-okn.net_kg_schema_Project
subproperty_of: dc_subject
range: Any

```
</details>