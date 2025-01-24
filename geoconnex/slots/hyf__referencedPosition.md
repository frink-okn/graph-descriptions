

# Slot: hyf__referencedPosition


_No slot (predicate) description specified_





URI: [hyf:/referencedPosition](https://www.opengis.net/def/schema/hy_features/hyf/referencedPosition)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HyfHYHydroLocation](../classes/HyfHYHydroLocation.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hyf__HY_HydroLocation → uri | https://geoconnex.us/iow/demo/AL00017 | hyf:/referencedPosition | https://gleaner.io/xid/genid/cktus4kip8t1e5gibka0 |


## Comments

* 481919 occurrences with subject type hyf__HY_HydroLocation and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hyf:/referencedPosition |
| native | geoconnex/:hyf__referencedPosition |




## LinkML Source

<details>
```yaml
name: hyf__referencedPosition
description: No slot (predicate) description specified
comments:
- 481919 occurrences with subject type hyf__HY_HydroLocation and object type uri.
examples:
- description: hyf__HY_HydroLocation → uri
  object:
    example_object: https://gleaner.io/xid/genid/cktus4kip8t1e5gibka0
    example_predicate: hyf:/referencedPosition
    example_subject: https://geoconnex.us/iow/demo/AL00017
from_schema: geoconnex
rank: 1000
slot_uri: hyf:/referencedPosition
alias: hyf__referencedPosition
domain_of:
- hyf__HY_HydroLocation
range: uri

```
</details>