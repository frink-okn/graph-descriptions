

# Class: tool design capability (sudokn_ToolDesignCapability)


_No type description provided_





URI: [sudokn:ToolDesignCapability](http://asu.edu/semantics/SUDOKN/ToolDesignCapability)






```mermaid
 classDiagram
    class SudoknToolDesignCapability
    click SudoknToolDesignCapability href "../SudoknToolDesignCapability"
      SudoknEngineeringCapability <|-- SudoknToolDesignCapability
        click SudoknEngineeringCapability href "../SudoknEngineeringCapability"
      

      SudoknToolDesignCapability <|-- SudoknDieDesignCapability
        click SudoknDieDesignCapability href "../SudoknDieDesignCapability"
      SudoknToolDesignCapability <|-- SudoknFixtureDesignCapability
        click SudoknFixtureDesignCapability href "../SudoknFixtureDesignCapability"
      
      
      
```





## Inheritance
* [IoscProductionCapability](../classes/IoscProductionCapability.md)
    * [SudoknEngineeringCapability](../classes/SudoknEngineeringCapability.md)
        * **SudoknToolDesignCapability**
            * [SudoknDieDesignCapability](../classes/SudoknDieDesignCapability.md)
            * [SudoknFixtureDesignCapability](../classes/SudoknFixtureDesignCapability.md)



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
| self | sudokn:ToolDesignCapability |
| native | sudokn-kg/:SudoknToolDesignCapability |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sudokn_ToolDesignCapability
description: No type description provided
title: tool design capability
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 0 occurences.
from_schema: sudokn-kg
rank: 1000
is_a: sudokn_EngineeringCapability
class_uri: sudokn:ToolDesignCapability

```
</details>

### Induced

<details>
```yaml
name: sudokn_ToolDesignCapability
description: No type description provided
title: tool design capability
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 0 occurences.
from_schema: sudokn-kg
rank: 1000
is_a: sudokn_EngineeringCapability
class_uri: sudokn:ToolDesignCapability

```
</details>