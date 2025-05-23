

# Slot: No slot (predicate) name specified (sockg_bookName)


_No slot (predicate) description specified_






This slot occurs 2 times.


URI: [sockg:bookName](https://idir.uta.edu/sockg-ontology/docs/bookName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgBook](../classes/SockgBook.md) | A Book is a written or printed work that provides information, stories, or re... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Book | string | sockg:individuals/46749 | Fractal Frontiers | 2 |




## LinkML Source

<details>

```yaml
name: sockg_bookName
annotations:
  count:
    tag: count
    value: 2
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Fractal Frontiers
    example_object_type: string
    example_predicate: sockg:bookName
    example_subject: sockg:individuals/46749
    example_subject_type: sockg_Book
from_schema: soc-kg
rank: 1000
domain: sockg_Book
slot_uri: sockg:bookName
alias: sockg_bookName
domain_of:
- sockg_Book
range: string

```
</details>