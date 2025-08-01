

# Slot: domain (rdfs_domain)


_A domain of the subject property._






This slot occurs 2 times.


URI: [rdfs:domain](http://www.w3.org/2000/01/rdf-schema#domain)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfDatatypeProperty](../classes/RdfDatatypeProperty.md) |  |  no  |
| [OwlOntologyProperty](../classes/OwlOntologyProperty.md) | The class of ontology properties |  no  |







## Properties

* Range: [RdfsClass](../classes/RdfsClass.md)







## LinkML Source

<details>

```yaml
name: rdfs_domain
description: A domain of the subject property.
title: domain
from_schema: okns:owl-rdf-rdfs
source: http://www.w3.org/2000/01/rdf-schema#
domain: rdf_Property
slot_uri: rdfs:domain
domain_of:
- owl_OntologyProperty
- rdf_DatatypeProperty
range: rdfs_Class

```
</details>