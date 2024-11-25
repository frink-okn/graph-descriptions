

# Slot: phila_belongs_to


_TODO -- tell the world what this slot (predicate) describes._





URI: [phila:belongs_to](https://metadata.phila.gov/belongs_to)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [PhilaBlockGroup](../classes/PhilaBlockGroup.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [PhilaCensusTract](../classes/PhilaCensusTract.md)






## Examples

| Value |
| --- |
| phila:BG_8 phila:belongs_to phila:CT_39000 |

## Comments

* 1250 occurrences with subject type phila_BlockGroup and object type phila_CensusTract.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: neighborhood-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | phila:belongs_to |
| native | neighborhood-kg/:phila_belongs_to |




## LinkML Source

<details>
```yaml
name: phila_belongs_to
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1250 occurrences with subject type phila_BlockGroup and object type phila_CensusTract.
examples:
- value: phila:BG_8 phila:belongs_to phila:CT_39000
from_schema: neighborhood-kg
rank: 1000
slot_uri: phila:belongs_to
alias: phila_belongs_to
domain_of:
- phila_BlockGroup
range: phila_CensusTract

```
</details>