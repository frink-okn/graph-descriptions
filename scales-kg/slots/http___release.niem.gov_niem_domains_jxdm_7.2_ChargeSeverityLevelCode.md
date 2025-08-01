

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSeverityLevelCode


_No slot (predicate) description specified_






This slot occurs 444717 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSeverityLevelCode](http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSeverityLevelCode)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2ArrestCharge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2ArrestCharge.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_ArrestCharge | string | scales:ArrestCharge/ga-atlanta-pd-100830802 | FC | 81232 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Charge | string | scales:Charge/fulton-01-10000019 | Misdemeanor | 363485 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSeverityLevelCode
annotations:
  count:
    tag: count
    value: 444717
description: No slot (predicate) description specified
examples:
- object:
    example_object: FC
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSeverityLevelCode
    example_subject: scales:ArrestCharge/ga-atlanta-pd-100830802
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_ArrestCharge
- object:
    example_object: Misdemeanor
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSeverityLevelCode
    example_subject: scales:Charge/fulton-01-10000019
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSeverityLevelCode
alias: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSeverityLevelCode
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_ArrestCharge
- http___release.niem.gov_niem_domains_jxdm_7.2_Charge
range: string

```
</details>