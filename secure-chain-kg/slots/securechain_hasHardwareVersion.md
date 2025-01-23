

# Slot: securechain_hasHardwareVersion


_No slot (predicate) description specified_





URI: [securechain:hasHardwareVersion](https://w3id.org/secure-chain/hasHardwareVersion)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainHardware](../classes/SecurechainHardware.md) | No class (type) description specified |  no  |







## Properties

* Range: [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| securechain_Hardware → securechain_HardwareVersion | securechain:Hardware/zz_qcs605 | securechain:hasHardwareVersion | securechain:HardwareVersion/zz_qcs605#- |


## Comments

* 57295 occurrences with subject type securechain_Hardware and object type securechain_HardwareVersion.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | securechain:hasHardwareVersion |
| native | secure-chain-kg/:securechain_hasHardwareVersion |




## LinkML Source

<details>
```yaml
name: securechain_hasHardwareVersion
description: No slot (predicate) description specified
comments:
- 57295 occurrences with subject type securechain_Hardware and object type securechain_HardwareVersion.
examples:
- description: securechain_Hardware → securechain_HardwareVersion
  object:
    example_object: securechain:HardwareVersion/zz_qcs605#-
    example_object_type: securechain_HardwareVersion
    example_predicate: securechain:hasHardwareVersion
    example_subject: securechain:Hardware/zz_qcs605
    example_subject_type: securechain_Hardware
from_schema: secure-chain-kg
rank: 1000
slot_uri: securechain:hasHardwareVersion
alias: securechain_hasHardwareVersion
domain_of:
- securechain_Hardware
range: securechain_HardwareVersion

```
</details>