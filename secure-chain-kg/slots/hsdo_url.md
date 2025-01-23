

# Slot: hsdo_url


_No slot (predicate) description specified_





URI: [hsdo:url](http://schema.org/url)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Organization → string | schema:Organization/1Password | hsdo:url | ['https://1password.com', 'http://1passwd.com', 'https://1password.com/zh-tw', 'https://1password.com/zh-cn'] |


## Comments

* 887 occurrences with subject type hsdo_Organization and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:url |
| native | secure-chain-kg/:hsdo_url |




## LinkML Source

<details>
```yaml
name: hsdo_url
description: No slot (predicate) description specified
comments:
- 887 occurrences with subject type hsdo_Organization and object type string.
examples:
- description: hsdo_Organization → string
  object:
    example_object: '[''https://1password.com'', ''http://1passwd.com'', ''https://1password.com/zh-tw'',
      ''https://1password.com/zh-cn'']'
    example_object_type: string
    example_predicate: hsdo:url
    example_subject: schema:Organization/1Password
    example_subject_type: hsdo_Organization
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:url
alias: hsdo_url
domain_of:
- hsdo_Organization
range: string

```
</details>