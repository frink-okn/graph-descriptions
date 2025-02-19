

# Slot: hsdo_disambiguatingDescription


_No slot (predicate) description specified_





URI: [hsdo:disambiguatingDescription](http://schema.org/disambiguatingDescription)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoServiceChannel](../classes/HsdoServiceChannel.md) | A means for accessing a service, e |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_ServiceChannel → string | dreamkg:service/channel/AB-4542572480692224 | hsdo:disambiguatingDescription | Aunt Bertha |


## Comments

* 174 occurrences with subject type hsdo_ServiceChannel and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:disambiguatingDescription |
| native | dream-kg/:hsdo_disambiguatingDescription |




## LinkML Source

<details>
```yaml
name: hsdo_disambiguatingDescription
description: No slot (predicate) description specified
comments:
- 174 occurrences with subject type hsdo_ServiceChannel and object type string.
examples:
- description: hsdo_ServiceChannel → string
  object:
    example_object: Aunt Bertha
    example_object_type: string
    example_predicate: hsdo:disambiguatingDescription
    example_subject: dreamkg:service/channel/AB-4542572480692224
    example_subject_type: hsdo_ServiceChannel
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:disambiguatingDescription
alias: hsdo_disambiguatingDescription
domain_of:
- hsdo_ServiceChannel
range: string

```
</details>