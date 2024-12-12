

# Slot: has management capability (sudokn_hasManagementCapability)


_No slot description provided_





URI: [sudokn:hasManagementCapability](http://asu.edu/semantics/SUDOKN/hasManagementCapability)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SudoknQualityManagementCapability](../classes/SudoknQualityManagementCapability.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| sudokn:/Manufacturer_1 sudokn:hasManagementCapability sudokn:/QualityManagementCapabiliy_1 |

## Comments

* 1 occurrences with subject type owl_NamedIndividual and object type sudokn_QualityManagementCapability.

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
| self | sudokn:hasManagementCapability |
| native | sudokn-kg/:sudokn_hasManagementCapability |




## LinkML Source

<details>
```yaml
name: sudokn_hasManagementCapability
description: No slot description provided
title: has management capability
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1 occurrences with subject type owl_NamedIndividual and object type sudokn_QualityManagementCapability.
examples:
- value: sudokn:/Manufacturer_1 sudokn:hasManagementCapability sudokn:/QualityManagementCapabiliy_1
from_schema: sudokn-kg
rank: 1000
domain: io_Organization
slot_uri: sudokn:hasManagementCapability
alias: sudokn_hasManagementCapability
domain_of:
- owl_NamedIndividual
range: Any
any_of:
- range: sudokn_QualityManagementCapability
- range: uri

```
</details>