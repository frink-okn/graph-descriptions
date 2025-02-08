

# Slot: scales_isInCircuit


_No slot (predicate) description specified_





URI: [scales:isInCircuit](http://schemas.scales-okn.org/rdf/scales#isInCircuit)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72Court](../classes/Jxdm72Court.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_Court → string | scales/Court/almd | scales:isInCircuit | Eleventh |
| None → string | scales:Court/akd | scales:isInCircuit | Ninth |


## Comments

* 94 occurrences with subject type jxdm72_Court and object type string.
* 94 occurrences with untyped subjects and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:isInCircuit |
| native | scales-kg-new/:scales_isInCircuit |




## LinkML Source

<details>

```yaml
name: scales_isInCircuit
description: No slot (predicate) description specified
comments:
- 94 occurrences with subject type jxdm72_Court and object type string.
- 94 occurrences with untyped subjects and object type string.
examples:
- description: jxdm72_Court → string
  object:
    example_object: Eleventh
    example_object_type: string
    example_predicate: scales:isInCircuit
    example_subject: scales/Court/almd
    example_subject_type: jxdm72_Court
- description: None → string
  object:
    example_object: Ninth
    example_object_type: string
    example_predicate: scales:isInCircuit
    example_subject: scales:Court/akd
    example_subject_type: None
from_schema: scales-kg-new
rank: 1000
slot_uri: scales:isInCircuit
alias: scales_isInCircuit
domain_of:
- jxdm72_Court
range: string

```
</details>