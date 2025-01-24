

# Slot: schema_about


_No slot (predicate) description specified_





URI: [schema:about](https://schema.org/about)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → uri | https://geoconnex.us/ca-gage-assessment/gages/09423350 | schema:about | https://geoconnex.us/usgs/monitoring-location/09423350 |


## Comments

* 2536 occurrences with subject type schema_Place and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:about |
| native | geoconnex/:schema_about |




## LinkML Source

<details>
```yaml
name: schema_about
description: No slot (predicate) description specified
comments:
- 2536 occurrences with subject type schema_Place and object type uri.
examples:
- description: schema_Place → uri
  object:
    example_object: https://geoconnex.us/usgs/monitoring-location/09423350
    example_predicate: schema:about
    example_subject: https://geoconnex.us/ca-gage-assessment/gages/09423350
from_schema: geoconnex
rank: 1000
slot_uri: schema:about
alias: schema_about
domain_of:
- schema_Place
range: uri

```
</details>