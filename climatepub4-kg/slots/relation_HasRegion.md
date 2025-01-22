

# Slot: relation_HasRegion


_No slot (predicate) description specified_





URI: [relation:HasRegion](http://relation.org/HasRegion)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoDataset](../classes/HsdoDataset.md) | A body of structured information describing some topic(s) of interest |  no  |







## Properties

* Range: [HsdoLocation](../classes/HsdoLocation.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Dataset → hsdo_Location | https://climateKG.org/entity/fe64cea2-19de-470c-a919-b24c744c696b | relation:HasRegion | https://climateKG.org/entity/86163a89-c736-4f6a-a48e-a6ca7a1a06af |


## Comments

* 109 occurrences with subject type hsdo_Dataset and object type hsdo_Location.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | relation:HasRegion |
| native | climatepub4-kg/:relation_HasRegion |




## LinkML Source

<details>
```yaml
name: relation_HasRegion
description: No slot (predicate) description specified
comments:
- 109 occurrences with subject type hsdo_Dataset and object type hsdo_Location.
examples:
- description: hsdo_Dataset → hsdo_Location
  object:
    example_object: https://climateKG.org/entity/86163a89-c736-4f6a-a48e-a6ca7a1a06af
    example_object_type: hsdo_Location
    example_predicate: relation:HasRegion
    example_subject: https://climateKG.org/entity/fe64cea2-19de-470c-a919-b24c744c696b
    example_subject_type: hsdo_Dataset
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:HasRegion
alias: relation_HasRegion
domain_of:
- hsdo_Dataset
range: hsdo_Location

```
</details>