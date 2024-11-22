

# Slot: http___relation.org_HasSourceType


_TODO -- tell the world what this slot (predicate) describes._





URI: [http://relation.org/HasSourceType](http://relation.org/HasSourceType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohDataset](../classes/SdohDataset.md) | A body of structured information describing some topic(s) of interest |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdohExperiment](../classes/SdohExperiment.md)&nbsp;or&nbsp;<br />[SdohSourceType](../classes/SdohSourceType.md)






## Examples

| Value |
| --- |
| https://climateKG.org/entity/81fcbd3b-e74e-4285-bc87-928d5852d1cf http://relation.org/HasSourceType https://climateKG.org/entity/878e70de-f929-4d2f-9325-145ca95787e9 |
| https://climateKG.org/entity/fe64cea2-19de-470c-a919-b24c744c696b http://relation.org/HasSourceType https://climateKG.org/entity/7568d0fd-d892-4aa6-b724-594920455398 |

## Comments

* 6 occurrences with subject type sdoh_Dataset and object type sdoh_Experiment.
* 100 occurrences with subject type sdoh_Dataset and object type sdoh_Source_Type.

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
| self | http://relation.org/HasSourceType |
| native | climatepub4-kg/:http___relation.org_HasSourceType |




## LinkML Source

<details>
```yaml
name: http___relation.org_HasSourceType
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 6 occurrences with subject type sdoh_Dataset and object type sdoh_Experiment.
- 100 occurrences with subject type sdoh_Dataset and object type sdoh_Source_Type.
examples:
- value: https://climateKG.org/entity/81fcbd3b-e74e-4285-bc87-928d5852d1cf http://relation.org/HasSourceType
    https://climateKG.org/entity/878e70de-f929-4d2f-9325-145ca95787e9
- value: https://climateKG.org/entity/fe64cea2-19de-470c-a919-b24c744c696b http://relation.org/HasSourceType
    https://climateKG.org/entity/7568d0fd-d892-4aa6-b724-594920455398
from_schema: climatepub4-kg
rank: 1000
slot_uri: http://relation.org/HasSourceType
alias: http___relation.org_HasSourceType
domain_of:
- sdoh_Dataset
range: Any
any_of:
- range: sdoh_Experiment
- range: sdoh_Source_Type

```
</details>