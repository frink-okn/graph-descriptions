

# Slot: securechain_hasSoftwareVersion


_No slot (predicate) description specified_





URI: [securechain:hasSoftwareVersion](https://w3id.org/secure-chain/hasSoftwareVersion)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | No class (type) description specified |  no  |







## Properties

* Range: [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| securechain_Software → securechain_SoftwareVersion | securechain:Software/zzuf | securechain:hasSoftwareVersion | securechain:SoftwareVersion/zzuf#0.15-4 |


## Comments

* 164001 occurrences with subject type securechain_Software and object type securechain_SoftwareVersion.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | securechain:hasSoftwareVersion |
| native | secure-chain-kg/:securechain_hasSoftwareVersion |




## LinkML Source

<details>
```yaml
name: securechain_hasSoftwareVersion
description: No slot (predicate) description specified
comments:
- 164001 occurrences with subject type securechain_Software and object type securechain_SoftwareVersion.
examples:
- description: securechain_Software → securechain_SoftwareVersion
  object:
    example_object: securechain:SoftwareVersion/zzuf#0.15-4
    example_object_type: securechain_SoftwareVersion
    example_predicate: securechain:hasSoftwareVersion
    example_subject: securechain:Software/zzuf
    example_subject_type: securechain_Software
from_schema: secure-chain-kg
rank: 1000
slot_uri: securechain:hasSoftwareVersion
alias: securechain_hasSoftwareVersion
domain_of:
- securechain_Software
range: securechain_SoftwareVersion

```
</details>