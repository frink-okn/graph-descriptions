

# Slot: scales_hasContents


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasContents](http://schemas.scales-okn.org/rdf/scales#hasContents)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesDocketEntry](../classes/ScalesDocketEntry.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ScalesCharge](../classes/ScalesCharge.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| scales:Charge/akd;;1:16-cr-00001_c1-3 scales:hasContents 26:7203 WILLFUL FAILURE TO FILE INCOME TAX RETURNS |
| scales:DocketEntry/akd;;1:16-cr-00001_de0 scales:hasContents MISDEMEANOR INFORMATION as to 01169B9 (1) count(s) 1-4. (Attachments: # 1 Criminal Cover Sheet re Defendant 01169B9) (CLW, COURT STAFF) (Entered: 02/03/2016) |

## Comments

* 262292 occurrences with subject type scales_Charge and object type string.
* 23661234 occurrences with subject type scales_DocketEntry and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:hasContents |
| native | scales-kg/:scales_hasContents |




## LinkML Source

<details>
```yaml
name: scales_hasContents
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 262292 occurrences with subject type scales_Charge and object type string.
- 23661234 occurrences with subject type scales_DocketEntry and object type string.
examples:
- value: scales:Charge/akd;;1:16-cr-00001_c1-3 scales:hasContents 26:7203 WILLFUL
    FAILURE TO FILE INCOME TAX RETURNS
- value: 'scales:DocketEntry/akd;;1:16-cr-00001_de0 scales:hasContents MISDEMEANOR
    INFORMATION as to 01169B9 (1) count(s) 1-4. (Attachments: # 1 Criminal Cover Sheet
    re Defendant 01169B9) (CLW, COURT STAFF) (Entered: 02/03/2016)'
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasContents
alias: scales_hasContents
domain_of:
- scales_Charge
- scales_DocketEntry
range: string

```
</details>