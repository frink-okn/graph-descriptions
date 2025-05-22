

# Slot: No slot (predicate) name specified -- this slot is noted as a subproperty of another slot in this graph but has not itself been defined. (skos_altLabel)


_No slot (predicate) description specified_






This slot occurs 8144 times.


URI: [skos:altLabel](http://www.w3.org/2004/02/skos/core#altLabel)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-PFAS-ParameterName](../classes/MeEgadEGAD-PFAS-ParameterName.md) | No class (type) description specified |  no  |
| [CosoSubstance](../classes/CosoSubstance.md) | No class (type) description specified |  no  |
| [CosoSubstanceCollection](../classes/CosoSubstanceCollection.md) | No class (type) description specified |  no  |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-SamplePoint | string | me_egad_data:samplePoint.100410 | B-5 | 8040 |
| owl_NamedIndividual | string | me_egad_data:parameter.10-2_FTS_A | 10:2 FTS_A | 104 |




## LinkML Source

<details>

```yaml
name: skos_altLabel
annotations:
  count:
    tag: count
    value: 8144
description: No slot (predicate) description specified
title: No slot (predicate) name specified -- this slot is noted as a subproperty of
  another slot in this graph but has not itself been defined.
examples:
- object:
    example_object: B-5
    example_object_type: string
    example_predicate: skos:altLabel
    example_subject: me_egad_data:samplePoint.100410
    example_subject_type: me_egad_EGAD-SamplePoint
- object:
    example_object: 10:2 FTS_A
    example_object_type: string
    example_predicate: skos:altLabel
    example_subject: me_egad_data:parameter.10-2_FTS_A
    example_subject_type: owl_NamedIndividual
from_schema: sawgraph-kg
rank: 1000
slot_uri: skos:altLabel
alias: skos_altLabel
domain_of:
- owl_NamedIndividual
- coso_Substance
- coso_SubstanceCollection
- me_egad_EGAD-PFAS-ParameterName
- me_egad_EGAD-SamplePoint
range: string

```
</details>