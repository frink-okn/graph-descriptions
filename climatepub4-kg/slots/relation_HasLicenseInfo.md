

# Slot: relation_HasLicenseInfo


_No slot (predicate) description specified_





URI: [relation:HasLicenseInfo](http://relation.org/HasLicenseInfo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoCmip6SourceId](../classes/HsdoCmip6SourceId.md) | No class (type) description specified |  no  |







## Properties

* Range: [HsdoLicense](../classes/HsdoLicense.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Cmip6_Source_Id → hsdo_License | https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7 | relation:HasLicenseInfo | https://climateKG.org/entity/95c7e601-fcfe-4fc9-9994-8105a1e11428 |


## Comments

* 131 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_License.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | relation:HasLicenseInfo |
| native | climatepub4-kg/:relation_HasLicenseInfo |




## LinkML Source

<details>
```yaml
name: relation_HasLicenseInfo
description: No slot (predicate) description specified
comments:
- 131 occurrences with subject type hsdo_Cmip6_Source_Id and object type hsdo_License.
examples:
- description: hsdo_Cmip6_Source_Id → hsdo_License
  object:
    example_object: https://climateKG.org/entity/95c7e601-fcfe-4fc9-9994-8105a1e11428
    example_object_type: hsdo_License
    example_predicate: relation:HasLicenseInfo
    example_subject: https://climateKG.org/entity/ffa6f7e9-e7e0-494d-84e4-41544a1762e7
    example_subject_type: hsdo_Cmip6_Source_Id
from_schema: climatepub4-kg
rank: 1000
slot_uri: relation:HasLicenseInfo
alias: relation_HasLicenseInfo
domain_of:
- hsdo_Cmip6_Source_Id
range: hsdo_License

```
</details>