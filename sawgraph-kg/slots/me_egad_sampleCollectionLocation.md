

# Slot: egad - sample collection location (me_egad_sampleCollectionLocation)


_No slot (predicate) description specified_






This slot occurs 15556 times.


URI: [me_egad:sampleCollectionLocation](http://sawgraph.spatialai.org/v1/me-egad#sampleCollectionLocation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleDetailedLocation](../classes/MeEgadEGAD-SampleDetailedLocation.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-Sample | me_egad_EGAD-SampleDetailedLocation | me_egad_data:sample.AAL217134101.20211228 | me_egad_data:sampleLocation.T | 15556 |
| me_egad_EGAD-Sample | owl_NamedIndividual | me_egad_data:sample.AAL217134101.20211228 | me_egad_data:sampleLocation.T | 15556 |




## LinkML Source

<details>

```yaml
name: me_egad_sampleCollectionLocation
annotations:
  count:
    tag: count
    value: 15556
description: No slot (predicate) description specified
title: egad - sample collection location
examples:
- object:
    example_object: me_egad_data:sampleLocation.T
    example_object_type: me_egad_EGAD-SampleDetailedLocation
    example_predicate: me_egad:sampleCollectionLocation
    example_subject: me_egad_data:sample.AAL217134101.20211228
    example_subject_type: me_egad_EGAD-Sample
- object:
    example_object: me_egad_data:sampleLocation.T
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:sampleCollectionLocation
    example_subject: me_egad_data:sample.AAL217134101.20211228
    example_subject_type: me_egad_EGAD-Sample
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:sampleCollectionLocation
alias: me_egad_sampleCollectionLocation
domain_of:
- me_egad_EGAD-Sample
subproperty_of: coso_sampleAnnotation
range: Any
any_of:
- range: me_egad_EGAD-SampleDetailedLocation
- range: owl_NamedIndividual

```
</details>