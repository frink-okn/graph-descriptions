

# Slot: securechain_dependsOn


_No slot description provided_





URI: [securechain:dependsOn](https://w3id.org/secure-chain/dependsOn)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md)






## Examples

| Value |
| --- |
| securechain:SoftwareVersion/RedPanda-CPP#1.0.6 securechain:dependsOn securechain:SoftwareVersion/debhelper#%3D12~ |
| securechain:SoftwareVersion/dde-qt5integration#5.5.23-1build3 securechain:dependsOn securechain:SoftwareVersion/libqt5x11extras5#%3E%3D+5.6.0 |
| securechain:SoftwareVersion/kstars#4%3A3.5.5-1 securechain:dependsOn securechain:SoftwareVersion/indi#4%3A3.5.5-1 |
| securechain:SoftwareVersion/dosbox-staging#svn_RELEASE_0_74_2 securechain:dependsOn securechain:SoftwareVersion/dosbox#0.74-2 |

## Comments

* 696916 occurrences with subject type securechain_SoftwareVersion and object type securechain_SoftwareVersion.
* 982961 occurrences with untyped subjects and object type https://w3id.org/secure-chain/SoftwareVersion.
* 39 occurrences with untyped subjects and object type uri.
* 2 occurrences with subject type securechain_SoftwareVersion and object type uri.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

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
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 696916 occurrences with subject type securechain_SoftwareVersion and object type
  securechain_SoftwareVersion.
- 982961 occurrences with untyped subjects and object type https://w3id.org/secure-chain/SoftwareVersion.
- 39 occurrences with untyped subjects and object type uri.
- 2 occurrences with subject type securechain_SoftwareVersion and object type uri.
examples:
- value: securechain:SoftwareVersion/RedPanda-CPP#1.0.6 securechain:dependsOn securechain:SoftwareVersion/debhelper#%3D12~
- value: securechain:SoftwareVersion/dde-qt5integration#5.5.23-1build3 securechain:dependsOn
    securechain:SoftwareVersion/libqt5x11extras5#%3E%3D+5.6.0
- value: securechain:SoftwareVersion/kstars#4%3A3.5.5-1 securechain:dependsOn securechain:SoftwareVersion/indi#4%3A3.5.5-1
- value: securechain:SoftwareVersion/dosbox-staging#svn_RELEASE_0_74_2 securechain:dependsOn
    securechain:SoftwareVersion/dosbox#0.74-2
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