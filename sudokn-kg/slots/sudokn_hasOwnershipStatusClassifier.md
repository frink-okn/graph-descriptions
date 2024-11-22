

# Slot: has ownership status classifier (sudokn_hasOwnershipStatusClassifier)


_TODO -- tell the world what this slot (predicate) describes._





URI: [sudokn:hasOwnershipStatusClassifier](http://asu.edu/semantics/SUDOKN/hasOwnershipStatusClassifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | TODO -- tell the world what this class (type) describes |  no  |
| [IoManufacturer](../classes/IoManufacturer.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SudoknOwnershipStatusClassifier](../classes/SudoknOwnershipStatusClassifier.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| sudokn:/Manufacturer_1 sudokn:hasOwnershipStatusClassifier sudokn:VeteranOwned |
| sudokn:applerock sudokn:hasOwnershipStatusClassifier sudokn:WomanOwned |

## Comments

* 1 occurrences with subject type owl_NamedIndividual and object type sudokn_OwnershipStatusClassifier.
* 1119 occurrences with subject type io_Manufacturer and object type sudokn_OwnershipStatusClassifier.

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
| self | sudokn:hasOwnershipStatusClassifier |
| native | sudokn-kg/:sudokn_hasOwnershipStatusClassifier |




## LinkML Source

<details>
```yaml
name: sudokn_hasOwnershipStatusClassifier
description: TODO -- tell the world what this slot (predicate) describes.
title: has ownership status classifier
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1 occurrences with subject type owl_NamedIndividual and object type sudokn_OwnershipStatusClassifier.
- 1119 occurrences with subject type io_Manufacturer and object type sudokn_OwnershipStatusClassifier.
examples:
- value: sudokn:/Manufacturer_1 sudokn:hasOwnershipStatusClassifier sudokn:VeteranOwned
- value: sudokn:applerock sudokn:hasOwnershipStatusClassifier sudokn:WomanOwned
from_schema: sudokn-kg
rank: 1000
domain: io_Organization
slot_uri: sudokn:hasOwnershipStatusClassifier
alias: sudokn_hasOwnershipStatusClassifier
domain_of:
- io_Manufacturer
- owl_NamedIndividual
range: Any
any_of:
- range: sudokn_OwnershipStatusClassifier
- range: uri

```
</details>