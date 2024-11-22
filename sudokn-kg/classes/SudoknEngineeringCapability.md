

# Class: engineering capability (sudokn_EngineeringCapability)


_TODO -- tell the world what this class (type) describes._





URI: [sudokn:EngineeringCapability](http://asu.edu/semantics/SUDOKN/EngineeringCapability)






```mermaid
 classDiagram
    class SudoknEngineeringCapability
    click SudoknEngineeringCapability href "../SudoknEngineeringCapability"
      IoscProductionCapability <|-- SudoknEngineeringCapability
        click IoscProductionCapability href "../IoscProductionCapability"
      

      SudoknEngineeringCapability <|-- SudoknCADCAMCapability
        click SudoknCADCAMCapability href "../SudoknCADCAMCapability"
      SudoknEngineeringCapability <|-- SudoknCADCapability
        click SudoknCADCapability href "../SudoknCADCapability"
      SudoknEngineeringCapability <|-- SudoknCAECapability
        click SudoknCAECapability href "../SudoknCAECapability"
      SudoknEngineeringCapability <|-- SudoknEngineeringDesignCapability
        click SudoknEngineeringDesignCapability href "../SudoknEngineeringDesignCapability"
      SudoknEngineeringCapability <|-- SudoknPLCProgrammingCapability
        click SudoknPLCProgrammingCapability href "../SudoknPLCProgrammingCapability"
      SudoknEngineeringCapability <|-- SudoknReverseEngineeringCapability
        click SudoknReverseEngineeringCapability href "../SudoknReverseEngineeringCapability"
      SudoknEngineeringCapability <|-- SudoknToolDesignCapability
        click SudoknToolDesignCapability href "../SudoknToolDesignCapability"
      
      
      
```





## Inheritance
* [IoscProductionCapability](../classes/IoscProductionCapability.md)
    * **SudoknEngineeringCapability**
        * [SudoknCADCAMCapability](../classes/SudoknCADCAMCapability.md)
        * [SudoknCADCapability](../classes/SudoknCADCapability.md)
        * [SudoknCAECapability](../classes/SudoknCAECapability.md)
        * [SudoknEngineeringDesignCapability](../classes/SudoknEngineeringDesignCapability.md)
        * [SudoknPLCProgrammingCapability](../classes/SudoknPLCProgrammingCapability.md)
        * [SudoknReverseEngineeringCapability](../classes/SudoknReverseEngineeringCapability.md)
        * [SudoknToolDesignCapability](../classes/SudoknToolDesignCapability.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |









## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sudokn-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sudokn:EngineeringCapability |
| native | sudokn-kg/:SudoknEngineeringCapability |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sudokn_EngineeringCapability
description: TODO -- tell the world what this class (type) describes.
title: engineering capability
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 0 occurences.
from_schema: sudokn-kg
is_a: iosc_ProductionCapability
class_uri: sudokn:EngineeringCapability

```
</details>

### Induced

<details>
```yaml
name: sudokn_EngineeringCapability
description: TODO -- tell the world what this class (type) describes.
title: engineering capability
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 0 occurences.
from_schema: sudokn-kg
is_a: iosc_ProductionCapability
class_uri: sudokn:EngineeringCapability

```
</details>