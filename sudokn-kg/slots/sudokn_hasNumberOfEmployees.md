

# Slot: No slot (predicate) name specified (sudokn_hasNumberOfEmployees)


_No slot (predicate) description specified_






This slot occurs 6931 times.


URI: [sudokn:hasNumberOfEmployees](http://asu.edu/semantics/SUDOKN/hasNumberOfEmployees)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | [sudokn_hasNumberOfEmployees](../slots/sudokn_hasNumberOfEmployees.md) | domain | [sudokn_hasNumberOfEmployees](../slots/sudokn_hasNumberOfEmployees.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| io_Manufacturer | integer | sudokn:101PIPE-company-inst | 50 | 6931 |




## LinkML Source

<details>

```yaml
name: sudokn_hasNumberOfEmployees
annotations:
  count:
    tag: count
    value: 6931
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '50'
    example_object_type: integer
    example_predicate: sudokn:hasNumberOfEmployees
    example_subject: sudokn:101PIPE-company-inst
    example_subject_type: io_Manufacturer
from_schema: sudokn-kg
rank: 1000
domain: sudokn_hasNumberOfEmployees
slot_uri: sudokn:hasNumberOfEmployees
alias: sudokn_hasNumberOfEmployees
domain_of:
- io_Manufacturer
range: Any
any_of:
- range: uri
- range: integer

```
</details>