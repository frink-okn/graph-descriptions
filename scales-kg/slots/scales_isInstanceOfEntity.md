

# Slot: scales_isInstanceOfEntity


_No slot (predicate) description specified_






This slot occurs 7044753 times.


URI: [scales:isInstanceOfEntity](http://schemas.scales-okn.org/rdf/scales#isInstanceOfEntity)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesParty](../classes/ScalesParty.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_Party | uri | scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00001_a0 | scales:PartyEntity/SPID-GA-CLAYTON-563646 | 7042309 |
| None | uri | scales:Agent/ga-clayton-magistrate-civil;;0:23-cm-00005_a0 | scales:PartyEntity/SPID-GA-CLAYTON-566344 | 2444 |




## LinkML Source

<details>

```yaml
name: scales_isInstanceOfEntity
annotations:
  count:
    tag: count
    value: 7044753
  uri:
    tag: uri
    value: 2444
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:PartyEntity/SPID-GA-CLAYTON-563646
    example_object_type: uri
    example_predicate: scales:isInstanceOfEntity
    example_subject: scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00001_a0
    example_subject_type: scales_Party
- object:
    example_object: scales:PartyEntity/SPID-GA-CLAYTON-566344
    example_object_type: uri
    example_predicate: scales:isInstanceOfEntity
    example_subject: scales:Agent/ga-clayton-magistrate-civil;;0:23-cm-00005_a0
    example_subject_type: None
from_schema: scales-kg
rank: 1000
slot_uri: scales:isInstanceOfEntity
alias: scales_isInstanceOfEntity
domain_of:
- scales_Party
range: uri

```
</details>