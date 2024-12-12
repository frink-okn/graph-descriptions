

# Slot: hsdo_serviceLocation


_No slot (predicate) description specified_





URI: [hsdo:serviceLocation](hsdo:serviceLocation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoServiceChannel](../classes/HsdoServiceChannel.md) | A means for accessing a service, e |  no  |







## Properties

* Range: [HsdoPlace](../classes/HsdoPlace.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_ServiceChannel → hsdo_Place | dreamkg:service/channel/P-5640139036164096 | hsdo:serviceLocation | dreamkg:service/location/5640139036164096 |


## Comments

* 87 occurrences with subject type hsdo_ServiceChannel and object type hsdo_Place.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:serviceLocation |
| native | dream-kg/:hsdo_serviceLocation |




## LinkML Source

<details>
```yaml
name: hsdo_serviceLocation
description: No slot (predicate) description specified
comments:
- 87 occurrences with subject type hsdo_ServiceChannel and object type hsdo_Place.
examples:
- description: hsdo_ServiceChannel → hsdo_Place
  object:
    example_object: dreamkg:service/location/5640139036164096
    example_predicate: hsdo:serviceLocation
    example_subject: dreamkg:service/channel/P-5640139036164096
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:serviceLocation
alias: hsdo_serviceLocation
domain_of:
- hsdo_ServiceChannel
range: hsdo_Place

```
</details>