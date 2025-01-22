

# Slot: attribute_pub_date


_No slot (predicate) description specified_





URI: [attribute:pub_date](http://attribute.org/pub_date)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoPaper](../classes/HsdoPaper.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_paper → string | https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb | attribute:pub_date | 2024-07-17 |


## Comments

* 181 occurrences with subject type hsdo_paper and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | attribute:pub_date |
| native | climatepub4-kg/:attribute_pub_date |




## LinkML Source

<details>
```yaml
name: attribute_pub_date
description: No slot (predicate) description specified
comments:
- 181 occurrences with subject type hsdo_paper and object type string.
examples:
- description: hsdo_paper → string
  object:
    example_object: '2024-07-17'
    example_object_type: string
    example_predicate: attribute:pub_date
    example_subject: https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb
    example_subject_type: hsdo_paper
from_schema: climatepub4-kg
rank: 1000
slot_uri: attribute:pub_date
alias: attribute_pub_date
domain_of:
- hsdo_paper
range: string

```
</details>