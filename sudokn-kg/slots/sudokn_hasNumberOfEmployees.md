

# Slot: sudokn_hasNumberOfEmployees


_No slot description provided_





URI: [sudokn:hasNumberOfEmployees](http://asu.edu/semantics/SUDOKN/hasNumberOfEmployees)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| sudokn:101PIPE-company-inst sudokn:hasNumberOfEmployees 50 |

## Comments

* 6931 occurrences with subject type io_Manufacturer and object type integer.

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
| self | sudokn:hasNumberOfEmployees |
| native | sudokn-kg/:sudokn_hasNumberOfEmployees |




## LinkML Source

<details>
```yaml
name: sudokn_hasNumberOfEmployees
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 6931 occurrences with subject type io_Manufacturer and object type integer.
examples:
- value: sudokn:101PIPE-company-inst sudokn:hasNumberOfEmployees 50
from_schema: sudokn-kg
rank: 1000
domain: io_Organization
slot_uri: sudokn:hasNumberOfEmployees
alias: sudokn_hasNumberOfEmployees
domain_of:
- io_Manufacturer
range: Any
any_of:
- range: integer
- range: uri

```
</details>