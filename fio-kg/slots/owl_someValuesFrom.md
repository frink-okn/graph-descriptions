

# Slot: No slot (predicate) name specified (owl_someValuesFrom)


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [owl:someValuesFrom](http://www.w3.org/2002/07/owl#someValuesFrom)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[OwlClass](../classes/OwlClass.md)&nbsp;or&nbsp;<br />[RdfsClass](../classes/RdfsClass.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | [owl_someValuesFrom](../slots/owl_someValuesFrom.md) | domain | [owl_someValuesFrom](../slots/owl_someValuesFrom.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Restriction | rdfs_Class | _:b0 | fio:Industry | 1 |
| owl_Restriction | owl_Class | _:b0 | fio:Industry | 1 |




## LinkML Source

<details>

```yaml
name: owl_someValuesFrom
annotations:
  count:
    tag: count
    value: 1
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: fio:Industry
    example_object_type: rdfs_Class
    example_predicate: owl:someValuesFrom
    example_subject: _:b0
    example_subject_type: owl_Restriction
- object:
    example_object: fio:Industry
    example_object_type: owl_Class
    example_predicate: owl:someValuesFrom
    example_subject: _:b0
    example_subject_type: owl_Restriction
from_schema: fio-kg
rank: 1000
domain: owl_someValuesFrom
slot_uri: owl:someValuesFrom
alias: owl_someValuesFrom
domain_of:
- owl_Restriction
range: Any
any_of:
- range: uri
- range: owl_Class
- range: rdfs_Class

```
</details>