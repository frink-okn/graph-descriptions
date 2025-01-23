

# Slot: hsdo_contributor


_No slot (predicate) description specified_





URI: [hsdo:contributor](http://schema.org/contributor)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | No class (type) description specified |  no  |







## Properties

* Range: [HsdoPerson](../classes/HsdoPerson.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None → hsdo_Person | securechain:Software/zapcc | hsdo:contributor | schema:Person/yrnkrn |
| securechain_Software → hsdo_Person | securechain:Software/zxing-cpp | hsdo:contributor | schema:Person/zander |


## Comments

* 3668 occurrences with untyped subjects and object type http://schema.org/Person.
* 33048 occurrences with subject type securechain_Software and object type hsdo_Person.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:contributor |
| native | secure-chain-kg/:hsdo_contributor |




## LinkML Source

<details>
```yaml
name: hsdo_contributor
description: No slot (predicate) description specified
comments:
- 3668 occurrences with untyped subjects and object type http://schema.org/Person.
- 33048 occurrences with subject type securechain_Software and object type hsdo_Person.
examples:
- description: None → hsdo_Person
  object:
    example_object: schema:Person/yrnkrn
    example_object_type: hsdo_Person
    example_predicate: hsdo:contributor
    example_subject: securechain:Software/zapcc
    example_subject_type: None
- description: securechain_Software → hsdo_Person
  object:
    example_object: schema:Person/zander
    example_object_type: hsdo_Person
    example_predicate: hsdo:contributor
    example_subject: securechain:Software/zxing-cpp
    example_subject_type: securechain_Software
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:contributor
alias: hsdo_contributor
domain_of:
- securechain_Software
range: hsdo_Person

```
</details>