

# Slot: hyf_referencedPosition


_No slot (predicate) description specified_





URI: [hyf:referencedPosition](https://www.opengis.net/def/schema/hy_features/hyfreferencedPosition)



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
| hyf__HY_HydroLocation → uri | https://geoconnex.us/ref/gages/1030898 | hyf:referencedPosition | _:b1064787 |


## Comments

* 10 occurrences with subject type hyf__HY_HydroLocation and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hyf:referencedPosition |
| native | geoconnex/:hyf_referencedPosition |




## LinkML Source

<details>
```yaml
name: hyf_referencedPosition
description: No slot (predicate) description specified
comments:
- 10 occurrences with subject type hyf__HY_HydroLocation and object type uri.
examples:
- description: hyf__HY_HydroLocation → uri
  object:
    example_object: _:b1064787
    example_predicate: hyf:referencedPosition
    example_subject: https://geoconnex.us/ref/gages/1030898
from_schema: geoconnex
rank: 1000
slot_uri: hyf:referencedPosition
alias: hyf_referencedPosition
domain_of:
- hyf__HY_HydroLocation
range: uri

```
</details>