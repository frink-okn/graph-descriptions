

# Slot: niem50_AddressPostalCode


_No slot (predicate) description specified_





URI: [niem50:AddressPostalCode](http://release.niem.gov/niem/niem-core/5.0/AddressPostalCode)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72Court](../classes/Jxdm72Court.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_Court → string | scales/Court/almd | niem50:AddressPostalCode | 35010 |


## Comments

* 40932 occurrences with subject type jxdm72_Court and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | niem50:AddressPostalCode |
| native | scales-kg-new/:niem50_AddressPostalCode |




## LinkML Source

<details>
```yaml
name: niem50_AddressPostalCode
description: No slot (predicate) description specified
comments:
- 40932 occurrences with subject type jxdm72_Court and object type string.
examples:
- description: jxdm72_Court → string
  object:
    example_object: '35010'
    example_object_type: string
    example_predicate: niem50:AddressPostalCode
    example_subject: scales/Court/almd
    example_subject_type: jxdm72_Court
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:AddressPostalCode
alias: niem50_AddressPostalCode
domain_of:
- jxdm72_Court
range: string

```
</details>