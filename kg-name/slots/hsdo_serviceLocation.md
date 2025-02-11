

# Slot: hsdo_serviceLocation


_No slot (predicate) description specified_





URI: [hsdo:serviceLocation](http://schema.org/serviceLocation)



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
| hsdo_ServiceChannel → hsdo_Place | dreamkg:service/channel/P-6710596967858176 | hsdo:serviceLocation | dreamkg:service/location/6710596967858176 |


## Comments

* 87 occurrences with subject type hsdo_ServiceChannel and object type hsdo_Place.

## Identifier and Mapping Information







### Schema Source


* from schema: kg-name




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:serviceLocation |
| native | kg-name/:hsdo_serviceLocation |




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
    example_object: dreamkg:service/location/6710596967858176
    example_object_type: hsdo_Place
    example_predicate: hsdo:serviceLocation
    example_subject: dreamkg:service/channel/P-6710596967858176
    example_subject_type: hsdo_ServiceChannel
from_schema: kg-name
rank: 1000
slot_uri: hsdo:serviceLocation
alias: hsdo_serviceLocation
domain_of:
- hsdo_ServiceChannel
range: hsdo_Place

```
</details>