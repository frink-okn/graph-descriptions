

# Slot: scales_hasBondType


_No slot (predicate) description specified_





URI: [scales:hasBondType](http://schemas.scales-okn.org/rdf/scales#hasBondType)



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
| jxdm72_Charge → string | scales/Charge/100271_c1106145-gafulton01254716 | scales:hasBondType | Surety Bond |


## Comments

* 76888 occurrences with subject type jxdm72_Charge and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:hasBondType |
| native | scales-kg-new/:scales_hasBondType |




## LinkML Source

<details>
```yaml
name: scales_hasBondType
description: No slot (predicate) description specified
comments:
- 76888 occurrences with subject type jxdm72_Charge and object type string.
examples:
- description: jxdm72_Charge → string
  object:
    example_object: Surety Bond
    example_object_type: string
    example_predicate: scales:hasBondType
    example_subject: scales/Charge/100271_c1106145-gafulton01254716
    example_subject_type: jxdm72_Charge
from_schema: scales-kg-new
rank: 1000
slot_uri: scales:hasBondType
alias: scales_hasBondType
domain_of:
- jxdm72_Charge
range: string

```
</details>