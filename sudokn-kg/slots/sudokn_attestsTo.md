

# Slot: attests to (sudokn_attestsTo)


_No slot description provided_





URI: [sudokn:attestsTo](http://asu.edu/semantics/SUDOKN/attestsTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknAS9100Certificate](../classes/SudoknAS9100Certificate.md) | No type description provided |  no  |
| [SudoknISO9000Certificate](../classes/SudoknISO9000Certificate.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SudoknQualityManagementCapability](../classes/SudoknQualityManagementCapability.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| sudokn:/ISO-9000Certificate_1 sudokn:attestsTo sudokn:/QualityManagementCapabiliy_1 |
| sudokn:/AS-9100Certificate_1 sudokn:attestsTo sudokn:/QualityManagementCapabiliy_1 |

## Comments

* 1 occurrences with subject type sudokn_ISO9000Certificate and object type sudokn_QualityManagementCapability.
* 1 occurrences with subject type sudokn_AS9100Certificate and object type sudokn_QualityManagementCapability.

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
| self | sudokn:attestsTo |
| native | sudokn-kg/:sudokn_attestsTo |




## LinkML Source

<details>
```yaml
name: sudokn_attestsTo
description: No slot description provided
title: attests to
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1 occurrences with subject type sudokn_ISO9000Certificate and object type sudokn_QualityManagementCapability.
- 1 occurrences with subject type sudokn_AS9100Certificate and object type sudokn_QualityManagementCapability.
examples:
- value: sudokn:/ISO-9000Certificate_1 sudokn:attestsTo sudokn:/QualityManagementCapabiliy_1
- value: sudokn:/AS-9100Certificate_1 sudokn:attestsTo sudokn:/QualityManagementCapabiliy_1
from_schema: sudokn-kg
rank: 1000
domain: sudokn_Certificate
slot_uri: sudokn:attestsTo
alias: sudokn_attestsTo
domain_of:
- sudokn_AS9100Certificate
- sudokn_ISO9000Certificate
range: Any
any_of:
- range: sudokn_QualityManagementCapability
- range: uri

```
</details>