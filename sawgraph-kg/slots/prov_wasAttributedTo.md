

# Slot: prov_wasAttributedTo


_No slot (predicate) description specified_






This slot occurs 597589 times.


URI: [prov:wasAttributedTo](http://www.w3.org/ns/prov#wasAttributedTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ProvAgent](../classes/ProvAgent.md)&nbsp;or&nbsp;<br />[ProvOrganization](../classes/ProvOrganization.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-Sample | prov_Agent | me_egad_data:sample.AAL210144001R.20210112 | me_egad_data:MEDACF | 20826 |
| me_egad_EGAD-PFAS-Observation | prov_Organization | me_egad_data:observation.AAL210144001R.20210112.1763231 | me_egad_data:organization.lab.AA | 576127 |
| me_egad_EGAD-PFAS-Observation | uri | me_egad_data:observation.NA101365P.20130507.1763231 | me_egad_data:organization.lab.NA | 636 |




## LinkML Source

<details>

```yaml
name: prov_wasAttributedTo
annotations:
  count:
    tag: count
    value: 597589
description: No slot (predicate) description specified
examples:
- object:
    example_object: me_egad_data:MEDACF
    example_object_type: prov_Agent
    example_predicate: prov:wasAttributedTo
    example_subject: me_egad_data:sample.AAL210144001R.20210112
    example_subject_type: me_egad_EGAD-Sample
- object:
    example_object: me_egad_data:organization.lab.AA
    example_object_type: prov_Organization
    example_predicate: prov:wasAttributedTo
    example_subject: me_egad_data:observation.AAL210144001R.20210112.1763231
    example_subject_type: me_egad_EGAD-PFAS-Observation
- object:
    example_object: me_egad_data:organization.lab.NA
    example_object_type: uri
    example_predicate: prov:wasAttributedTo
    example_subject: me_egad_data:observation.NA101365P.20130507.1763231
    example_subject_type: me_egad_EGAD-PFAS-Observation
from_schema: sawgraph-kg
rank: 1000
slot_uri: prov:wasAttributedTo
alias: prov_wasAttributedTo
domain_of:
- me_egad_EGAD-PFAS-Observation
- me_egad_EGAD-Sample
range: Any
any_of:
- range: prov_Agent
- range: prov_Organization
- range: uri

```
</details>