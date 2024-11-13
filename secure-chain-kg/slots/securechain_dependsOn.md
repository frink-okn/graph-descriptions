

# Slot: securechain_dependsOn


_TODO -- tell the world what this slot (predicate) describes._





URI: [securechain:dependsOn](https://w3id.org/secure-chain/dependsOn)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| securechain:SoftwareVersion/anymeal#1.31-1 securechain:dependsOn securechain:SoftwareVersion/libqt5widgets5t64#%3E%3D+5.0.2 |
| securechain:SoftwareVersion/dosbox-staging#svn_RELEASE_0_74_2 securechain:dependsOn securechain:SoftwareVersion/dosbox#0.74-2 |

## Comments

* 696916 occurrences with subject type securechain_SoftwareVersion and object type securechain_SoftwareVersion.
* 2 occurrences with subject type securechain_SoftwareVersion and object type uri.
* 982961 occurrences on untyped entities with type securechain_SoftwareVersion.
* 39 occurrences on untyped entities with datatype uri.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg/develop




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | securechain:dependsOn |
| native | secure-chain-kg/develop/:securechain_dependsOn |




## LinkML Source

<details>
```yaml
name: securechain_dependsOn
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 696916 occurrences with subject type securechain_SoftwareVersion and object type
  securechain_SoftwareVersion.
- 2 occurrences with subject type securechain_SoftwareVersion and object type uri.
- 982961 occurrences on untyped entities with type securechain_SoftwareVersion.
- 39 occurrences on untyped entities with datatype uri.
examples:
- value: securechain:SoftwareVersion/anymeal#1.31-1 securechain:dependsOn securechain:SoftwareVersion/libqt5widgets5t64#%3E%3D+5.0.2
- value: securechain:SoftwareVersion/dosbox-staging#svn_RELEASE_0_74_2 securechain:dependsOn
    securechain:SoftwareVersion/dosbox#0.74-2
from_schema: secure-chain-kg/develop
rank: 1000
slot_uri: securechain:dependsOn
alias: securechain_dependsOn
domain_of:
- securechain_SoftwareVersion
range: Any
any_of:
- range: securechain_SoftwareVersion
- range: uri

```
</details>