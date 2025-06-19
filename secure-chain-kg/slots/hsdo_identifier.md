

# Slot: hsdo_identifier


_No slot (predicate) description specified_






This slot occurs 261432 times.


URI: [hsdo:identifier](http://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | No class (type) description specified |  yes  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | No class (type) description specified |  yes  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainVulnerability](../classes/SecurechainVulnerability.md) | No class (type) description specified |  yes  |
| [SecurechainLicense](../classes/SecurechainLicense.md) | No class (type) description specified |  yes  |
| [SecurechainVulnerabilityType](../classes/SecurechainVulnerabilityType.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| securechain_VulnerabilityType | string | https://cwe.mitre.org/data/definitions/1.html | CWE-1 | 445 |
| securechain_Vulnerability | string | https://nvd.nist.gov/vuln/detail/CVE-1999-0060 | CVE-1999-0060 | 259806 |
| securechain_License | string | https://spdx.org/licenses/%28Apache-2.0.html | (Apache-2.0 | 294 |
| hsdo_Organization | string | https://www.google.com/search?q=1Password | Q2150861 | 883 |
| securechain_Software | string | https://www.google.com/search?q=Kernel | Q202400 | 4 |




## LinkML Source

<details>

```yaml
name: hsdo_identifier
annotations:
  count:
    tag: count
    value: 261432
description: No slot (predicate) description specified
examples:
- object:
    example_object: CWE-1
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: https://cwe.mitre.org/data/definitions/1.html
    example_subject_type: securechain_VulnerabilityType
- object:
    example_object: CVE-1999-0060
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: https://nvd.nist.gov/vuln/detail/CVE-1999-0060
    example_subject_type: securechain_Vulnerability
- object:
    example_object: (Apache-2.0
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: https://spdx.org/licenses/%28Apache-2.0.html
    example_subject_type: securechain_License
- object:
    example_object: Q2150861
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: https://www.google.com/search?q=1Password
    example_subject_type: hsdo_Organization
- object:
    example_object: Q202400
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: https://www.google.com/search?q=Kernel
    example_subject_type: securechain_Software
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:identifier
alias: hsdo_identifier
domain_of:
- hsdo_Organization
- securechain_License
- securechain_Software
- securechain_Vulnerability
- securechain_VulnerabilityType
range: string

```
</details>