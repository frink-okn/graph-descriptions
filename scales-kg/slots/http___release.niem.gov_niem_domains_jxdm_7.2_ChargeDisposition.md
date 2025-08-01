

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeDisposition


_No slot (predicate) description specified_






This slot occurs 389366 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/ChargeDisposition](http://release.niem.gov/niem/domains/jxdm/7.2/ChargeDisposition)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Charge | string | scales:/Charge/akd;;1:16-cr-00001_c0-1-3 | Counts 1-4: 12 months 1 day imprisonment; 1 year Supervised Release; $600,064.00 Restitution; $100.00 Special Assessment. | 389366 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeDisposition
annotations:
  count:
    tag: count
    value: 389366
description: No slot (predicate) description specified
examples:
- object:
    example_object: 'Counts 1-4: 12 months 1 day imprisonment; 1 year Supervised Release;
      $600,064.00 Restitution; $100.00 Special Assessment.'
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ChargeDisposition
    example_subject: scales:/Charge/akd;;1:16-cr-00001_c0-1-3
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/ChargeDisposition
alias: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeDisposition
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Charge
range: string

```
</details>