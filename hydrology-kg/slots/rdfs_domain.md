

# Slot: domain (rdfs_domain)


_A domain of the subject property._






This slot occurs 10 times.


URI: [rdfs:domain](http://www.w3.org/2000/01/rdf-schema#domain)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfDatatypeProperty](../classes/RdfDatatypeProperty.md) |  |  no  |
| [OwlDataProperty](../classes/OwlDataProperty.md) |  |  no  |







## Properties

* Range: [RdfsClass](../classes/RdfsClass.md)







## LinkML Source

<details>

```yaml
name: rdfs_domain
description: A domain of the subject property.
title: domain
notes:
- No occurrences of this slot in the graph.
from_schema: okns:owl-rdf-rdfs
source: http://www.w3.org/2000/01/rdf-schema#
domain: rdf_Property
slot_uri: rdfs:domain
domain_of:
- rdf_DatatypeProperty
- owl_DataProperty
range: rdfs_Class

```
</details>