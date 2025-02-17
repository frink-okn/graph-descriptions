

# Slot: identifier (hsdo_identifier)


_The identifier property represents any kind of identifier for any kind of [[Thing]], such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See [background notes](/docs/datamodel.html#identifierBg) for more details.␊        _






This slot occurs 291120 times.


URI: [hsdo:identifier](http://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  yes  |
| [HsdoPerson](../classes/HsdoPerson.md) | A person (alive, dead, undead, or fictional) |  yes  |
| [SecurechainVulnerability](../classes/SecurechainVulnerability.md) | No class (type) description specified |  yes  |
| [HsdoCreativeWork](../classes/HsdoCreativeWork.md) | The most generic kind of creative work, including books, movies, photographs,... |  yes  |
| [SecurechainLicense](../classes/SecurechainLicense.md) | No class (type) description specified |  no  |
| [SecurechainVulnerabilityType](../classes/SecurechainVulnerabilityType.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Person | string | schema:Person/0----0 | 0----0 | 30434 |
| securechain_Vulnerability | string | securechain:Vulnerability/CVE-1999-0043 | CVE-1999-0043 | 259334 |
| securechain_VulnerabilityType | string | securechain:VulnerabilityType/CWE-1 | CWE-1 | 445 |
| hsdo_Organization | string | schema:Organization/1Password | Q2150861 | 887 |
| hsdo_CreativeWork | string | securechain:License/0bsd | 0bsd | 20 |




## LinkML Source

<details>

```yaml
name: hsdo_identifier
annotations:
  count:
    tag: count
    value: 291120
description: 'The identifier property represents any kind of identifier for any kind
  of [[Thing]], such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated
  properties for representing many of these, either as textual strings or as URL (URI)
  links. See [background notes](/docs/datamodel.html#identifierBg) for more details.␊        '
title: identifier
examples:
- object:
    example_object: 0----0
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: schema:Person/0----0
    example_subject_type: hsdo_Person
- object:
    example_object: CVE-1999-0043
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: securechain:Vulnerability/CVE-1999-0043
    example_subject_type: securechain_Vulnerability
- object:
    example_object: CWE-1
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: securechain:VulnerabilityType/CWE-1
    example_subject_type: securechain_VulnerabilityType
- object:
    example_object: Q2150861
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: schema:Organization/1Password
    example_subject_type: hsdo_Organization
- object:
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