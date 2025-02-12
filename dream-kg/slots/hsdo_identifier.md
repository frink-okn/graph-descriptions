

# Slot: identifier (hsdo_identifier)


_The identifier property represents any kind of identifier for any kind of [[Thing]], such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See [background notes](/docs/datamodel.html#identifierBg) for more details.␊        _






This slot occurs 126 times.


URI: [hsdo:identifier](http://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |
| [HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md) | A geographical region, typically under the jurisdiction of a particular gover... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Service | string | dreamkg:service/6379467169595392 | 6379467169595392 | 87 |
| hsdo_AdministrativeArea | string | dreamkg:zip/19131 | 19131 | 39 |




## LinkML Source

<details>

```yaml
name: hsdo_identifier
annotations:
  count:
    tag: count
    value: 126
description: 'The identifier property represents any kind of identifier for any kind
  of [[Thing]], such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated
  properties for representing many of these, either as textual strings or as URL (URI)
  links. See [background notes](/docs/datamodel.html#identifierBg) for more details.␊        '
title: identifier
examples:
- description: hsdo_Service→string
  object:
    example_object: '6379467169595392'
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: dreamkg:service/6379467169595392
    example_subject_type: hsdo_Service
- description: hsdo_AdministrativeArea→string
  object:
    example_object: '19131'
    example_object_type: string
    example_predicate: hsdo:identifier
    example_subject: dreamkg:zip/19131
    example_subject_type: hsdo_AdministrativeArea
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:identifier
alias: hsdo_identifier
domain_of:
- hsdo_AdministrativeArea
- hsdo_Service
range: string

```
</details>