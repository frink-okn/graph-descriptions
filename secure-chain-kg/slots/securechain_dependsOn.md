

# Slot: No slot (predicate) name specified (securechain_dependsOn)


_No slot (predicate) description specified_






This slot occurs 1679918 times.


URI: [securechain:dependsOn](https://w3id.org/secure-chain/dependsOn)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| securechain_SoftwareVersion | securechain_SoftwareVersion | securechain:SoftwareVersion/0ad#0.0.17-1 | securechain:SoftwareVersion/0ad-data#%3E%3D+0.0.17%26%3C%3D+0.0.17-1 | 696916 |
| None | securechain_SoftwareVersion | securechain:SoftwareVersion/zzuf#0.15-4%2Bb3 | securechain:SoftwareVersion/libc6#%3E%3E+2.39%26%3C%3C+2.40 | 982961 |
| securechain_SoftwareVersion | uri | securechain:SoftwareVersion/dosbox-staging#svn_RELEASE_0_74_2 | securechain:SoftwareVersion/dosbox#0.74-2 | 2 |
| None | uri | securechain:SoftwareVersion/glaze#v0.0.1 | securechain:SoftwareVersion/fast_float#v3.4.0 | 39 |




## LinkML Source

<details>

```yaml
name: securechain_dependsOn
annotations:
  count:
    tag: count
    value: 1679918
  securechain_SoftwareVersion:
    tag: securechain_SoftwareVersion
    value: 982961
  uri:
    tag: uri
    value: 39
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: securechain:SoftwareVersion/0ad-data#%3E%3D+0.0.17%26%3C%3D+0.0.17-1
    example_object_type: securechain_SoftwareVersion
    example_predicate: securechain:dependsOn
    example_subject: securechain:SoftwareVersion/0ad#0.0.17-1
    example_subject_type: securechain_SoftwareVersion
- object:
    example_object: securechain:SoftwareVersion/libc6#%3E%3E+2.39%26%3C%3C+2.40
    example_object_type: securechain_SoftwareVersion
    example_predicate: securechain:dependsOn
    example_subject: securechain:SoftwareVersion/zzuf#0.15-4%2Bb3
    example_subject_type: None
- object:
    example_object: securechain:SoftwareVersion/dosbox#0.74-2
    example_object_type: uri
    example_predicate: securechain:dependsOn
    example_subject: securechain:SoftwareVersion/dosbox-staging#svn_RELEASE_0_74_2
    example_subject_type: securechain_SoftwareVersion
- object:
    example_object: securechain:SoftwareVersion/fast_float#v3.4.0
    example_object_type: uri
    example_predicate: securechain:dependsOn
    example_subject: securechain:SoftwareVersion/glaze#v0.0.1
    example_subject_type: None
from_schema: secure-chain-kg
rank: 1000
slot_uri: securechain:dependsOn
alias: securechain_dependsOn
domain_of:
- securechain_SoftwareVersion
range: Any
any_of:
- range: uri
- range: securechain_SoftwareVersion

```
</details>