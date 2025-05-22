

# Slot: hsdo_url


_No slot (predicate) description specified_






This slot occurs 7734800 times.


URI: [hsdo:url](http://schema.org/url)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | No class (type) description specified |  yes  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | No class (type) description specified |  yes  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| securechain_SoftwareVersion | string | https://crates.io/crates/a-gpt/0.1.0/ | https://github.com/ddddddeon/a | 7733913 |
| hsdo_Organization | uri | https://www.google.com/search?q=1Password | ['https://1password.com', 'http://1passwd.com', 'https://1password.com/zh-tw', 'https://1password.com/zh-cn'] | 883 |
| securechain_Software | uri | https://www.google.com/search?q=Kernel | [] | 4 |




## LinkML Source

<details>

```yaml
name: hsdo_url
annotations:
  count:
    tag: count
    value: 7734800
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://github.com/ddddddeon/a
    example_object_type: string
    example_predicate: hsdo:url
    example_subject: https://crates.io/crates/a-gpt/0.1.0/
    example_subject_type: securechain_SoftwareVersion
- object:
    example_object: '[''https://1password.com'', ''http://1passwd.com'', ''https://1password.com/zh-tw'',
      ''https://1password.com/zh-cn'']'
    example_object_type: uri
    example_predicate: hsdo:url
    example_subject: https://www.google.com/search?q=1Password
    example_subject_type: hsdo_Organization
- object:
    example_object: '[]'
    example_object_type: uri
    example_predicate: hsdo:url
    example_subject: https://www.google.com/search?q=Kernel
    example_subject_type: securechain_Software
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:url
alias: hsdo_url
domain_of:
- hsdo_Organization
- securechain_Software
- securechain_SoftwareVersion
range: Any
any_of:
- range: string
- range: uri

```
</details>