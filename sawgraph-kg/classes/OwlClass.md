

# Class: No class (entity type) name specified (owl_Class)


_No class (type) description specified_







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
| [OwlRestriction](../classes/OwlRestriction.md) | [owl_allValuesFrom](../slots/owl_allValuesFrom.md) | any_of[range] | [OwlClass](../classes/OwlClass.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: owl_Class
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (entity type) name specified
from_schema: sawgraph-kg
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
description: No class (type) description specified
title: No class (entity type) name specified
from_schema: sawgraph-kg
rank: 1000
is_a: rdfs_Class
class_uri: owl:Class

```
</details>