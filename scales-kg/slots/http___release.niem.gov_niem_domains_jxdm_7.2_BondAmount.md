

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_BondAmount


_No slot (predicate) description specified_






This slot occurs 99402 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/BondAmount](http://release.niem.gov/niem/domains/jxdm/7.2/BondAmount)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Charge | float | scales:Charge/fulton-01-10000019 | 300.0 | 99402 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_BondAmount
annotations:
  count:
    tag: count
    value: 99402
description: No slot (predicate) description specified
examples:
- object:
    example_object: '300.0'
    example_object_type: float
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/BondAmount
    example_subject: scales:Charge/fulton-01-10000019
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/BondAmount
alias: http___release.niem.gov_niem_domains_jxdm_7.2_BondAmount
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Charge
range: float

```
</details>