

# Slot: No slot (predicate) name specified (owl_unionOf)


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [owl:unionOf](http://www.w3.org/2002/07/owl#unionOf)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RdfList](../classes/RdfList.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | uri | _:B1b00703a3b4a6351310cd78550f4f30c | _:B57b3759ec92f5d59c8cc2dac709be33d | 1 |




## LinkML Source

<details>

```yaml
name: owl_unionOf
annotations:
  count:
    tag: count
    value: 1
  uri:
    tag: uri
    value: 1
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: _:B57b3759ec92f5d59c8cc2dac709be33d
    example_object_type: uri
    example_predicate: owl:unionOf
    example_subject: _:B1b00703a3b4a6351310cd78550f4f30c
    example_subject_type: None
from_schema: fio-kg
rank: 1000
domain: rdfs_Class
slot_uri: owl:unionOf
alias: owl_unionOf
range: Any
any_of:
- range: rdf_List
- range: uri

```
</details>