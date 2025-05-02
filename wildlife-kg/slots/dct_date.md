

# Slot: dct_date


_No slot (predicate) description specified_






This slot occurs 5205 times.


URI: [dct:date](http://purl.org/dc/terms/date)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfStatement](../classes/RdfStatement.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime)&nbsp;or&nbsp;<br />[xsd:date](http://www.w3.org/2001/XMLSchema#date)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| rdf_Statement | datetime | https://wildlife.proto-okn.net/kg/relationship/14856 | 2018-12-26T18:04:00 | 5118 |
| rdf_Statement | date | https://wildlife.proto-okn.net/kg/relationship/15004 | 2023-10-18 | 87 |




## LinkML Source

<details>

```yaml
name: dct_date
annotations:
  count:
    tag: count
    value: 5205
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2018-12-26T18:04:00'
    example_object_type: datetime
    example_predicate: dct:date
    example_subject: https://wildlife.proto-okn.net/kg/relationship/14856
    example_subject_type: rdf_Statement
- object:
    example_object: '2023-10-18'
    example_object_type: date
    example_predicate: dct:date
    example_subject: https://wildlife.proto-okn.net/kg/relationship/15004
    example_subject_type: rdf_Statement
from_schema: wildlife-kg
rank: 1000
slot_uri: dct:date
alias: dct_date
domain_of:
- rdf_Statement
range: Any
any_of:
- range: datetime
- range: date

```
</details>