

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterActionDate


_No slot (predicate) description specified_






This slot occurs 58355686 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/RegisterActionDate](http://release.niem.gov/niem/domains/jxdm/7.2/RegisterActionDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:date](http://www.w3.org/2001/XMLSchema#date)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | date | scales:DocketEntry/akd;;1:16-cr-00001_de0 | 2016-02-03 | 30414852 |
| http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction | date | scales:DocketEntry/ga-clayton-magistrate-civil;;0:00-cm-00001_de0 | 2000-01-10 | 27940834 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterActionDate
annotations:
  count:
    tag: count
    value: 58355686
  date:
    tag: date
    value: 30414852
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2016-02-03'
    example_object_type: date
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterActionDate
    example_subject: scales:DocketEntry/akd;;1:16-cr-00001_de0
    example_subject_type: None
- object:
    example_object: '2000-01-10'
    example_object_type: date
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterActionDate
    example_subject: scales:DocketEntry/ga-clayton-magistrate-civil;;0:00-cm-00001_de0
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterActionDate
alias: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterActionDate
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
range: date

```
</details>