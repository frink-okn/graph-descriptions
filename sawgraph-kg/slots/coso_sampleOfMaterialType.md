

# Slot: sample of material type (coso_sampleOfMaterialType)


_No slot (predicate) description specified_






This slot occurs 24273 times.


URI: [coso:sampleOfMaterialType](http://w3id.org/coso/v1/contaminoso#sampleOfMaterialType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleMaterialType](../classes/MeEgadEGAD-SampleMaterialType.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleMaterialTypeQualifier](../classes/MeEgadEGAD-SampleMaterialTypeQualifier.md)&nbsp;or&nbsp;<br />[CosoSampleMaterialType](../classes/CosoSampleMaterialType.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-Sample | me_egad_EGAD-SampleMaterialType | me_egad_data:sample.AAL210144001R.20210112 | me_egad_data:sampleMaterialType.MLK | 23004 |
| me_egad_EGAD-Sample | owl_NamedIndividual | me_egad_data:sample.AAL210144001R.20210112 | me_egad_data:sampleMaterialType.MLK | 24273 |
| me_egad_EGAD-Sample | me_egad_EGAD-SampleMaterialTypeQualifier | me_egad_data:sample.AAL211038502R.20210303 | me_egad_data:sampleMaterialTypeQualifier.TMR | 1269 |




## LinkML Source

<details>

```yaml
name: coso_sampleOfMaterialType
annotations:
  count:
    tag: count
    value: 24273
description: No slot (predicate) description specified
title: sample of material type
examples:
- object:
    example_object: me_egad_data:sampleMaterialType.MLK
    example_object_type: me_egad_EGAD-SampleMaterialType
    example_predicate: coso:sampleOfMaterialType
    example_subject: me_egad_data:sample.AAL210144001R.20210112
    example_subject_type: me_egad_EGAD-Sample
- object:
    example_object: me_egad_data:sampleMaterialType.MLK
    example_object_type: owl_NamedIndividual
    example_predicate: coso:sampleOfMaterialType
    example_subject: me_egad_data:sample.AAL210144001R.20210112
    example_subject_type: me_egad_EGAD-Sample
- object:
    example_object: me_egad_data:sampleMaterialTypeQualifier.TMR
    example_object_type: me_egad_EGAD-SampleMaterialTypeQualifier
    example_predicate: coso:sampleOfMaterialType
    example_subject: me_egad_data:sample.AAL211038502R.20210303
    example_subject_type: me_egad_EGAD-Sample
from_schema: sawgraph-kg
rank: 1000
domain: coso_MaterialSample
slot_uri: coso:sampleOfMaterialType
alias: coso_sampleOfMaterialType
domain_of:
- me_egad_EGAD-Sample
range: Any
any_of:
- range: me_egad_EGAD-SampleMaterialType
- range: owl_NamedIndividual
- range: me_egad_EGAD-SampleMaterialTypeQualifier
- range: coso_SampleMaterialType

```
</details>