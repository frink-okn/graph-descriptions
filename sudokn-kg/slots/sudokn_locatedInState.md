

# Slot: sudokn_locatedInState


_No slot (predicate) description specified_






This slot occurs 3734 times.


URI: [sudokn:locatedInState](http://asu.edu/semantics/SUDOKN/locatedInState)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknCity](../classes/SudoknCity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [SudoknState](../classes/SudoknState.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sudokn_City | sudokn_State | sudokn:(NO%20CITY)-City | sudokn:HUMB-State | 3734 |




## LinkML Source

<details>

```yaml
name: sudokn_locatedInState
annotations:
  count:
    tag: count
    value: 3734
description: No slot (predicate) description specified
examples:
- object:
    example_object: sudokn:HUMB-State
    example_object_type: sudokn_State
    example_predicate: sudokn:locatedInState
    example_subject: sudokn:(NO%20CITY)-City
    example_subject_type: sudokn_City
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:locatedInState
alias: sudokn_locatedInState
domain_of:
- sudokn_City
range: sudokn_State

```
</details>