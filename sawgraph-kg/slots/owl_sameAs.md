

# Slot: owl_sameAs


_No slot (predicate) description specified_






This slot occurs 62 times.


URI: [owl:sameAs](http://www.w3.org/2002/07/owl#sameAs)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Site](../classes/MeEgadEGAD-Site.md) | No class (type) description specified |  yes  |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) | No class (type) description specified |  yes  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[QudtUnit](../classes/QudtUnit.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| qudt_Unit | qudt_Unit | http://qudt.org/vocab/unit/PERCENT | http://qudt.org/vocab/unit/PERCENT | 1 |
| me_egad_EGAD-Site | uri | me_egad_data:site.124837 | http://geoconnex.us/ref/pws/ME0002893 | 48 |
| me_egad_EGAD-PFAS-Site | uri | me_egad_data:site.131980 | http://geoconnex.us/ref/pws/ME0090540 | 13 |




## LinkML Source

<details>

```yaml
name: owl_sameAs
annotations:
  count:
    tag: count
    value: 62
description: No slot (predicate) description specified
examples:
- object:
    example_object: http://qudt.org/vocab/unit/PERCENT
    example_object_type: qudt_Unit
    example_predicate: owl:sameAs
    example_subject: http://qudt.org/vocab/unit/PERCENT
    example_subject_type: qudt_Unit
- object:
    example_object: http://geoconnex.us/ref/pws/ME0002893
    example_object_type: uri
    example_predicate: owl:sameAs
    example_subject: me_egad_data:site.124837
    example_subject_type: me_egad_EGAD-Site
- object:
    example_object: http://geoconnex.us/ref/pws/ME0090540
    example_object_type: uri
    example_predicate: owl:sameAs
    example_subject: me_egad_data:site.131980
    example_subject_type: me_egad_EGAD-PFAS-Site
from_schema: sawgraph-kg
rank: 1000
slot_uri: owl:sameAs
alias: owl_sameAs
domain_of:
- qudt_Unit
- me_egad_EGAD-PFAS-Site
- me_egad_EGAD-Site
range: Any
any_of:
- range: qudt_Unit
- range: uri

```
</details>