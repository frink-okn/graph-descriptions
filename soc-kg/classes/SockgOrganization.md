

# Class: TODO -- what's a good name for what this class (type) describes? (sockg_Organization)


_No type description provided_





URI: [sockg:Organization](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/Organization)






```mermaid
 classDiagram
    class SockgOrganization
    click SockgOrganization href "../SockgOrganization"
      SockgOrganization : sockg_fundsExperiment
        
          
    
    
    SockgOrganization --> "0..1" SockgExperiment : sockg_fundsExperiment
    click SockgExperiment href "../SockgExperiment"

        
      SockgOrganization : sockg_organizationName
        
          
    
    
    SockgOrganization --> "0..1" String : sockg_organizationName
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg_fundsExperiment](../slots/sockg_fundsExperiment.md) | 0..1 <br/> [SockgExperiment](../classes/SockgExperiment.md) | No slot description provided | direct |
| [sockg_organizationName](../slots/sockg_organizationName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SockgDepartment](../classes/SockgDepartment.md) | [sockg_departmentOf](../slots/sockg_departmentOf.md) | range | [SockgOrganization](../classes/SockgOrganization.md) |
| [SockgPerson](../classes/SockgPerson.md) | [sockg_worksFor](../slots/sockg_worksFor.md) | range | [SockgOrganization](../classes/SockgOrganization.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#203275 |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: soc-kg/main




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sockg:Organization |
| native | soc-kg/main/:SockgOrganization |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg_Organization
description: No type description provided
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 7 instances of this class.
examples:
- value: neo4j://graph.individuals#203275
from_schema: soc-kg/main
rank: 1000
slots:
- sockg_fundsExperiment
- sockg_organizationName
class_uri: sockg:Organization

```
</details>

### Induced

<details>
```yaml
name: sockg_Organization
description: No type description provided
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 7 instances of this class.
examples:
- value: neo4j://graph.individuals#203275
from_schema: soc-kg/main
rank: 1000
attributes:
  sockg_fundsExperiment:
    name: sockg_fundsExperiment
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 3 occurrences with subject type sockg:Organization and object type sockg:Experiment.
    examples:
    - value: neo4j://graph.individuals#203273 sockg:fundsExperiment neo4j://graph.individuals#51709
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:fundsExperiment
    alias: sockg_fundsExperiment
    owner: sockg_Organization
    domain_of:
    - sockg_Organization
    range: sockg_Experiment
  sockg_organizationName:
    name: sockg_organizationName
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 7 occurrences with subject type sockg:Organization and object type string.
    examples:
    - value: neo4j://graph.individuals#203277 sockg:organizationName ARS-Colorado
        State University Partnership
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:organizationName
    alias: sockg_organizationName
    owner: sockg_Organization
    domain_of:
    - sockg_Organization
    range: string
class_uri: sockg:Organization

```
</details>