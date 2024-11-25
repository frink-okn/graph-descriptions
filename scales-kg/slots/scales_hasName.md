

# Slot: scales_hasName


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasName](http://schemas.scales-okn.org/rdf/scales#hasName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCourt](../classes/ScalesCourt.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ScalesAgent](../classes/ScalesAgent.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| scales:Agent/akd;;1:16-cr-00001_a0 scales:hasName SCALES-Party-Hash-01169B980BF3557176ECC743C5841A32 |
| scales:Court/akd scales:hasName District Court, D. Alaska |
| scales:JudgeEntity/SJ000000 scales:hasName Cj Williams |

## Comments

* 11020147 occurrences with subject type scales_Agent and object type string.
* 94 occurrences with subject type scales_Court and object type string.
* 5385 occurrences with untyped subjects and object type string.

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
| self | scales:hasName |
| native | scales-kg/:scales_hasName |




## LinkML Source

<details>
```yaml
name: scales_hasName
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 11020147 occurrences with subject type scales_Agent and object type string.
- 94 occurrences with subject type scales_Court and object type string.
- 5385 occurrences with untyped subjects and object type string.
examples:
- value: scales:Agent/akd;;1:16-cr-00001_a0 scales:hasName SCALES-Party-Hash-01169B980BF3557176ECC743C5841A32
- value: scales:Court/akd scales:hasName District Court, D. Alaska
- value: scales:JudgeEntity/SJ000000 scales:hasName Cj Williams
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasName
alias: scales_hasName
domain_of:
- scales_Agent
- scales_Court
range: string

```
</details>