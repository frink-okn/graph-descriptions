

# Slot: http___relation.org_HasAdditionalAllowedModelComponents


_TODO -- tell the world what this slot (predicate) describes._





URI: [http://relation.org/HasAdditionalAllowedModelComponents](http://relation.org/HasAdditionalAllowedModelComponents)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohExperiment](../classes/SdohExperiment.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdohProvider](../classes/SdohProvider.md)&nbsp;or&nbsp;<br />[SdohExperiment](../classes/SdohExperiment.md)&nbsp;or&nbsp;<br />[SdohSourceType](../classes/SdohSourceType.md)






## Examples

| Value |
| --- |
| https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 http://relation.org/HasAdditionalAllowedModelComponents https://climateKG.org/entity/3b16a2e8-cc4d-40ce-a6c8-336bea211078 |
| https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 http://relation.org/HasAdditionalAllowedModelComponents https://climateKG.org/entity/910d9fdb-84fe-4f62-9172-41888cc181a4 |
| https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 http://relation.org/HasAdditionalAllowedModelComponents https://climateKG.org/entity/eb6ac594-7a26-4220-a587-4f2200e5dca6 |

## Comments

* 239 occurrences with subject type sdoh_Experiment and object type sdoh_Provider.
* 216 occurrences with subject type sdoh_Experiment and object type sdoh_Experiment.
* 251 occurrences with subject type sdoh_Experiment and object type sdoh_Source_Type.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://relation.org/HasAdditionalAllowedModelComponents |
| native | climatepub4-kg/:http___relation.org_HasAdditionalAllowedModelComponents |




## LinkML Source

<details>
```yaml
name: http___relation.org_HasAdditionalAllowedModelComponents
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 239 occurrences with subject type sdoh_Experiment and object type sdoh_Provider.
- 216 occurrences with subject type sdoh_Experiment and object type sdoh_Experiment.
- 251 occurrences with subject type sdoh_Experiment and object type sdoh_Source_Type.
examples:
- value: https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 http://relation.org/HasAdditionalAllowedModelComponents
    https://climateKG.org/entity/3b16a2e8-cc4d-40ce-a6c8-336bea211078
- value: https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 http://relation.org/HasAdditionalAllowedModelComponents
    https://climateKG.org/entity/910d9fdb-84fe-4f62-9172-41888cc181a4
- value: https://climateKG.org/entity/ffcfde92-a161-4705-a7c6-7e400b5fb4e9 http://relation.org/HasAdditionalAllowedModelComponents
    https://climateKG.org/entity/eb6ac594-7a26-4220-a587-4f2200e5dca6
from_schema: climatepub4-kg
rank: 1000
slot_uri: http://relation.org/HasAdditionalAllowedModelComponents
alias: http___relation.org_HasAdditionalAllowedModelComponents
domain_of:
- sdoh_Experiment
range: Any
any_of:
- range: sdoh_Provider
- range: sdoh_Experiment
- range: sdoh_Source_Type

```
</details>