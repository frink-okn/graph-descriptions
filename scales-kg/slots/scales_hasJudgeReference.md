

# Slot: scales_hasJudgeReference


_No slot (predicate) description specified_






This slot occurs 95868 times.


URI: [scales:hasJudgeReference](http://schemas.scales-okn.org/rdf/scales#hasJudgeReference)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2Judge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Judge.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | http___release.niem.gov_niem_domains_jxdm_7.2_Judge | scales:/DocketEntry/casd;;3:17-cr-03540_de9 | scales:/JudgeEntity/SJ002053 | 94865 |
| None | uri | scales:/DocketEntry/casd;;3:16-cv-01698_de3 | scales:/JudgeEntity/Inconclusive | 1003 |




## LinkML Source

<details>

```yaml
name: scales_hasJudgeReference
annotations:
  count:
    tag: count
    value: 95868
  http___release.niem.gov_niem_domains_jxdm_7.2_Judge:
    tag: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    value: 94865
  uri:
    tag: uri
    value: 1003
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/JudgeEntity/SJ002053
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    example_predicate: scales:hasJudgeReference
    example_subject: scales:/DocketEntry/casd;;3:17-cr-03540_de9
    example_subject_type: None
- object:
    example_object: scales:/JudgeEntity/Inconclusive
    example_object_type: uri
    example_predicate: scales:hasJudgeReference
    example_subject: scales:/DocketEntry/casd;;3:16-cv-01698_de3
    example_subject_type: None
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasJudgeReference
alias: scales_hasJudgeReference
range: Any
any_of:
- range: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
- range: uri

```
</details>