

# Slot: jxdm72_ChargeSeverityText


_No slot (predicate) description specified_





URI: [jxdm72:ChargeSeverityText](http://release.niem.gov/niem/domains/jxdm/7.2/#ChargeSeverityText)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72Charge](../classes/Jxdm72Charge.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_Charge → string | scales/Charge/100271_c1106145-gafulton01254716 | jxdm72:ChargeSeverityText | Misdemeanor |


## Comments

* 218372 occurrences with subject type jxdm72_Charge and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | jxdm72:ChargeSeverityText |
| native | scales-kg-new/:jxdm72_ChargeSeverityText |




## LinkML Source

<details>
```yaml
name: jxdm72_ChargeSeverityText
description: No slot (predicate) description specified
comments:
- 218372 occurrences with subject type jxdm72_Charge and object type string.
examples:
- description: jxdm72_Charge → string
  object:
    example_object: Misdemeanor
    example_object_type: string
    example_predicate: jxdm72:ChargeSeverityText
    example_subject: scales/Charge/100271_c1106145-gafulton01254716
    example_subject_type: jxdm72_Charge
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:ChargeSeverityText
alias: jxdm72_ChargeSeverityText
domain_of:
- jxdm72_Charge
range: string

```
</details>