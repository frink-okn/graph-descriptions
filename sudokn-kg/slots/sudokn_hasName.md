

# Slot: has name (sudokn_hasName)


_TODO -- tell the world what this slot (predicate) describes._





URI: [sudokn:hasName](http://asu.edu/semantics/SUDOKN/hasName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [SudoknOrganizationName](../classes/SudoknOrganizationName.md)






## Examples

| Value |
| --- |
| sudokn:/Manufacturer_1 sudokn:hasName sudokn:/OrganizationName_1 |

## Comments

* 1 occurrences with subject type owl_NamedIndividual and object type sudokn_OrganizationName.

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
| self | sudokn:hasName |
| native | sudokn-kg/:sudokn_hasName |




## LinkML Source

<details>
```yaml
name: sudokn_hasName
description: TODO -- tell the world what this slot (predicate) describes.
title: has name
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1 occurrences with subject type owl_NamedIndividual and object type sudokn_OrganizationName.
examples:
- value: sudokn:/Manufacturer_1 sudokn:hasName sudokn:/OrganizationName_1
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:hasName
alias: sudokn_hasName
domain_of:
- owl_NamedIndividual
subproperty_of: io_denotedBy
range: sudokn_OrganizationName

```
</details>