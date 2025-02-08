

# Slot: jxdm72_RegisterOfActions


_No slot (predicate) description specified_





URI: [jxdm72:RegisterOfActions](http://release.niem.gov/niem/domains/jxdm/7.2/#RegisterOfActions)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72Case](../classes/Jxdm72Case.md) | No class (type) description specified |  no  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Jxdm72RegisterOfActions](../classes/Jxdm72RegisterOfActions.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Jxdm72Case](../classes/Jxdm72Case.md) | [Jxdm72RegisterOfActions](../classes/Jxdm72RegisterOfActions.md) | any_of[range] | [Jxdm72RegisterOfActions](../classes/Jxdm72RegisterOfActions.md) |
| [ScalesCase](../classes/ScalesCase.md) | [Jxdm72RegisterOfActions](../classes/Jxdm72RegisterOfActions.md) | any_of[range] | [Jxdm72RegisterOfActions](../classes/Jxdm72RegisterOfActions.md) |







## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| scales_Case → uri | scales/CaseCivil | jxdm72:RegisterOfActions | scales/DocketTable/almd;;1:16-cv-00016 |
| jxdm72_Case → jxdm72_RegisterOfActions | scales/CaseCriminal/ga/fulton/01/99233 | jxdm72:RegisterOfActions | scales/DocketTable/DocketTable/ga-fulton-01-99233 |


## Comments

* 581243 occurrences with subject type scales_Case and object type uri.
* 94929 occurrences with subject type jxdm72_Case and object type jxdm72_RegisterOfActions.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | jxdm72:RegisterOfActions |
| native | scales-kg-new/:Jxdm72RegisterOfActions |




## LinkML Source

<details>
```yaml
name: jxdm72_RegisterOfActions
description: No slot (predicate) description specified
comments:
- 581243 occurrences with subject type scales_Case and object type uri.
- 94929 occurrences with subject type jxdm72_Case and object type jxdm72_RegisterOfActions.
examples:
- description: scales_Case → uri
  object:
    example_object: scales/DocketTable/almd;;1:16-cv-00016
    example_object_type: uri
    example_predicate: jxdm72:RegisterOfActions
    example_subject: scales/CaseCivil
    example_subject_type: scales_Case
- description: jxdm72_Case → jxdm72_RegisterOfActions
  object:
    example_object: scales/DocketTable/DocketTable/ga-fulton-01-99233
    example_object_type: jxdm72_RegisterOfActions
    example_predicate: jxdm72:RegisterOfActions
    example_subject: scales/CaseCriminal/ga/fulton/01/99233
    example_subject_type: jxdm72_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:RegisterOfActions
alias: jxdm72_RegisterOfActions
domain_of:
- jxdm72_Case
- scales_Case
range: Any
any_of:
- range: jxdm72_RegisterOfActions
- range: uri

```
</details>