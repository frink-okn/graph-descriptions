

# Slot: attribute_title


_No slot (predicate) description specified_





URI: [attribute:title](http://attribute.org/title)



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
| hsdo_paper → string | https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb | attribute:title | Evaluating management strategies for eastern Bering Sea walleye pollock (Theragra chalcogramma) in a changing environment |


## Comments

* 286 occurrences with subject type hsdo_paper and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | attribute:title |
| native | climatepub4-kg/:attribute_title |




## LinkML Source

<details>
```yaml
name: attribute_title
description: No slot (predicate) description specified
comments:
- 286 occurrences with subject type hsdo_paper and object type string.
examples:
- description: hsdo_paper → string
  object:
    example_object: Evaluating management strategies for eastern Bering Sea walleye
      pollock (Theragra chalcogramma) in a changing environment
    example_object_type: string
    example_predicate: attribute:title
    example_subject: https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb
    example_subject_type: hsdo_paper
from_schema: climatepub4-kg
rank: 1000
slot_uri: attribute:title
alias: attribute_title
domain_of:
- hsdo_paper
range: string

```
</details>