

# Slot: us_sdwis_hasPWSID


_No slot (predicate) description specified_






This slot occurs 61 times.


URI: [us_sdwis:hasPWSID](http://sawgraph.spatialai.org/v1/us-sdwis#hasPWSID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Site](../classes/MeEgadEGAD-Site.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-Site | string | me_egad_data:site.124837 | ME0002893 | 48 |
| me_egad_EGAD-PFAS-Site | string | me_egad_data:site.131980 | ME0090540 | 13 |




## LinkML Source

<details>

```yaml
name: us_sdwis_hasPWSID
annotations:
  count:
    tag: count
    value: 61
description: No slot (predicate) description specified
examples:
- object:
    example_object: ME0002893
    example_object_type: string
    example_predicate: us_sdwis:hasPWSID
    example_subject: me_egad_data:site.124837
    example_subject_type: me_egad_EGAD-Site
- object:
    example_object: ME0090540
    example_object_type: string
    example_predicate: us_sdwis:hasPWSID
    example_subject: me_egad_data:site.131980
    example_subject_type: me_egad_EGAD-PFAS-Site
from_schema: sawgraph-kg
rank: 1000
slot_uri: us_sdwis:hasPWSID
alias: us_sdwis_hasPWSID
domain_of:
- me_egad_EGAD-PFAS-Site
- me_egad_EGAD-Site
range: string

```
</details>