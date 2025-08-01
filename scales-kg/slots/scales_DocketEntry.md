

# Slot: scales_DocketEntry


_No slot (predicate) description specified_






This slot occurs 58334996 times.


URI: [scales:DocketEntry](http://schemas.scales-okn.org/rdf/scales#DocketEntry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction | uri | scales:/DocketTable/akd;;1:16-cr-00001 | scales:/DocketEntry/akd;;1:16-cr-00001_de0 | 30414852 |
| http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions | http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction | scales:DocketTable/ga-clayton-magistrate-civil;;0:00-cm-00001 | scales:DocketEntry/ga-clayton-magistrate-civil;;0:00-cm-00001_de0 | 27920144 |




## LinkML Source

<details>

```yaml
name: scales_DocketEntry
annotations:
  count:
    tag: count
    value: 58334996
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/DocketEntry/akd;;1:16-cr-00001_de0
    example_object_type: uri
    example_predicate: scales:DocketEntry
    example_subject: scales:/DocketTable/akd;;1:16-cr-00001
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
- object:
    example_object: scales:DocketEntry/ga-clayton-magistrate-civil;;0:00-cm-00001_de0
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    example_predicate: scales:DocketEntry
    example_subject: scales:DocketTable/ga-clayton-magistrate-civil;;0:00-cm-00001
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
from_schema: scales-kg
rank: 1000
slot_uri: scales:DocketEntry
alias: scales_DocketEntry
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
- http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
range: Any
any_of:
- range: uri
- range: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction

```
</details>