

# Slot: jxdm72_ChargeIdentification


_No slot (predicate) description specified_





URI: [jxdm72:ChargeIdentification](http://release.niem.gov/niem/domains/jxdm/7.2/#ChargeIdentification)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72Charge](../classes/Jxdm72Charge.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:integer](xsd:integer)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_Charge → integer | scales/Charge/100271_c1106145-gafulton01254716 | jxdm72:ChargeIdentification | 254716 |


## Comments

* 218359 occurrences with subject type jxdm72_Charge and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | jxdm72:ChargeIdentification |
| native | scales-kg-new/:jxdm72_ChargeIdentification |




## LinkML Source

<details>
```yaml
name: jxdm72_ChargeIdentification
description: No slot (predicate) description specified
comments:
- 218359 occurrences with subject type jxdm72_Charge and object type integer.
examples:
- description: jxdm72_Charge → integer
  object:
    example_object: '254716'
    example_object_type: integer
    example_predicate: jxdm72:ChargeIdentification
    example_subject: scales/Charge/100271_c1106145-gafulton01254716
    example_subject_type: jxdm72_Charge
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:ChargeIdentification
alias: jxdm72_ChargeIdentification
domain_of:
- jxdm72_Charge
range: integer

```
</details>