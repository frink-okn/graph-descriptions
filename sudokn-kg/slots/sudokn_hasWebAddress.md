

# Slot: has web address (sudokn_hasWebAddress)


_No slot description provided_





URI: [sudokn:hasWebAddress](http://asu.edu/semantics/SUDOKN/hasWebAddress)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SudoknWebAddress](../classes/SudoknWebAddress.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| sudokn:/Manufacturer_1 sudokn:hasWebAddress sudokn:/WebAddress_1 |

## Comments

* 1 occurrences with subject type owl_NamedIndividual and object type sudokn_WebAddress.

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
| self | sudokn:hasWebAddress |
| native | sudokn-kg/:sudokn_hasWebAddress |




## LinkML Source

<details>
```yaml
name: sudokn_hasWebAddress
description: No slot description provided
title: has web address
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1 occurrences with subject type owl_NamedIndividual and object type sudokn_WebAddress.
examples:
- value: sudokn:/Manufacturer_1 sudokn:hasWebAddress sudokn:/WebAddress_1
from_schema: sudokn-kg
rank: 1000
domain: io_Organization
slot_uri: sudokn:hasWebAddress
alias: sudokn_hasWebAddress
domain_of:
- owl_NamedIndividual
range: Any
any_of:
- range: sudokn_WebAddress
- range: uri

```
</details>