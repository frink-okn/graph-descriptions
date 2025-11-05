

# Class: Depression (rural_substanceabuse_Concept_Depression)


_Major depressive episode and depression symptoms across adult and youth populations_







URI: [rural:substanceabuse/Concept_Depression](http://sail.ua.edu/ruralkg/substanceabuse/Concept_Depression)






```mermaid
 classDiagram
    class RuralSubstanceabuseConceptDepression
    click RuralSubstanceabuseConceptDepression href "../RuralSubstanceabuseConceptDepression"
      RuralSubstanceabuseConceptMentalHealth <|-- RuralSubstanceabuseConceptDepression
        click RuralSubstanceabuseConceptMentalHealth href "../RuralSubstanceabuseConceptMentalHealth"
      

      RuralSubstanceabuseConceptDepression <|-- RuralSubstanceabuseConceptAdultDepression
        click RuralSubstanceabuseConceptAdultDepression href "../RuralSubstanceabuseConceptAdultDepression"
      RuralSubstanceabuseConceptDepression <|-- RuralSubstanceabuseConceptYouthDepression
        click RuralSubstanceabuseConceptYouthDepression href "../RuralSubstanceabuseConceptYouthDepression"
      
      
      
```





## Inheritance
* [RuralSubstanceabuseSubstanceAbuse](../classes/RuralSubstanceabuseSubstanceAbuse.md)
    * [RuralSubstanceabuseConceptMentalHealth](../classes/RuralSubstanceabuseConceptMentalHealth.md)
        * **RuralSubstanceabuseConceptDepression**
            * [RuralSubstanceabuseConceptAdultDepression](../classes/RuralSubstanceabuseConceptAdultDepression.md)
            * [RuralSubstanceabuseConceptYouthDepression](../classes/RuralSubstanceabuseConceptYouthDepression.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: rural_substanceabuse_Concept_Depression
description: Major depressive episode and depression symptoms across adult and youth
  populations
title: Depression
from_schema: okns:rural-kg
rank: 1000
is_a: rural_substanceabuse_Concept_Mental_Health
class_uri: rural:substanceabuse/Concept_Depression

```
</details>

### Induced

<details>

```yaml
name: rural_substanceabuse_Concept_Depression
description: Major depressive episode and depression symptoms across adult and youth
  populations
title: Depression
from_schema: okns:rural-kg
rank: 1000
is_a: rural_substanceabuse_Concept_Mental_Health
class_uri: rural:substanceabuse/Concept_Depression

```
</details>