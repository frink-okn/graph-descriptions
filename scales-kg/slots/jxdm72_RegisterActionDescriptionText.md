

# Slot: jxdm72_RegisterActionDescriptionText


_No slot (predicate) description specified_





URI: [jxdm72:RegisterActionDescriptionText](http://release.niem.gov/niem/domains/jxdm/7.2/#RegisterActionDescriptionText)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72RegisterAction](../classes/Jxdm72RegisterAction.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_RegisterAction → string | scales/Docket/100271 | jxdm72:RegisterActionDescriptionText | BOND FORFEITURE JUDGMENT CALENDAR on 2002-09-24 00:00:00.000 |
| None → string | scales/DocketEntry/almd;;1:16-cr-00020_de0 | jxdm72:RegisterActionDescriptionText | INDICTMENT as to 01C9DB7 (1) count(s) 1. FORFEITURE ALLEGATION. (cb, ) Modified on 10/6/2016 to strike forfeiture allegation pursuant to order this date. (ajr, ). (Entered: 02/04/2016) |


## Comments

* 561095 occurrences with subject type jxdm72_RegisterAction and object type string.
* 19671841 occurrences with untyped subjects and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | jxdm72:RegisterActionDescriptionText |
| native | scales-kg-new/:jxdm72_RegisterActionDescriptionText |




## LinkML Source

<details>

```yaml
name: jxdm72_RegisterActionDescriptionText
description: No slot (predicate) description specified
comments:
- 561095 occurrences with subject type jxdm72_RegisterAction and object type string.
- 19671841 occurrences with untyped subjects and object type string.
examples:
- description: jxdm72_RegisterAction → string
  object:
    example_object: BOND FORFEITURE JUDGMENT CALENDAR on 2002-09-24 00:00:00.000
    example_object_type: string
    example_predicate: jxdm72:RegisterActionDescriptionText
    example_subject: scales/Docket/100271
    example_subject_type: jxdm72_RegisterAction
- description: None → string
  object:
    example_object: 'INDICTMENT as to 01C9DB7 (1) count(s) 1. FORFEITURE ALLEGATION.
      (cb, ) Modified on 10/6/2016 to strike forfeiture allegation pursuant to order
      this date. (ajr, ). (Entered: 02/04/2016)'
    example_object_type: string
    example_predicate: jxdm72:RegisterActionDescriptionText
    example_subject: scales/DocketEntry/almd;;1:16-cr-00020_de0
    example_subject_type: None
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:RegisterActionDescriptionText
alias: jxdm72_RegisterActionDescriptionText
domain_of:
- jxdm72_RegisterAction
range: string

```
</details>