

# Slot: hsdo_target


_No slot (predicate) description specified_





URI: [hsdo:target](http://schema.org/target)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoSearchAction](../classes/HsdoSearchAction.md) | The act of searching for an object |  no  |







## Properties

* Range: [HsdoEntryPoint](../classes/HsdoEntryPoint.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_SearchAction → hsdo_EntryPoint | https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pjg | hsdo:target | https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pk0 |


## Comments

* 1 occurrences with subject type hsdo_SearchAction and object type hsdo_EntryPoint.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:target |
| native | geoconnex/:hsdo_target |




## LinkML Source

<details>
```yaml
name: hsdo_target
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type hsdo_SearchAction and object type hsdo_EntryPoint.
examples:
- description: hsdo_SearchAction → hsdo_EntryPoint
  object:
    example_object: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pk0
    example_predicate: hsdo:target
    example_subject: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pjg
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:target
alias: hsdo_target
domain_of:
- hsdo_SearchAction
range: hsdo_EntryPoint

```
</details>