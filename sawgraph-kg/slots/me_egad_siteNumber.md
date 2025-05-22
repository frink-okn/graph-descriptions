

# Slot: site number (me_egad_siteNumber)


_Site number in the EGAD dataset from the state of Maine._






This slot occurs 957 times.


URI: [me_egad:siteNumber](http://sawgraph.spatialai.org/v1/me-egad#siteNumber)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Site](../classes/MeEgadEGAD-Site.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-Site | integer | me_egad_data:site.100843 | 100843 | 912 |
| me_egad_EGAD-PFAS-Site | integer | me_egad_data:site.131980 | 131980 | 45 |




## LinkML Source

<details>

```yaml
name: me_egad_siteNumber
annotations:
  count:
    tag: count
    value: 957
description: Site number in the EGAD dataset from the state of Maine.
title: site number
examples:
- object:
    example_object: '100843'
    example_object_type: integer
    example_predicate: me_egad:siteNumber
    example_subject: me_egad_data:site.100843
    example_subject_type: me_egad_EGAD-Site
- object:
    example_object: '131980'
    example_object_type: integer
    example_predicate: me_egad:siteNumber
    example_subject: me_egad_data:site.131980
    example_subject_type: me_egad_EGAD-PFAS-Site
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:siteNumber
alias: me_egad_siteNumber
domain_of:
- me_egad_EGAD-PFAS-Site
- me_egad_EGAD-Site
subproperty_of: dct_identifier
range: integer

```
</details>