

# Slot: hyf__HY_HydroLocationType


_No slot (predicate) description specified_





URI: [hyf:/HY_HydroLocationType](https://www.opengis.net/def/schema/hy_features/hyf/HY_HydroLocationType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HyfHYHydroLocation](../classes/HyfHYHydroLocation.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hyf__HY_HydroLocation → string | https://geoconnex.us/iow/demo/AL00017 | hyf:/HY_HydroLocationType | hydrometricStation |


## Comments

* 187886 occurrences with subject type hyf__HY_HydroLocation and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hyf:/HY_HydroLocationType |
| native | geoconnex/:hyf__HY_HydroLocationType |




## LinkML Source

<details>
```yaml
name: hyf__HY_HydroLocationType
description: No slot (predicate) description specified
comments:
- 187886 occurrences with subject type hyf__HY_HydroLocation and object type string.
examples:
- description: hyf__HY_HydroLocation → string
  object:
    example_object: hydrometricStation
    example_predicate: hyf:/HY_HydroLocationType
    example_subject: https://geoconnex.us/iow/demo/AL00017
from_schema: geoconnex
rank: 1000
slot_uri: hyf:/HY_HydroLocationType
alias: hyf__HY_HydroLocationType
domain_of:
- hyf__HY_HydroLocation
range: string

```
</details>