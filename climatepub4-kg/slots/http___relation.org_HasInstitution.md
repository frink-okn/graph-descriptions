

# Slot: http___relation.org_HasInstitution


_TODO -- tell the world what this slot (predicate) describes._





URI: [http://relation.org/HasInstitution](http://relation.org/HasInstitution)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohDataset](../classes/SdohDataset.md) | A body of structured information describing some topic(s) of interest |  no  |
| [SdohCmip6SourceId](../classes/SdohCmip6SourceId.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [SdohInstitution](../classes/SdohInstitution.md)






## Examples

| Value |
| --- |
| https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 http://relation.org/HasInstitution https://climateKG.org/entity/6ebec28f-5920-492b-856e-7fe9a9d7eca3 |
| https://climateKG.org/entity/fe64cea2-19de-470c-a919-b24c744c696b http://relation.org/HasInstitution https://climateKG.org/entity/caf10913-e092-4008-a6cb-f7efe8037047 |

## Comments

* 154 occurrences with subject type sdoh_Cmip6_Source_Id and object type sdoh_Institution.
* 103 occurrences with subject type sdoh_Dataset and object type sdoh_Institution.

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
| self | http://relation.org/HasInstitution |
| native | climatepub4-kg/:http___relation.org_HasInstitution |




## LinkML Source

<details>
```yaml
name: http___relation.org_HasInstitution
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 154 occurrences with subject type sdoh_Cmip6_Source_Id and object type sdoh_Institution.
- 103 occurrences with subject type sdoh_Dataset and object type sdoh_Institution.
examples:
- value: https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 http://relation.org/HasInstitution
    https://climateKG.org/entity/6ebec28f-5920-492b-856e-7fe9a9d7eca3
- value: https://climateKG.org/entity/fe64cea2-19de-470c-a919-b24c744c696b http://relation.org/HasInstitution
    https://climateKG.org/entity/caf10913-e092-4008-a6cb-f7efe8037047
from_schema: climatepub4-kg
rank: 1000
slot_uri: http://relation.org/HasInstitution
alias: http___relation.org_HasInstitution
domain_of:
- sdoh_Cmip6_Source_Id
- sdoh_Dataset
range: sdoh_Institution

```
</details>