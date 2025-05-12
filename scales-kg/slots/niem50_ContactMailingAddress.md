

# Slot: niem50_ContactMailingAddress


_No slot (predicate) description specified_






This slot occurs 17703 times.


URI: [niem50:ContactMailingAddress](http://release.niem.gov/niem/niem-core/5.0/ContactMailingAddress)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Attorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Attorney.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney | string | scales:/Agent/casd;;3:16-cv-01644_a4 | 225 Broadway
Suite 900
San Diego, CA 92101-5008 | 7659 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney | string | scales:/Agent/casd;;3:16-cv-01644_a5 | 880 Front Street
Room 6293
San Diego, CA 92101 | 9307 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Attorney | string | scales:/Agent/casd;;3:16-cv-01692_a23 | 800 Wilshire Blvd.
Suite 500
Los Angeles, CA 90017 | 737 |




## LinkML Source

<details>

```yaml
name: niem50_ContactMailingAddress
annotations:
  count:
    tag: count
    value: 17703
description: No slot (predicate) description specified
examples:
- object:
    example_object: '225 Broadway

      Suite 900

      San Diego, CA 92101-5008'
    example_object_type: string
    example_predicate: niem50:ContactMailingAddress
    example_subject: scales:/Agent/casd;;3:16-cv-01644_a4
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
- object:
    example_object: '880 Front Street

      Room 6293

      San Diego, CA 92101'
    example_object_type: string
    example_predicate: niem50:ContactMailingAddress
    example_subject: scales:/Agent/casd;;3:16-cv-01644_a5
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
- object:
    example_object: '800 Wilshire Blvd.

      Suite 500

      Los Angeles, CA 90017'
    example_object_type: string
    example_predicate: niem50:ContactMailingAddress
    example_subject: scales:/Agent/casd;;3:16-cv-01692_a23
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
from_schema: scales-kg
rank: 1000
slot_uri: niem50:ContactMailingAddress
alias: niem50_ContactMailingAddress
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
range: string

```
</details>