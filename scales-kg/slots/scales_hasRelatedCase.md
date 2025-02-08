

# Slot: scales_hasRelatedCase


_No slot (predicate) description specified_





URI: [scales:hasRelatedCase](http://schemas.scales-okn.org/rdf/scales#hasRelatedCase)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ScalesCase](../classes/ScalesCase.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| scales_Case → scales_Case | scales/CaseCriminal | scales:hasRelatedCase | scales/CaseCriminal |
| scales_Case → uri | scales/CaseCivil | scales:hasRelatedCase | scales/CaseOther |


## Comments

* 4 occurrences with subject type scales_Case and object type scales_Case.
* 1 occurrences with subject type scales_Case and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:hasRelatedCase |
| native | scales-kg-new/:scales_hasRelatedCase |




## LinkML Source

<details>

```yaml
name: scales_hasRelatedCase
description: No slot (predicate) description specified
comments:
- 4 occurrences with subject type scales_Case and object type scales_Case.
- 1 occurrences with subject type scales_Case and object type uri.
examples:
- description: scales_Case → scales_Case
  object:
    example_object: scales/CaseCriminal
    example_object_type: scales_Case
    example_predicate: scales:hasRelatedCase
    example_subject: scales/CaseCriminal
    example_subject_type: scales_Case
- description: scales_Case → uri
  object:
    example_object: scales/CaseOther
    example_object_type: uri
    example_predicate: scales:hasRelatedCase
    example_subject: scales/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: scales:hasRelatedCase
alias: scales_hasRelatedCase
domain_of:
- scales_Case
range: Any
any_of:
- range: scales_Case
- range: uri

```
</details>