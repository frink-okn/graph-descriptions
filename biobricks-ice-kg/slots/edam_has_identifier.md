

# Slot: edam_has_identifier


_TODO -- tell the world what this slot (predicate) describes._





URI: [edam:has_identifier](http://edamontology.org/has_identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Cheminf000000](../classes/Cheminf000000.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Cheminf000568](../classes/Cheminf000568.md)&nbsp;or&nbsp;<br />[Cheminf000446](../classes/Cheminf000446.md)






## Examples

| Value |
| --- |
| http://example.com/ice/Endocrine_In_Vivo_Endocrine.parquet/dtxsid/DTXSID9047962/Chemical_Entity edam:has_identifier http://identifiers.org/cas/101-53-1 |
| http://example.com/ice/Endocrine_In_Vivo_Endocrine.parquet/dtxsid/DTXSID9047962/Chemical_Entity edam:has_identifier https://comptox.epa.gov/dashboard/chemical/details/DTXSID9047962 |

## Comments

* 197214 occurrences with subject type cheminf_000000 and object type cheminf_000446.
* 197214 occurrences with subject type cheminf_000000 and object type cheminf_000568.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: biobricks-ice-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | edam:has_identifier |
| native | biobricks-ice-kg/:edam_has_identifier |




## LinkML Source

<details>
```yaml
name: edam_has_identifier
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 197214 occurrences with subject type cheminf_000000 and object type cheminf_000446.
- 197214 occurrences with subject type cheminf_000000 and object type cheminf_000568.
examples:
- value: http://example.com/ice/Endocrine_In_Vivo_Endocrine.parquet/dtxsid/DTXSID9047962/Chemical_Entity
    edam:has_identifier http://identifiers.org/cas/101-53-1
- value: http://example.com/ice/Endocrine_In_Vivo_Endocrine.parquet/dtxsid/DTXSID9047962/Chemical_Entity
    edam:has_identifier https://comptox.epa.gov/dashboard/chemical/details/DTXSID9047962
from_schema: biobricks-ice-kg
rank: 1000
slot_uri: edam:has_identifier
alias: edam_has_identifier
domain_of:
- cheminf_000000
range: Any
any_of:
- range: cheminf_000568
- range: cheminf_000446

```
</details>