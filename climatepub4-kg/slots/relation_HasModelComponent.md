

# Slot: relation_HasModelComponent


_No slot description provided_





URI: [relation:HasModelComponent](http://relation.org/HasModelComponent)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoProvider](../classes/HsdoProvider.md)&nbsp;or&nbsp;<br />[HsdoLocation](../classes/HsdoLocation.md)&nbsp;or&nbsp;<br />[HsdoRealm](../classes/HsdoRealm.md)&nbsp;or&nbsp;<br />[HsdoExperiment](../classes/HsdoExperiment.md)






## Examples

| Value |
| --- |
| https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 relation:HasModelComponent https://climateKG.org/entity/6dc62d63-4e16-4187-a136-e91183c0c2a9 |
| https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 relation:HasModelComponent https://climateKG.org/entity/5668f6df-ab5a-4991-9720-dda2faae7f3e |
| https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 relation:HasModelComponent https://climateKG.org/entity/e2e53a45-c6ee-4fac-9c08-7677c1318533 |
| https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 relation:HasModelComponent https://climateKG.org/entity/fac06b86-cd69-418f-86f6-b14d60d37cfd |

## Comments

* 237 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Realm.
* 195 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Location.
* 122 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Experiment.
* 123 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Provider.

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
| self | relation:HasModelComponent |
| native | climatepub4-kg/:relation_HasModelComponent |




## LinkML Source

<details>
```yaml
name: relation_HasModelComponent
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 237 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Realm.
- 195 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Location.
- 122 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Experiment.
- 123 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Provider.
examples:
- value: https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 relation:HasModelComponent
    https://climateKG.org/entity/6dc62d63-4e16-4187-a136-e91183c0c2a9
- value: https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 relation:HasModelComponent
    https://climateKG.org/entity/5668f6df-ab5a-4991-9720-dda2faae7f3e
- value: https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 relation:HasModelComponent
    https://climateKG.org/entity/e2e53a45-c6ee-4fac-9c08-7677c1318533
- value: https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 relation:HasModelComponent
    https://climateKG.org/entity/fac06b86-cd69-418f-86f6-b14d60d37cfd
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:HasModelComponent
alias: relation_HasModelComponent
domain_of:
- hsdo_Cmip6_Source_Id
range: Any
any_of:
- range: hsdo_Provider
- range: hsdo_Location
- range: hsdo_Realm
- range: hsdo_Experiment

```
</details>