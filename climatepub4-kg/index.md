# TODO_Give_this_schema_a_name!

TODO -- tell the world what this schema describes.

URI: climatepub4-kg

Name: climatepub4-kg



## Schema Diagram

```mermaid
erDiagram
Any {

}
SdohActivity {
    string skos_prefLabel  
    string skos_definition  
}
SdohChronostratigraphicUnit {
    string skos_prefLabel  
    string skos_definition  
}
SdohCmip6SourceId {
    string skos_prefLabel  
    string skos_definition  
}
SdohDataFormat {
    string skos_prefLabel  
    string skos_definition  
}
SdohDataset {
    string skos_prefLabel  
    string skos_definition  
}
SdohExperiment {
    string http___attribute.org_end_year  
    string http___attribute.org_experiment  
    string skos_prefLabel  
    string http___attribute.org_tier  
    string http___attribute.org_start_year  
    string skos_definition  
}
SdohFrequency {
    string skos_prefLabel  
    string skos_definition  
}
SdohGridLabel {

}
SdohHorizontalResolutionRange {
    string skos_prefLabel  
}
SdohInstitution {
    string skos_prefLabel  
    string skos_definition  
}
SdohInstrument {
    string skos_prefLabel  
    string skos_definition  
}
SdohLicense {
    string skos_prefLabel  
    string skos_definition  
}
SdohLocation {
    string skos_prefLabel  
    string skos_definition  
}
SdohMeasurementName {
    string skos_prefLabel  
    string skos_definition  
}
SdohMimeType {
    string skos_prefLabel  
    string skos_definition  
}
SdohModel {
    string skos_prefLabel  
    string skos_definition  
}
SdohModels {
    string skos_prefLabel  
    string skos_definition  
}
SdohNominalResolution {
    string skos_prefLabel  
}
SdohObs4MipsSourceId {

}
SdohPlatform {
    string skos_prefLabel  
    string skos_definition  
}
SdohProject {
    string skos_prefLabel  
    string skos_definition  
}
SdohProvider {
    string skos_prefLabel  
    string skos_definition  
}
SdohRealm {
    string skos_prefLabel  
}
SdohRegion {

}
SdohRelatedUrlContentType {
    string skos_prefLabel  
    string skos_definition  
}
SdohScienceKeyword {
    string skos_prefLabel  
    string skos_definition  
}
SdohSourceType {
    string skos_prefLabel  
    string skos_definition  
}
SdohSubExperimentId {
    string skos_prefLabel  
    string skos_definition  
}
SdohTemporalResolutionRange {
    string skos_prefLabel  
    string skos_definition  
}
SdohVariable {
    string skos_prefLabel  
    string skos_definition  
}
SdohVerticalResolutionRange {
    string skos_prefLabel  
}
SdohPaper {
    string http___attribute.org_title  
    string http___attribute.org_authors  
    string http___attribute.org_doi  
    string http___attribute.org_pub_date  
}
SkosConcept {
    uri skos_inScheme  
    string skos_prefLabel  
    string skos_definition  
}

SdohActivity ||--|o Any : "http___relation.org_UsedIn"
SdohActivity ||--|o SdohProject : "http___relation.org_HasProjectName"
SdohActivity ||--|o Any : "http___relation.org_RunBy"
SdohActivity ||--|o Any : "skos_broader"
SdohActivity ||--|o Any : "http___relation.org_TargetsLocation"
SdohActivity ||--|o Any : "http___relation.org_ProvidedBy"
SdohActivity ||--|o Any : "http___relation.org_MeasuredAt"
SdohActivity ||--|o Any : "http___relation.org_ComparedTo"
SdohChronostratigraphicUnit ||--|o Any : "http___relation.org_UsedIn"
SdohChronostratigraphicUnit ||--|o Any : "http___relation.org_RunBy"
SdohChronostratigraphicUnit ||--|o Any : "skos_broader"
SdohChronostratigraphicUnit ||--|o Any : "http___relation.org_TargetsLocation"
SdohChronostratigraphicUnit ||--|o Any : "http___relation.org_MeasuredAt"
SdohChronostratigraphicUnit ||--|o Any : "http___relation.org_ComparedTo"
SdohCmip6SourceId ||--|o Any : "http___relation.org_HasModelComponent"
SdohCmip6SourceId ||--|o SdohProject : "http___relation.org_HasProjectName"
SdohCmip6SourceId ||--|o Any : "http___relation.org_UsedIn"
SdohCmip6SourceId ||--|o Any : "http___relation.org_RunBy"
SdohCmip6SourceId ||--|o Any : "skos_broader"
SdohCmip6SourceId ||--|o Any : "http___relation.org_ComparedTo"
SdohCmip6SourceId ||--|o Any : "http___relation.org_Outputs"
SdohCmip6SourceId ||--|o Any : "http___relation.org_TargetsLocation"
SdohCmip6SourceId ||--|o Any : "http___relation.org_ProvidedBy"
SdohCmip6SourceId ||--|o SdohActivity : "http___relation.org_HasActivityParticipation"
SdohCmip6SourceId ||--|o Any : "http___relation.org_ValidatedBy"
SdohCmip6SourceId ||--|o SdohLicense : "http___relation.org_HasLicenseInfo"
SdohCmip6SourceId ||--|o SdohInstitution : "http___relation.org_HasInstitution"
SdohDataFormat ||--|o Any : "http___relation.org_UsedIn"
SdohDataFormat ||--|o Any : "skos_broader"
SdohDataFormat ||--|o Any : "http___relation.org_Outputs"
SdohDataFormat ||--|o Any : "http___relation.org_TargetsLocation"
SdohDataFormat ||--|o Any : "http___relation.org_ProvidedBy"
SdohDataFormat ||--|o Any : "http___relation.org_MeasuredAt"
SdohDataFormat ||--|o Any : "http___relation.org_ComparedTo"
SdohDataset ||--|o Any : "http___relation.org_UsedIn"
SdohDataset ||--|o SdohProject : "http___relation.org_HasProjectName"
SdohDataset ||--|o Any : "http___relation.org_HasSourceType"
SdohDataset ||--|o Any : "skos_broader"
SdohDataset ||--|o Any : "http___relation.org_Outputs"
SdohDataset ||--|o Any : "http___relation.org_ComparedTo"
SdohDataset ||--|o Any : "http___relation.org_TargetsLocation"
SdohDataset ||--|o Any : "http___relation.org_ProvidedBy"
SdohDataset ||--|o Any : "http___relation.org_MeasuredAt"
SdohDataset ||--|o SdohLocation : "http___relation.org_HasRegion"
SdohDataset ||--|o SdohInstitution : "http___relation.org_HasInstitution"
SdohExperiment ||--|o Any : "skos_broader"
SdohExperiment ||--|o Any : "http___relation.org_Outputs"
SdohExperiment ||--|o Any : "http___relation.org_ValidatedBy"
SdohExperiment ||--|o Any : "http___relation.org_ProvidedBy"
SdohExperiment ||--|o Any : "http___relation.org_UsedIn"
SdohExperiment ||--|o Any : "http___relation.org_MountedOn"
SdohExperiment ||--|o SdohProject : "http___relation.org_HasProjectName"
SdohExperiment ||--|o SdohActivity : "http___relation.org_HasActivity"
SdohExperiment ||--|o SdohActivity : "http___relation.org_HasParentActivity"
SdohExperiment ||--|o SdohExperiment : "http___relation.org_HasParentExperiment"
SdohExperiment ||--|o Any : "http___relation.org_HasAdditionalAllowedModelComponents"
SdohExperiment ||--|o Any : "http___relation.org_ComparedTo"
SdohExperiment ||--|o Any : "http___relation.org_RunBy"
SdohExperiment ||--|o Any : "http___relation.org_TargetsLocation"
SdohExperiment ||--|o Any : "http___relation.org_HasRequiredModelComponents"
SdohExperiment ||--|o Any : "http___relation.org_MeasuredAt"
SdohFrequency ||--|o Any : "skos_broader"
SdohFrequency ||--|o Any : "http___relation.org_MeasuredAt"
SdohHorizontalResolutionRange ||--|o Any : "skos_broader"
SdohHorizontalResolutionRange ||--|o Any : "http___relation.org_MeasuredAt"
SdohInstitution ||--|o Any : "http___relation.org_UsedIn"
SdohInstitution ||--|o Any : "skos_broader"
SdohInstitution ||--|o Any : "http___relation.org_ComparedTo"
SdohInstitution ||--|o Any : "http___relation.org_Outputs"
SdohInstitution ||--|o Any : "http___relation.org_TargetsLocation"
SdohInstitution ||--|o Any : "http___relation.org_MeasuredAt"
SdohInstitution ||--|o Any : "http___relation.org_ValidatedBy"
SdohInstitution ||--|o Any : "http___relation.org_ProvidedBy"
SdohInstrument ||--|o Any : "http___relation.org_UsedIn"
SdohInstrument ||--|o SdohProject : "http___relation.org_HasProjectName"
SdohInstrument ||--|o Any : "http___relation.org_RunBy"
SdohInstrument ||--|o Any : "skos_broader"
SdohInstrument ||--|o Any : "http___relation.org_MountedOn"
SdohInstrument ||--|o Any : "http___relation.org_Outputs"
SdohInstrument ||--|o Any : "http___relation.org_TargetsLocation"
SdohInstrument ||--|o Any : "http___relation.org_ProvidedBy"
SdohInstrument ||--|o Any : "http___relation.org_MeasuredAt"
SdohInstrument ||--|o Any : "http___relation.org_ValidatedBy"
SdohInstrument ||--|o Any : "http___relation.org_ComparedTo"
SdohLicense ||--|o Any : "skos_broader"
SdohLocation ||--|o Any : "http___relation.org_UsedIn"
SdohLocation ||--|o SdohProject : "http___relation.org_HasProjectName"
SdohLocation ||--|o Any : "http___relation.org_RunBy"
SdohLocation ||--|o Any : "skos_broader"
SdohLocation ||--|o Any : "http___relation.org_MountedOn"
SdohLocation ||--|o Any : "http___relation.org_Outputs"
SdohLocation ||--|o Any : "http___relation.org_TargetsLocation"
SdohLocation ||--|o Any : "http___relation.org_ProvidedBy"
SdohLocation ||--|o Any : "http___relation.org_MeasuredAt"
SdohLocation ||--|o Any : "http___relation.org_ValidatedBy"
SdohLocation ||--|o Any : "http___relation.org_ComparedTo"
SdohMeasurementName ||--|o Any : "http___relation.org_UsedIn"
SdohMeasurementName ||--|o Any : "skos_broader"
SdohMeasurementName ||--|o Any : "http___relation.org_TargetsLocation"
SdohMeasurementName ||--|o Any : "http___relation.org_MeasuredAt"
SdohMeasurementName ||--|o Any : "http___relation.org_ComparedTo"
SdohMimeType ||--|o Any : "skos_broader"
SdohModel ||--|o Any : "http___relation.org_UsedIn"
SdohModel ||--|o SdohProject : "http___relation.org_HasProjectName"
SdohModel ||--|o Any : "http___relation.org_RunBy"
SdohModel ||--|o Any : "skos_broader"
SdohModel ||--|o Any : "http___relation.org_ComparedTo"
SdohModel ||--|o Any : "http___relation.org_Outputs"
SdohModel ||--|o Any : "http___relation.org_TargetsLocation"
SdohModel ||--|o Any : "http___relation.org_MeasuredAt"
SdohModel ||--|o Any : "http___relation.org_ValidatedBy"
SdohModel ||--|o Any : "http___relation.org_ProvidedBy"
SdohModels ||--|o Any : "http___relation.org_UsedIn"
SdohModels ||--|o SdohProject : "http___relation.org_HasProjectName"
SdohModels ||--|o Any : "http___relation.org_RunBy"
SdohModels ||--|o Any : "skos_broader"
SdohModels ||--|o Any : "http___relation.org_ComparedTo"
SdohModels ||--|o Any : "http___relation.org_Outputs"
SdohModels ||--|o Any : "http___relation.org_TargetsLocation"
SdohModels ||--|o Any : "http___relation.org_MeasuredAt"
SdohModels ||--|o Any : "http___relation.org_ValidatedBy"
SdohModels ||--|o Any : "http___relation.org_ProvidedBy"
SdohNominalResolution ||--|o Any : "skos_broader"
SdohPlatform ||--|o Any : "http___relation.org_UsedIn"
SdohPlatform ||--|o Any : "http___relation.org_RunBy"
SdohPlatform ||--|o Any : "skos_broader"
SdohPlatform ||--|o Any : "http___relation.org_ComparedTo"
SdohPlatform ||--|o Any : "http___relation.org_MountedOn"
SdohPlatform ||--|o Any : "http___relation.org_Outputs"
SdohPlatform ||--|o Any : "http___relation.org_TargetsLocation"
SdohPlatform ||--|o Any : "http___relation.org_MeasuredAt"
SdohPlatform ||--|o Any : "http___relation.org_ProvidedBy"
SdohProject ||--|o Any : "http___relation.org_UsedIn"
SdohProject ||--|o SdohProject : "http___relation.org_HasProjectName"
SdohProject ||--|o Any : "http___relation.org_RunBy"
SdohProject ||--|o Any : "skos_broader"
SdohProject ||--|o Any : "http___relation.org_MountedOn"
SdohProject ||--|o Any : "http___relation.org_Outputs"
SdohProject ||--|o Any : "http___relation.org_TargetsLocation"
SdohProject ||--|o Any : "http___relation.org_ProvidedBy"
SdohProject ||--|o Any : "http___relation.org_MeasuredAt"
SdohProject ||--|o Any : "http___relation.org_ValidatedBy"
SdohProject ||--|o Any : "http___relation.org_ComparedTo"
SdohProvider ||--|o Any : "http___relation.org_UsedIn"
SdohProvider ||--|o SdohProject : "http___relation.org_HasProjectName"
SdohProvider ||--|o Any : "skos_broader"
SdohProvider ||--|o Any : "http___relation.org_MountedOn"
SdohProvider ||--|o Any : "http___relation.org_Outputs"
SdohProvider ||--|o Any : "http___relation.org_TargetsLocation"
SdohProvider ||--|o Any : "http___relation.org_ProvidedBy"
SdohProvider ||--|o Any : "http___relation.org_MeasuredAt"
SdohProvider ||--|o Any : "http___relation.org_ValidatedBy"
SdohProvider ||--|o Any : "http___relation.org_ComparedTo"
SdohRealm ||--|o SdohProject : "http___relation.org_HasProjectName"
SdohRealm ||--|o Any : "skos_broader"
SdohRelatedUrlContentType ||--|o Any : "http___relation.org_UsedIn"
SdohRelatedUrlContentType ||--|o Any : "skos_broader"
SdohRelatedUrlContentType ||--|o Any : "http___relation.org_TargetsLocation"
SdohRelatedUrlContentType ||--|o Any : "http___relation.org_MeasuredAt"
SdohRelatedUrlContentType ||--|o Any : "http___relation.org_ComparedTo"
SdohScienceKeyword ||--|o Any : "http___relation.org_UsedIn"
SdohScienceKeyword ||--|o Any : "http___relation.org_RunBy"
SdohScienceKeyword ||--|o Any : "skos_broader"
SdohScienceKeyword ||--|o Any : "http___relation.org_Outputs"
SdohScienceKeyword ||--|o Any : "http___relation.org_TargetsLocation"
SdohScienceKeyword ||--|o Any : "http___relation.org_ProvidedBy"
SdohScienceKeyword ||--|o Any : "http___relation.org_MeasuredAt"
SdohScienceKeyword ||--|o Any : "http___relation.org_ComparedTo"
SdohSourceType ||--|o Any : "skos_broader"
SdohSubExperimentId ||--|o Any : "skos_broader"
SdohSubExperimentId ||--|o Any : "http___relation.org_TargetsLocation"
SdohSubExperimentId ||--|o Any : "http___relation.org_MeasuredAt"
SdohSubExperimentId ||--|o Any : "http___relation.org_ComparedTo"
SdohTemporalResolutionRange ||--|o Any : "http___relation.org_UsedIn"
SdohTemporalResolutionRange ||--|o Any : "skos_broader"
SdohTemporalResolutionRange ||--|o Any : "http___relation.org_TargetsLocation"
SdohTemporalResolutionRange ||--|o Any : "http___relation.org_MeasuredAt"
SdohVariable ||--|o Any : "http___relation.org_UsedIn"
SdohVariable ||--|o SdohProject : "http___relation.org_HasProjectName"
SdohVariable ||--|o Any : "skos_broader"
SdohVariable ||--|o Any : "http___relation.org_Outputs"
SdohVariable ||--|o Any : "http___relation.org_TargetsLocation"
SdohVariable ||--|o Any : "http___relation.org_ProvidedBy"
SdohVariable ||--|o Any : "http___relation.org_MeasuredAt"
SdohVariable ||--|o Any : "http___relation.org_ValidatedBy"
SdohVariable ||--|o Any : "http___relation.org_ComparedTo"
SdohVerticalResolutionRange ||--|o Any : "skos_broader"
SdohPaper ||--|o Any : "http___relation.org_Mention"
SkosConcept ||--|o SkosConcept : "skos_narrower"
SkosConcept ||--|o Any : "skos_broader"

```


