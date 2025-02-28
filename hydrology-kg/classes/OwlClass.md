

# Class: No class (type) name specified (owl_Class)


_No class (type) description specified_






This class occurs 0 times.


URI: [owl:Class](http://www.w3.org/2002/07/owl#Class)






```mermaid
 classDiagram
    class OwlClass
    click OwlClass href "../OwlClass"
      RdfsClass <|-- OwlClass
        click RdfsClass href "../RdfsClass"
      

      OwlClass <|-- OwlRestriction
        click OwlRestriction href "../OwlRestriction"
      
      
      
```





## Inheritance
* [RdfsClass](../classes/RdfsClass.md)
    * **OwlClass**
        * [OwlRestriction](../classes/OwlRestriction.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [rdfs_range](../slots/rdfs_range.md) | any_of[range] | [OwlClass](../classes/OwlClass.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [rdfs_domain](../slots/rdfs_domain.md) | any_of[range] | [OwlClass](../classes/OwlClass.md) |
| [OwlNothing](../classes/OwlNothing.md) | [rdfs_range](../slots/rdfs_range.md) | any_of[range] | [OwlClass](../classes/OwlClass.md) |
| [OwlNothing](../classes/OwlNothing.md) | [rdfs_domain](../slots/rdfs_domain.md) | any_of[range] | [OwlClass](../classes/OwlClass.md) |
| [OwlThing](../classes/OwlThing.md) | [rdfs_range](../slots/rdfs_range.md) | any_of[range] | [OwlClass](../classes/OwlClass.md) |
| [OwlThing](../classes/OwlThing.md) | [rdfs_domain](../slots/rdfs_domain.md) | any_of[range] | [OwlClass](../classes/OwlClass.md) |
| [RdfObjectProperty](../classes/RdfObjectProperty.md) | [rdfs_domain](../slots/rdfs_domain.md) | any_of[range] | [OwlClass](../classes/OwlClass.md) |
| [RdfObjectProperty](../classes/RdfObjectProperty.md) | [rdfs_range](../slots/rdfs_range.md) | any_of[range] | [OwlClass](../classes/OwlClass.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: owl_Class
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 0
description: No class (type) description specified
title: No class (type) name specified
from_schema: hydrology-kg
rank: 1000
is_a: rdfs_Class
class_uri: owl:Class

```
</details>

### Induced

<details>

```yaml
name: owl_Class
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 0
description: No class (type) description specified
title: No class (type) name specified
from_schema: hydrology-kg
rank: 1000
is_a: rdfs_Class
class_uri: owl:Class

```
</details>