

# Slot: subjectOf (schema_subjectOf)


_A CreativeWork or Event about this Thing._






This slot occurs 5205 times.


URI: [schema:subjectOf](https://schema.org/subjectOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfStatement](../classes/RdfStatement.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| rdf_Statement | uri | https://wildlife.proto-okn.net/kg/relationship/14856 | https://www.inaturalist.org/observations/19259838 | 5205 |




## LinkML Source

<details>

```yaml
name: schema_subjectOf
annotations:
  count:
    tag: count
    value: 5205
description: A CreativeWork or Event about this Thing.
title: subjectOf
examples:
- object:
    example_object: https://www.inaturalist.org/observations/19259838
    example_object_type: uri
    example_predicate: schema:subjectOf
    example_subject: https://wildlife.proto-okn.net/kg/relationship/14856
    example_subject_type: rdf_Statement
from_schema: wildlife-kg
rank: 1000
slot_uri: schema:subjectOf
alias: schema_subjectOf
domain_of:
- rdf_Statement
range: uri

```
</details>