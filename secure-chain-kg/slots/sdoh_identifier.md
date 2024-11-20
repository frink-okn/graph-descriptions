

# Slot: sdoh_identifier


_TODO -- tell the world what this slot (predicate) describes._





URI: [sdoh:identifier](http://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainVulnerabilityType](../classes/SecurechainVulnerabilityType.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SdohOrganization](../classes/SdohOrganization.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SecurechainVulnerability](../classes/SecurechainVulnerability.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SdohCreativeWork](../classes/SdohCreativeWork.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SdohPerson](../classes/SdohPerson.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| securechain:Vulnerability/CVE-2023-52458 sdoh:identifier CVE-2023-52458 |
| schema:Person/Touhou-fan sdoh:identifier Touhou-fan |
| securechain:VulnerabilityType/CWE-842 sdoh:identifier CWE-842 |
| schema:Organization/Basecamp sdoh:identifier Q36908 |
| securechain:License/bsl-1.0 sdoh:identifier bsl-1.0 |

## Comments

* 259334 occurrences with subject type securechain_Vulnerability and object type string.
* 30434 occurrences with subject type sdoh_Person and object type string.
* 445 occurrences with subject type securechain_VulnerabilityType and object type string.
* 887 occurrences with subject type sdoh_Organization and object type string.
* 20 occurrences with subject type sdoh_CreativeWork and object type string.

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
| self | sdoh:identifier |
| native | secure-chain-kg/develop/:sdoh_identifier |




## LinkML Source

<details>
```yaml
name: sdoh_identifier
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 259334 occurrences with subject type securechain_Vulnerability and object type string.
- 30434 occurrences with subject type sdoh_Person and object type string.
- 445 occurrences with subject type securechain_VulnerabilityType and object type
  string.
- 887 occurrences with subject type sdoh_Organization and object type string.
- 20 occurrences with subject type sdoh_CreativeWork and object type string.
examples:
- value: securechain:Vulnerability/CVE-2023-52458 sdoh:identifier CVE-2023-52458
- value: schema:Person/Touhou-fan sdoh:identifier Touhou-fan
- value: securechain:VulnerabilityType/CWE-842 sdoh:identifier CWE-842
- value: schema:Organization/Basecamp sdoh:identifier Q36908
- value: securechain:License/bsl-1.0 sdoh:identifier bsl-1.0
from_schema: secure-chain-kg/develop
rank: 1000
slot_uri: sdoh:identifier
alias: sdoh_identifier
domain_of:
- securechain_Vulnerability
- securechain_VulnerabilityType
- sdoh_CreativeWork
- sdoh_Organization
- sdoh_Person
range: string

```
</details>