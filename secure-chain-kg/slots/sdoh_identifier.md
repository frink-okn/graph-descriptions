

# Slot: sdoh_identifier


_No slot description provided_





URI: [sdoh:identifier](http://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohPerson](../classes/SdohPerson.md) | A person (alive, dead, undead, or fictional) |  no  |
| [SecurechainVulnerability](../classes/SecurechainVulnerability.md) | No type description provided |  no  |
| [SdohOrganization](../classes/SdohOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [SdohCreativeWork](../classes/SdohCreativeWork.md) | The most generic kind of creative work, including books, movies, photographs,... |  no  |
| [SecurechainVulnerabilityType](../classes/SecurechainVulnerabilityType.md) | No type description provided |  no  |
| [SecurechainLicense](../classes/SecurechainLicense.md) | No type description provided |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Value |
| --- |
| securechain:Vulnerability/CVE-2019-9484 sdoh:identifier CVE-2019-9484 |
| schema:Person/rncbc sdoh:identifier rncbc |
| securechain:VulnerabilityType/CWE-228 sdoh:identifier CWE-228 |
| schema:Organization/Jgraph sdoh:identifier Q59339175 |
| securechain:License/mpl-2.0 sdoh:identifier mpl-2.0 |

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


* from schema: secure-chain-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:identifier |
| native | secure-chain-kg/:sdoh_identifier |




## LinkML Source

<details>
```yaml
name: sdoh_identifier
description: No slot description provided
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
- value: securechain:Vulnerability/CVE-2019-9484 sdoh:identifier CVE-2019-9484
- value: schema:Person/rncbc sdoh:identifier rncbc
- value: securechain:VulnerabilityType/CWE-228 sdoh:identifier CWE-228
- value: schema:Organization/Jgraph sdoh:identifier Q59339175
- value: securechain:License/mpl-2.0 sdoh:identifier mpl-2.0
from_schema: secure-chain-kg
rank: 1000
slot_uri: sdoh:identifier
alias: sdoh_identifier
domain_of:
- sdoh_CreativeWork
- sdoh_Organization
- sdoh_Person
- securechain_Vulnerability
- securechain_VulnerabilityType
range: string

```
</details>