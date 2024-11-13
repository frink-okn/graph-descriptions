

# Slot: rdfs_isDefinedBy


_TODO -- tell the world what this slot (predicate) describes._





URI: [rdfs:isDefinedBy](http://www.w3.org/2000/01/rdf-schema#isDefinedBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfsClass](../classes/RdfsClass.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [OwlOntology](../classes/OwlOntology.md)






## Examples

| Value |
| --- |
| rural:settlementtype/SettlementType rdfs:isDefinedBy rural:ontology |

## Comments

* 5 occurrences with subject type rdfs_Class and object type owl_Ontology.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rdfs:isDefinedBy |
| native | rural-kg/:rdfs_isDefinedBy |




## LinkML Source

<details>
```yaml
name: rdfs_isDefinedBy
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 5 occurrences with subject type rdfs_Class and object type owl_Ontology.
examples:
- value: rural:settlementtype/SettlementType rdfs:isDefinedBy rural:ontology
from_schema: rural-kg
rank: 1000
slot_uri: rdfs:isDefinedBy
alias: rdfs_isDefinedBy
domain_of:
- rdfs_Class
range: owl_Ontology

```
</details>