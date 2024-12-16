

# Class: Administrative Area (rural_administrativearea_AdministrativeArea)


_No class (type) description specified_





URI: [rural:administrativearea/AdministrativeArea](http://sail.ua.edu/ruralkg/administrativearea/AdministrativeArea)






```mermaid
 classDiagram
    class RuralAdministrativeareaAdministrativeArea
    click RuralAdministrativeareaAdministrativeArea href "../RuralAdministrativeareaAdministrativeArea"
      RuralAdministrativeareaAdministrativeArea <|-- RuralAdministrativeareaCity
        click RuralAdministrativeareaCity href "../RuralAdministrativeareaCity"
      RuralAdministrativeareaAdministrativeArea <|-- RuralAdministrativeareaCounty
        click RuralAdministrativeareaCounty href "../RuralAdministrativeareaCounty"
      RuralAdministrativeareaAdministrativeArea <|-- RuralAdministrativeareaState
        click RuralAdministrativeareaState href "../RuralAdministrativeareaState"
      
      
```





## Inheritance
* **RuralAdministrativeareaAdministrativeArea**
    * [RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md)
    * [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md)
    * [RuralAdministrativeareaState](../classes/RuralAdministrativeareaState.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |









## Comments

* Covers all administrative regions, including State, City, County, and MSA (undergoing).

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:administrativearea/AdministrativeArea |
| native | rural-kg/:RuralAdministrativeareaAdministrativeArea |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: rural_administrativearea_AdministrativeArea
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: Administrative Area
notes:
- Class with 0 occurrences.
comments:
- Covers all administrative regions, including State, City, County, and MSA (undergoing).
from_schema: rural-kg
source: http://sail.ua.edu/ruralkg/ontology
rank: 1000
class_uri: rural:administrativearea/AdministrativeArea

```
</details>

### Induced

<details>
```yaml
name: rural_administrativearea_AdministrativeArea
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: Administrative Area
notes:
- Class with 0 occurrences.
comments:
- Covers all administrative regions, including State, City, County, and MSA (undergoing).
from_schema: rural-kg
source: http://sail.ua.edu/ruralkg/ontology
rank: 1000
class_uri: rural:administrativearea/AdministrativeArea

```
</details>