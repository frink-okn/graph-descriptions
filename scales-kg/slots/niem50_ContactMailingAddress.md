

# Slot: niem50_ContactMailingAddress


_No slot (predicate) description specified_






This slot occurs 3083592 times.


URI: [niem50:ContactMailingAddress](http://release.niem.gov/niem/niem-core/5.0/ContactMailingAddress)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Attorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Attorney.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney | string | scales:/Agent/akd;;1:16-cr-00001_a3 | 425 G Street, Suite 800
Anchorage, AK 99501 | 1571811 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney | string | scales:/Agent/akd;;1:16-cr-00001_a5 | 709 West 9th Street, Rm 937
P.O. Box 21627
Juneau, AK 99801 | 1432528 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Attorney | string | scales:/Agent/akd;;1:16-cv-00008_a22 | 100 Cushman Street, Suite 400
Fairbanks, AK 99701 | 79253 |




## LinkML Source

<details>

```yaml
name: niem50_ContactMailingAddress
annotations:
  count:
    tag: count
    value: 3083592
description: No slot (predicate) description specified
examples:
- object:
    example_object: '425 G Street, Suite 800

      Anchorage, AK 99501'
    example_object_type: string
    example_predicate: niem50:ContactMailingAddress
    example_subject: scales:/Agent/akd;;1:16-cr-00001_a3
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
- object:
    example_object: '709 West 9th Street, Rm 937

      P.O. Box 21627

      Juneau, AK 99801'
    example_object_type: string
    example_predicate: niem50:ContactMailingAddress
    example_subject: scales:/Agent/akd;;1:16-cr-00001_a5
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
- object:
    example_object: '100 Cushman Street, Suite 400

      Fairbanks, AK 99701'
    example_object_type: string
    example_predicate: niem50:ContactMailingAddress
    example_subject: scales:/Agent/akd;;1:16-cv-00008_a22
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