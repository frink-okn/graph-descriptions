

# Slot: relation_HasInstitution


_TODO -- tell the world what this slot (predicate) describes._





URI: [relation:HasInstitution](http://relation.org/HasInstitution)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoDataset](../classes/HsdoDataset.md) | A body of structured information describing some topic(s) of interest |  no  |
| [HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [HsdoInstitution](../classes/HsdoInstitution.md)






## Examples

| Value |
| --- |
| https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 relation:HasInstitution https://climateKG.org/entity/6ebec28f-5920-492b-856e-7fe9a9d7eca3 |
| https://climateKG.org/entity/fe64cea2-19de-470c-a919-b24c744c696b relation:HasInstitution https://climateKG.org/entity/caf10913-e092-4008-a6cb-f7efe8037047 |

## Comments

* 154 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Institution.
* 103 occurrences with subject type hsdo_Dataset and object type hsdo_Institution.

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
| self | relation:HasInstitution |
| native | climatepub4-kg/:relation_HasInstitution |




## LinkML Source

<details>
```yaml
name: relation_HasInstitution
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 154 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_Institution.
- 103 occurrences with subject type hsdo_Dataset and object type hsdo_Institution.
examples:
- value: https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 relation:HasInstitution
    https://climateKG.org/entity/6ebec28f-5920-492b-856e-7fe9a9d7eca3
- value: https://climateKG.org/entity/fe64cea2-19de-470c-a919-b24c744c696b relation:HasInstitution
    https://climateKG.org/entity/caf10913-e092-4008-a6cb-f7efe8037047
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:HasInstitution
alias: relation_HasInstitution
domain_of:
- hsdo_Cmip6_Source_Id
- hsdo_Dataset
range: hsdo_Institution

```
</details>