## Classes

| Class | Description |
| --- | --- |
| [Any](classes/Any.md) | None |
| [SdohActivity](classes/SdohActivity.md) | TODO -- tell the world what this class (type) describes. |
| [SdohChronostratigraphicUnit](classes/SdohChronostratigraphicUnit.md) | TODO -- tell the world what this class (type) describes. |
| [SdohCmip6SourceId](classes/SdohCmip6SourceId.md) | TODO -- tell the world what this class (type) describes. |
| [SdohDataFormat](classes/SdohDataFormat.md) | TODO -- tell the world what this class (type) describes. |
| [SdohDataset](classes/SdohDataset.md) | A body of structured information describing some topic(s) of interest. |
| [SdohExperiment](classes/SdohExperiment.md) | TODO -- tell the world what this class (type) describes. |
| [SdohFrequency](classes/SdohFrequency.md) | TODO -- tell the world what this class (type) describes. |
| [SdohGridLabel](classes/SdohGridLabel.md) | TODO -- tell the world what this class (type) describes. |
| [SdohHorizontalResolutionRange](classes/SdohHorizontalResolutionRange.md) | TODO -- tell the world what this class (type) describes. |
| [SdohInstitution](classes/SdohInstitution.md) | TODO -- tell the world what this class (type) describes. |
| [SdohInstrument](classes/SdohInstrument.md) | TODO -- tell the world what this class (type) describes. |
| [SdohLicense](classes/SdohLicense.md) | TODO -- tell the world what this class (type) describes. |
| [SdohLocation](classes/SdohLocation.md) | TODO -- tell the world what this class (type) describes. |
| [SdohMeasurementName](classes/SdohMeasurementName.md) | TODO -- tell the world what this class (type) describes. |
| [SdohMimeType](classes/SdohMimeType.md) | TODO -- tell the world what this class (type) describes. |
| [SdohModel](classes/SdohModel.md) | TODO -- tell the world what this class (type) describes. |
| [SdohModels](classes/SdohModels.md) | TODO -- tell the world what this class (type) describes. |
| [SdohNominalResolution](classes/SdohNominalResolution.md) | TODO -- tell the world what this class (type) describes. |
| [SdohObs4MipsSourceId](classes/SdohObs4MipsSourceId.md) | TODO -- tell the world what this class (type) describes. |
| [SdohPaper](classes/SdohPaper.md) | TODO -- tell the world what this class (type) describes. |
| [SdohPlatform](classes/SdohPlatform.md) | TODO -- tell the world what this class (type) describes. |
| [SdohProject](classes/SdohProject.md) | An enterprise (potentially individual but typically collaborative), planned to achieve a particular aim.
Use properties from [[Organization]], [[subOrganization]]/[[parentOrganization]] to indicate project sub-structures. 
    |
