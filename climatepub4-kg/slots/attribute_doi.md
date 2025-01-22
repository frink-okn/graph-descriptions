

# Slot: attribute_doi


_No slot (predicate) description specified_





URI: [attribute:doi](http://attribute.org/doi)



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
| hsdo_paper → string | https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb | attribute:doi | 10.1093/icesjms/fsr010 |


## Comments

* 284 occurrences with subject type hsdo_paper and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | attribute:doi |
| native | climatepub4-kg/:attribute_doi |




## LinkML Source

<details>
```yaml
name: attribute_doi
description: No slot (predicate) description specified
comments:
- 284 occurrences with subject type hsdo_paper and object type string.
examples:
- description: hsdo_paper → string
  object:
    example_object: 10.1093/icesjms/fsr010
    example_object_type: string
    example_predicate: attribute:doi
    example_subject: https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb
    example_subject_type: hsdo_paper
from_schema: climatepub4-kg
rank: 1000
slot_uri: attribute:doi
alias: attribute_doi
domain_of:
- hsdo_paper
range: string

```
</details>