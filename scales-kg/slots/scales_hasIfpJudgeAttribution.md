

# Slot: scales_hasIfpJudgeAttribution


_No slot (predicate) description specified_






This slot occurs 262 times.


URI: [scales:hasIfpJudgeAttribution](http://schemas.scales-okn.org/rdf/scales#hasIfpJudgeAttribution)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2Judge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Judge.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | http___release.niem.gov_niem_domains_jxdm_7.2_Judge | scales:/DocketEntry/casd;;3:16-cv-03134_de2 | scales:/JudgeEntity/SJ003090 | 260 |
| None | uri | scales:/DocketEntry/casd;;3:16-cv-02094_de2 | scales:/JudgeEntity/Inconclusive | 2 |




## LinkML Source

<details>

```yaml
name: scales_hasIfpJudgeAttribution
annotations:
  count:
    tag: count
    value: 262
  http___release.niem.gov_niem_domains_jxdm_7.2_Judge:
    tag: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    value: 260
  uri:
    tag: uri
    value: 2
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/JudgeEntity/SJ003090
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    example_predicate: scales:hasIfpJudgeAttribution
    example_subject: scales:/DocketEntry/casd;;3:16-cv-03134_de2
    example_subject_type: None
- object:
    example_object: scales:/JudgeEntity/Inconclusive
    example_object_type: uri
    example_predicate: scales:hasIfpJudgeAttribution
    example_subject: scales:/DocketEntry/casd;;3:16-cv-02094_de2
    example_subject_type: None
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIfpJudgeAttribution
alias: scales_hasIfpJudgeAttribution
range: Any
any_of:
- range: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
- range: uri

```
</details>