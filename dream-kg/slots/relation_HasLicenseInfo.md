

# Slot: relation_HasLicenseInfo


_No slot (predicate) description specified_






This slot occurs 131 times.


URI: [relation:HasLicenseInfo](http://relation.org/HasLicenseInfo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md) | No class (type) description specified |  yes  |
| [HsdoScienceKeyword](../classes/HsdoScienceKeyword.md) | No class (type) description specified |  yes  |
| [HsdoModels](../classes/HsdoModels.md) | No class (type) description specified |  yes  |
| [HsdoExperiment](../classes/HsdoExperiment.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HsdoLicense](../classes/HsdoLicense.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Cmip6_Source_Id | hsdo_License | https://climateKG.org/entity/0cd4d2c4-ebfa-4759-b7aa-f9982122f581 | https://climateKG.org/entity/95c7e601-fcfe-4fc9-9994-8105a1e11428 | 131 |
| hsdo_Models | hsdo_License | https://climateKG.org/entity/0cd4d2c4-ebfa-4759-b7aa-f9982122f581 | https://climateKG.org/entity/95c7e601-fcfe-4fc9-9994-8105a1e11428 | 131 |
| hsdo_Science_Keyword | hsdo_License | https://climateKG.org/entity/0cd4d2c4-ebfa-4759-b7aa-f9982122f581 | https://climateKG.org/entity/95c7e601-fcfe-4fc9-9994-8105a1e11428 | 131 |
| hsdo_Experiment | hsdo_License | https://climateKG.org/entity/f2c510b5-e0dc-413f-a7a2-35791cb07090 | https://climateKG.org/entity/95c7e601-fcfe-4fc9-9994-8105a1e11428 | 1 |




## LinkML Source

<details>

```yaml
name: relation_HasLicenseInfo
annotations:
  count:
    tag: count
    value: 131
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://climateKG.org/entity/95c7e601-fcfe-4fc9-9994-8105a1e11428
    example_object_type: hsdo_License
    example_predicate: relation:HasLicenseInfo
    example_subject: https://climateKG.org/entity/0cd4d2c4-ebfa-4759-b7aa-f9982122f581
    example_subject_type: hsdo_Cmip6_Source_Id
- object:
    example_object: https://climateKG.org/entity/95c7e601-fcfe-4fc9-9994-8105a1e11428
    example_object_type: hsdo_License
    example_predicate: relation:HasLicenseInfo
    example_subject: https://climateKG.org/entity/0cd4d2c4-ebfa-4759-b7aa-f9982122f581
    example_subject_type: hsdo_Models
- object:
    example_object: https://climateKG.org/entity/95c7e601-fcfe-4fc9-9994-8105a1e11428
    example_object_type: hsdo_License
    example_predicate: relation:HasLicenseInfo
    example_subject: https://climateKG.org/entity/0cd4d2c4-ebfa-4759-b7aa-f9982122f581
    example_subject_type: hsdo_Science_Keyword
- object:
    example_object: https://climateKG.org/entity/95c7e601-fcfe-4fc9-9994-8105a1e11428
    example_object_type: hsdo_License
    example_predicate: relation:HasLicenseInfo
    example_subject: https://climateKG.org/entity/f2c510b5-e0dc-413f-a7a2-35791cb07090
    example_subject_type: hsdo_Experiment
from_schema: dream-kg
rank: 1000
slot_uri: relation:HasLicenseInfo
alias: relation_HasLicenseInfo
domain_of:
- hsdo_Cmip6_Source_Id
- hsdo_Experiment
- hsdo_Models
- hsdo_Science_Keyword
range: hsdo_License

```
</details>