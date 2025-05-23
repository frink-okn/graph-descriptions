

# Slot: No slot (predicate) name specified (sockg_samplingStartStopInterval)


_No slot (predicate) description specified_






This slot occurs 891 times.


URI: [sockg:samplingStartStopInterval](https://idir.uta.edu/sockg-ontology/docs/samplingStartStopInterval)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | WaterQualityConc represents the concentration of various water quality parame... |  yes  |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | The GasNutrientLoss class represents the assessment of gaseous nutrient losse... |  yes  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | The WindErosionArea class represents regions affected by wind erosion, detail... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WaterQualityConc | string | sockg:individuals/364993 | Stop-Start | 812 |
| sockg_GasNutrientLoss | string | sockg:individuals/55858 | Stop-Start | 64 |
| sockg_WindErosionArea | string | sockg:individuals/624572 | Stop | 15 |




## LinkML Source

<details>

```yaml
name: sockg_samplingStartStopInterval
annotations:
  count:
    tag: count
    value: 891
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Stop-Start
    example_object_type: string
    example_predicate: sockg:samplingStartStopInterval
    example_subject: sockg:individuals/364993
    example_subject_type: sockg_WaterQualityConc
- object:
    example_object: Stop-Start
    example_object_type: string
    example_predicate: sockg:samplingStartStopInterval
    example_subject: sockg:individuals/55858
    example_subject_type: sockg_GasNutrientLoss
- object:
    example_object: Stop
    example_object_type: string
    example_predicate: sockg:samplingStartStopInterval
    example_subject: sockg:individuals/624572
    example_subject_type: sockg_WindErosionArea
from_schema: soc-kg
rank: 1000
slot_uri: sockg:samplingStartStopInterval
alias: sockg_samplingStartStopInterval
domain_of:
- sockg_GasNutrientLoss
- sockg_WaterQualityConc
- sockg_WindErosionArea
union_of:
- '{''domain'': ''sockg_GasNutrientLoss''}'
- '{''domain'': ''sockg_WaterQualityConc''}'
- '{''domain'': ''sockg_WaterQualityArea''}'
- '{''domain'': ''sockg_WindErosionArea''}'
range: string

```
</details>