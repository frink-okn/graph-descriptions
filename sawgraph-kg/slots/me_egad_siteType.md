

# Slot: me_egad_siteType


_No slot (predicate) description specified_






This slot occurs 1318 times.


URI: [me_egad:siteType](http://sawgraph.spatialai.org/v1/me-egad#siteType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Site](../classes/MeEgadEGAD-Site.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SiteType](../classes/MeEgadEGAD-SiteType.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-PFAS-Site | me_egad_EGAD-SiteType | me_egad_data:site.100843 | me_egad_data:siteType.UNCDOD | 1318 |
| me_egad_EGAD-PFAS-Site | owl_NamedIndividual | me_egad_data:site.100843 | me_egad_data:siteType.UNCDOD | 1318 |
| me_egad_EGAD-Site | me_egad_EGAD-SiteType | me_egad_data:site.100843 | me_egad_data:siteType.UNCDOD | 1318 |
| me_egad_EGAD-Site | owl_NamedIndividual | me_egad_data:site.100843 | me_egad_data:siteType.UNCDOD | 1318 |




## LinkML Source

<details>

```yaml
name: me_egad_siteType
annotations:
  count:
    tag: count
    value: 1318
description: No slot (predicate) description specified
examples:
- object:
    example_object: me_egad_data:siteType.UNCDOD
    example_object_type: me_egad_EGAD-SiteType
    example_predicate: me_egad:siteType
    example_subject: me_egad_data:site.100843
    example_subject_type: me_egad_EGAD-PFAS-Site
- object:
    example_object: me_egad_data:siteType.UNCDOD
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:siteType
    example_subject: me_egad_data:site.100843
    example_subject_type: me_egad_EGAD-PFAS-Site
- object:
    example_object: me_egad_data:siteType.UNCDOD
    example_object_type: me_egad_EGAD-SiteType
    example_predicate: me_egad:siteType
    example_subject: me_egad_data:site.100843
    example_subject_type: me_egad_EGAD-Site
- object:
    example_object: me_egad_data:siteType.UNCDOD
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:siteType
    example_subject: me_egad_data:site.100843
    example_subject_type: me_egad_EGAD-Site
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:siteType
alias: me_egad_siteType
domain_of:
- me_egad_EGAD-PFAS-Site
- me_egad_EGAD-Site
range: Any
any_of:
- range: me_egad_EGAD-SiteType
- range: owl_NamedIndividual

```
</details>