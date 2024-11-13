

# Slot: securechain_versionName


_TODO -- tell the world what this slot (predicate) describes._





URI: [securechain:versionName](https://w3id.org/secure-chain/versionName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| securechain:SoftwareVersion/gee-0.8#0.8 securechain:versionName 0.8 |
| securechain:HardwareVersion/wsr-600dhp#- securechain:versionName - |

## Comments

* 164001 occurrences with subject type securechain_SoftwareVersion and object type string.
* 57295 occurrences with subject type securechain_HardwareVersion and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg/develop




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | securechain:versionName |
| native | secure-chain-kg/develop/:securechain_versionName |




## LinkML Source

<details>
```yaml
name: securechain_versionName
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 164001 occurrences with subject type securechain_SoftwareVersion and object type
  string.
- 57295 occurrences with subject type securechain_HardwareVersion and object type
  string.
examples:
- value: securechain:SoftwareVersion/gee-0.8#0.8 securechain:versionName 0.8
- value: securechain:HardwareVersion/wsr-600dhp#- securechain:versionName -
from_schema: secure-chain-kg/develop
rank: 1000
slot_uri: securechain:versionName
alias: securechain_versionName
domain_of:
- securechain_HardwareVersion
- securechain_SoftwareVersion
range: string

```
</details>