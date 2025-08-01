

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge


_No slot (predicate) description specified_






This slot occurs 4424121 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge](http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | uri | scales:/CivilCase/akd;;1:16-cv-00001 | scales:/Agent/akd;;1:16-cv-00001_a2 | 984400 |
| scales_CriminalCase | uri | scales:/CriminalCase/akd;;1:16-cr-00001 | scales:/Agent/akd;;1:16-cr-00001_a2 | 231931 |
| scales_CivilCase | http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge | scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001 | scales:Judge/ga-clayton-magistrate-civil;;0:00-cm-00001_3 | 1076604 |
| scales_CriminalCase | http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge | scales:Case/ga-clayton-magistrate;;0:00-bc-00001 | scales:Judge/ga-clayton-magistrate;;0:00-bc-00001_0 | 2131186 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
annotations:
  count:
    tag: count
    value: 4424121
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Agent/akd;;1:16-cv-00001_a2
    example_object_type: uri
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:/Agent/akd;;1:16-cr-00001_a2
    example_object_type: uri
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
- object:
    example_object: scales:Judge/ga-clayton-magistrate-civil;;0:00-cm-00001_3
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
    example_subject: scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:Judge/ga-clayton-magistrate;;0:00-bc-00001_0
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
    example_subject: scales:Case/ga-clayton-magistrate;;0:00-bc-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: Any
any_of:
- range: uri
- range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge

```
</details>