

# Class: No class (entity type) name specified -- this class is noted as a superclass of another class in this graph but has not itself been defined. (owl_ObjectProperty)


_No class (type) description specified_







URI: [owl:ObjectProperty](http://www.w3.org/2002/07/owl#ObjectProperty)






```mermaid
 classDiagram
    class OwlObjectProperty
    click OwlObjectProperty href "../OwlObjectProperty"
      OwlObjectProperty <|-- OwlAsymmetricProperty
        click OwlAsymmetricProperty href "../OwlAsymmetricProperty"
      OwlObjectProperty <|-- OwlInverseFunctionalProperty
        click OwlInverseFunctionalProperty href "../OwlInverseFunctionalProperty"
      OwlObjectProperty <|-- OwlIrreflexiveProperty
        click OwlIrreflexiveProperty href "../OwlIrreflexiveProperty"
      OwlObjectProperty <|-- OwlReflexiveProperty
        click OwlReflexiveProperty href "../OwlReflexiveProperty"
      OwlObjectProperty <|-- OwlSymmetricProperty
        click OwlSymmetricProperty href "../OwlSymmetricProperty"
      OwlObjectProperty <|-- OwlTransitiveProperty
        click OwlTransitiveProperty href "../OwlTransitiveProperty"
      
      
```





## Inheritance
* **OwlObjectProperty**
    * [OwlAsymmetricProperty](../classes/OwlAsymmetricProperty.md)
    * [OwlInverseFunctionalProperty](../classes/OwlInverseFunctionalProperty.md)
    * [OwlIrreflexiveProperty](../classes/OwlIrreflexiveProperty.md)
    * [OwlReflexiveProperty](../classes/OwlReflexiveProperty.md)
    * [OwlSymmetricProperty](../classes/OwlSymmetricProperty.md)
    * [OwlTransitiveProperty](../classes/OwlTransitiveProperty.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | [owl_onProperty](../slots/owl_onProperty.md) | any_of[range] | [OwlObjectProperty](../classes/OwlObjectProperty.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: owl_ObjectProperty
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: fio-kg
rank: 1000
class_uri: owl:ObjectProperty

```
</details>

### Induced

<details>

```yaml
name: owl_ObjectProperty
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: fio-kg
rank: 1000
class_uri: owl:ObjectProperty

```
</details>