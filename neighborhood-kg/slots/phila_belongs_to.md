

# Slot: phila_belongs_to


_No slot (predicate) description specified_





URI: [phila:belongs_to](https://metadata.phila.gov/belongs_to)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [PhilaBlockGroup](../classes/PhilaBlockGroup.md) | No class (type) description specified |  no  |







## Properties

* Range: [PhilaCensusTract](../classes/PhilaCensusTract.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| phila_BlockGroup → phila_CensusTract | phila:BG_8 | phila:belongs_to | phila:CT_39000 |


## Comments

* 1250 occurrences with subject type phila_BlockGroup and object type phila_CensusTract.

## Identifier and Mapping Information







### Schema Source


* from schema: neighborhood-information-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | phila:belongs_to |
| native | neighborhood-information-kg/:phila_belongs_to |




## LinkML Source

<details>
```yaml
name: phila_belongs_to
description: No slot (predicate) description specified
comments:
- 1250 occurrences with subject type phila_BlockGroup and object type phila_CensusTract.
examples:
- description: phila_BlockGroup → phila_CensusTract
  object:
    example_object: phila:CT_39000
    example_object_type: phila_CensusTract
    example_predicate: phila:belongs_to
    example_subject: phila:BG_8
    example_subject_type: phila_BlockGroup
from_schema: neighborhood-information-kg
rank: 1000
slot_uri: phila:belongs_to
alias: phila_belongs_to
domain_of:
- phila_BlockGroup
range: phila_CensusTract

```
</details>