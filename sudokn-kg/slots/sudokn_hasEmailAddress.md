

# Slot: has email address (sudokn_hasEmailAddress)


_No slot description provided_





URI: [sudokn:hasEmailAddress](http://asu.edu/semantics/SUDOKN/hasEmailAddress)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SudoknEmailAddress](../classes/SudoknEmailAddress.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| sudokn:/Manufacturer_1 sudokn:hasEmailAddress sudokn:/EmailAddress_1 |

## Comments

* 1 occurrences with subject type owl_NamedIndividual and object type sudokn_EmailAddress.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sudokn-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sudokn:hasEmailAddress |
| native | sudokn-kg/:sudokn_hasEmailAddress |




## LinkML Source

<details>
```yaml
name: sudokn_hasEmailAddress
description: No slot description provided
title: has email address
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1 occurrences with subject type owl_NamedIndividual and object type sudokn_EmailAddress.
examples:
- value: sudokn:/Manufacturer_1 sudokn:hasEmailAddress sudokn:/EmailAddress_1
from_schema: sudokn-kg
rank: 1000
domain: io_Organization
slot_uri: sudokn:hasEmailAddress
alias: sudokn_hasEmailAddress
domain_of:
- owl_NamedIndividual
range: Any
any_of:
- range: sudokn_EmailAddress
- range: uri

```
</details>