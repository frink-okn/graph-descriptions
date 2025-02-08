

# Slot: rdf_Type


_No slot (predicate) description specified_





URI: [rdf:Type](http://www.w3.org/1999/02/22-rdf-syntax-ns#Type)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None → uri | scales/Agent/almd;;1:16-cr-00020_a0 | rdf:Type | jxdm72:CaseDefendantParty |
| scales_Case → uri | scales/CaseCivil | rdf:Type | jxdm72:Case |


## Comments

* 10426705 occurrences with untyped subjects and object type uri.
* 2 occurrences with subject type scales_Case and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rdf:Type |
| native | scales-kg-new/:rdf_Type |




## LinkML Source

<details>
```yaml
name: rdf_Type
description: No slot (predicate) description specified
comments:
- 10426705 occurrences with untyped subjects and object type uri.
- 2 occurrences with subject type scales_Case and object type uri.
examples:
- description: None → uri
  object:
    example_object: jxdm72:CaseDefendantParty
    example_object_type: uri
    example_predicate: rdf:Type
    example_subject: scales/Agent/almd;;1:16-cr-00020_a0
    example_subject_type: None
- description: scales_Case → uri
  object:
    example_object: jxdm72:Case
    example_object_type: uri
    example_predicate: rdf:Type
    example_subject: scales/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: rdf:Type
alias: rdf_Type
domain_of:
- scales_Case
range: uri

```
</details>