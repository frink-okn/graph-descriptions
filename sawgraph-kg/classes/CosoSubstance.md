

# Class: Substance (coso_Substance)


_Any organic or inorganic substance of a particular molecular identity, including any combination of these substances occurring in whole or in part as a result of a chemical reaction or occurring in nature, and any element or uncombined radical._







URI: [coso:Substance](http://w3id.org/coso/v1/contaminoso#Substance)






```mermaid
 classDiagram
    class CosoSubstance
    click CosoSubstance href "../CosoSubstance"
      OwlThing <|-- CosoSubstance
        click OwlThing href "../OwlThing"
      

      CosoSubstance <|-- HttpW3id.orgComptoxV1ChemicalEntity
        click HttpW3id.orgComptoxV1ChemicalEntity href "../HttpW3id.orgComptoxV1ChemicalEntity"
      CosoSubstance <|-- HttpW3id.orgSawgraphV1Us-wqp#Characteristic
        click HttpW3id.orgSawgraphV1Us-wqp#Characteristic href "../HttpW3id.orgSawgraphV1Us-wqp#Characteristic"
      
      
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * **CosoSubstance**
        * [HttpW3id.orgComptoxV1ChemicalEntity](../classes/HttpW3id.orgComptoxV1ChemicalEntity.md)
        * [HttpW3id.orgSawgraphV1Us-wqp#Characteristic](../classes/HttpW3id.orgSawgraphV1Us-wqp#Characteristic.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Beb7217b5b32080b9606028314249e33b](../classes/Beb7217b5b32080b9606028314249e33b.md) | [http___w3id.org_comptox_sameAsComptoxSubstance](../slots/http___w3id.org_comptox_sameAsComptoxSubstance.md) | any_of[range] | [CosoSubstance](../classes/CosoSubstance.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName.md) | [http___w3id.org_comptox_sameAsComptoxSubstance](../slots/http___w3id.org_comptox_sameAsComptoxSubstance.md) | any_of[range] | [CosoSubstance](../classes/CosoSubstance.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: coso_Substance
description: Any organic or inorganic substance of a particular molecular identity,
  including any combination of these substances occurring in whole or in part as a
  result of a chemical reaction or occurring in nature, and any element or uncombined
  radical.
title: Substance
from_schema: okns:sawgraph-kg
rank: 1000
is_a: owl_Thing
class_uri: coso:Substance

```
</details>

### Induced

<details>

```yaml
name: coso_Substance
description: Any organic or inorganic substance of a particular molecular identity,
  including any combination of these substances occurring in whole or in part as a
  result of a chemical reaction or occurring in nature, and any element or uncombined
  radical.
title: Substance
from_schema: okns:sawgraph-kg
rank: 1000
is_a: owl_Thing
class_uri: coso:Substance

```
</details>