

# Slot: rdfs_label


_TODO -- tell the world what this slot (predicate) describes._





URI: [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfsClass](../classes/RdfsClass.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| rural:substanceabuse/SubstanceAbuse rdfs:label Substance Abuse |

## Comments

* 5 occurrences with subject type rdfs_Class and object type string.

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
| self | rdfs:label |
| native | rural-kg/:rdfs_label |




## LinkML Source

<details>
```yaml
name: rdfs_label
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 5 occurrences with subject type rdfs_Class and object type string.
examples:
- value: rural:substanceabuse/SubstanceAbuse rdfs:label Substance Abuse
from_schema: rural-kg
rank: 1000
slot_uri: rdfs:label
alias: rdfs_label
domain_of:
- rdfs_Class
range: string

```
</details>