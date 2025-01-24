

# Slot: hyf__HydroLocationType


_No slot (predicate) description specified_





URI: [hyf:/HydroLocationType](https://www.opengis.net/def/schema/hy_features/hyf/HydroLocationType)



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
| hyf__HY_HydroLocation → string | https://sta.geoconnex.dev/collections/USGS/Things/items/'AR008-334933091153501' | hyf:/HydroLocationType | Well |


## Comments

* 13471 occurrences with subject type hyf__HY_HydroLocation and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hyf:/HydroLocationType |
| native | geoconnex/:hyf__HydroLocationType |




## LinkML Source

<details>
```yaml
name: hyf__HydroLocationType
description: No slot (predicate) description specified
comments:
- 13471 occurrences with subject type hyf__HY_HydroLocation and object type string.
examples:
- description: hyf__HY_HydroLocation → string
  object:
    example_object: Well
    example_predicate: hyf:/HydroLocationType
    example_subject: https://sta.geoconnex.dev/collections/USGS/Things/items/'AR008-334933091153501'
from_schema: geoconnex
rank: 1000
slot_uri: hyf:/HydroLocationType
alias: hyf__HydroLocationType
domain_of:
- hyf__HY_HydroLocation
range: string

```
</details>