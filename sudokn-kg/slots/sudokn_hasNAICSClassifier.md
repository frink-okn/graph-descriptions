

# Slot: has NAICS classifier (sudokn_hasNAICSClassifier)


_No slot description provided_





URI: [sudokn:hasNAICSClassifier](http://asu.edu/semantics/SUDOKN/hasNAICSClassifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SudoknNAICSClassifier](../classes/SudoknNAICSClassifier.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| sudokn:/Manufacturer_1 sudokn:hasNAICSClassifier sudokn:/NAICSClassifier_1 |

## Comments

* 1 occurrences with subject type owl_NamedIndividual and object type sudokn_NAICSClassifier.

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
| self | sudokn:hasNAICSClassifier |
| native | sudokn-kg/:sudokn_hasNAICSClassifier |




## LinkML Source

<details>
```yaml
name: sudokn_hasNAICSClassifier
description: No slot description provided
title: has NAICS classifier
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1 occurrences with subject type owl_NamedIndividual and object type sudokn_NAICSClassifier.
examples:
- value: sudokn:/Manufacturer_1 sudokn:hasNAICSClassifier sudokn:/NAICSClassifier_1
from_schema: sudokn-kg
rank: 1000
domain: io_Organization
slot_uri: sudokn:hasNAICSClassifier
alias: sudokn_hasNAICSClassifier
domain_of:
- owl_NamedIndividual
range: Any
any_of:
- range: sudokn_NAICSClassifier
- range: uri

```
</details>