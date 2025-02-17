

# Slot: url (hsdo_url)


_URL of the item._






This slot occurs 887 times.


URI: [hsdo:url](http://schema.org/url)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Organization | string | schema:Organization/1Password | ['https://1password.com', 'http://1passwd.com', 'https://1password.com/zh-tw', 'https://1password.com/zh-cn'] | 887 |




## LinkML Source

<details>

```yaml
name: hsdo_url
annotations:
  count:
    tag: count
    value: 887
description: URL of the item.
title: url
examples:
- object:
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