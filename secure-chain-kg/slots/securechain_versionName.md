

# Slot: securechain_versionName


_No slot (predicate) description specified_





URI: [securechain:versionName](https://w3id.org/secure-chain/versionName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| securechain_HardwareVersion → string | securechain:HardwareVersion/-#- | securechain:versionName | - |
| securechain_SoftwareVersion → string | securechain:SoftwareVersion/#%22%2F%2Fapi%23%2A | securechain:versionName | "//api#* |


## Comments

* 57295 occurrences with subject type securechain_HardwareVersion and object type string.
* 164000 occurrences with subject type securechain_SoftwareVersion and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | securechain:versionName |
| native | secure-chain-kg/:securechain_versionName |




## LinkML Source

<details>
```yaml
name: securechain_versionName
description: No slot (predicate) description specified
comments:
- 57295 occurrences with subject type securechain_HardwareVersion and object type
  string.
- 164000 occurrences with subject type securechain_SoftwareVersion and object type
  string.
examples:
- description: securechain_HardwareVersion → string
  object:
    example_object: '-'
    example_object_type: string
    example_predicate: securechain:versionName
    example_subject: securechain:HardwareVersion/-#-
    example_subject_type: securechain_HardwareVersion
- description: securechain_SoftwareVersion → string
  object:
    example_object: '"//api#*'
    example_object_type: string
    example_predicate: securechain:versionName
    example_subject: securechain:SoftwareVersion/#%22%2F%2Fapi%23%2A
    example_subject_type: securechain_SoftwareVersion
from_schema: secure-chain-kg
rank: 1000
slot_uri: securechain:versionName
alias: securechain_versionName
domain_of:
- securechain_HardwareVersion
- securechain_SoftwareVersion
range: string

```
</details>