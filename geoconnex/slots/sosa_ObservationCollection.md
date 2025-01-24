

# Slot: sosa_ObservationCollection


_No slot (predicate) description specified_





URI: [sosa:ObservationCollection](http://www.w3.org/ns/sosa/ObservationCollection)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → string | https://geoconnex.us/nmwdi/st/locations/1 | sosa:ObservationCollection | https://locations.newmexicowaterdata.org/collections/Datastreams/items/18517 |


## Comments

* 6788 occurrences with subject type schema_Place and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sosa:ObservationCollection |
| native | geoconnex/:sosa_ObservationCollection |




## LinkML Source

<details>
```yaml
name: sosa_ObservationCollection
description: No slot (predicate) description specified
comments:
- 6788 occurrences with subject type schema_Place and object type string.
examples:
- description: schema_Place → string
  object:
    example_object: https://locations.newmexicowaterdata.org/collections/Datastreams/items/18517
    example_predicate: sosa:ObservationCollection
    example_subject: https://geoconnex.us/nmwdi/st/locations/1
from_schema: geoconnex
rank: 1000
slot_uri: sosa:ObservationCollection
alias: sosa_ObservationCollection
domain_of:
- schema_Place
range: string

```
</details>