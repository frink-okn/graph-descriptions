

# Slot: hyf__linearElement


_No slot (predicate) description specified_





URI: [hyf:/linearElement](https://www.opengis.net/def/schema/hy_features/hyf/linearElement)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)&nbsp;or&nbsp;<br />[SchemaPlace](../classes/SchemaPlace.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None → uri | _:b1819395 | hyf:/linearElement | https://geoconnex.us/nhdplusv2/reachcode/17090010000231 |
| None → schema_Place | https://gleaner.io/xid/genid/cri6355vd7os738ck6b0 | hyf:/linearElement | https://geoconnex.us/ref/mainstems/2435206 |
| None → string | https://gleaner.io/xid/genid/ckturcsip8t1e5gi9940 | hyf:/linearElement | https://geoconnex.us/nhdplusv2/reachcode/05130101000250 |


## Comments

* 296195 occurrences with untyped subjects and object type uri.
* 323140 occurrences with untyped subjects and object type https://schema.org/Place.
* 2014 occurrences with untyped subjects and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hyf:/linearElement |
| native | geoconnex/:hyf__linearElement |




## LinkML Source

<details>
```yaml
name: hyf__linearElement
description: No slot (predicate) description specified
comments:
- 296195 occurrences with untyped subjects and object type uri.
- 323140 occurrences with untyped subjects and object type https://schema.org/Place.
- 2014 occurrences with untyped subjects and object type string.
examples:
- description: None → uri
  object:
    example_object: https://geoconnex.us/nhdplusv2/reachcode/17090010000231
    example_predicate: hyf:/linearElement
    example_subject: _:b1819395
- description: None → schema_Place
  object:
    example_object: https://geoconnex.us/ref/mainstems/2435206
    example_predicate: hyf:/linearElement
    example_subject: https://gleaner.io/xid/genid/cri6355vd7os738ck6b0
- description: None → string
  object:
    example_object: https://geoconnex.us/nhdplusv2/reachcode/05130101000250
    example_predicate: hyf:/linearElement
    example_subject: https://gleaner.io/xid/genid/ckturcsip8t1e5gi9940
from_schema: geoconnex
rank: 1000
slot_uri: hyf:/linearElement
alias: hyf__linearElement
range: Any
any_of:
- range: uri
- range: string
- range: schema_Place

```
</details>