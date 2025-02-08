

# Slot: scales_Party


_No slot (predicate) description specified_





URI: [scales:Party](http://schemas.scales-okn.org/rdf/scales#Party)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| scales_Case → uri | scales/CaseCivil | scales:Party | scales/Agent/almd;;1:16-cv-00082_a5 |


## Comments

* 231186 occurrences with subject type scales_Case and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:Party |
| native | scales-kg-new/:scales_Party |




## LinkML Source

<details>

```yaml
name: scales_Party
description: No slot (predicate) description specified
comments:
- 231186 occurrences with subject type scales_Case and object type uri.
examples:
- description: scales_Case → uri
  object:
    example_object: scales/Agent/almd;;1:16-cv-00082_a5
    example_object_type: uri
    example_predicate: scales:Party
    example_subject: scales/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: scales:Party
alias: scales_Party
domain_of:
- scales_Case
range: uri

```
</details>