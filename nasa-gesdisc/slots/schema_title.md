

# Slot: title (schema_title)


_The title of the job._






This slot occurs 135343 times.


URI: [schema:title](https://schema.org/title)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| https___nasa-gesdisc.proto-okn.net_kg_schema_Publication | string | https://nasa-gesdisc.proto-okn.net/kg/node/10000 | Priority areas for conservation of Old World vultures | 135343 |




## LinkML Source

<details>

```yaml
name: schema_title
annotations:
  count:
    tag: count
    value: 135343
description: The title of the job.
title: title
examples:
- object:
    example_object: Priority areas for conservation of Old World vultures
    example_object_type: string
    example_predicate: schema:title
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/10000
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
from_schema: nasa-gesdisc
rank: 1000
slot_uri: schema:title
alias: schema_title
domain_of:
- https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
range: string

```
</details>