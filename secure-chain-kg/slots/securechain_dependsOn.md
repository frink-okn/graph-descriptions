

# Slot: securechain_dependsOn


_No slot (predicate) description specified_





URI: [securechain:dependsOn](https://w3id.org/secure-chain/dependsOn)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| securechain_SoftwareVersion → securechain_SoftwareVersion | securechain:SoftwareVersion/zzuf#0.15-4 | securechain:dependsOn | securechain:SoftwareVersion/libc6#%3E%3E+2.39%26%3C%3C+2.40 |
| None → securechain_SoftwareVersion | securechain:SoftwareVersion/zzuf#0.15-4%2Bb3 | securechain:dependsOn | securechain:SoftwareVersion/libc6#%3E%3E+2.39%26%3C%3C+2.40 |
| securechain_SoftwareVersion → uri | securechain:SoftwareVersion/dosbox-staging#svn_RELEASE_0_74_2 | securechain:dependsOn | securechain:SoftwareVersion/dosbox#0.74-2 |
| None → uri | securechain:SoftwareVersion/glaze#v0.0.1 | securechain:dependsOn | securechain:SoftwareVersion/fast_float#v3.4.0 |


## Comments

* 696916 occurrences with subject type securechain_SoftwareVersion and object type securechain_SoftwareVersion.
* 982961 occurrences with untyped subjects and object type https://w3id.org/secure-chain/SoftwareVersion.
* 2 occurrences with subject type securechain_SoftwareVersion and object type uri.
* 39 occurrences with untyped subjects and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | securechain:dependsOn |
| native | secure-chain-kg/:securechain_dependsOn |




## LinkML Source

<details>
```yaml
name: securechain_dependsOn
description: No slot (predicate) description specified
comments:
- 696916 occurrences with subject type securechain_SoftwareVersion and object type
  securechain_SoftwareVersion.
- 982961 occurrences with untyped subjects and object type https://w3id.org/secure-chain/SoftwareVersion.
- 2 occurrences with subject type securechain_SoftwareVersion and object type uri.
- 39 occurrences with untyped subjects and object type uri.
examples:
- description: securechain_SoftwareVersion → securechain_SoftwareVersion
  object:
    example_object: securechain:SoftwareVersion/libc6#%3E%3E+2.39%26%3C%3C+2.40
    example_object_type: securechain_SoftwareVersion
    example_predicate: securechain:dependsOn
    example_subject: securechain:SoftwareVersion/zzuf#0.15-4
    example_subject_type: securechain_SoftwareVersion
- description: None → securechain_SoftwareVersion
  object:
    example_object: securechain:SoftwareVersion/libc6#%3E%3E+2.39%26%3C%3C+2.40
    example_object_type: securechain_SoftwareVersion
    example_predicate: securechain:dependsOn
    example_subject: securechain:SoftwareVersion/zzuf#0.15-4%2Bb3
    example_subject_type: None
- description: securechain_SoftwareVersion → uri
  object:
    example_object: securechain:SoftwareVersion/dosbox#0.74-2
    example_object_type: uri
    example_predicate: securechain:dependsOn
    example_subject: securechain:SoftwareVersion/dosbox-staging#svn_RELEASE_0_74_2
    example_subject_type: securechain_SoftwareVersion
- description: None → uri
  object:
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