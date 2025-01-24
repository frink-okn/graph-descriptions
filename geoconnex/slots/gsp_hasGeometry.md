

# Slot: gsp_hasGeometry


_No slot (predicate) description specified_





URI: [gsp:hasGeometry](gsp:hasGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |
| [HyfHYHydroLocation](../classes/HyfHYHydroLocation.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Sf#Point](../classes/Sf#Point.md)&nbsp;or&nbsp;<br />[Sf#Polygon](../classes/Sf#Polygon.md)&nbsp;or&nbsp;<br />[Sf#MultiPolygon](../classes/Sf#MultiPolygon.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → sf_#Point | https://geoconnex.us/ref/dams/1096875 | gsp:hasGeometry | https://gleaner.io/xid/genid/cl2fibsip8tadg8qd2i0 |
| hyf__HY_HydroLocation → sf_#Point | https://geoconnex.us/ref/gages/1168507 | gsp:hasGeometry | https://gleaner.io/xid/genid/cl2gf1kip8tadg8qd86g |
| schema_Place → sf_#MultiPolygon | https://geoconnex.us/ref/pws/WI8260121 | gsp:hasGeometry | https://gleaner.io/xid/genid/cl2f8u4ip8tadg8qcvtg |
| schema_Place → sf_#Polygon | https://geoconnex.us/ref/pws/WV3303609 | gsp:hasGeometry | https://gleaner.io/xid/genid/cl2gam4ip8tadg8qd740 |


## Comments

* 187 occurrences with subject type schema_Place and object type sf_#Point.
* 77 occurrences with subject type hyf__HY_HydroLocation and object type sf_#Point.
* 353 occurrences with subject type schema_Place and object type sf_#MultiPolygon.
* 171 occurrences with subject type schema_Place and object type sf_#Polygon.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | gsp:hasGeometry |
| native | geoconnex/:gsp_hasGeometry |




## LinkML Source

<details>
```yaml
name: gsp_hasGeometry
description: No slot (predicate) description specified
comments:
- 187 occurrences with subject type schema_Place and object type sf_#Point.
- 77 occurrences with subject type hyf__HY_HydroLocation and object type sf_#Point.
- 353 occurrences with subject type schema_Place and object type sf_#MultiPolygon.
- 171 occurrences with subject type schema_Place and object type sf_#Polygon.
examples:
- description: schema_Place → sf_#Point
  object:
    example_object: https://gleaner.io/xid/genid/cl2fibsip8tadg8qd2i0
    example_predicate: gsp:hasGeometry
    example_subject: https://geoconnex.us/ref/dams/1096875
- description: hyf__HY_HydroLocation → sf_#Point
  object:
    example_object: https://gleaner.io/xid/genid/cl2gf1kip8tadg8qd86g
    example_predicate: gsp:hasGeometry
    example_subject: https://geoconnex.us/ref/gages/1168507
- description: schema_Place → sf_#MultiPolygon
  object:
    example_object: https://gleaner.io/xid/genid/cl2f8u4ip8tadg8qcvtg
    example_predicate: gsp:hasGeometry
    example_subject: https://geoconnex.us/ref/pws/WI8260121
- description: schema_Place → sf_#Polygon
  object:
    example_object: https://gleaner.io/xid/genid/cl2gam4ip8tadg8qd740
    example_predicate: gsp:hasGeometry
    example_subject: https://geoconnex.us/ref/pws/WV3303609
from_schema: geoconnex
rank: 1000
slot_uri: gsp:hasGeometry
alias: gsp_hasGeometry
domain_of:
- hyf__HY_HydroLocation
- schema_Place
range: Any
any_of:
- range: sf_#Point
- range: sf_#Polygon
- range: sf_#MultiPolygon

```
</details>