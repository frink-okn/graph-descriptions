

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterActionDescriptionText


_No slot (predicate) description specified_






This slot occurs 58354320 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/RegisterActionDescriptionText](http://release.niem.gov/niem/domains/jxdm/7.2/RegisterActionDescriptionText)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | string | scales:DocketEntry/akd;;1:16-cr-00001_de0 | MISDEMEANOR INFORMATION as to 01169B9 (1) count(s) 1-4. (Attachments: # 1 Criminal Cover Sheet re Defendant 01169B9) (CLW, COURT STAFF) (Entered: 02/03/2016) | 30414809 |
| http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction | string | scales:DocketEntry/ga-clayton-magistrate-civil;;0:00-cm-00001_de0 | Contract
against SCALES-1258027 | 27939511 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterActionDescriptionText
annotations:
  count:
    tag: count
    value: 58354320
  string:
    tag: string
    value: 30414809
description: No slot (predicate) description specified
examples:
- object:
    example_object: 'MISDEMEANOR INFORMATION as to 01169B9 (1) count(s) 1-4. (Attachments:
      # 1 Criminal Cover Sheet re Defendant 01169B9) (CLW, COURT STAFF) (Entered:
      02/03/2016)'
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterActionDescriptionText
    example_subject: scales:DocketEntry/akd;;1:16-cr-00001_de0
    example_subject_type: None
- object:
    example_object: 'Contract

      against SCALES-1258027'
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterActionDescriptionText
    example_subject: scales:DocketEntry/ga-clayton-magistrate-civil;;0:00-cm-00001_de0
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterActionDescriptionText
alias: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterActionDescriptionText
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
range: string

```
</details>