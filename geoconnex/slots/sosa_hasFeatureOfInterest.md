

# Slot: sosa_hasFeatureOfInterest


_No slot (predicate) description specified_





URI: [sosa:hasFeatureOfInterest](http://www.w3.org/ns/sosa/hasFeatureOfInterest)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → uri | https://sta.geoconnex.dev/collections/WQIE-WQP/Datastreams/items/'007ab627-00bf-f48c-a27c-d1af60f4e3c6' | sosa:hasFeatureOfInterest | _:b1548067 |
| schema_Place → string | https://sta.geoconnex.dev/collections/WQIE-WQP/Datastreams/items/'007ab627-00bf-f48c-a27c-d1af60f4e3c6' | sosa:hasFeatureOfInterest | https://sta.geoconnex.dev/collections/WQIE-WQP/Things/items/'11NPSWRD_WQX-MEVE_3P_MAN01' |


## Comments

* 1 occurrences with subject type schema_Place and object type uri.
* 1 occurrences with subject type schema_Place and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sosa:hasFeatureOfInterest |
| native | geoconnex/:sosa_hasFeatureOfInterest |




## LinkML Source

<details>
```yaml
name: sosa_hasFeatureOfInterest
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type schema_Place and object type uri.
- 1 occurrences with subject type schema_Place and object type string.
examples:
- description: schema_Place → uri
  object:
    example_object: _:b1548067
    example_predicate: sosa:hasFeatureOfInterest
    example_subject: https://sta.geoconnex.dev/collections/WQIE-WQP/Datastreams/items/'007ab627-00bf-f48c-a27c-d1af60f4e3c6'
- description: schema_Place → string
  object:
    example_object: https://sta.geoconnex.dev/collections/WQIE-WQP/Things/items/'11NPSWRD_WQX-MEVE_3P_MAN01'
    example_predicate: sosa:hasFeatureOfInterest
    example_subject: https://sta.geoconnex.dev/collections/WQIE-WQP/Datastreams/items/'007ab627-00bf-f48c-a27c-d1af60f4e3c6'
from_schema: geoconnex
rank: 1000
slot_uri: sosa:hasFeatureOfInterest
alias: sosa_hasFeatureOfInterest
domain_of:
- schema_Place
range: Any
any_of:
- range: uri
- range: string

```
</details>