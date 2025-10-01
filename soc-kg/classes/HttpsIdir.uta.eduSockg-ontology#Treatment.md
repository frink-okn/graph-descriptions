

# Class: HttpsIdir.uta.eduSockg-ontology#Treatment




This class occurs 769 times.


URI: [https://idir.uta.edu/sockg-ontology#Treatment](https://idir.uta.edu/sockg-ontology#Treatment)






```mermaid
 classDiagram
    class HttpsIdir.uta.eduSockg-ontology#Treatment
    click HttpsIdir.uta.eduSockg-ontology#Treatment href "../HttpsIdir.uta.eduSockg-ontology#Treatment"
      HttpsIdir.uta.eduSockg-ontology#Treatment : dct_description
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" String : dct_description
    click String href "../String"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : dct_identifier
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" RdfsLiteral : dct_identifier
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#fromProject
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#Project : https___idir.uta.edu_sockg_ontology#fromProject
    click HttpsIdir.uta.eduSockg-ontology#Project href "../HttpsIdir.uta.eduSockg-ontology#Project"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#hasAnimalSpecies
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#AnimalSpecies : https___idir.uta.edu_sockg_ontology#hasAnimalSpecies
    click HttpsIdir.uta.eduSockg-ontology#AnimalSpecies href "../HttpsIdir.uta.eduSockg-ontology#AnimalSpecies"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#hasGrazingRate
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#GrazingRate : https___idir.uta.edu_sockg_ontology#hasGrazingRate
    click HttpsIdir.uta.eduSockg-ontology#GrazingRate href "../HttpsIdir.uta.eduSockg-ontology#GrazingRate"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#hasProjectScenario
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#ProjectScenario : https___idir.uta.edu_sockg_ontology#hasProjectScenario
    click HttpsIdir.uta.eduSockg-ontology#ProjectScenario href "../HttpsIdir.uta.eduSockg-ontology#ProjectScenario"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#hasRotation
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#Rotation : https___idir.uta.edu_sockg_ontology#hasRotation
    click HttpsIdir.uta.eduSockg-ontology#Rotation href "../HttpsIdir.uta.eduSockg-ontology#Rotation"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#hasTillage
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#Tillage : https___idir.uta.edu_sockg_ontology#hasTillage
    click HttpsIdir.uta.eduSockg-ontology#Tillage href "../HttpsIdir.uta.eduSockg-ontology#Tillage"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#irrigation
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" Boolean : https___idir.uta.edu_sockg_ontology#irrigation
    click Boolean href "../Boolean"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#organicManagement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" Boolean : https___idir.uta.edu_sockg_ontology#organicManagement
    click Boolean href "../Boolean"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#startDate
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" Date : https___idir.uta.edu_sockg_ontology#startDate
    click Date href "../Date"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#tileDrainage
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" Boolean : https___idir.uta.edu_sockg_ontology#tileDrainage
    click Boolean href "../Boolean"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#treatmentHasAmendment
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#Amendment : https___idir.uta.edu_sockg_ontology#treatmentHasAmendment
    click HttpsIdir.uta.eduSockg-ontology#Amendment href "../HttpsIdir.uta.eduSockg-ontology#Amendment"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#treatmentHasGrazingManagement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#GrazingManagement : https___idir.uta.edu_sockg_ontology#treatmentHasGrazingManagement
    click HttpsIdir.uta.eduSockg-ontology#GrazingManagement href "../HttpsIdir.uta.eduSockg-ontology#GrazingManagement"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#treatmentHasGrowthStageManagement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement : https___idir.uta.edu_sockg_ontology#treatmentHasGrowthStageManagement
    click HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement href "../HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#treatmentHasPlantingManagement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#PlantingManagement : https___idir.uta.edu_sockg_ontology#treatmentHasPlantingManagement
    click HttpsIdir.uta.eduSockg-ontology#PlantingManagement href "../HttpsIdir.uta.eduSockg-ontology#PlantingManagement"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#treatmentHasResidueManagement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#ResidueManagement : https___idir.uta.edu_sockg_ontology#treatmentHasResidueManagement
    click HttpsIdir.uta.eduSockg-ontology#ResidueManagement href "../HttpsIdir.uta.eduSockg-ontology#ResidueManagement"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#treatmentHasTillageManagement
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#TillageManagement : https___idir.uta.edu_sockg_ontology#treatmentHasTillageManagement
    click HttpsIdir.uta.eduSockg-ontology#TillageManagement href "../HttpsIdir.uta.eduSockg-ontology#TillageManagement"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#usesCoverCrop
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#CoverCrop : https___idir.uta.edu_sockg_ontology#usesCoverCrop
    click HttpsIdir.uta.eduSockg-ontology#CoverCrop href "../HttpsIdir.uta.eduSockg-ontology#CoverCrop"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#usesFertilizerAmendment
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#FertilizerAmendment : https___idir.uta.edu_sockg_ontology#usesFertilizerAmendment
    click HttpsIdir.uta.eduSockg-ontology#FertilizerAmendment href "../HttpsIdir.uta.eduSockg-ontology#FertilizerAmendment"

        
      HttpsIdir.uta.eduSockg-ontology#Treatment : https___idir.uta.edu_sockg_ontology#usesResidueRemoval
        
          
    
    
    HttpsIdir.uta.eduSockg-ontology#Treatment --> "0..1" HttpsIdir.uta.eduSockg-ontology#ResidueRemoval : https___idir.uta.edu_sockg_ontology#usesResidueRemoval
    click HttpsIdir.uta.eduSockg-ontology#ResidueRemoval href "../HttpsIdir.uta.eduSockg-ontology#ResidueRemoval"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___idir.uta.edu_sockg_ontology#treatmentHasGrowthStageManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasGrowthStageManagement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrowthStageManagement.md) |  <br/>  | direct | 5148 |
| [https___idir.uta.edu_sockg_ontology#hasRotation](../slots/https___idir.uta.edu_sockg_ontology#hasRotation.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Rotation](../classes/HttpsIdir.uta.eduSockg-ontology#Rotation.md) |  <br/>  | direct | 761 |
| [https___idir.uta.edu_sockg_ontology#hasProjectScenario](../slots/https___idir.uta.edu_sockg_ontology#hasProjectScenario.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#ProjectScenario](../classes/HttpsIdir.uta.eduSockg-ontology#ProjectScenario.md) |  <br/>  | direct | 826 |
| [https___idir.uta.edu_sockg_ontology#tileDrainage](../slots/https___idir.uta.edu_sockg_ontology#tileDrainage.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) |  <br/>  | direct | 438 |
| [https___idir.uta.edu_sockg_ontology#treatmentHasTillageManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasTillageManagement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#TillageManagement](../classes/HttpsIdir.uta.eduSockg-ontology#TillageManagement.md) |  <br/>  | direct | 27450 |
| [https___idir.uta.edu_sockg_ontology#usesCoverCrop](../slots/https___idir.uta.edu_sockg_ontology#usesCoverCrop.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#CoverCrop](../classes/HttpsIdir.uta.eduSockg-ontology#CoverCrop.md) |  <br/>  | direct | 194 |
| [dct_description](../slots/dct_description.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | Description may include but is not limited to: an abstract, a table of conten... <br/> description: An account of the resource. | direct | 774 |
| [https___idir.uta.edu_sockg_ontology#usesResidueRemoval](../slots/https___idir.uta.edu_sockg_ontology#usesResidueRemoval.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#ResidueRemoval](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueRemoval.md) |  <br/>  | direct | 769 |
| [https___idir.uta.edu_sockg_ontology#startDate](../slots/https___idir.uta.edu_sockg_ontology#startDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 769 |
| [https___idir.uta.edu_sockg_ontology#fromProject](../slots/https___idir.uta.edu_sockg_ontology#fromProject.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Project](../classes/HttpsIdir.uta.eduSockg-ontology#Project.md) |  <br/>  | direct | 935 |
| [https___idir.uta.edu_sockg_ontology#organicManagement](../slots/https___idir.uta.edu_sockg_ontology#organicManagement.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) |  <br/>  | direct | 769 |
| [https___idir.uta.edu_sockg_ontology#treatmentHasGrazingManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasGrazingManagement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#GrazingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingManagement.md) |  <br/>  | direct | 1945 |
| [https___idir.uta.edu_sockg_ontology#hasAnimalSpecies](../slots/https___idir.uta.edu_sockg_ontology#hasAnimalSpecies.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#AnimalSpecies](../classes/HttpsIdir.uta.eduSockg-ontology#AnimalSpecies.md) |  <br/>  | direct | 3 |
| [dct_identifier](../slots/dct_identifier.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | Recommended practice is to identify the resource by means of a string conform... <br/> description: An unambiguous reference to the resource within a given context. | direct | 769 |
| [https___idir.uta.edu_sockg_ontology#hasGrazingRate](../slots/https___idir.uta.edu_sockg_ontology#hasGrazingRate.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#GrazingRate](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingRate.md) |  <br/>  | direct | 20 |
| [https___idir.uta.edu_sockg_ontology#treatmentHasPlantingManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasPlantingManagement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#PlantingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#PlantingManagement.md) |  <br/>  | direct | 23616 |
| [https___idir.uta.edu_sockg_ontology#irrigation](../slots/https___idir.uta.edu_sockg_ontology#irrigation.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) |  <br/>  | direct | 774 |
| [https___idir.uta.edu_sockg_ontology#treatmentHasResidueManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasResidueManagement.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#ResidueManagement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueManagement.md) |  <br/>  | direct | 3334 |
| [https___idir.uta.edu_sockg_ontology#treatmentHasAmendment](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasAmendment.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Amendment](../classes/HttpsIdir.uta.eduSockg-ontology#Amendment.md) |  <br/>  | direct | 47106 |
| [https___idir.uta.edu_sockg_ontology#hasTillage](../slots/https___idir.uta.edu_sockg_ontology#hasTillage.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#Tillage](../classes/HttpsIdir.uta.eduSockg-ontology#Tillage.md) |  <br/>  | direct | 711 |
| [https___idir.uta.edu_sockg_ontology#usesFertilizerAmendment](../slots/https___idir.uta.edu_sockg_ontology#usesFertilizerAmendment.md) | 0..1 <br/> [HttpsIdir.uta.eduSockg-ontology#FertilizerAmendment](../classes/HttpsIdir.uta.eduSockg-ontology#FertilizerAmendment.md) |  <br/>  | direct | 653 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassCarbohydrate.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassEnergy](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassEnergy.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#BiomassMineral](../classes/HttpsIdir.uta.eduSockg-ontology#BiomassMineral.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#GHGFlux](../classes/HttpsIdir.uta.eduSockg-ontology#GHGFlux.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss](../classes/HttpsIdir.uta.eduSockg-ontology#GasNutrientLoss.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#GrazingManagement](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingManagement.md) | [https___idir.uta.edu_sockg_ontology#hasAnimalSpecies](../slots/https___idir.uta.edu_sockg_ontology#hasAnimalSpecies.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#GrazingPlants](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingPlants.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#HarvestFraction](../classes/HttpsIdir.uta.eduSockg-ontology#HarvestFraction.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) | [https___idir.uta.edu_sockg_ontology#hasTreatment](../slots/https___idir.uta.edu_sockg_ontology#hasTreatment.md) | range | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency](../classes/HttpsIdir.uta.eduSockg-ontology#NutrientEfficiency.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueMeasurement.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilBiologicalSample.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilChemicalSample.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilCover](../classes/HttpsIdir.uta.eduSockg-ontology#SoilCover.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample](../classes/HttpsIdir.uta.eduSockg-ontology#SoilPhysicalSample.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#treatmentHasGrowthStageManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasGrowthStageManagement.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#hasRotation](../slots/https___idir.uta.edu_sockg_ontology#hasRotation.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#hasProjectScenario](../slots/https___idir.uta.edu_sockg_ontology#hasProjectScenario.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#tileDrainage](../slots/https___idir.uta.edu_sockg_ontology#tileDrainage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#treatmentHasTillageManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasTillageManagement.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#usesCoverCrop](../slots/https___idir.uta.edu_sockg_ontology#usesCoverCrop.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#usesResidueRemoval](../slots/https___idir.uta.edu_sockg_ontology#usesResidueRemoval.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#fromProject](../slots/https___idir.uta.edu_sockg_ontology#fromProject.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#organicManagement](../slots/https___idir.uta.edu_sockg_ontology#organicManagement.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#treatmentHasGrazingManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasGrazingManagement.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#hasAnimalSpecies](../slots/https___idir.uta.edu_sockg_ontology#hasAnimalSpecies.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#hasGrazingRate](../slots/https___idir.uta.edu_sockg_ontology#hasGrazingRate.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#treatmentHasPlantingManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasPlantingManagement.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#irrigation](../slots/https___idir.uta.edu_sockg_ontology#irrigation.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#treatmentHasResidueManagement](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasResidueManagement.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#treatmentHasAmendment](../slots/https___idir.uta.edu_sockg_ontology#treatmentHasAmendment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#hasTillage](../slots/https___idir.uta.edu_sockg_ontology#hasTillage.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) | [https___idir.uta.edu_sockg_ontology#usesFertilizerAmendment](../slots/https___idir.uta.edu_sockg_ontology#usesFertilizerAmendment.md) | domain | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityArea](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityArea.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration](../classes/HttpsIdir.uta.eduSockg-ontology#WaterQualityConcentration.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#WeatherObservation](../classes/HttpsIdir.uta.eduSockg-ontology#WeatherObservation.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#WindErosionArea](../classes/HttpsIdir.uta.eduSockg-ontology#WindErosionArea.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |
| [HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake](../classes/HttpsIdir.uta.eduSockg-ontology#YieldNutrientUptake.md) | [https___idir.uta.edu_sockg_ontology#usesTreatment](../slots/https___idir.uta.edu_sockg_ontology#usesTreatment.md) | any_of[range] | [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Treatment
from_schema: okns:soc-kg
rank: 1000
slots:
- https___idir.uta.edu_sockg-ontology#treatmentHasGrowthStageManagement
- https___idir.uta.edu_sockg-ontology#hasRotation
- https___idir.uta.edu_sockg-ontology#hasProjectScenario
- https___idir.uta.edu_sockg-ontology#tileDrainage
- https___idir.uta.edu_sockg-ontology#treatmentHasTillageManagement
- https___idir.uta.edu_sockg-ontology#usesCoverCrop
- dct_description
- https___idir.uta.edu_sockg-ontology#usesResidueRemoval
- https___idir.uta.edu_sockg-ontology#startDate
- https___idir.uta.edu_sockg-ontology#fromProject
- https___idir.uta.edu_sockg-ontology#organicManagement
- https___idir.uta.edu_sockg-ontology#treatmentHasGrazingManagement
- https___idir.uta.edu_sockg-ontology#hasAnimalSpecies
- dct_identifier
- https___idir.uta.edu_sockg-ontology#hasGrazingRate
- https___idir.uta.edu_sockg-ontology#treatmentHasPlantingManagement
- https___idir.uta.edu_sockg-ontology#irrigation
- https___idir.uta.edu_sockg-ontology#treatmentHasResidueManagement
- https___idir.uta.edu_sockg-ontology#treatmentHasAmendment
- https___idir.uta.edu_sockg-ontology#hasTillage
- https___idir.uta.edu_sockg-ontology#usesFertilizerAmendment
class_uri: https://idir.uta.edu/sockg-ontology#Treatment

```
</details>

### Induced

<details>

```yaml
name: https___idir.uta.edu_sockg-ontology#Treatment
from_schema: okns:soc-kg
rank: 1000
attributes:
  https___idir.uta.edu_sockg-ontology#treatmentHasGrowthStageManagement:
    name: https___idir.uta.edu_sockg-ontology#treatmentHasGrowthStageManagement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#treatmentHasGrowthStageManagement
    alias: https___idir.uta.edu_sockg_ontology#treatmentHasGrowthStageManagement
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#GrowthStageManagement
  https___idir.uta.edu_sockg-ontology#hasRotation:
    name: https___idir.uta.edu_sockg-ontology#hasRotation
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#hasRotation
    alias: https___idir.uta.edu_sockg_ontology#hasRotation
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#Rotation
  https___idir.uta.edu_sockg-ontology#hasProjectScenario:
    name: https___idir.uta.edu_sockg-ontology#hasProjectScenario
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#hasProjectScenario
    alias: https___idir.uta.edu_sockg_ontology#hasProjectScenario
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#ProjectScenario
  https___idir.uta.edu_sockg-ontology#tileDrainage:
    name: https___idir.uta.edu_sockg-ontology#tileDrainage
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#tileDrainage
    alias: https___idir.uta.edu_sockg_ontology#tileDrainage
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: boolean
  https___idir.uta.edu_sockg-ontology#treatmentHasTillageManagement:
    name: https___idir.uta.edu_sockg-ontology#treatmentHasTillageManagement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#treatmentHasTillageManagement
    alias: https___idir.uta.edu_sockg_ontology#treatmentHasTillageManagement
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#TillageManagement
  https___idir.uta.edu_sockg-ontology#usesCoverCrop:
    name: https___idir.uta.edu_sockg-ontology#usesCoverCrop
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#usesCoverCrop
    alias: https___idir.uta.edu_sockg_ontology#usesCoverCrop
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#CoverCrop
  dct_description:
    name: dct_description
    description: 'Description may include but is not limited to: an abstract, a table
      of contents, a graphical representation, or a free-text account of the resource.'
    title: Description
    comments:
    - 'description: An account of the resource.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:description
    alias: dct_description
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - qudt_BinaryPrefix
    - qudt_CardinalityType
    - qudt_ContextualUnit
    - qudt_CountingUnit
    - qudt_DecimalPrefix
    - qudt_DerivedUnit
    - qudt_DimensionlessUnit
    - qudt_LogarithmicUnit
    - qudt_Unit
    - vaem_GraphRole
    - https___idir.uta.edu_sockg-ontology#AnimalSpecies
    - https___idir.uta.edu_sockg-ontology#CoverCrop
    - https___idir.uta.edu_sockg-ontology#FertilizerAmendment
    - https___idir.uta.edu_sockg-ontology#GrazingRate
    - https___idir.uta.edu_sockg-ontology#JournalArticle
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Proceedings
    - https___idir.uta.edu_sockg-ontology#Project
    - https___idir.uta.edu_sockg-ontology#ProjectScenario
    - https___idir.uta.edu_sockg-ontology#ResidueRemoval
    - https___idir.uta.edu_sockg-ontology#Rotation
    - https___idir.uta.edu_sockg-ontology#Thesis
    - https___idir.uta.edu_sockg-ontology#Tillage
    - https___idir.uta.edu_sockg-ontology#Timing
    - https___idir.uta.edu_sockg-ontology#Treatment
    subproperty_of: dc_description
    range: string
  https___idir.uta.edu_sockg-ontology#usesResidueRemoval:
    name: https___idir.uta.edu_sockg-ontology#usesResidueRemoval
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#usesResidueRemoval
    alias: https___idir.uta.edu_sockg_ontology#usesResidueRemoval
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#ResidueRemoval
  https___idir.uta.edu_sockg-ontology#startDate:
    name: https___idir.uta.edu_sockg-ontology#startDate
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Location
    slot_uri: https://idir.uta.edu/sockg-ontology#startDate
    alias: https___idir.uta.edu_sockg_ontology#startDate
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Amendment
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    - https___idir.uta.edu_sockg-ontology#GrazingManagement
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#PlantingManagement
    - https___idir.uta.edu_sockg-ontology#ResidueManagement
    - https___idir.uta.edu_sockg-ontology#TillageManagement
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: date
  https___idir.uta.edu_sockg-ontology#fromProject:
    name: https___idir.uta.edu_sockg-ontology#fromProject
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#fromProject
    alias: https___idir.uta.edu_sockg_ontology#fromProject
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#Project
  https___idir.uta.edu_sockg-ontology#organicManagement:
    name: https___idir.uta.edu_sockg-ontology#organicManagement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#organicManagement
    alias: https___idir.uta.edu_sockg_ontology#organicManagement
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: boolean
  https___idir.uta.edu_sockg-ontology#treatmentHasGrazingManagement:
    name: https___idir.uta.edu_sockg-ontology#treatmentHasGrazingManagement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#treatmentHasGrazingManagement
    alias: https___idir.uta.edu_sockg_ontology#treatmentHasGrazingManagement
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#GrazingManagement
  https___idir.uta.edu_sockg-ontology#hasAnimalSpecies:
    name: https___idir.uta.edu_sockg-ontology#hasAnimalSpecies
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#hasAnimalSpecies
    alias: https___idir.uta.edu_sockg_ontology#hasAnimalSpecies
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#GrazingManagement
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#AnimalSpecies
  dct_identifier:
    name: dct_identifier
    description: Recommended practice is to identify the resource by means of a string
      conforming to an identification system. Examples include International Standard
      Book Number (ISBN), Digital Object Identifier (DOI), and Uniform Resource Name
      (URN).  Persistent identifiers should be provided as HTTP URIs.
    title: Identifier
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: An unambiguous reference to the resource within a given context.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:identifier
    alias: dct_identifier
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#ExperimentalUnit
    - https___idir.uta.edu_sockg-ontology#JournalArticle
    - https___idir.uta.edu_sockg-ontology#Location
    - https___idir.uta.edu_sockg-ontology#Site
    - https___idir.uta.edu_sockg-ontology#Treatment
    subproperty_of: dc_identifier
    range: rdfs_Literal
  https___idir.uta.edu_sockg-ontology#hasGrazingRate:
    name: https___idir.uta.edu_sockg-ontology#hasGrazingRate
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#hasGrazingRate
    alias: https___idir.uta.edu_sockg_ontology#hasGrazingRate
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#GrazingRate
  https___idir.uta.edu_sockg-ontology#treatmentHasPlantingManagement:
    name: https___idir.uta.edu_sockg-ontology#treatmentHasPlantingManagement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#treatmentHasPlantingManagement
    alias: https___idir.uta.edu_sockg_ontology#treatmentHasPlantingManagement
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#PlantingManagement
  https___idir.uta.edu_sockg-ontology#irrigation:
    name: https___idir.uta.edu_sockg-ontology#irrigation
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#irrigation
    alias: https___idir.uta.edu_sockg_ontology#irrigation
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: boolean
  https___idir.uta.edu_sockg-ontology#treatmentHasResidueManagement:
    name: https___idir.uta.edu_sockg-ontology#treatmentHasResidueManagement
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#treatmentHasResidueManagement
    alias: https___idir.uta.edu_sockg_ontology#treatmentHasResidueManagement
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#ResidueManagement
  https___idir.uta.edu_sockg-ontology#treatmentHasAmendment:
    name: https___idir.uta.edu_sockg-ontology#treatmentHasAmendment
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#treatmentHasAmendment
    alias: https___idir.uta.edu_sockg_ontology#treatmentHasAmendment
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#Amendment
  https___idir.uta.edu_sockg-ontology#hasTillage:
    name: https___idir.uta.edu_sockg-ontology#hasTillage
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#hasTillage
    alias: https___idir.uta.edu_sockg_ontology#hasTillage
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#Tillage
  https___idir.uta.edu_sockg-ontology#usesFertilizerAmendment:
    name: https___idir.uta.edu_sockg-ontology#usesFertilizerAmendment
    from_schema: okns:soc-kg
    rank: 1000
    domain: https___idir.uta.edu_sockg-ontology#Treatment
    slot_uri: https://idir.uta.edu/sockg-ontology#usesFertilizerAmendment
    alias: https___idir.uta.edu_sockg_ontology#usesFertilizerAmendment
    owner: https___idir.uta.edu_sockg-ontology#Treatment
    domain_of:
    - https___idir.uta.edu_sockg-ontology#Treatment
    range: https___idir.uta.edu_sockg-ontology#FertilizerAmendment
class_uri: https://idir.uta.edu/sockg-ontology#Treatment

```
</details>