| [SdohProvider](classes/SdohProvider.md) | TODO -- tell the world what this class (type) describes. |
| [SdohRealm](classes/SdohRealm.md) | TODO -- tell the world what this class (type) describes. |
| [SdohRegion](classes/SdohRegion.md) | TODO -- tell the world what this class (type) describes. |
| [SdohRelatedUrlContentType](classes/SdohRelatedUrlContentType.md) | TODO -- tell the world what this class (type) describes. |
| [SdohScienceKeyword](classes/SdohScienceKeyword.md) | TODO -- tell the world what this class (type) describes. |
| [SdohSourceType](classes/SdohSourceType.md) | TODO -- tell the world what this class (type) describes. |
| [SdohSubExperimentId](classes/SdohSubExperimentId.md) | TODO -- tell the world what this class (type) describes. |
| [SdohTemporalResolutionRange](classes/SdohTemporalResolutionRange.md) | TODO -- tell the world what this class (type) describes. |
| [SdohVariable](classes/SdohVariable.md) | TODO -- tell the world what this class (type) describes. |
| [SdohVerticalResolutionRange](classes/SdohVerticalResolutionRange.md) | TODO -- tell the world what this class (type) describes. |
| [SkosConcept](classes/SkosConcept.md) | TODO -- tell the world what this class (type) describes. |



