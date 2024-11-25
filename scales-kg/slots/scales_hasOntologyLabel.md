

# Slot: scales_hasOntologyLabel


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasOntologyLabel](http://schemas.scales-okn.org/rdf/scales#hasOntologyLabel)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesDocketEntry](../classes/ScalesDocketEntry.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| scales:DocketEntry/akd;;1:16-cr-00001_de0 scales:hasOntologyLabel scales:OntologyLabel/information |

## Comments

* 26816737 occurrences with subject type scales_DocketEntry and object type uri.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:hasOntologyLabel |
| native | scales-kg/:scales_hasOntologyLabel |




## LinkML Source

<details>
```yaml
name: scales_hasOntologyLabel
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 26816737 occurrences with subject type scales_DocketEntry and object type uri.
examples:
- value: scales:DocketEntry/akd;;1:16-cr-00001_de0 scales:hasOntologyLabel scales:OntologyLabel/information
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasOntologyLabel
alias: scales_hasOntologyLabel
domain_of:
- scales_DocketEntry
range: uri

```
</details>