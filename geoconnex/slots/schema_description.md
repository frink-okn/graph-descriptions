

# Slot: schema_description


_No slot (predicate) description specified_





URI: [schema:description](https://schema.org/description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaDataset](../classes/SchemaDataset.md) | A body of structured information describing some topic(s) of interest |  no  |
| [SchemaPropertyValue](../classes/SchemaPropertyValue.md) | A property-value pair, e |  no  |
| [HyfHYHydroLocation](../classes/HyfHYHydroLocation.md) | No class (type) description specified |  no  |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Dataset → string | _:b1000000 | schema:description | Temperature, water / USGS-293229091230800-40caf7117fe1485c9263289eb6b6205d |
| schema_PropertyValue → string | _:b1000007 | schema:description | Gage height in ft |
| None → string | https://gleaner.io/xid/genid/ckt9vv4ip8t5kr9ueha0 | schema:description | Location of well where measurements are made |
| hyf__HY_HydroLocation → string | https://geoconnex.us/iow/demo/AL00017 | schema:description | Monitoring Location at BIG CREEK |
| schema_Place → string | https://geoconnex.us/nmwdi/st/locations/1 | schema:description | Well drilled or set into subsurface for the purposes of pumping water or monitoring groundwater |


## Comments

* 28216 occurrences with subject type schema_Dataset and object type string.
* 28217 occurrences with subject type schema_PropertyValue and object type string.
* 17510 occurrences with untyped subjects and object type string.
* 187886 occurrences with subject type hyf__HY_HydroLocation and object type string.
* 107289 occurrences with subject type schema_Place and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:description |
| native | geoconnex/:schema_description |




## LinkML Source

<details>
```yaml
name: schema_description
description: No slot (predicate) description specified
comments:
- 28216 occurrences with subject type schema_Dataset and object type string.
- 28217 occurrences with subject type schema_PropertyValue and object type string.
- 17510 occurrences with untyped subjects and object type string.
- 187886 occurrences with subject type hyf__HY_HydroLocation and object type string.
- 107289 occurrences with subject type schema_Place and object type string.
examples:
- description: schema_Dataset → string
  object:
    example_object: Temperature, water / USGS-293229091230800-40caf7117fe1485c9263289eb6b6205d
    example_predicate: schema:description
    example_subject: _:b1000000
- description: schema_PropertyValue → string
  object:
    example_object: Gage height in ft
    example_predicate: schema:description
    example_subject: _:b1000007
- description: None → string
  object:
    example_object: Location of well where measurements are made
    example_predicate: schema:description
    example_subject: https://gleaner.io/xid/genid/ckt9vv4ip8t5kr9ueha0
- description: hyf__HY_HydroLocation → string
  object:
    example_object: Monitoring Location at BIG CREEK
    example_predicate: schema:description
    example_subject: https://geoconnex.us/iow/demo/AL00017
- description: schema_Place → string
  object:
    example_object: Well drilled or set into subsurface for the purposes of pumping
      water or monitoring groundwater
    example_predicate: schema:description
    example_subject: https://geoconnex.us/nmwdi/st/locations/1
from_schema: geoconnex
rank: 1000
slot_uri: schema:description
alias: schema_description
domain_of:
- hyf__HY_HydroLocation
- schema_Dataset
- schema_Place
- schema_PropertyValue
range: string

```
</details>