## Slots

| Slot | Description |
| --- | --- |
| [http___attribute.org_authors](slots/http___attribute.org_authors.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___attribute.org_doi](slots/http___attribute.org_doi.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___attribute.org_end_year](slots/http___attribute.org_end_year.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___attribute.org_experiment](slots/http___attribute.org_experiment.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___attribute.org_pub_date](slots/http___attribute.org_pub_date.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___attribute.org_start_year](slots/http___attribute.org_start_year.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___attribute.org_tier](slots/http___attribute.org_tier.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___attribute.org_title](slots/http___attribute.org_title.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___example.org_ontology_definition](slots/http___example.org_ontology_definition.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___example.org_ontology_id](slots/http___example.org_ontology_id.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___example.org_ontology_path_id](slots/http___example.org_ontology_path_id.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___example.org_ontology_path_label](slots/http___example.org_ontology_path_label.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___example.org_ontology_prefLabel](slots/http___example.org_ontology_prefLabel.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___example.org_ontology_reference](slots/http___example.org_ontology_reference.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___example.org_ontology_tag](slots/http___example.org_ontology_tag.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_ComparedTo](slots/http___relation.org_ComparedTo.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_HasActivity](slots/http___relation.org_HasActivity.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_HasActivityParticipation](slots/http___relation.org_HasActivityParticipation.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_HasAdditionalAllowedModelComponents](slots/http___relation.org_HasAdditionalAllowedModelComponents.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_HasInstitution](slots/http___relation.org_HasInstitution.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_HasLicenseInfo](slots/http___relation.org_HasLicenseInfo.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_HasModelComponent](slots/http___relation.org_HasModelComponent.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_HasParentActivity](slots/http___relation.org_HasParentActivity.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_HasParentExperiment](slots/http___relation.org_HasParentExperiment.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_HasProjectName](slots/http___relation.org_HasProjectName.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_HasRegion](slots/http___relation.org_HasRegion.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_HasRequiredModelComponents](slots/http___relation.org_HasRequiredModelComponents.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_HasSourceType](slots/http___relation.org_HasSourceType.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_MeasuredAt](slots/http___relation.org_MeasuredAt.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_Mention](slots/http___relation.org_Mention.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_MountedOn](slots/http___relation.org_MountedOn.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_Outputs](slots/http___relation.org_Outputs.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_ProvidedBy](slots/http___relation.org_ProvidedBy.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_RunBy](slots/http___relation.org_RunBy.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_TargetsLocation](slots/http___relation.org_TargetsLocation.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_UsedIn](slots/http___relation.org_UsedIn.md) | TODO -- tell the world what this slot (predicate) describes |
| [http___relation.org_ValidatedBy](slots/http___relation.org_ValidatedBy.md) | TODO -- tell the world what this slot (predicate) describes |
| [skos_broader](slots/skos_broader.md) | TODO -- tell the world what this slot (predicate) describes |
| [skos_definition](slots/skos_definition.md) | TODO -- tell the world what this slot (predicate) describes |
| [skos_inScheme](slots/skos_inScheme.md) | TODO -- tell the world what this slot (predicate) describes |
| [skos_narrower](slots/skos_narrower.md) | TODO -- tell the world what this slot (predicate) describes |
| [skos_prefLabel](slots/skos_prefLabel.md) | TODO -- tell the world what this slot (predicate) describes |


## Enumerations

| Enumeration | Description |
| --- | --- |


## Types

| Type | Description |
| --- | --- |


## Subsets

| Subset | Description |
| --- | --- |
