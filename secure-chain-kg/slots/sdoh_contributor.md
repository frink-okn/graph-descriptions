

# Slot: sdoh_contributor


_No slot description provided_





URI: [sdoh:contributor](http://schema.org/contributor)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | No type description provided |  no  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No type description provided |  no  |







## Properties

* Range: [SdohPerson](../classes/SdohPerson.md)






## Examples

| Value |
| --- |
| securechain:Software/cuml sdoh:contributor schema:Person/minseokl |
| securechain:Software/velox sdoh:contributor schema:Person/DavidSGK |

## Comments

* 33048 occurrences with subject type securechain_Software and object type sdoh_Person.
* 3668 occurrences with untyped subjects and object type http://schema.org/Person.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:contributor |
| native | secure-chain-kg/:sdoh_contributor |




## LinkML Source

<details>
```yaml
name: sdoh_contributor
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 33048 occurrences with subject type securechain_Software and object type sdoh_Person.
- 3668 occurrences with untyped subjects and object type http://schema.org/Person.
examples:
- value: securechain:Software/cuml sdoh:contributor schema:Person/minseokl
- value: securechain:Software/velox sdoh:contributor schema:Person/DavidSGK
from_schema: secure-chain-kg
rank: 1000
slot_uri: sdoh:contributor
alias: sdoh_contributor
domain_of:
- securechain_Software
range: sdoh_Person

```
</details>