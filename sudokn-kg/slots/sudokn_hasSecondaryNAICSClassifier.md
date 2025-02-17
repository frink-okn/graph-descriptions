

# Slot: sudokn_hasSecondaryNAICSClassifier


_No slot (predicate) description specified_






This slot occurs 112 times.


URI: [sudokn:hasSecondaryNAICSClassifier](http://asu.edu/semantics/SUDOKN/hasSecondaryNAICSClassifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | No class (type) description specified |  yes  |







## Properties

* Range: [SudoknNAICSClassifier](../classes/SudoknNAICSClassifier.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| io_Manufacturer | sudokn_NAICSClassifier | sudokn:AdkinsTruckEquipmentCo | sudokn:NAICS-336 | 112 |




## LinkML Source

<details>

```yaml
name: sudokn_hasSecondaryNAICSClassifier
annotations:
  count:
    tag: count
    value: 112
description: No slot (predicate) description specified
examples:
- object:
    example_object: sudokn:NAICS-336
    example_object_type: sudokn_NAICSClassifier
    example_predicate: sudokn:hasSecondaryNAICSClassifier
    example_subject: sudokn:AdkinsTruckEquipmentCo
    example_subject_type: io_Manufacturer
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:hasSecondaryNAICSClassifier
alias: sudokn_hasSecondaryNAICSClassifier
domain_of:
- io_Manufacturer
range: sudokn_NAICSClassifier

```
</details>