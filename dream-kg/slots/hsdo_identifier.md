

# Slot: hsdo_identifier


_The identifier property represents any kind of identifier for any kind of [[Thing]], such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See [background notes](/docs/datamodel.html#identifierBg) for more details.␊        _






This slot occurs 126 times.


URI: [schema:identifier](http://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md) | A geographical region, typically under the jurisdiction of a particular gover... |  yes  |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | string | dreamkg:service/4542572480692224 | 4542572480692224 | 126 |
| hsdo_Service | string | dreamkg:service/4542572480692224 | 4542572480692224 | 87 |
| hsdo_AdministrativeArea | string | dreamkg:zip/17602 | 17602 | 39 |




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
examples:
- object:
    example_object: '4542572480692224'
    example_object_type: string
    example_predicate: schema:identifier
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: '4542572480692224'
    example_object_type: string
    example_predicate: schema:identifier
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: '17602'
    example_object_type: string
    example_predicate: schema:identifier
    example_subject: dreamkg:zip/17602
    example_subject_type: hsdo_AdministrativeArea
from_schema: dream-kg
rank: 1000
slot_uri: schema:identifier
alias: hsdo_identifier
domain_of:
- hsdo_AdministrativeArea
- hsdo_Service
- prov_Entity
range: string

```
</details>