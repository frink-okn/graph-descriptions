

# Slot: No slot (predicate) name specified (sudokn_attestsTo)


_No slot (predicate) description specified_






This slot occurs 2 times.


URI: [sudokn:attestsTo](http://asu.edu/semantics/SUDOKN/attestsTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknAS9100Certificate](../classes/SudoknAS9100Certificate.md) | No class (type) description specified |  yes  |
| [SudoknISO9000Certificate](../classes/SudoknISO9000Certificate.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[SudoknQualityManagementCapability](../classes/SudoknQualityManagementCapability.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [sudokn_attestsTo](../slots/sudokn_attestsTo.md) | domain | [sudokn_attestsTo](../slots/sudokn_attestsTo.md) |
| [SudoknAS9100Certificate](../classes/SudoknAS9100Certificate.md) | [sudokn_attestsTo](../slots/sudokn_attestsTo.md) | domain | [sudokn_attestsTo](../slots/sudokn_attestsTo.md) |
| [SudoknISO9000Certificate](../classes/SudoknISO9000Certificate.md) | [sudokn_attestsTo](../slots/sudokn_attestsTo.md) | domain | [sudokn_attestsTo](../slots/sudokn_attestsTo.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_NamedIndividual | owl_NamedIndividual | sudokn:/ISO-9000Certificate_1 | sudokn:/QualityManagementCapabiliy_1 | 2 |
| owl_NamedIndividual | sudokn_QualityManagementCapability | sudokn:/ISO-9000Certificate_1 | sudokn:/QualityManagementCapabiliy_1 | 2 |
| sudokn_ISO9000Certificate | owl_NamedIndividual | sudokn:/ISO-9000Certificate_1 | sudokn:/QualityManagementCapabiliy_1 | 1 |
| sudokn_ISO9000Certificate | sudokn_QualityManagementCapability | sudokn:/ISO-9000Certificate_1 | sudokn:/QualityManagementCapabiliy_1 | 1 |
| sudokn_AS9100Certificate | owl_NamedIndividual | sudokn:/AS-9100Certificate_1 | sudokn:/QualityManagementCapabiliy_1 | 1 |
| sudokn_AS9100Certificate | sudokn_QualityManagementCapability | sudokn:/AS-9100Certificate_1 | sudokn:/QualityManagementCapabiliy_1 | 1 |




## LinkML Source

<details>

```yaml
name: sudokn_attestsTo
annotations:
  count:
    tag: count
    value: 2
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sudokn:/QualityManagementCapabiliy_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:attestsTo
    example_subject: sudokn:/ISO-9000Certificate_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/QualityManagementCapabiliy_1
    example_object_type: sudokn_QualityManagementCapability
    example_predicate: sudokn:attestsTo
    example_subject: sudokn:/ISO-9000Certificate_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/QualityManagementCapabiliy_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:attestsTo
    example_subject: sudokn:/ISO-9000Certificate_1
    example_subject_type: sudokn_ISO9000Certificate
- object:
    example_object: sudokn:/QualityManagementCapabiliy_1
    example_object_type: sudokn_QualityManagementCapability
    example_predicate: sudokn:attestsTo
    example_subject: sudokn:/ISO-9000Certificate_1
    example_subject_type: sudokn_ISO9000Certificate
- object:
    example_object: sudokn:/QualityManagementCapabiliy_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:attestsTo
    example_subject: sudokn:/AS-9100Certificate_1
    example_subject_type: sudokn_AS9100Certificate
- object:
    example_object: sudokn:/QualityManagementCapabiliy_1
    example_object_type: sudokn_QualityManagementCapability
    example_predicate: sudokn:attestsTo
    example_subject: sudokn:/AS-9100Certificate_1
    example_subject_type: sudokn_AS9100Certificate
from_schema: sudokn-kg
rank: 1000
domain: sudokn_attestsTo
slot_uri: sudokn:attestsTo
alias: sudokn_attestsTo
domain_of:
- owl_NamedIndividual
- sudokn_AS9100Certificate
- sudokn_ISO9000Certificate
range: Any
any_of:
- range: owl_NamedIndividual
- range: uri
- range: sudokn_QualityManagementCapability

```
</details>