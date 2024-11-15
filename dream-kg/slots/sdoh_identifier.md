

# Slot: identifier (sdoh_identifier)


_The identifier property represents any kind of identifier for any kind of [[Thing]], such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See [background notes](/docs/datamodel.html#identifierBg) for more details._

_        _





URI: [sdoh:identifier](http://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohAdministrativeArea](../classes/SdohAdministrativeArea.md) | A geographical region, typically under the jurisdiction of a particular gover... |  no  |
| [SdohService](../classes/SdohService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| dreamkg:service/4542572480692224 sdoh:identifier 4542572480692224 |
| dreamkg:zip/19130 sdoh:identifier 19130 |

## Comments

* 87 occurrences with subject type sdoh_Service and object type string.
* 39 occurrences with subject type sdoh_AdministrativeArea and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:identifier |
| native | dream-kg/:sdoh_identifier |




## LinkML Source

<details>
```yaml
name: sdoh_identifier
description: "The identifier property represents any kind of identifier for any kind\
  \ of [[Thing]], such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated\
  \ properties for representing many of these, either as textual strings or as URL\
  \ (URI) links. See [background notes](/docs/datamodel.html#identifierBg) for more\
  \ details.\n        "
title: identifier
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 87 occurrences with subject type sdoh_Service and object type string.
- 39 occurrences with subject type sdoh_AdministrativeArea and object type string.
examples:
- value: dreamkg:service/4542572480692224 sdoh:identifier 4542572480692224
- value: dreamkg:zip/19130 sdoh:identifier 19130
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:identifier
alias: sdoh_identifier
domain_of:
- sdoh_AdministrativeArea
- sdoh_Service
range: string

```
</details>