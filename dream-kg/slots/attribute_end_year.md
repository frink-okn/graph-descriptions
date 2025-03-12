

# Slot: attribute_end_year


_No slot (predicate) description specified_






This slot occurs 322 times.


URI: [attribute:end_year](http://attribute.org/end_year)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoModel](../classes/HsdoModel.md) | No class (type) description specified |  yes  |
| [HsdoExperiment](../classes/HsdoExperiment.md) | No class (type) description specified |  yes  |
| [HsdoLocation](../classes/HsdoLocation.md) | No class (type) description specified |  yes  |
| [HsdoProject](../classes/HsdoProject.md) | An enterprise (potentially individual but typically collaborative), planned t... |  yes  |
| [HsdoProvider](../classes/HsdoProvider.md) | No class (type) description specified |  yes  |
| [HsdoVariable](../classes/HsdoVariable.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Experiment | string | https://climateKG.org/entity/033c6854-b6b0-47b7-b41d-6c482932f336 |  | 322 |
| hsdo_Model | string | https://climateKG.org/entity/0f07d4c2-cfee-43ff-86d1-289058fe5050 | 2100 or 2300 | 4 |
| hsdo_Location | string | https://climateKG.org/entity/20dea6db-e5d4-42a9-a1d5-0421c65fced8 | 2014 | 3 |
| hsdo_Provider | string | https://climateKG.org/entity/20dea6db-e5d4-42a9-a1d5-0421c65fced8 | 2014 | 2 |
| hsdo_Variable | string | https://climateKG.org/entity/20dea6db-e5d4-42a9-a1d5-0421c65fced8 | 2014 | 5 |
| hsdo_Project | string | https://climateKG.org/entity/4c94cb2e-37fb-4a76-a69b-a9d0731dbe3c |  | 4 |




## LinkML Source

<details>

```yaml
name: attribute_end_year
annotations:
  count:
    tag: count
    value: 322
description: No slot (predicate) description specified
examples:
- object:
    example_object: ''
    example_object_type: string
    example_predicate: attribute:end_year
    example_subject: https://climateKG.org/entity/033c6854-b6b0-47b7-b41d-6c482932f336
    example_subject_type: hsdo_Experiment
- object:
    example_object: 2100 or 2300
    example_object_type: string
    example_predicate: attribute:end_year
    example_subject: https://climateKG.org/entity/0f07d4c2-cfee-43ff-86d1-289058fe5050
    example_subject_type: hsdo_Model
- object:
    example_object: '2014'
    example_object_type: string
    example_predicate: attribute:end_year
    example_subject: https://climateKG.org/entity/20dea6db-e5d4-42a9-a1d5-0421c65fced8
    example_subject_type: hsdo_Location
- object:
    example_object: '2014'
    example_object_type: string
    example_predicate: attribute:end_year
    example_subject: https://climateKG.org/entity/20dea6db-e5d4-42a9-a1d5-0421c65fced8
    example_subject_type: hsdo_Provider
- object:
    example_object: '2014'
    example_object_type: string
    example_predicate: attribute:end_year
    example_subject: https://climateKG.org/entity/20dea6db-e5d4-42a9-a1d5-0421c65fced8
    example_subject_type: hsdo_Variable
- object:
    example_object: ''
    example_object_type: string
    example_predicate: attribute:end_year
    example_subject: https://climateKG.org/entity/4c94cb2e-37fb-4a76-a69b-a9d0731dbe3c
    example_subject_type: hsdo_Project
from_schema: dream-kg
rank: 1000
slot_uri: attribute:end_year
alias: attribute_end_year
domain_of:
- hsdo_Experiment
- hsdo_Location
- hsdo_Model
- hsdo_Project
- hsdo_Provider
- hsdo_Variable
range: string

```
</details>