

# Slot: hsdo_identifier


_No slot (predicate) description specified_





URI: [hsdo:identifier](http://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainVulnerability](../classes/SecurechainVulnerability.md) | No class (type) description specified |  no  |
| [SecurechainVulnerabilityType](../classes/SecurechainVulnerabilityType.md) | No class (type) description specified |  no  |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [SecurechainLicense](../classes/SecurechainLicense.md) | No class (type) description specified |  no  |
| [HsdoPerson](../classes/HsdoPerson.md) | A person (alive, dead, undead, or fictional) |  no  |
| [HsdoCreativeWork](../classes/HsdoCreativeWork.md) | The most generic kind of creative work, including books, movies, photographs,... |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Person → string | schema:Person/0----0 | hsdo:identifier | 0----0 |
| securechain_Vulnerability → string | securechain:Vulnerability/CVE-1999-0043 | hsdo:identifier | CVE-1999-0043 |
| securechain_VulnerabilityType → string | securechain:VulnerabilityType/CWE-1 | hsdo:identifier | CWE-1 |
| hsdo_Organization → string | schema:Organization/1Password | hsdo:identifier | Q2150861 |
| hsdo_CreativeWork → string | securechain:License/0bsd | hsdo:identifier | 0bsd |


## Comments

* 30434 occurrences with subject type hsdo_Person and object type string.
* 259334 occurrences with subject type securechain_Vulnerability and object type string.
* 445 occurrences with subject type securechain_VulnerabilityType and object type string.
* 887 occurrences with subject type hsdo_Organization and object type string.
* 20 occurrences with subject type hsdo_CreativeWork and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:identifier |
| native | secure-chain-kg/:hsdo_identifier |




## LinkML Source

<details>
```yaml
name: hsdo_identifier
description: No slot (predicate) description specified
comments:
- 30434 occurrences with subject type hsdo_Person and object type string.
- 259334 occurrences with subject type securechain_Vulnerability and object type string.
- 445 occurrences with subject type securechain_VulnerabilityType and object type
  string.
- 887 occurrences with subject type hsdo_Organization and object type string.
- 20 occurrences with subject type hsdo_CreativeWork and object type string.
examples:
- description: hsdo_Person → string
  object:
    example_object: 0----0
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: schema:Person/0----0
    example_subject_type: hsdo_Person
- description: securechain_Vulnerability → string
  object:
    example_object: CVE-1999-0043
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: securechain:Vulnerability/CVE-1999-0043
    example_subject_type: securechain_Vulnerability
- description: securechain_VulnerabilityType → string
  object:
    example_object: CWE-1
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: securechain:VulnerabilityType/CWE-1
    example_subject_type: securechain_VulnerabilityType
- description: hsdo_Organization → string
  object:
    example_object: Q2150861
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: schema:Organization/1Password
    example_subject_type: hsdo_Organization
- description: hsdo_CreativeWork → string
  object:
    example_object: 0bsd
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: securechain:License/0bsd
    example_subject_type: hsdo_CreativeWork
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:identifier
alias: hsdo_identifier
domain_of:
- hsdo_CreativeWork
- hsdo_Organization
- hsdo_Person
- securechain_Vulnerability
- securechain_VulnerabilityType
range: string

```
</details>