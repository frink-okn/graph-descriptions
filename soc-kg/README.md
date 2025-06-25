# sockg

No schema description specified



## Schema Diagram

```mermaid
erDiagram
RdfAlt {

}
RdfBag {

}
RdfCompoundLiteral {

}
RdfList {
    string rdfs_comment  
    owl_Ontology rdfs_isDefinedBy  
    string rdfs_label  
}
RdfProperty {

}
RdfSeq {

}
RdfStatement {

}
RdfsClass {

}
RdfsContainer {

}
RdfsContainerMembershipProperty {

}
RdfsDatatype {

}
RdfsLiteral {

}
RdfsResource {

}
GeoGeometry {
    geo_wktLiteral geo_asWKT  
}
HttpWww.opengis.netOntGeosparqlFeature {

}
KwgrS2CellLevel13 {

}
SockgAmendment {
    double sockg_amendmentDepth_cm  
    string sockg_type  
    float sockg_irrigationNitrogen_mg_per_L  
    double sockg_irrigationNitrogen_mg_per_L  
    string sockg_crop  
    string sockg_startDate  
    date sockg_startDate  
    string sockg_amendmentPlacement  
    float sockg_irrigationAmount_cm  
    double sockg_irrigationAmount_cm  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    float sockg_irrigationType  
    string sockg_irrigationType  
    string sockg_mgtAmendments_UID  
    float sockg_totalNitrogenAmount_kgN_per_ha  
    double sockg_totalNitrogenAmount_kgN_per_ha  
    float sockg_totalPhosphorusAmount_kgP_per_ha  
    double sockg_totalPhosphorusAmount_kgP_per_ha  
    float sockg_totalPotassiumAmount_kgK_per_ha  
    double sockg_totalPotassiumAmount_kgK_per_ha  
    uri rdfs_seeAlso  
    float sockg_totalAmendmentAmount_kg_per_ha  
    double sockg_totalAmendmentAmount_kg_per_ha  
}
SockgBioMassCarbohydrate {
    float sockg_crudeProtein_g_per_kg  
    double sockg_crudeProtein_g_per_kg  
    string sockg_date  
    date sockg_date  
    float sockg_nonFiberCarbs_g_per_kg  
    double sockg_nonFiberCarbs_g_per_kg  
    float sockg_glucan_g_per_kg  
    double sockg_glucan_g_per_kg  
    string sockg_crop  
    string sockg_growthStage  
    string sockg_plantFraction  
    float sockg_xylan_g_per_kg  
    double sockg_xylan_g_per_kg  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    float sockg_ash_g_per_kg  
    double sockg_ash_g_per_kg  
    float sockg_galactan_g_per_kg  
    double sockg_galactan_g_per_kg  
    string sockg_measBiomassCHO_UID  
    float sockg_neutralDetFiber_g_per_kg  
    double sockg_neutralDetFiber_g_per_kg  
    float sockg_lignin_g_per_kg  
    double sockg_lignin_g_per_kg  
    uri rdfs_seeAlso  
    double sockg_arabinan_g_per_kg  
    float sockg_acidDetFiber_g_per_kg  
    double sockg_acidDetFiber_g_per_kg  
}
SockgBioMassEnergy {
    string sockg_date  
    date sockg_date  
    string sockg_crop  
    string sockg_growthStage  
    string sockg_measBiomassEnergy_UID  
    string sockg_plantFraction  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    float sockg_mineralMatter_g_per_kg  
    double sockg_mineralMatter_g_per_kg  
    float sockg_grossCalorificValue_MJ_per_kg  
    double sockg_grossCalorificValue_MJ_per_kg  
    uri rdfs_seeAlso  
}
SockgBioMassMineral {
    float sockg_copperConcentration_mg_per_kg  
    double sockg_copperConcentration_mg_per_kg  
    float sockg_sodiumConcentration_g_per_kg  
    double sockg_sodiumConcentration_g_per_kg  
    string sockg_crop  
    string sockg_measBiomassMinAn_UID  
    float sockg_carbonConcentration_g_per_kg  
    double sockg_carbonConcentration_g_per_kg  
    float sockg_sulfurConcentration_g_per_kg  
    double sockg_sulfurConcentration_g_per_kg  
    string sockg_plantFraction  
    float sockg_magnesiumConcentration_g_per_kg  
    double sockg_magnesiumConcentration_g_per_kg  
    float sockg_boronConcentration_mg_per_kg  
    double sockg_boronConcentration_mg_per_kg  
    float sockg_aluminumConcentration_mg_per_kg  
    double sockg_aluminumConcentration_mg_per_kg  
    float sockg_manganeseConcentration_mg_per_kg  
    double sockg_manganeseConcentration_mg_per_kg  
    string sockg_growthStage  
    float sockg_phosphorusConcentration_g_per_kg  
    double sockg_phosphorusConcentration_g_per_kg  
    float sockg_nitrogenConcentration_g_per_kg  
    double sockg_nitrogenConcentration_g_per_kg  
    float sockg_potassiumConcentration_g_per_kg  
    double sockg_potassiumConcentration_g_per_kg  
    float sockg_ironConcentration_mg_per_kg  
    double sockg_ironConcentration_mg_per_kg  
    string sockg_date  
    date sockg_date  
    float sockg_zincConcentration_mg_per_kg  
    double sockg_zincConcentration_mg_per_kg  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    float sockg_calciumConcentration_g_per_kg  
    double sockg_calciumConcentration_g_per_kg  
    uri rdfs_seeAlso  
}
SockgBook {
    string sockg_bookName  
}
SockgCity {
    string sockg_cityName  
    uri rdfs_seeAlso  
}
SockgCountry {
    string sockg_countryName  
}
SockgCounty {
    string sockg_countyName  
    uri rdfs_seeAlso  
    string sockg_countyFIPS  
}
SockgCropGrowthStage {
    string sockg_mgtGrowthStages_UID  
    string sockg_date  
    date sockg_date  
    string sockg_crop  
    string sockg_growthStage  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    uri rdfs_seeAlso  
}
SockgDepartment {
    string sockg_departmentName  
}
SockgExperiment {
    string sockg_projectName  
    string sockg_startDate  
    date sockg_startDate  
    string sockg_experimentName  
    string sockg_endDate  
    date sockg_endDate  
    uri rdfs_seeAlso  
}
SockgExperimentalUnit {
    string sockg_startDate  
    date sockg_startDate  
    string sockg_expUnit_UID  
    string sockg_endDate  
    date sockg_endDate  
    string sockg_expUnitId  
    uri rdfs_seeAlso  
}
SockgField {
    string sockg_fieldId  
    uri rdfs_seeAlso  
}
SockgGasNutrientLoss {
    string sockg_date  
    date sockg_date  
    string sockg_samplingStartStopInterval  
    string sockg_fieldId  
    double sockg_ammoniaNitrogen_kg_ha  
    string sockg_growthStage  
    string sockg_measGasNutrientLoss_UID  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    string sockg_crop  
    string sockg_modelIfSimulated  
    string sockg_expUnitId  
    uri rdfs_seeAlso  
    float sockg_nitrousOxide_g_ha  
    double sockg_nitrousOxide_g_ha  
    string sockg_expUnit_UID  
}
SockgGasSample {
    string sockg_crop  
    float sockg_soilTemperatureSd_degC  
    double sockg_soilTemperatureSd_degC  
    float sockg_carbonDioxideSd_gC_per_ha_per_d  
    double sockg_carbonDioxideSd_gC_per_ha_per_d  
    string sockg_chamberPlacement  
    float sockg_carbonDioxide_gC_per_ha_per_d  
    double sockg_carbonDioxide_gC_per_ha_per_d  
    float sockg_airTemperature_degC  
    double sockg_airTemperature_degC  
    integer sockg_isCarbonDioxideInterpolated  
    int32 sockg_isCarbonDioxideInterpolated  
    float sockg_methaneSd_gC_per_ha_per_d  
    double sockg_methaneSd_gC_per_ha_per_d  
    double sockg_soilMoisture_percent_volume  
    time sockg_time  
    string sockg_time  
    integer sockg_isNitrousOxideInterpolated  
    int32 sockg_isNitrousOxideInterpolated  
    double sockg_airTemperatureSd_degC  
    float sockg_soilTemperature_degC  
    double sockg_soilTemperature_degC  
    integer sockg_soilMoistureDepth_cm  
    string sockg_date  
    date sockg_date  
    integer sockg_isMethaneInterpolated  
    int32 sockg_isMethaneInterpolated  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    string sockg_measGHGFlux_UID  
    float sockg_nitrousOxideSd_gN_per_ha_per_d  
    double sockg_nitrousOxideSd_gN_per_ha_per_d  
    float sockg_methane_gC_per_ha_per_d  
    double sockg_methane_gC_per_ha_per_d  
    double sockg_soilMoistureSd_percent_volume  
    uri rdfs_seeAlso  
    float sockg_nitrousOxide_gN_per_ha_per_d  
    double sockg_nitrousOxide_gN_per_ha_per_d  
}
SockgGrazing {
    string sockg_date  
    date sockg_date  
    string sockg_growthStage  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    float sockg_aboveGroundBiomassNitrogen_kgN_per_ha  
    double sockg_aboveGroundBiomassNitrogen_kgN_per_ha  
    double sockg_atandingDeadDry_kg_per_ha  
    string sockg_measGrazingPlants_UID  
    float sockg_aboveGroundBiomassCarbon_kgC_per_ha  
    double sockg_aboveGroundBiomassCarbon_kgC_per_ha  
    double sockg_aurfaceLitterDry_kg_per_ha  
    float sockg_aboveGroundBiomassDry_kg_per_ha  
    double sockg_aboveGroundBiomassDry_kg_per_ha  
    string sockg_broadleafOrGrass  
    float sockg_biomassNitrogenPercentage  
    double sockg_biomassNitrogenPercentage  
    float sockg_leafAreaIndexDry_kg_per_ha  
    double sockg_leafAreaIndexDry_kg_per_ha  
    uri rdfs_seeAlso  
    string sockg_speciesMix  
}
SockgGrazingManagementEvent {
    string sockg_mgtGrazing_UID  
    string sockg_animalClass  
    string sockg_startDate  
    date sockg_startDate  
    string sockg_otherEvents  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    float sockg_stockingRate_number_animals_per_ha  
    double sockg_stockingRate_number_animals_per_ha  
    string sockg_endDate  
    date sockg_endDate  
    string sockg_animalSpecies  
    uri rdfs_seeAlso  
}
SockgHarvest {
    string sockg_measResidueMgnt_UID  
    string sockg_crop  
    float sockg_nonHarvestedResidueNitrogenContent_kgN_per_ha  
    double sockg_nonHarvestedResidueNitrogenContent_kgN_per_ha  
    double sockg_grainCarbonSd_kgC_per_ha  
    float sockg_grainNitrogenSd_kgN_per_ha  
    double sockg_grainNitrogenSd_kgN_per_ha  
    float sockg_nonHarvestedResidueMoisturePercent  
    double sockg_nonHarvestedResidueMoisturePercent  
    float sockg_nonHarvestedResidueMass_kg_per_ha  
    double sockg_nonHarvestedResidueMass_kg_per_ha  
    float sockg_unitGrainWeight_mg  
    double sockg_unitGrainWeight_mg  
    float sockg_driedHarvestedResidue_kg_per_ha  
    double sockg_driedHarvestedResidue_kg_per_ha  
    float sockg_grainNitrogen_kgN_per_ha  
    double sockg_grainNitrogen_kgN_per_ha  
    double sockg_grainMoisturePercentStd  
    double sockg_harvestedResidueNitrogen_kgN_per_ha  
    float sockg_aboveGroundBiomassSd_kg_per_ha  
    double sockg_aboveGroundBiomassSd_kg_per_ha  
    double sockg_harvestedResidueNitrogenSd_kgN_per_ha  
    string sockg_growthStage  
    double sockg_harvestedResidueMoisturePercent  
    float sockg_grainYield_kg_per_ha  
    double sockg_grainYield_kg_per_ha  
    string sockg_harvestedFrac  
    string sockg_date  
    date sockg_date  
    double sockg_harvestedResidueCarbon_kgC_per_ha  
    float sockg_grainYieldSd_kg_per_ha  
    double sockg_grainYieldSd_kg_per_ha  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    float sockg_nonHarvestedResidueCarbonContent_kgC_per_ha  
    double sockg_nonHarvestedResidueCarbonContent_kgC_per_ha  
    float sockg_grainCarbon_kgC_per_ha  
    double sockg_grainCarbon_kgC_per_ha  
    float sockg_aboveGroundBiomass_kg_per_ha  
    double sockg_aboveGroundBiomass_kg_per_ha  
    uri rdfs_seeAlso  
    float sockg_grainMoisturePercent  
    double sockg_grainMoisturePercent  
    double sockg_harvestedResidueCarbonSd_kgC_per_ha  
}
SockgHarvestFraction {
    string sockg_date  
    date sockg_date  
    float sockg_moisturePercent  
    double sockg_moisturePercent  
    string sockg_crop  
    string sockg_growthStage  
    string sockg_plantFraction  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    string sockg_measHarvestFraction_UID  
    float sockg_nitrogen_kgN_per_ha  
    double sockg_nitrogen_kgN_per_ha  
    float sockg_carbon_kgC_per_ha  
    double sockg_carbon_kgC_per_ha  
    uri rdfs_seeAlso  
    float sockg_dryBiomass_kg_per_ha  
    double sockg_dryBiomass_kg_per_ha  
}
SockgMiscellaneousMeasurement {

}
SockgNutrientEfficiency {
    string sockg_date  
    date sockg_date  
    string sockg_crop  
    string sockg_fieldId  
    float sockg_fracNitrogen_kg_ha  
    double sockg_fracNitrogen_kg_ha  
    string sockg_growthStage  
    string sockg_plantFraction  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    float sockg_nutrientEfficiencyRatio_kg_kg  
    double sockg_nutrientEfficiencyRatio_kg_kg  
    string sockg_measNutrEff_UID  
    float sockg_agronomicEfficiency_kg_kg  
    double sockg_agronomicEfficiency_kg_kg  
    string sockg_expUnitId  
    float sockg_nitrogenUseEfficiencyPct  
    double sockg_nitrogenUseEfficiencyPct  
    uri rdfs_seeAlso  
    string sockg_expUnit_UID  
}
SockgOrganization {
    string sockg_organizationName  
    uri rdfs_seeAlso  
}
SockgPerson {
    string sockg_phoneNumber  
    string sockg_email  
    string sockg_organizationName  
    string sockg_profession  
    string sockg_website  
    string sockg_middleName  
    string sockg_note  
    string sockg_roleInStudy  
    string sockg_isPrimaryContact  
    string sockg_suffix  
    string sockg_persons_UID  
    uri rdfs_seeAlso  
    string sockg_lastName  
    string sockg_firstName  
}
SockgPesticide {
    string sockg_pesticidePlacement  
    string sockg_pesticideTarget  
    string sockg_pesticideActiveIngredientType  
    float sockg_totalPesticideAmount_kg_per_ha  
    double sockg_totalPesticideAmount_kg_per_ha  
    string sockg_pesticide_UID  
    uri rdfs_seeAlso  
}
SockgPlantingEvent {
    double sockg_plantingRate_number_seeds_per_ha  
    string sockg_mgtPlanting_UID  
    string sockg_crop  
    string sockg_startDate  
    date sockg_startDate  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    string sockg_plantingMethod  
    float sockg_rowWidth_cm  
    double sockg_rowWidth_cm  
    string sockg_cultivar  
    uri rdfs_seeAlso  
    string sockg_expUnitId  
    double sockg_plantingDensity_kg_per_ha  
    float sockg_depth_cm  
    double sockg_depth_cm  
    int32 sockg_depth_cm  
}
SockgProject {
    uri rdfs_seeAlso  
    string sockg_projectName  
}
SockgPublication {
    string sockg_description  
    string sockg_citationType  
    string sockg_citation  
    string sockg_identifier  
    string sockg_publicationDate  
    string sockg_author  
    uri rdfs_seeAlso  
    string sockg_correspondingAuthor  
    string sockg_title  
}
SockgResearchUnit {
    uri rdfs_seeAlso  
}
SockgResidueManagementEvent {
    string sockg_date  
    date sockg_date  
    float sockg_rowsHarvestedPercent  
    integer sockg_rowsHarvestedPercent  
    string sockg_crop  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    double sockg_perennialStandAge_years  
    int32 sockg_perennialStandAge_years  
    string sockg_stageAtHarvest  
    string sockg_residueCuttingHeight  
    string sockg_equipmentType  
    uri rdfs_seeAlso  
    string sockg_mgtResidue_UID  
}
SockgRotation {
    string sockg_rotationDescriptor  
    uri rdfs_seeAlso  
}
SockgSite {
    double sockg_postalCodeNumber  
    int32 sockg_postalCodeNumber  
    string sockg_siteSpatialDescription  
    string sockg_siteId  
    uri rdfs_seeAlso  
}
SockgSoil {
    uri rdfs_seeAlso  
}
SockgSoilBiologicalSample {
    integer sockg_lowerDepth_cm  
    double sockg_lowerDepth_cm  
    int32 sockg_lowerDepth_cm  
    string sockg_date  
    date sockg_date  
    float sockg_alkPhosphatase_mg_per_kg_per_hr  
    double sockg_alkPhosphatase_mg_per_kg_per_hr  
    float sockg_glucosaminidase_mg_per_kg_per_hr  
    double sockg_glucosaminidase_mg_per_kg_per_hr  
    string sockg_measSoilBiol_UID  
    double sockg_soilfluoresceinDiacetateHydrol_mg_per_kg_per_hr  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    float sockg_particulateOrganicMatter_gC_per_kg  
    double sockg_particulateOrganicMatter_gC_per_kg  
    float sockg_nitrogenMicrobialBiomass_mgN_per_kg  
    double sockg_nitrogenMicrobialBiomass_mgN_per_kg  
    float sockg_acidPhosphatase_mg_per_kg_per_hr  
    double sockg_acidPhosphatase_mg_per_kg_per_hr  
    uri rdfs_seeAlso  
    integer sockg_upperDepth_cm  
    double sockg_upperDepth_cm  
    int32 sockg_upperDepth_cm  
    float sockg_glucosidase_mg_per_kg_per_hr  
    double sockg_glucosidase_mg_per_kg_per_hr  
    double sockg_carbonMicrobialBiomass_mgC_per_kg  
}
SockgSoilChemicalSample {
    float sockg_nitrateSd_mgN_per_kg  
    double sockg_nitrateSd_mgN_per_kg  
    string sockg_measSoilChem_UID  
    float sockg_totalSoilCarbonSd_gC_per_kg  
    double sockg_totalSoilCarbonSd_gC_per_kg  
    float sockg_totalSoilCarbon_gC_per_kg  
    double sockg_totalSoilCarbon_gC_per_kg  
    float sockg_extractableZinc_mgZn_per_kg  
    double sockg_extractableZinc_mgZn_per_kg  
    float sockg_mineralCarbon_gC_per_kg  
    double sockg_mineralCarbon_gC_per_kg  
    float sockg_phosphorus_mgP_per_kg  
    double sockg_phosphorus_mgP_per_kg  
    integer sockg_upperDepth_cm  
    double sockg_upperDepth_cm  
    int32 sockg_upperDepth_cm  
    float sockg_electricalConductivity_siemens_per_m  
    double sockg_electricalConductivity_siemens_per_m  
    float sockg_organicCarbon_gC_per_kg  
    double sockg_organicCarbon_gC_per_kg  
    float sockg_ammoniumSd_mgN_per_kg  
    double sockg_ammoniumSd_mgN_per_kg  
    float sockg_nitrate_mgN_per_kg  
    double sockg_nitrate_mgN_per_kg  
    integer sockg_lowerDepth_cm  
    double sockg_lowerDepth_cm  
    int32 sockg_lowerDepth_cm  
    float sockg_extractableIron_mgFe_per_kg  
    double sockg_extractableIron_mgFe_per_kg  
    float sockg_extractableCopper_mgCu_per_kg  
    double sockg_extractableCopper_mgCu_per_kg  
    float sockg_potassium_mgK_per_kg  
    double sockg_potassium_mgK_per_kg  
    string sockg_potassium_mgK_per_kg  
    float sockg_inorganicCarbon_gC_per_kg  
    double sockg_inorganicCarbon_gC_per_kg  
    float sockg_ph  
    double sockg_ph  
    float sockg_totalSoilNitrogenSd_gN_per_kg  
    double sockg_totalSoilNitrogenSd_gN_per_kg  
    string sockg_date  
    date sockg_date  
    float sockg_extractableCalcium_mgCa_per_kg  
    double sockg_extractableCalcium_mgCa_per_kg  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    float sockg_ammonium_mgN_per_kg  
    double sockg_ammonium_mgN_per_kg  
    float sockg_extractableManganese_mgMN_per_kg  
    double sockg_extractableManganese_mgMN_per_kg  
    uri rdfs_seeAlso  
    float sockg_cationExchangeCapacity_cmol_per_kg  
    double sockg_cationExchangeCapacity_cmol_per_kg  
    float sockg_extractableMagnesium_mgMg_per_kg  
    double sockg_extractableMagnesium_mgMg_per_kg  
    float sockg_totalSoilNitrogen_gN_per_kg  
    double sockg_totalSoilNitrogen_gN_per_kg  
}
SockgSoilCover {
    string sockg_date  
    date sockg_date  
    uri rdfs_seeAlso  
    string sockg_soilCoverTimingDescriptor  
    string sockg_measSoilCover_UID  
}
SockgSoilPhysicalSample {
    float sockg_saturatedHydraulicConductivity_cm_per_sec  
    double sockg_saturatedHydraulicConductivity_cm_per_sec  
    integer sockg_lowerDepth_cm  
    double sockg_lowerDepth_cm  
    int32 sockg_lowerDepth_cm  
    string sockg_date  
    date sockg_date  
    string sockg_measSoilPhys_UID  
    float sockg_clayPercent  
    double sockg_clayPercent  
    float sockg_sandPercent  
    double sockg_sandPercent  
    float sockg_siltPercent  
    double sockg_siltPercent  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    float sockg_bulkDensitySd_g_per_cm_cubed  
    double sockg_bulkDensitySd_g_per_cm_cubed  
    float sockg_wiltingPoint_percent_volume  
    double sockg_wiltingPoint_percent_volume  
    float sockg_saturatedHydraulicConductivitySd_cm_per_sec  
    double sockg_saturatedHydraulicConductivitySd_cm_per_sec  
    double sockg_fieldCapacitySd_percent_volume  
    float sockg_waterStableAggregatePercent  
    double sockg_waterStableAggregatePercent  
    float sockg_bulkDensity_g_per_cm_cubed  
    double sockg_bulkDensity_g_per_cm_cubed  
    integer sockg_upperDepth_cm  
    double sockg_upperDepth_cm  
    int32 sockg_upperDepth_cm  
    uri rdfs_seeAlso  
    double sockg_fieldCapacity_percent_volume  
}
SockgState {
    string sockg_stateProvince  
    uri rdfs_seeAlso  
    string sockg_stateFIPS  
}
SockgTillage {
    string sockg_mgtTillage_UID  
    string sockg_startDate  
    date sockg_startDate  
    string sockg_tillageEventMethod  
    double sockg_tillageEventDepth_cm  
    string sockg_tillageEvent  
    uri rdfs_seeAlso  
}
SockgTreatment {
    string sockg_irrigation  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    string sockg_treatmentDescriptor  
    string sockg_residueRemoval  
    string sockg_nitrogenTreatmentDescriptor  
    string sockg_fertilizerAmendmentClass  
    string sockg_coverCrop  
    string sockg_tileDrainage  
    string sockg_projectScenario  
    string sockg_tillageDescriptor  
    string sockg_organicManagement  
    uri rdfs_seeAlso  
    string sockg_grazingRate  
}
SockgVersion {
    string sockg_versionDate  
}
SockgWaterQualityArea {
    string sockg_date  
    date sockg_date  
    double sockg_ammoniumNitroge_kg_ha  
    float sockg_totalNitrogen_kg_ha  
    double sockg_totalNitrogen_kg_ha  
    float sockg_totalDissolvedPhosphorus_kgP_ha  
    double sockg_totalDissolvedPhosphorus_kgP_ha  
    string sockg_fieldId  
    string sockg_surfaceOrLeaching  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    float sockg_lossesOrDeposition  
    string sockg_lossesOrDeposition  
    float sockg_erosionTotalSolids_t_ha  
    double sockg_erosionTotalSolids_t_ha  
    float sockg_nitrateNitrogen_kg_ha  
    double sockg_nitrateNitrogen_kg_ha  
    double sockg_totalPhosphoru_kg_ha  
    string sockg_expUnitId  
    float sockg_water_mm  
    double sockg_water_mm  
    uri rdfs_seeAlso  
    string sockg_expUnit_UID  
    string sockg_measWaterQualityArea_UID  
}
SockgWaterQualityConc {
    double sockg_nitrate_mg_l  
    string sockg_crop  
    double sockg_totalPhosphorus_mg_l  
    double sockg_InorganicNitrogen_mg_l  
    double sockg_totalDissolvedPhosphorus_mgP_l  
    string sockg_surfaceOrLeaching  
    float sockg_samplingDepth_cm  
    integer sockg_samplingDepth_cm  
    string sockg_expUnit_UID  
    double sockg_totalNitrogen_mg_l  
    string sockg_samplingStartStopInterval  
    string sockg_growthStage  
    string sockg_modelIfSimulated  
    float sockg_water_mm  
    double sockg_water_mm  
    string sockg_date  
    date sockg_date  
    string sockg_measWaterQualityConc_UID  
    string sockg_fieldId  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    string sockg_expUnitId  
    uri rdfs_seeAlso  
}
SockgWeatherObservation {
    float sockg_windSpeed_m_per_s  
    double sockg_windSpeed_m_per_s  
    float sockg_precipitation_mm_per_d  
    double sockg_precipitation_mm_per_d  
    float sockg_tempMin_degC  
    double sockg_tempMin_degC  
    float sockg_soilTemp5cm_degC  
    double sockg_soilTemp5cm_degC  
    double sockg_totalSolarRadiationBareSoil_MJ_per_m_squared_per_d  
    float sockg_solarRadiationVegetatedGround_MJ_per_m_squared_per_d  
    double sockg_solarRadiationVegetatedGround_MJ_per_m_squared_per_d  
    float sockg_soilTemp10cm_degC  
    double sockg_soilTemp10cm_degC  
    float sockg_windDirectionDegFromNorth  
    double sockg_windDirectionDegFromNorth  
    float sockg_atmosphericNitrogenDeposition_kg_per_ha_per_d  
    double sockg_atmosphericNitrogenDeposition_kg_per_ha_per_d  
    string sockg_weatherDaily_UID  
    float sockg_tempMax_degC  
    double sockg_tempMax_degC  
    float sockg_solarRadiationBareSoil_MJ_per_m_squared_per_d  
    double sockg_solarRadiationBareSoil_MJ_per_m_squared_per_d  
    string sockg_date  
    date sockg_date  
    string sockg_weatherStationId  
    float sockg_relativeHumidityPercent  
    double sockg_relativeHumidityPercent  
    float sockg_openPanEvaporation_mm_per_d  
    double sockg_openPanEvaporation_mm_per_d  
    double sockg_weatherBadValueFlag  
    int32 sockg_weatherBadValueFlag  
    double sockg_dewPointDegc  
    uri rdfs_seeAlso  
}
SockgWeatherStation {
    string sockg_date  
    date sockg_date  
    string sockg_weatherStationId  
    uri rdfs_seeAlso  
}
SockgWindErosionArea {
    string sockg_date  
    date sockg_date  
    string sockg_samplingStartStopInterval  
    string sockg_fieldId  
    string sockg_growthStage  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    string sockg_measWindErosionArea_UID  
    float sockg_lossesOrDeposition  
    string sockg_lossesOrDeposition  
    string sockg_modelIfSimulated  
    float sockg_soilSd_t_ha  
    double sockg_soilSd_t_ha  
    string sockg_expUnitId  
    uri rdfs_seeAlso  
    float sockg_soil_t_ha  
    double sockg_soil_t_ha  
    string sockg_expUnit_UID  
}
SockgYieldNutrientUptake {
    float sockg_fracCarbonSd_kgC_ha  
    double sockg_fracCarbonSd_kgC_ha  
    string sockg_crop  
    string sockg_expUnitId  
    float sockg_fracNitrogenSd_kgN_ha  
    double sockg_fracNitrogenSd_kgN_ha  
    float sockg_fracProductivitySd_kg_ha  
    double sockg_fracProductivitySd_kg_ha  
    float sockg_fracManganese_gMn_ha  
    double sockg_fracManganese_gMn_ha  
    float sockg_fracIron_gFe_ha  
    double sockg_fracIron_gFe_ha  
    string sockg_plantFraction  
    float sockg_fracZincSd_gZn_ha  
    double sockg_fracZincSd_gZn_ha  
    float sockg_fracCarbon_kgC_ha  
    double sockg_fracCarbon_kgC_ha  
    string sockg_expUnit_UID  
    float sockg_fracMoisturePercent  
    double sockg_fracMoisturePercent  
    string sockg_growthStage  
    float sockg_fracCropProductivity_kg_ha  
    double sockg_fracCropProductivity_kg_ha  
    float sockg_fracZinc_gZn_ha  
    double sockg_fracZinc_gZn_ha  
    float sockg_fracIronSd_gFe_ha  
    double sockg_fracIronSd_gFe_ha  
    string sockg_date  
    date sockg_date  
    string sockg_fieldId  
    float sockg_treatmentId  
    string sockg_treatmentId  
    date sockg_treatmentId  
    string sockg_measYieldNutUptake_UID  
    float sockg_fracNitrogen_kgN_ha  
    double sockg_fracNitrogen_kgN_ha  
    float sockg_fracManganeseSd_gMn_ha  
    double sockg_fracManganeseSd_gMn_ha  
    float sockg_fracCopper_gCu_ha  
    double sockg_fracCopper_gCu_ha  
    float sockg_fracCopperSd_gCu_ha  
    double sockg_fracCopperSd_gCu_ha  
    uri rdfs_seeAlso  
}

RdfList ||--|o RdfsLiteral : "rdfs_comment"
RdfList ||--|o RdfsResource : "rdfs_isDefinedBy"
RdfList ||--|o RdfsLiteral : "rdfs_label"
KwgrS2CellLevel13 ||--|o SockgSite : "kwgr_sfContains"
KwgrS2CellLevel13 ||--|o SockgSite : "kwgr_spatialRelation"
SockgAmendment ||--|o SockgPesticide : "sockg_hasPesticide"
SockgCountry ||--|o SockgState : "sockg_hasState"
SockgCounty ||--|o SockgCity : "sockg_hasCity"
SockgDepartment ||--|o SockgOrganization : "sockg_departmentOf"
SockgExperiment ||--|o SockgTreatment : "sockg_hasTreatment"
SockgExperimentalUnit ||--|o SockgField : "sockg_locatedInField"
SockgExperimentalUnit ||--|o SockgHarvest : "sockg_isHarvested"
SockgExperimentalUnit ||--|o SockgSoilBiologicalSample : "sockg_hasBioSample"
SockgExperimentalUnit ||--|o SockgHarvestFraction : "sockg_hasHarvestFractionData"
SockgExperimentalUnit ||--|o SockgGrazingManagementEvent : "sockg_hasGrazingManagementEvent"
SockgExperimentalUnit ||--|o SockgBioMassEnergy : "sockg_hasBioMassEnergyData"
SockgExperimentalUnit ||--|o SockgSoilPhysicalSample : "sockg_hasPhysSample"
SockgExperimentalUnit ||--|o SockgGasSample : "sockg_hasGasSample"
SockgExperimentalUnit ||--|o SockgGrazing : "sockg_hasGrazingData"
SockgExperimentalUnit ||--|o SockgSite : "sockg_locatedInSite"
SockgExperimentalUnit ||--|o SockgAmendment : "sockg_hasAmendment"
SockgExperimentalUnit ||--|o SockgBioMassMineral : "sockg_hasBioMassMineralData"
SockgExperimentalUnit ||--|o SockgResidueManagementEvent : "sockg_hasResidueManagementEvent"
SockgExperimentalUnit ||--|o SockgSoilCover : "sockg_hasSoilCover"
SockgExperimentalUnit ||--|o SockgBioMassCarbohydrate : "sockg_hasBioMassCarbohydrateData"
SockgExperimentalUnit ||--|o SockgSoilChemicalSample : "sockg_hasChemSample"
SockgExperimentalUnit ||--|o SockgTillage : "sockg_hasTillage"
SockgExperimentalUnit ||--|o SockgCropGrowthStage : "sockg_tracksGrowth"
SockgOrganization ||--|o SockgExperiment : "sockg_fundsExperiment"
SockgPerson ||--|o SockgOrganization : "sockg_worksFor"
SockgPerson ||--|o SockgDepartment : "sockg_worksAtDepartment"
SockgPerson ||--|o SockgSite : "sockg_worksIn"
SockgPlantingEvent ||--|o SockgExperimentalUnit : "sockg_plantingAt"
SockgPublication ||--|o SockgSite : "sockg_studiesSite"
SockgSite ||--|o SockgField : "sockg_hasField"
SockgSite ||--|o KwgrS2CellLevel13 : "kwgr_sfWithin"
SockgSite ||--|o SockgCity : "sockg_locatedInCity"
SockgSite ||--|o GeoGeometry : "geo_hasGeometry"
SockgSite ||--|o SockgState : "sockg_locatedInState"
SockgSite ||--|o SockgCountry : "sockg_locatedInCountry"
SockgSite ||--|o SockgCounty : "sockg_locatedInCounty"
SockgSoilChemicalSample ||--|o SockgTreatment : "sockg_chemSampleHasTreatment"
SockgState ||--|o SockgCounty : "sockg_hasCounty"
SockgTreatment ||--|o SockgRotation : "sockg_hasRotation"
SockgWaterQualityArea ||--|o SockgTreatment : "sockg_waterQualityAreaTreatment"
SockgWaterQualityArea ||--|o SockgField : "sockg_waterQualityAreaDataAt"
SockgWaterQualityConc ||--|o SockgField : "sockg_waterQualityConcDataAt"
SockgWaterQualityConc ||--|o SockgTreatment : "sockg_waterQualityConcTreatment"
SockgWeatherObservation ||--|o SockgSite : "sockg_weatherRecordedAt"
SockgWeatherObservation ||--|o SockgField : "sockg_weatherAtField"
SockgWeatherStation ||--|o SockgField : "sockg_recordsWeatherForField"
SockgWeatherStation ||--|o SockgWeatherObservation : "sockg_weatherRecordedBy"
SockgWeatherStation ||--|o SockgSite : "sockg_recordsWeatherForSite"
SockgWindErosionArea ||--|o SockgField : "sockg_windErosionDataAt"
SockgWindErosionArea ||--|o SockgTreatment : "sockg_windErosionTreatment"
SockgYieldNutrientUptake ||--|o SockgField : "sockg_yieldNutrUptakeDataAt"
SockgYieldNutrientUptake ||--|o SockgTreatment : "sockg_yieldNutrUptakeTreatment"

```



## Imports


* linkml:types
* https://raw.githubusercontent.com/frink-okn/schema-gen/refs/heads/main/rdf-rdfs
* https://raw.githubusercontent.com/linkml/linkml-model/refs/heads/main/linkml_model/model/schema/extended_types



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [GeoGeometry](classes/GeoGeometry.md) | No class (type) description specified<br/>| 47 | 
| [HttpWww.opengis.netOntGeosparqlFeature](classes/HttpWww.opengis.netOntGeosparqlFeature.md) | No class (type) description specified<br/>|  | 
| [KwgrS2CellLevel13](classes/KwgrS2CellLevel13.md) | No class (type) description specified<br/>| 2404 | 
| [RdfsDatatype](classes/RdfsDatatype.md) | No class (type) description specified<br/>| 2 | 
| [SockgAmendment](classes/SockgAmendment.md) | An Amendment represents a specific alteration or addition made to agricultural practices aimed at improving soil health and crop yields. It encompasses various treatments involving nutrient management, irrigation strategies, and application timing, contributing to optimized agricultural productivity.<br/>| 37796 | 
| [SockgBioMassCarbohydrate](classes/SockgBioMassCarbohydrate.md) | BioMassCarbohydrate represents the carbohydrate content in biomass derived from various crops at different growth stages, providing essential information for evaluating feedstock quality and nutritional value. This class includes detailed measurements related to the composition of carbohydrates and fibers, critical for optimizing agricultural production and processing strategies.<br/>| 1367 | 
| [SockgBioMassEnergy](classes/SockgBioMassEnergy.md) | BioMassEnergy represents the energy content derived from agricultural biomass, taking into account various components such as plant material and mineral content at different growth stages. This class is essential for evaluating the viability and energy potential of crops used for bioenergy production in sustainable agricultural practices.<br/>| 799 | 
| [SockgBioMassMineral](classes/SockgBioMassMineral.md) | BioMassMiner is a class that represents the analysis of biomass in terms of its mineral nutrient concentrations and their relevance to crop growth stages. This information is essential for understanding the nutritional requirements of plants and optimizing agricultural practices for enhanced yield.<br/>| 6723 | 
| [SockgBook](classes/SockgBook.md) | A Book is a written or printed work that provides information, stories, or research, often serving as a valuable resource for learners and professionals in the field of agriculture. Such texts can encompass a wide range of topics, including crop management, sustainable farming practices, and agricultural innovations, fostering knowledge and understanding within the agricultural community.<br/>| 179 | 
| [SockgCity](classes/SockgCity.md) | A City is a large human settlement that serves as a hub for economic, social, and cultural activities. In the context of agriculture, cities play a crucial role in the distribution of agricultural products and can influence farming practices and food availability.<br/>| 37 | 
| [SockgCountry](classes/SockgCountry.md) | A Country is a distinct territorial body with its own government and borders, often influencing agricultural policies and practices. It serves as a fundamental unit in understanding agricultural production, trade, and the distribution of resources vital for farming.<br/>| 3 | 
| [SockgCounty](classes/SockgCounty.md) | A County represents a specific geographical area within a state, often encompassing various agricultural zones where farming and livestock are key economic activities. Understanding the divisions and characteristics of counties is essential for managing agricultural resources and planning rural development.<br/>| 33 | 
| [SockgCropGrowthStage](classes/SockgCropGrowthStage.md) | The CropGrowthStage class represents the various phases of development that a crop undergoes from planting to harvest, impacting management decisions and timing. Understanding these stages is crucial for optimizing agricultural practices and maximizing crop yield.<br/>| 4896 | 
| [SockgDepartment](classes/SockgDepartment.md) | A Department represents a specialized division within an agricultural institution, focused on specific areas of study or practice, such as Plant Sciences or Agricultural Engineering. Each department plays a crucial role in advancing agricultural research, education, and outreach in its designated field.<br/>| 49 | 
| [SockgExperiment](classes/SockgExperiment.md) | An Experiment is a structured investigation carried out to observe and analyze the effects of various agricultural practices and conditions, aimed at improving crop yields or sustainability. It often encompasses a defined timeline and may be part of a larger agricultural project, contributing valuable insights into agronomic science.<br/>| 55 | 
| [SockgExperimentalUnit](classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research focused on testing hypotheses and observing agricultural practices over defined periods. Each unit is characterized by unique identifiers and can reflect alterations in management approaches across its lifespan.<br/>| 3863 | 
| [SockgField](classes/SockgField.md) | A Field represents a specific area of land used for agricultural purposes, where crops are cultivated or animals are raised. Its geographic and elevation characteristics are essential for determining the suitability of the land for various agricultural activities.<br/>| 58 | 
| [SockgGasNutrientLoss](classes/SockgGasNutrientLoss.md) | The GasNutrientLoss class represents the assessment of gaseous nutrient losses in agricultural systems during various growth stages of crops. It encompasses information related to nitrogen losses, treatment methods, and field management practices essential for optimizing fertilizer use and improving sustainability in agriculture.<br/>| 748 | 
| [SockgGasSample](classes/SockgGasSample.md) | GasSample represents a collection of measurements related to greenhouse gas emissions from agricultural soils, including temperature and gas flux data over time. This class is essential for understanding the dynamics of carbon dioxide, methane, and nitrous oxide emissions in relation to soil and air temperatures, contributing to effective climate management practices in agriculture.<br/>| 107354 | 
| [SockgGrazing](classes/SockgGrazing.md) | The Grazing class represents the assessment of various productivity metrics and biomass characteristics of grazing plants in agricultural systems. It encompasses essential parameters that influence soil health and plant growth, contributing to sustainable land management practices.<br/>| 6995 | 
| [SockgGrazingManagementEvent](classes/SockgGrazingManagementEvent.md) | A GrazingManagementEvent represents a specific instance of land management practices aimed at optimizing the grazing of livestock on pasture. It encompasses various factors such as the timing and intensity of grazing, the types of animals involved, and the cycles of land use, ensuring sustainable agricultural practices.<br/>| 1951 | 
| [SockgHarvest](classes/SockgHarvest.md) | Harvest represents the process of collecting mature crops from the fields, with emphasis on various metrics such as grain quality, moisture levels, and biomass yield. This class encompasses critical parameters affecting crop performance and residue management, essential for sustainable agricultural practices.<br/>| 18356 | 
| [SockgHarvestFraction](classes/SockgHarvestFraction.md) | The HarvestFraction class represents the quantifiable metrics and characteristics related to the harvest of crops, including aspects of plant growth and the quality of the harvested grains. It plays a crucial role in evaluating crop yield and assessing the efficacy of different agricultural treatments.<br/>| 9470 | 
| [SockgMiscellaneousMeasurement](classes/SockgMiscellaneousMeasurement.md) | No class (type) description specified<br/>|  | 
| [SockgNutrientEfficiency](classes/SockgNutrientEfficiency.md) | The NutrientEfficiency class represents the effectiveness of nutrient utilization in crops, focusing on how efficiently plants absorb and utilize nitrogen for growth. This class is essential for evaluating different treatments and growth stages, allowing for improved agronomic practices and enhanced crop yields.<br/>| 2791 | 
| [SockgOrganization](classes/SockgOrganization.md) | An Organization is a structured group of individuals working together to achieve common goals, often within specific sectors such as agriculture, where they may focus on research, production, or advocacy. These entities can play vital roles in promoting sustainable farming practices, enhancing food security, and supporting farmers through resources and education.<br/>| 11 | 
| [SockgPerson](classes/SockgPerson.md) | A Person represents an individual involved in agricultural activities, serving various roles such as researchers, farmers, or stakeholders in agricultural studies. Each person is uniquely identified and may have contact information, professional designations, and additional details relevant to their contributions in the field of agriculture.<br/>| 98 | 
| [SockgPesticide](classes/SockgPesticide.md) | Pesticides are substances used in agriculture to manage pests and diseases that affect crops, ensuring better yield and quality. Each pesticide is characterized by its active ingredients, application methods, target organisms, and usage amounts to optimize agricultural practices and minimize environmental impact.<br/>| 356 | 
| [SockgPlantingEvent](classes/SockgPlantingEvent.md) | An event involving the act of planting, which includes considerations for spacing and depth to optimize growth. This concept encompasses various methods and plant types to ensure successful agricultural production.<br/>| 23450 | 
| [SockgProject](classes/SockgProject.md) | A project in the context of agriculture refers to a planned set of activities aimed at achieving specific goals, such as improving crop yields, implementing sustainable farming practices, or conducting research on pest resistance. Each project typically has a defined focus and scope, contributing to advancements in agricultural practices and productivity.<br/>| 9 | 
| [SockgPublication](classes/SockgPublication.md) | A Publication is a documented work that disseminates findings, research, or insights relevant to the field of agriculture, often detailing innovations, methodologies, or case studies. These works contribute to the body of knowledge that supports agricultural practices, policy development, and research advancement in the sector.<br/>| 162 | 
| [SockgResearchUnit](classes/SockgResearchUnit.md) | No class (type) description specified<br/>| 65 | 
| [SockgResidueManagementEvent](classes/SockgResidueManagementEvent.md) | A ResidueManagementEvent represents a specific instance of managing agricultural residues following a harvest, encompassing the timing and extent of harvest operations as well as the characteristics of perennial crop stands. This class captures vital information regarding the practices and equipment used to optimize residue management for sustainable farming.<br/>| 3308 | 
| [SockgRotation](classes/SockgRotation.md) | Rotation refers to the practice of systematically changing the types of crops grown in a specific area over a certain period, which helps to improve soil health, prevent pest build-up, and enhance yield. This method is essential in sustainable agriculture as it promotes biodiversity and optimizes the use of nutrients in the soil.<br/>| 74 | 
| [SockgSite](classes/SockgSite.md) | A Site represents a specific geographical location related to agricultural activities, encompassing its ecological features, historical context, and resource management practices. This class provides insights into the characteristics and significance of the land in supporting agricultural productivity and sustainability.<br/>| 60 | 
| [SockgSoil](classes/SockgSoil.md) | No class (type) description specified<br/>| 4113 | 
| [SockgSoilBiologicalSample](classes/SockgSoilBiologicalSample.md) | SoilBiologicalSample represents a collection of measurements related to microbial biomass and enzyme activity in soil, crucial for assessing soil health and fertility in agricultural practices. These samples provide insights into nutrient cycling and organic matter dynamics, helping farmers and researchers optimize soil management for improved crop productivity.<br/>| 18222 | 
| [SockgSoilChemicalSample](classes/SockgSoilChemicalSample.md) | The SoilChemicalSample class represents a comprehensive analysis of soil chemistry, capturing essential information about nutrient contents and soil properties that influence agricultural productivity. These samples play a crucial role in assessing soil health and informing management practices for optimal crop growth and sustainability.<br/>| 53833 | 
| [SockgSoilCover](classes/SockgSoilCover.md) | SoilCover refers to the layer of organic and inorganic materials that covers the soil surface, playing a critical role in agriculture by impacting soil moisture retention, erosion control, and crop health. Monitoring soil cover is essential for sustainable farming practices, as it influences both productivity and environmental quality.<br/>| 1034 | 
| [SockgSoilPhysicalSample](classes/SockgSoilPhysicalSample.md) | SoilPhysicalSample represents a comprehensive analysis of soil characteristics at specific depths, crucial for understanding its capacity to retain water, nutrients, and support plant growth. These samples are essential for optimizing agricultural practices and improving soil management strategies.<br/>| 28082 | 
| [SockgState](classes/SockgState.md) | A State represents a regional jurisdiction within a country, often defined by its own governance and regulatory frameworks. In agriculture, states play a crucial role in determining land use policies, agricultural practices, and resource management that affect local farming communities and their economic viability.<br/>| 19 | 
| [SockgTillage](classes/SockgTillage.md) | Tillage refers to the agricultural preparation of soil through mechanical agitation, including activities such as plowing, stirring, and overturning. This process is essential for seedbed preparation, incorporating organic matter, and controlling weeds in crop production.<br/>| 27137 | 
| [SockgTreatment](classes/SockgTreatment.md) | The Treatment class encompasses various agricultural practices and management techniques applied to enhance crop production and sustainability. It includes strategies for soil improvement, nutrient management, and crop rotation, aimed at optimizing farm productivity while minimizing environmental impact.<br/>| 769 | 
| [SockgVersion](classes/SockgVersion.md) | A Version represents a specific iteration or update of agricultural practices, research, or standards, reflecting changes over time in the field. It is essential for tracking advancements and ensuring that current methodologies are based on the latest information and developments in agriculture.<br/>| 1 | 
| [SockgWaterQualityArea](classes/SockgWaterQualityArea.md) | A WaterQualityArea represents a designated agricultural zone where water quality parameters are monitored to assess the impact of various treatments and environmental factors on soil and crop health. This area is crucial for understanding water conditions, nutrient levels, and potential erosion, which can inform sustainable farming practices and improve crop yields.<br/>| 667 | 
| [SockgWaterQualityConc](classes/SockgWaterQualityConc.md) | WaterQualityConc represents the concentration of various water quality parameters relevant to agricultural practices, including the effects of erosion processes and nutrient transport. It encompasses critical factors such as electrical conductivity and pH levels, which are essential for assessing water suitability for crop growth.<br/>| 1479 | 
| [SockgWeatherObservation](classes/SockgWeatherObservation.md) | The WeatherObservation class captures daily meteorological data that are crucial for understanding the impact of weather conditions on agricultural practices. It includes measurements that help in assessing soil health, crop growth, and overall farm productivity.<br/>| 147305 | 
| [SockgWeatherStation](classes/SockgWeatherStation.md) | A WeatherStation is a facility that collects and records meteorological data, providing essential information for agricultural practices and crop management. By monitoring atmospheric conditions and topographical features, it helps farmers optimize their activities based on local weather patterns.<br/>| 110795 | 
| [SockgWindErosionArea](classes/SockgWindErosionArea.md) | The WindErosionArea class represents regions affected by wind erosion, detailing various factors including the methods of erosion and the nutrient composition of the soil. It is essential for assessing soil health and implementing effective agricultural practices to combat erosion and maintain crop productivity.<br/>| 15 | 
| [SockgYieldNutrientUptake](classes/SockgYieldNutrientUptake.md) | The YieldNutrientUptake class represents the assessment of nutrient uptake by crops during different growth stages, essential for understanding the efficiency of nutrient use in agricultural practices. It facilitates the analysis of various nutrients' contributions to crop productivity and helps in optimizing fertilization strategies for enhanced yield.<br/>| 429 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [dcgeoid_cityDCID](slots/dcgeoid_cityDCID.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [geo_asWKT](slots/geo_asWKT.md) | No slot (predicate) description specified<br/>| 47 |
| [geo_hasGeometry](slots/geo_hasGeometry.md) | No slot (predicate) description specified<br/>| 47 |
| [kwgr_countyFIPS](slots/kwgr_countyFIPS.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [kwgr_sfContains](slots/kwgr_sfContains.md) | No slot (predicate) description specified<br/>| 4351 |
| [kwgr_sfWithin](slots/kwgr_sfWithin.md) | No slot (predicate) description specified<br/>| 4351 |
| [kwgr_spatialRelation](slots/kwgr_spatialRelation.md) | No slot (predicate) description specified<br/>| 4351 |
| [kwgr_stateFIPS](slots/kwgr_stateFIPS.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [rdfs_seeAlso](slots/rdfs_seeAlso.md) | No slot (predicate) description specified<br/>| 624784 |
| [sockg_aboveGroundBiomass_kg_per_ha](slots/sockg_aboveGroundBiomass_kg_per_ha.md) | No slot (predicate) description specified<br/>| 11829 |
| [sockg_aboveGroundBiomassCarbon_kgC_per_ha](slots/sockg_aboveGroundBiomassCarbon_kgC_per_ha.md) | No slot (predicate) description specified<br/>| 2149 |
| [sockg_aboveGroundBiomassCarbonSd_kgC_per_ha](slots/sockg_aboveGroundBiomassCarbonSd_kgC_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_aboveGroundBiomassDry_kg_per_ha](slots/sockg_aboveGroundBiomassDry_kg_per_ha.md) | No slot (predicate) description specified<br/>| 6995 |
| [sockg_aboveGroundBiomassDrySd_kg_per_ha](slots/sockg_aboveGroundBiomassDrySd_kg_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_aboveGroundBiomassNitrogen_kgN_per_ha](slots/sockg_aboveGroundBiomassNitrogen_kgN_per_ha.md) | No slot (predicate) description specified<br/>| 2149 |
| [sockg_aboveGroundBiomassNitrogenSd_kgN_per_ha](slots/sockg_aboveGroundBiomassNitrogenSd_kgN_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_aboveGroundBiomassSd_kg_per_ha](slots/sockg_aboveGroundBiomassSd_kg_per_ha.md) | No slot (predicate) description specified<br/>| 32 |
| [sockg_abovegroundNetPrimaryProductivityCarbon_kgC_per_ha_per_yr](slots/sockg_abovegroundNetPrimaryProductivityCarbon_kgC_per_ha_per_yr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_abovegroundNetPrimaryProductivityCarbonSd_kgC_per_ha_per_yr](slots/sockg_abovegroundNetPrimaryProductivityCarbonSd_kgC_per_ha_per_yr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_abovegroundNetPrimaryProductivityNitrogen_kgN_per_ha_per_yr](slots/sockg_abovegroundNetPrimaryProductivityNitrogen_kgN_per_ha_per_yr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_abovegroundNetPrimaryProductivityNitrogenSd_kgN_per_ha_per_yr](slots/sockg_abovegroundNetPrimaryProductivityNitrogenSd_kgN_per_ha_per_yr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_acidDetFiber_g_per_kg](slots/sockg_acidDetFiber_g_per_kg.md) | No slot (predicate) description specified<br/>| 799 |
| [sockg_acidDetFiberSd_g_per_kg](slots/sockg_acidDetFiberSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_acidInsolubleLigninSd_g_per_kg](slots/sockg_acidInsolubleLigninSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_acidPhosphatase_mg_per_kg_per_hr](slots/sockg_acidPhosphatase_mg_per_kg_per_hr.md) | No slot (predicate) description specified<br/>| 213 |
| [sockg_acidPhosphataseSd_mg_per_kg_per_hr](slots/sockg_acidPhosphataseSd_mg_per_kg_per_hr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_acidSolubleLignin_g_per_kg](slots/sockg_acidSolubleLignin_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_acidSolubleLigninSd_g_per_kg](slots/sockg_acidSolubleLigninSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_aggregationPercent](slots/sockg_aggregationPercent.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_agronomicEfficiency_kg_kg](slots/sockg_agronomicEfficiency_kg_kg.md) | No slot (predicate) description specified<br/>| 203 |
| [sockg_airTemperature_degC](slots/sockg_airTemperature_degC.md) | No slot (predicate) description specified<br/>| 107350 |
| [sockg_airTemperatureSd_degC](slots/sockg_airTemperatureSd_degC.md) | No slot (predicate) description specified<br/>| 6790 |
| [sockg_alkPhosphatase_mg_per_kg_per_hr](slots/sockg_alkPhosphatase_mg_per_kg_per_hr.md) | No slot (predicate) description specified<br/>| 465 |
| [sockg_alkPhosphataseSd_mg_per_kg_per_hr](slots/sockg_alkPhosphataseSd_mg_per_kg_per_hr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_aluminum_kg_ha](slots/sockg_aluminum_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_aluminumConcentration_mg_per_kg](slots/sockg_aluminumConcentration_mg_per_kg.md) | No slot (predicate) description specified<br/>| 6253 |
| [sockg_aluminumConcentrationSd_mg_per_kg](slots/sockg_aluminumConcentrationSd_mg_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_aluminumSd_kg_ha](slots/sockg_aluminumSd_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_amendmentDepth_cm](slots/sockg_amendmentDepth_cm.md) | No slot (predicate) description specified<br/>| 11887 |
| [sockg_amendmentPlacement](slots/sockg_amendmentPlacement.md) | No slot (predicate) description specified<br/>| 22624 |
| [sockg_ammoniaNitrogen_kg_ha](slots/sockg_ammoniaNitrogen_kg_ha.md) | No slot (predicate) description specified<br/>| 748 |
| [sockg_ammoniaNitrogenSd_kg_ha](slots/sockg_ammoniaNitrogenSd_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_ammonium_mgN_per_kg](slots/sockg_ammonium_mgN_per_kg.md) | No slot (predicate) description specified<br/>| 35301 |
| [sockg_ammoniumNitroge_kg_ha](slots/sockg_ammoniumNitroge_kg_ha.md) | No slot (predicate) description specified<br/>| 667 |
| [sockg_ammoniumNitrogen_kg_ha](slots/sockg_ammoniumNitrogen_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_ammoniumSd_mgN_per_kg](slots/sockg_ammoniumSd_mgN_per_kg.md) | No slot (predicate) description specified<br/>| 354 |
| [sockg_animalClass](slots/sockg_animalClass.md) | No slot (predicate) description specified<br/>| 1833 |
| [sockg_animalSpecies](slots/sockg_animalSpecies.md) | No slot (predicate) description specified<br/>| 1951 |
| [sockg_appliedInField](slots/sockg_appliedInField.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_appliedOnSoil](slots/sockg_appliedOnSoil.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_arabinan_g_per_kg](slots/sockg_arabinan_g_per_kg.md) | No slot (predicate) description specified<br/>| 1367 |
| [sockg_arabinanSd_g_per_kg](slots/sockg_arabinanSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_ash_g_per_kg](slots/sockg_ash_g_per_kg.md) | No slot (predicate) description specified<br/>| 799 |
| [sockg_ashSd_g_per_kg](slots/sockg_ashSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_atandingDeadDry_kg_per_ha](slots/sockg_atandingDeadDry_kg_per_ha.md) | No slot (predicate) description specified<br/>| 311 |
| [sockg_atmosphericNitrogenDeposition_kg_per_ha_per_d](slots/sockg_atmosphericNitrogenDeposition_kg_per_ha_per_d.md) | No slot (predicate) description specified<br/>| 954 |
| [sockg_aurfaceLitterDry_kg_per_ha](slots/sockg_aurfaceLitterDry_kg_per_ha.md) | No slot (predicate) description specified<br/>| 1902 |
| [sockg_author](slots/sockg_author.md) | No slot (predicate) description specified<br/>| 158 |
| [sockg_belowGroundBiomassCarbon_kgC_per_ha](slots/sockg_belowGroundBiomassCarbon_kgC_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_belowGroundBiomassCarbonSd_kgC_per_ha](slots/sockg_belowGroundBiomassCarbonSd_kgC_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_belowGroundBiomassNitrogen_kgN_per_ha](slots/sockg_belowGroundBiomassNitrogen_kgN_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_belowGroundBiomassNitrogenSd_kgN_per_ha](slots/sockg_belowGroundBiomassNitrogenSd_kgN_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_belowgroundNetPrimaryProductivityCarbon_kgC_per_ha_per_yr](slots/sockg_belowgroundNetPrimaryProductivityCarbon_kgC_per_ha_per_yr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_belowgroundNetPrimaryProductivityCarbonSd_kgC_per_ha_per_yr](slots/sockg_belowgroundNetPrimaryProductivityCarbonSd_kgC_per_ha_per_yr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_belowgroundNetPrimaryProductivityNitrogen_kgN_per_ha_per_yr](slots/sockg_belowgroundNetPrimaryProductivityNitrogen_kgN_per_ha_per_yr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_belowgroundNetPrimaryProductivityNitrogenSd_kgN_per_ha_per_yr](slots/sockg_belowgroundNetPrimaryProductivityNitrogenSd_kgN_per_ha_per_yr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_biomassNitrogenPercentage](slots/sockg_biomassNitrogenPercentage.md) | No slot (predicate) description specified<br/>| 2149 |
| [sockg_biomassNitrogenPercentageSd](slots/sockg_biomassNitrogenPercentageSd.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_bookName](slots/sockg_bookName.md) | No slot (predicate) description specified<br/>| 2 |
| [sockg_boron_g_ha](slots/sockg_boron_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_boronConcentration_mg_per_kg](slots/sockg_boronConcentration_mg_per_kg.md) | No slot (predicate) description specified<br/>| 3967 |
| [sockg_boronConcentrationSd_mg_per_kg](slots/sockg_boronConcentrationSd_mg_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_boronSd_g_ha](slots/sockg_boronSd_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_broadleafOrGrass](slots/sockg_broadleafOrGrass.md) | No slot (predicate) description specified<br/>| 6995 |
| [sockg_bulkDensity_g_per_cm_cubed](slots/sockg_bulkDensity_g_per_cm_cubed.md) | No slot (predicate) description specified<br/>| 19670 |
| [sockg_bulkDensitySd_g_per_cm_cubed](slots/sockg_bulkDensitySd_g_per_cm_cubed.md) | No slot (predicate) description specified<br/>| 50 |
| [sockg_burnIntensity](slots/sockg_burnIntensity.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_calcium_kg_ha](slots/sockg_calcium_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_calciumConcentration_g_per_kg](slots/sockg_calciumConcentration_g_per_kg.md) | No slot (predicate) description specified<br/>| 6723 |
| [sockg_calciumConcentrationSd_g_per_kg](slots/sockg_calciumConcentrationSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_calciumSd_kg_ha](slots/sockg_calciumSd_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_capacity_percent_volume](slots/sockg_capacity_percent_volume.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_capacitySd_percent_volume](slots/sockg_capacitySd_percent_volume.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_carbon_kgC_per_ha](slots/sockg_carbon_kgC_per_ha.md) | No slot (predicate) description specified<br/>| 9110 |
| [sockg_carbonConcentration_g_per_kg](slots/sockg_carbonConcentration_g_per_kg.md) | No slot (predicate) description specified<br/>| 6723 |
| [sockg_carbonConcentrationSd_g_per_kg](slots/sockg_carbonConcentrationSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_carbonDioxide_gC_per_ha_per_d](slots/sockg_carbonDioxide_gC_per_ha_per_d.md) | No slot (predicate) description specified<br/>| 107150 |
| [sockg_carbonDioxideSd_gC_per_ha_per_d](slots/sockg_carbonDioxideSd_gC_per_ha_per_d.md) | No slot (predicate) description specified<br/>| 101109 |
| [sockg_carbonMicrobialBiomass_mgC_per_kg](slots/sockg_carbonMicrobialBiomass_mgC_per_kg.md) | No slot (predicate) description specified<br/>| 18222 |
| [sockg_carbonMicrobialBiomassSd_mgC_per_kg](slots/sockg_carbonMicrobialBiomassSd_mgC_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_carbonSd_kgC_per_ha](slots/sockg_carbonSd_kgC_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_cationExchangeCapacity_cmol_per_kg](slots/sockg_cationExchangeCapacity_cmol_per_kg.md) | No slot (predicate) description specified<br/>| 3398 |
| [sockg_cationExchangeCapacitySd_cmol_per_kg](slots/sockg_cationExchangeCapacitySd_cmol_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_chamberPlacement](slots/sockg_chamberPlacement.md) | No slot (predicate) description specified<br/>| 103543 |
| [sockg_changeInManagement](slots/sockg_changeInManagement.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_chemSampleHasTreatment](slots/sockg_chemSampleHasTreatment.md) | No slot (predicate) description specified<br/>| 54015 |
| [sockg_chloride_mg_L](slots/sockg_chloride_mg_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_chlorideSd_mg_L](slots/sockg_chlorideSd_mg_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_chlorineConcentration_g_per_kg](slots/sockg_chlorineConcentration_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_chlorineConcentrationSd_g_per_kg](slots/sockg_chlorineConcentrationSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_citation](slots/sockg_citation.md) | No slot (predicate) description specified<br/>| 162 |
| [sockg_citationType](slots/sockg_citationType.md) | No slot (predicate) description specified<br/>| 153 |
| [sockg_cityName](slots/sockg_cityName.md) | No slot (predicate) description specified<br/>| 33 |
| [sockg_classification](slots/sockg_classification.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_clayPercent](slots/sockg_clayPercent.md) | No slot (predicate) description specified<br/>| 27112 |
| [sockg_closedPanEvaporation_mm_per_d](slots/sockg_closedPanEvaporation_mm_per_d.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_copper_g_ha](slots/sockg_copper_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_copperConcentration_mg_per_kg](slots/sockg_copperConcentration_mg_per_kg.md) | No slot (predicate) description specified<br/>| 6723 |
| [sockg_copperConcentrationSd_mg_per_kg](slots/sockg_copperConcentrationSd_mg_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_copperSd_g_ha](slots/sockg_copperSd_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_cornEarHeight_cm](slots/sockg_cornEarHeight_cm.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_cornEarHeightSd_cm](slots/sockg_cornEarHeightSd_cm.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_correspondingAuthor](slots/sockg_correspondingAuthor.md) | No slot (predicate) description specified<br/>| 126 |
| [sockg_countryName](slots/sockg_countryName.md) | No slot (predicate) description specified<br/>| 3 |
| [sockg_countyFIPS](slots/sockg_countyFIPS.md) | No slot (predicate) description specified<br/>| 31 |
| [sockg_countyName](slots/sockg_countyName.md) | No slot (predicate) description specified<br/>| 33 |
| [sockg_coverCrop](slots/sockg_coverCrop.md) | No slot (predicate) description specified<br/>| 194 |
| [sockg_crop](slots/sockg_crop.md) | No slot (predicate) description specified<br/>| 213189 |
| [sockg_crudeProtein_g_per_kg](slots/sockg_crudeProtein_g_per_kg.md) | No slot (predicate) description specified<br/>| 799 |
| [sockg_crudeProteinSd_g_per_kg](slots/sockg_crudeProteinSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_cultivar](slots/sockg_cultivar.md) | No slot (predicate) description specified<br/>| 20817 |
| [sockg_cuttingHeight](slots/sockg_cuttingHeight.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_date](slots/sockg_date.md) | No slot (predicate) description specified<br/>| 523520 |
| [sockg_density_kg_per_ha](slots/sockg_density_kg_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_departmentName](slots/sockg_departmentName.md) | No slot (predicate) description specified<br/>| 33 |
| [sockg_departmentOf](slots/sockg_departmentOf.md) | No slot (predicate) description specified<br/>| 11 |
| [sockg_depth_cm](slots/sockg_depth_cm.md) | No slot (predicate) description specified<br/>| 20535 |
| [sockg_description](slots/sockg_description.md) | No slot (predicate) description specified<br/>| 53 |
| [sockg_descriptor](slots/sockg_descriptor.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dewPoint](slots/sockg_dewPoint.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dewPointDegc](slots/sockg_dewPointDegc.md) | No slot (predicate) description specified<br/>| 121030 |
| [sockg_directionFromField](slots/sockg_directionFromField.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedAluminum_kgAl_ha](slots/sockg_dissolvedAluminum_kgAl_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedAluminum_mgAl_L](slots/sockg_dissolvedAluminum_mgAl_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedAluminumSd_kgAl_ha](slots/sockg_dissolvedAluminumSd_kgAl_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedAluminumSd_mgAl_L](slots/sockg_dissolvedAluminumSd_mgAl_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedBoron_gB_ha](slots/sockg_dissolvedBoron_gB_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedBoron_ugB_L](slots/sockg_dissolvedBoron_ugB_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedBoronSd_gB_ha](slots/sockg_dissolvedBoronSd_gB_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedBoronSd_ugB_L](slots/sockg_dissolvedBoronSd_ugB_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedCalcium_kgCa_ha](slots/sockg_dissolvedCalcium_kgCa_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedCalcium_mgCa_L](slots/sockg_dissolvedCalcium_mgCa_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedCalciumSd_kgCa_ha](slots/sockg_dissolvedCalciumSd_kgCa_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedCalciumSd_mgCa_L](slots/sockg_dissolvedCalciumSd_mgCa_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedCopper_gCu_ha](slots/sockg_dissolvedCopper_gCu_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedCopper_ugCu_L](slots/sockg_dissolvedCopper_ugCu_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedCopperSd_gCu_ha](slots/sockg_dissolvedCopperSd_gCu_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedCopperSd_ugCu_L](slots/sockg_dissolvedCopperSd_ugCu_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedIron_gFe_ha](slots/sockg_dissolvedIron_gFe_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedIron_ugFe_L](slots/sockg_dissolvedIron_ugFe_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedIronSd_gFe_ha](slots/sockg_dissolvedIronSd_gFe_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedIronSd_ugFe_L](slots/sockg_dissolvedIronSd_ugFe_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedMagnesium_kgMg_ha](slots/sockg_dissolvedMagnesium_kgMg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedMagnesium_mgMg_L](slots/sockg_dissolvedMagnesium_mgMg_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedMagnesiumSd_kgMg_ha](slots/sockg_dissolvedMagnesiumSd_kgMg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedMagnesiumSd_mgMg_L](slots/sockg_dissolvedMagnesiumSd_mgMg_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedManganese_gMn_ha](slots/sockg_dissolvedManganese_gMn_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedManganese_ugMn_L](slots/sockg_dissolvedManganese_ugMn_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedManganeseSd_gMn_ha](slots/sockg_dissolvedManganeseSd_gMn_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedManganeseSd_ugMn_L](slots/sockg_dissolvedManganeseSd_ugMn_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedMolybdenum_gMo_ha](slots/sockg_dissolvedMolybdenum_gMo_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedMolybdenum_ugMo_L](slots/sockg_dissolvedMolybdenum_ugMo_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedMolybdenumSd_gMo_ha](slots/sockg_dissolvedMolybdenumSd_gMo_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedMolybdenumSd_ugMo_L](slots/sockg_dissolvedMolybdenumSd_ugMo_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedPotassium_kgK_ha](slots/sockg_dissolvedPotassium_kgK_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedPotassium_mgK_L](slots/sockg_dissolvedPotassium_mgK_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedPotassiumSd_kgK_ha](slots/sockg_dissolvedPotassiumSd_kgK_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedPotassiumSd_mgK_L](slots/sockg_dissolvedPotassiumSd_mgK_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedSilicon_kgSi_ha](slots/sockg_dissolvedSilicon_kgSi_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedSilicon_mgSi_L](slots/sockg_dissolvedSilicon_mgSi_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedSiliconSd_mgSi_L](slots/sockg_dissolvedSiliconSd_mgSi_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedSodium_kgNa_ha](slots/sockg_dissolvedSodium_kgNa_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedSodium_mgNa_L](slots/sockg_dissolvedSodium_mgNa_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedSodiumSd_mgNa_L](slots/sockg_dissolvedSodiumSd_mgNa_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedSulfur_kgS_ha](slots/sockg_dissolvedSulfur_kgS_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedSulfur_mgS_L](slots/sockg_dissolvedSulfur_mgS_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedSulfurSd_kgS_ha](slots/sockg_dissolvedSulfurSd_kgS_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedSulfurSd_mgS_L](slots/sockg_dissolvedSulfurSd_mgS_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedZinc_gZn_ha](slots/sockg_dissolvedZinc_gZn_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedZinc_ugZn_L](slots/sockg_dissolvedZinc_ugZn_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedZincSd_gZn_ha](slots/sockg_dissolvedZincSd_gZn_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissolvedZincSd_ugZn_L](slots/sockg_dissolvedZincSd_ugZn_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissovledSiliconSd_kgSi_ha](slots/sockg_dissovledSiliconSd_kgSi_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dissovledSodiumSd_kgNa_ha](slots/sockg_dissovledSodiumSd_kgNa_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_distanceFromField_m](slots/sockg_distanceFromField_m.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_driedHarvestedResidue_kg_per_ha](slots/sockg_driedHarvestedResidue_kg_per_ha.md) | No slot (predicate) description specified<br/>| 1851 |
| [sockg_driedHarvestedResidueSd_kg_per_ha](slots/sockg_driedHarvestedResidueSd_kg_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_dryBiomass_kg_per_ha](slots/sockg_dryBiomass_kg_per_ha.md) | No slot (predicate) description specified<br/>| 7547 |
| [sockg_dryBiomassSd_kg_per_ha](slots/sockg_dryBiomassSd_kg_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_durationOfStudy](slots/sockg_durationOfStudy.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_electricalConductivity_ms_cm](slots/sockg_electricalConductivity_ms_cm.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_electricalConductivity_siemens_per_m](slots/sockg_electricalConductivity_siemens_per_m.md) | No slot (predicate) description specified<br/>| 5552 |
| [sockg_electricalConductivitySd_ms_cm](slots/sockg_electricalConductivitySd_ms_cm.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_electricalConductivitySd_siemens_per_m](slots/sockg_electricalConductivitySd_siemens_per_m.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_elevation_m](slots/sockg_elevation_m.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_email](slots/sockg_email.md) | No slot (predicate) description specified<br/>| 87 |
| [sockg_endDate](slots/sockg_endDate.md) | No slot (predicate) description specified<br/>| 3951 |
| [sockg_equipmentType](slots/sockg_equipmentType.md) | No slot (predicate) description specified<br/>| 3044 |
| [sockg_erosionMethod](slots/sockg_erosionMethod.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_erosionSediment_kg](slots/sockg_erosionSediment_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_erosionSediment_t_ha](slots/sockg_erosionSediment_t_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_erosionSedimentSd_kg](slots/sockg_erosionSedimentSd_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_erosionSedimentSd_t_ha](slots/sockg_erosionSedimentSd_t_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_erosionTotalSolids_kg](slots/sockg_erosionTotalSolids_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_erosionTotalSolids_t_ha](slots/sockg_erosionTotalSolids_t_ha.md) | No slot (predicate) description specified<br/>| 667 |
| [sockg_erosionTotalSolidsSd_kg](slots/sockg_erosionTotalSolidsSd_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_erosionTotalSolidsSd_t_ha](slots/sockg_erosionTotalSolidsSd_t_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_erosionTotalSuspendedSolids_kg](slots/sockg_erosionTotalSuspendedSolids_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_erosionTotalSuspendedSolids_t_ha](slots/sockg_erosionTotalSuspendedSolids_t_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_erosionTotalSuspendedSolidsSd_kg](slots/sockg_erosionTotalSuspendedSolidsSd_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_erosionTotalSuspendedSolidsSd_t_ha](slots/sockg_erosionTotalSuspendedSolidsSd_t_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_event](slots/sockg_event.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_eventDepth_cm](slots/sockg_eventDepth_cm.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_eventMethod](slots/sockg_eventMethod.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_experimentName](slots/sockg_experimentName.md) | No slot (predicate) description specified<br/>| 55 |
| [sockg_expUnit_UID](slots/sockg_expUnit_UID.md) | No slot (predicate) description specified<br/>| 9992 |
| [sockg_expUnitId](slots/sockg_expUnitId.md) | No slot (predicate) description specified<br/>| 33442 |
| [sockg_extractableCalcium_mgCa_per_kg](slots/sockg_extractableCalcium_mgCa_per_kg.md) | No slot (predicate) description specified<br/>| 3336 |
| [sockg_extractableCalciumSd_mgCa_per_kg](slots/sockg_extractableCalciumSd_mgCa_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_extractableCopper_mgCu_per_kg](slots/sockg_extractableCopper_mgCu_per_kg.md) | No slot (predicate) description specified<br/>| 1314 |
| [sockg_extractableCopperSd_mgCu_per_kg](slots/sockg_extractableCopperSd_mgCu_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_extractableIron_mgFe_per_kg](slots/sockg_extractableIron_mgFe_per_kg.md) | No slot (predicate) description specified<br/>| 1742 |
| [sockg_extractableIronSd_mgFe_per_kg](slots/sockg_extractableIronSd_mgFe_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_extractableMagnesium_mgMg_per_kg](slots/sockg_extractableMagnesium_mgMg_per_kg.md) | No slot (predicate) description specified<br/>| 3337 |
| [sockg_extractableMagnesiumSd_mgMg_per_kg](slots/sockg_extractableMagnesiumSd_mgMg_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_extractableManganese_mgMN_per_kg](slots/sockg_extractableManganese_mgMN_per_kg.md) | No slot (predicate) description specified<br/>| 2932 |
| [sockg_extractableManganeseSd_mgMN_per_kg](slots/sockg_extractableManganeseSd_mgMN_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_extractableZinc_mgZn_per_kg](slots/sockg_extractableZinc_mgZn_per_kg.md) | No slot (predicate) description specified<br/>| 2952 |
| [sockg_extractableZincSd_mgZn_per_kg](slots/sockg_extractableZincSd_mgZn_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fattyAcidMethylEsters](slots/sockg_fattyAcidMethylEsters.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fertilizerAmendmentClass](slots/sockg_fertilizerAmendmentClass.md) | No slot (predicate) description specified<br/>| 653 |
| [sockg_fieldCapacity_percent_volume](slots/sockg_fieldCapacity_percent_volume.md) | No slot (predicate) description specified<br/>| 24 |
| [sockg_fieldCapacitySd_percent_volume](slots/sockg_fieldCapacitySd_percent_volume.md) | No slot (predicate) description specified<br/>| 18 |
| [sockg_fieldId](slots/sockg_fieldId.md) | No slot (predicate) description specified<br/>| 6187 |
| [sockg_firstName](slots/sockg_firstName.md) | No slot (predicate) description specified<br/>| 98 |
| [sockg_fluoresceinDiacetateHydrol_mg_per_kg_per_hr](slots/sockg_fluoresceinDiacetateHydrol_mg_per_kg_per_hr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fluoresceinDiacetateHydrolSd_mg_per_kg_per_hr](slots/sockg_fluoresceinDiacetateHydrolSd_mg_per_kg_per_hr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracBoron_gB_ha](slots/sockg_fracBoron_gB_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracBoronSd_gB_ha](slots/sockg_fracBoronSd_gB_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracCalcium_kgCa_ha](slots/sockg_fracCalcium_kgCa_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracCalciumSd_kgCa_ha](slots/sockg_fracCalciumSd_kgCa_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracCarbon_kgC_ha](slots/sockg_fracCarbon_kgC_ha.md) | No slot (predicate) description specified<br/>| 429 |
| [sockg_fracCarbonSd_kgC_ha](slots/sockg_fracCarbonSd_kgC_ha.md) | No slot (predicate) description specified<br/>| 20 |
| [sockg_fracCopper_gCu_ha](slots/sockg_fracCopper_gCu_ha.md) | No slot (predicate) description specified<br/>| 20 |
| [sockg_fracCopperSd_gCu_ha](slots/sockg_fracCopperSd_gCu_ha.md) | No slot (predicate) description specified<br/>| 20 |
| [sockg_fracCropProductivity_kg_ha](slots/sockg_fracCropProductivity_kg_ha.md) | No slot (predicate) description specified<br/>| 429 |
| [sockg_fracIron_gFe_ha](slots/sockg_fracIron_gFe_ha.md) | No slot (predicate) description specified<br/>| 20 |
| [sockg_fracIronSd_gFe_ha](slots/sockg_fracIronSd_gFe_ha.md) | No slot (predicate) description specified<br/>| 20 |
| [sockg_fracMagnesium_kgMg_ha](slots/sockg_fracMagnesium_kgMg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracMagnesiumSd_kgMg_ha](slots/sockg_fracMagnesiumSd_kgMg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracManganese_gMn_ha](slots/sockg_fracManganese_gMn_ha.md) | No slot (predicate) description specified<br/>| 20 |
| [sockg_fracManganeseSd_gMn_ha](slots/sockg_fracManganeseSd_gMn_ha.md) | No slot (predicate) description specified<br/>| 20 |
| [sockg_fracMoisturePercent](slots/sockg_fracMoisturePercent.md) | No slot (predicate) description specified<br/>| 20 |
| [sockg_fracMoisturePercentSd](slots/sockg_fracMoisturePercentSd.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracMolybdenum_gMo_ha](slots/sockg_fracMolybdenum_gMo_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracMolybdenumSd_gMo_ha](slots/sockg_fracMolybdenumSd_gMo_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracNitrogen_kg_ha](slots/sockg_fracNitrogen_kg_ha.md) | No slot (predicate) description specified<br/>| 2791 |
| [sockg_fracNitrogen_kgN_ha](slots/sockg_fracNitrogen_kgN_ha.md) | No slot (predicate) description specified<br/>| 429 |
| [sockg_fracNitrogenSd_kgN_ha](slots/sockg_fracNitrogenSd_kgN_ha.md) | No slot (predicate) description specified<br/>| 20 |
| [sockg_fracPhosphorus_kgP_ha](slots/sockg_fracPhosphorus_kgP_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracPhosphorusSd_kgP_ha](slots/sockg_fracPhosphorusSd_kgP_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracPotassium_kgK_ha](slots/sockg_fracPotassium_kgK_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracPotassiumSd_kgK_ha](slots/sockg_fracPotassiumSd_kgK_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracProductivitySd](slots/sockg_fracProductivitySd.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracProductivitySd_kg_ha](slots/sockg_fracProductivitySd_kg_ha.md) | No slot (predicate) description specified<br/>| 20 |
| [sockg_fracSulfur_kgS_ha](slots/sockg_fracSulfur_kgS_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracSulfurSd_kgS_ha](slots/sockg_fracSulfurSd_kgS_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_fracZinc_gZn_ha](slots/sockg_fracZinc_gZn_ha.md) | No slot (predicate) description specified<br/>| 20 |
| [sockg_fracZincSd_gZn_ha](slots/sockg_fracZincSd_gZn_ha.md) | No slot (predicate) description specified<br/>| 20 |
| [sockg_fundsExperiment](slots/sockg_fundsExperiment.md) | No slot (predicate) description specified<br/>| 3 |
| [sockg_galactan_g_per_kg](slots/sockg_galactan_g_per_kg.md) | No slot (predicate) description specified<br/>| 1367 |
| [sockg_galactanSd_g_per_kg](slots/sockg_galactanSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_glomalin_g_per_kg](slots/sockg_glomalin_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_glomalinSd_g_per_kg](slots/sockg_glomalinSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_glucan_g_per_kg](slots/sockg_glucan_g_per_kg.md) | No slot (predicate) description specified<br/>| 1367 |
| [sockg_glucanSd_g_per_kg](slots/sockg_glucanSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_glucosaminidase_mg_per_kg_per_hr](slots/sockg_glucosaminidase_mg_per_kg_per_hr.md) | No slot (predicate) description specified<br/>| 601 |
| [sockg_glucosaminidaseSd_mg_per_kg_per_hr](slots/sockg_glucosaminidaseSd_mg_per_kg_per_hr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_glucosidase_mg_per_kg_per_hr](slots/sockg_glucosidase_mg_per_kg_per_hr.md) | No slot (predicate) description specified<br/>| 1516 |
| [sockg_glucosidaseSd_mg_per_kg_per_hr](slots/sockg_glucosidaseSd_mg_per_kg_per_hr.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_grainCarbon_kgC_per_ha](slots/sockg_grainCarbon_kgC_per_ha.md) | No slot (predicate) description specified<br/>| 13693 |
| [sockg_grainCarbonSd_kgC_per_ha](slots/sockg_grainCarbonSd_kgC_per_ha.md) | No slot (predicate) description specified<br/>| 72 |
| [sockg_grainMoisturePercent](slots/sockg_grainMoisturePercent.md) | No slot (predicate) description specified<br/>| 8426 |
| [sockg_grainMoisturePercentSd](slots/sockg_grainMoisturePercentSd.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_grainMoisturePercentStd](slots/sockg_grainMoisturePercentStd.md) | No slot (predicate) description specified<br/>| 30 |
| [sockg_grainNitrogen_kgN_per_ha](slots/sockg_grainNitrogen_kgN_per_ha.md) | No slot (predicate) description specified<br/>| 11255 |
| [sockg_grainNitrogenSd_kgN_per_ha](slots/sockg_grainNitrogenSd_kgN_per_ha.md) | No slot (predicate) description specified<br/>| 70 |
| [sockg_grainWeight_mg_per_kernel](slots/sockg_grainWeight_mg_per_kernel.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_grainWeightKernelYnu_mg](slots/sockg_grainWeightKernelYnu_mg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_grainWeightKernelYnuSd_mg](slots/sockg_grainWeightKernelYnuSd_mg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_grainWeightSd_mg_per_lernel](slots/sockg_grainWeightSd_mg_per_lernel.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_grainYield_kg_per_ha](slots/sockg_grainYield_kg_per_ha.md) | No slot (predicate) description specified<br/>| 15410 |
| [sockg_grainYieldSd_kg_per_ha](slots/sockg_grainYieldSd_kg_per_ha.md) | No slot (predicate) description specified<br/>| 50 |
| [sockg_grazingRate](slots/sockg_grazingRate.md) | No slot (predicate) description specified<br/>| 20 |
| [sockg_grossCalorificValue_MJ_per_kg](slots/sockg_grossCalorificValue_MJ_per_kg.md) | No slot (predicate) description specified<br/>| 795 |
| [sockg_grossCalorificValueSd_MJ_per_kg](slots/sockg_grossCalorificValueSd_MJ_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_groundCoverPercentage](slots/sockg_groundCoverPercentage.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_groundCoverPercentageSd](slots/sockg_groundCoverPercentageSd.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_growthStage](slots/sockg_growthStage.md) | No slot (predicate) description specified<br/>| 51226 |
| [sockg_happenedAtResearchUnit](slots/sockg_happenedAtResearchUnit.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_harvestedFrac](slots/sockg_harvestedFrac.md) | No slot (predicate) description specified<br/>| 18047 |
| [sockg_harvestedResidueCarbon_kgC_per_ha](slots/sockg_harvestedResidueCarbon_kgC_per_ha.md) | No slot (predicate) description specified<br/>| 962 |
| [sockg_harvestedResidueCarbonSd_kgC_per_ha](slots/sockg_harvestedResidueCarbonSd_kgC_per_ha.md) | No slot (predicate) description specified<br/>| 40 |
| [sockg_harvestedResidueMoisturePercent](slots/sockg_harvestedResidueMoisturePercent.md) | No slot (predicate) description specified<br/>| 1086 |
| [sockg_harvestedResidueNitrogen_kgN_per_ha](slots/sockg_harvestedResidueNitrogen_kgN_per_ha.md) | No slot (predicate) description specified<br/>| 602 |
| [sockg_harvestedResidueNitrogenSd_kgN_per_ha](slots/sockg_harvestedResidueNitrogenSd_kgN_per_ha.md) | No slot (predicate) description specified<br/>| 40 |
| [sockg_hasAmendment](slots/sockg_hasAmendment.md) | No slot (predicate) description specified<br/>| 37796 |
| [sockg_hasBioMassCarbohydrateData](slots/sockg_hasBioMassCarbohydrateData.md) | No slot (predicate) description specified<br/>| 1367 |
| [sockg_hasBioMassEnergyData](slots/sockg_hasBioMassEnergyData.md) | No slot (predicate) description specified<br/>| 799 |
| [sockg_hasBioMassMineralData](slots/sockg_hasBioMassMineralData.md) | No slot (predicate) description specified<br/>| 6723 |
| [sockg_hasBioSample](slots/sockg_hasBioSample.md) | No slot (predicate) description specified<br/>| 18222 |
| [sockg_hasChemSample](slots/sockg_hasChemSample.md) | No slot (predicate) description specified<br/>| 53833 |
| [sockg_hasCity](slots/sockg_hasCity.md) | No slot (predicate) description specified<br/>| 33 |
| [sockg_hasCounty](slots/sockg_hasCounty.md) | No slot (predicate) description specified<br/>| 33 |
| [sockg_hasField](slots/sockg_hasField.md) | No slot (predicate) description specified<br/>| 65 |
| [sockg_hasGasNutrientData](slots/sockg_hasGasNutrientData.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_hasGasSample](slots/sockg_hasGasSample.md) | No slot (predicate) description specified<br/>| 106447 |
| [sockg_hasGrazingData](slots/sockg_hasGrazingData.md) | No slot (predicate) description specified<br/>| 6995 |
| [sockg_hasGrazingManagementEvent](slots/sockg_hasGrazingManagementEvent.md) | No slot (predicate) description specified<br/>| 1951 |
| [sockg_hasHarvestFractionData](slots/sockg_hasHarvestFractionData.md) | No slot (predicate) description specified<br/>| 9110 |
| [sockg_hasMiscellaneousMeasurement](slots/sockg_hasMiscellaneousMeasurement.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_hasPesticide](slots/sockg_hasPesticide.md) | No slot (predicate) description specified<br/>| 42545 |
| [sockg_hasPhysSample](slots/sockg_hasPhysSample.md) | No slot (predicate) description specified<br/>| 28082 |
| [sockg_hasResidueManagementEvent](slots/sockg_hasResidueManagementEvent.md) | No slot (predicate) description specified<br/>| 3308 |
| [sockg_hasRotation](slots/sockg_hasRotation.md) | No slot (predicate) description specified<br/>| 761 |
| [sockg_hasSoilCover](slots/sockg_hasSoilCover.md) | No slot (predicate) description specified<br/>| 1034 |
| [sockg_hasState](slots/sockg_hasState.md) | No slot (predicate) description specified<br/>| 19 |
| [sockg_hasTillage](slots/sockg_hasTillage.md) | No slot (predicate) description specified<br/>| 27137 |
| [sockg_hasTreatment](slots/sockg_hasTreatment.md) | No slot (predicate) description specified<br/>| 741 |
| [sockg_hasWaterQualityAreaData](slots/sockg_hasWaterQualityAreaData.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_hasWaterQualityConcData](slots/sockg_hasWaterQualityConcData.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_hasWindErosionData](slots/sockg_hasWindErosionData.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_hasYieldNutrUptakeData](slots/sockg_hasYieldNutrUptakeData.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_heatFlux_MJ_per_m_squared](slots/sockg_heatFlux_MJ_per_m_squared.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_heatFluxSd_MJ_per_m_squared](slots/sockg_heatFluxSd_MJ_per_m_squared.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_identifier](slots/sockg_identifier.md) | No slot (predicate) description specified<br/>| 114 |
| [sockg_inorganicCarbon_gC_per_kg](slots/sockg_inorganicCarbon_gC_per_kg.md) | No slot (predicate) description specified<br/>| 5391 |
| [sockg_inorganicCarbonSd_gC_per_kg](slots/sockg_inorganicCarbonSd_gC_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_inorganicNitrogen_kgN_ha](slots/sockg_inorganicNitrogen_kgN_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_InorganicNitrogen_mg_L](slots/sockg_InorganicNitrogen_mg_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_InorganicNitrogen_mg_l](slots/sockg_InorganicNitrogen_mg_l.md) | No slot (predicate) description specified<br/>| 667 |
| [sockg_inorganicNitrogenSd_kgN_ha](slots/sockg_inorganicNitrogenSd_kgN_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_InorganicNitrogenSd_mg_L](slots/sockg_InorganicNitrogenSd_mg_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_iron_g_ha](slots/sockg_iron_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_ironConcentration_mg_per_kg](slots/sockg_ironConcentration_mg_per_kg.md) | No slot (predicate) description specified<br/>| 6723 |
| [sockg_ironConcentrationSd_mg_per_kg](slots/sockg_ironConcentrationSd_mg_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_ironSd_g_ha](slots/sockg_ironSd_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_irrigation](slots/sockg_irrigation.md) | No slot (predicate) description specified<br/>| 769 |
| [sockg_irrigationAmount_cm](slots/sockg_irrigationAmount_cm.md) | No slot (predicate) description specified<br/>| 4382 |
| [sockg_irrigationNitrogen_mg_per_L](slots/sockg_irrigationNitrogen_mg_per_L.md) | No slot (predicate) description specified<br/>| 160 |
| [sockg_irrigationType](slots/sockg_irrigationType.md) | No slot (predicate) description specified<br/>| 4220 |
| [sockg_isAuthorOfPublication](slots/sockg_isAuthorOfPublication.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_isCarbonDioxideInterpolated](slots/sockg_isCarbonDioxideInterpolated.md) | No slot (predicate) description specified<br/>| 107354 |
| [sockg_isChapterOf](slots/sockg_isChapterOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_isCorrespondingAuthor](slots/sockg_isCorrespondingAuthor.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_isHarvested](slots/sockg_isHarvested.md) | No slot (predicate) description specified<br/>| 18356 |
| [sockg_isMethaneInterpolated](slots/sockg_isMethaneInterpolated.md) | No slot (predicate) description specified<br/>| 107354 |
| [sockg_isNitrousOxideInterpolated](slots/sockg_isNitrousOxideInterpolated.md) | No slot (predicate) description specified<br/>| 107354 |
| [sockg_isPrimaryContact](slots/sockg_isPrimaryContact.md) | No slot (predicate) description specified<br/>| 84 |
| [sockg_landscapePosition](slots/sockg_landscapePosition.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_lastName](slots/sockg_lastName.md) | No slot (predicate) description specified<br/>| 98 |
| [sockg_latitude](slots/sockg_latitude.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_latitude_decimal_deg](slots/sockg_latitude_decimal_deg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_leafAreaIndexDry_kg_per_ha](slots/sockg_leafAreaIndexDry_kg_per_ha.md) | No slot (predicate) description specified<br/>| 312 |
| [sockg_leafAreaIndexDrySd_kg_per_ha](slots/sockg_leafAreaIndexDrySd_kg_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_lignin_g_per_kg](slots/sockg_lignin_g_per_kg.md) | No slot (predicate) description specified<br/>| 799 |
| [sockg_ligninPercentage](slots/sockg_ligninPercentage.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_ligninPercentageSd](slots/sockg_ligninPercentageSd.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_ligninSd_g_per_kg](slots/sockg_ligninSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_locatedInCity](slots/sockg_locatedInCity.md) | No slot (predicate) description specified<br/>| 59 |
| [sockg_locatedInCountry](slots/sockg_locatedInCountry.md) | No slot (predicate) description specified<br/>| 60 |
| [sockg_locatedInCounty](slots/sockg_locatedInCounty.md) | No slot (predicate) description specified<br/>| 61 |
| [sockg_locatedInField](slots/sockg_locatedInField.md) | No slot (predicate) description specified<br/>| 3809 |
| [sockg_locatedInSite](slots/sockg_locatedInSite.md) | No slot (predicate) description specified<br/>| 3803 |
| [sockg_locatedInState](slots/sockg_locatedInState.md) | No slot (predicate) description specified<br/>| 60 |
| [sockg_longitude](slots/sockg_longitude.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_longitude_decimal_deg](slots/sockg_longitude_decimal_deg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_lossesOrDeposition](slots/sockg_lossesOrDeposition.md) | No slot (predicate) description specified<br/>| 139 |
| [sockg_lowerDepth_cm](slots/sockg_lowerDepth_cm.md) | No slot (predicate) description specified<br/>| 100137 |
| [sockg_macroAggregatesPercentSd](slots/sockg_macroAggregatesPercentSd.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_magnesiumConcentration_g_per_kg](slots/sockg_magnesiumConcentration_g_per_kg.md) | No slot (predicate) description specified<br/>| 6723 |
| [sockg_magnesiumConcentrationSd_g_per_kg](slots/sockg_magnesiumConcentrationSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_magnesiumSd_kg_ha](slots/sockg_magnesiumSd_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_majorLandResourceArea](slots/sockg_majorLandResourceArea.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_manganese_g_ha](slots/sockg_manganese_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_manganeseConcentration_mg_per_kg](slots/sockg_manganeseConcentration_mg_per_kg.md) | No slot (predicate) description specified<br/>| 6723 |
| [sockg_manganeseConcentrationSd_mg_per_kg](slots/sockg_manganeseConcentrationSd_mg_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_manganeseSd_g_ha](slots/sockg_manganeseSd_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_mannan_g_per_kg](slots/sockg_mannan_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_mannanSd_g_per_kg](slots/sockg_mannanSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_measBiomassCHO_UID](slots/sockg_measBiomassCHO_UID.md) | No slot (predicate) description specified<br/>| 1367 |
| [sockg_measBiomassEnergy_UID](slots/sockg_measBiomassEnergy_UID.md) | No slot (predicate) description specified<br/>| 799 |
| [sockg_measBiomassMinAn_UID](slots/sockg_measBiomassMinAn_UID.md) | No slot (predicate) description specified<br/>| 6723 |
| [sockg_measGasNutrientLoss_UID](slots/sockg_measGasNutrientLoss_UID.md) | No slot (predicate) description specified<br/>| 748 |
| [sockg_measGHGFlux_UID](slots/sockg_measGHGFlux_UID.md) | No slot (predicate) description specified<br/>| 107354 |
| [sockg_measGrazingPlants_UID](slots/sockg_measGrazingPlants_UID.md) | No slot (predicate) description specified<br/>| 6995 |
| [sockg_measHarvestFraction_UID](slots/sockg_measHarvestFraction_UID.md) | No slot (predicate) description specified<br/>| 9470 |
| [sockg_measNutrEff_UID](slots/sockg_measNutrEff_UID.md) | No slot (predicate) description specified<br/>| 2791 |
| [sockg_measResidueMgnt_UID](slots/sockg_measResidueMgnt_UID.md) | No slot (predicate) description specified<br/>| 18356 |
| [sockg_measSoilBiol_UID](slots/sockg_measSoilBiol_UID.md) | No slot (predicate) description specified<br/>| 18222 |
| [sockg_measSoilChem_UID](slots/sockg_measSoilChem_UID.md) | No slot (predicate) description specified<br/>| 53833 |
| [sockg_measSoilCover_UID](slots/sockg_measSoilCover_UID.md) | No slot (predicate) description specified<br/>| 1034 |
| [sockg_measSoilPhys_UID](slots/sockg_measSoilPhys_UID.md) | No slot (predicate) description specified<br/>| 28082 |
| [sockg_measWaterQualityArea_UID](slots/sockg_measWaterQualityArea_UID.md) | No slot (predicate) description specified<br/>| 667 |
| [sockg_measWaterQualityConc_UID](slots/sockg_measWaterQualityConc_UID.md) | No slot (predicate) description specified<br/>| 1479 |
| [sockg_measWindErosionArea_UID](slots/sockg_measWindErosionArea_UID.md) | No slot (predicate) description specified<br/>| 15 |
| [sockg_measYieldNutUptake_UID](slots/sockg_measYieldNutUptake_UID.md) | No slot (predicate) description specified<br/>| 429 |
| [sockg_methane_gC_per_ha_per_d](slots/sockg_methane_gC_per_ha_per_d.md) | No slot (predicate) description specified<br/>| 107090 |
| [sockg_methaneSd_gC_per_ha_per_d](slots/sockg_methaneSd_gC_per_ha_per_d.md) | No slot (predicate) description specified<br/>| 101109 |
| [sockg_mgtAmendments_UID](slots/sockg_mgtAmendments_UID.md) | No slot (predicate) description specified<br/>| 37796 |
| [sockg_mgtGrazing_UID](slots/sockg_mgtGrazing_UID.md) | No slot (predicate) description specified<br/>| 1951 |
| [sockg_mgtGrowthStages_UID](slots/sockg_mgtGrowthStages_UID.md) | No slot (predicate) description specified<br/>| 4896 |
| [sockg_mgtPlanting_UID](slots/sockg_mgtPlanting_UID.md) | No slot (predicate) description specified<br/>| 23450 |
| [sockg_mgtResidue_UID](slots/sockg_mgtResidue_UID.md) | No slot (predicate) description specified<br/>| 3308 |
| [sockg_mgtTillage_UID](slots/sockg_mgtTillage_UID.md) | No slot (predicate) description specified<br/>| 27137 |
| [sockg_middleName](slots/sockg_middleName.md) | No slot (predicate) description specified<br/>| 65 |
| [sockg_mineralCarbon_gC_per_kg](slots/sockg_mineralCarbon_gC_per_kg.md) | No slot (predicate) description specified<br/>| 3343 |
| [sockg_mineralCarbonSd_gC_per_kg](slots/sockg_mineralCarbonSd_gC_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_mineralizableNitrogen_gN_per_kg](slots/sockg_mineralizableNitrogen_gN_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_mineralizableNitrogenSd_gN_per_kg](slots/sockg_mineralizableNitrogenSd_gN_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_mineralMatter_g_per_kg](slots/sockg_mineralMatter_g_per_kg.md) | No slot (predicate) description specified<br/>| 799 |
| [sockg_mineralMatterSd_g_per_kg](slots/sockg_mineralMatterSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_miscellaneousMeasurementUniqueId](slots/sockg_miscellaneousMeasurementUniqueId.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_modelIfSimulated](slots/sockg_modelIfSimulated.md) | No slot (predicate) description specified<br/>| 861 |
| [sockg_moisture_percent_volume](slots/sockg_moisture_percent_volume.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_moistureDepth_cm](slots/sockg_moistureDepth_cm.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_moisturePercent](slots/sockg_moisturePercent.md) | No slot (predicate) description specified<br/>| 846 |
| [sockg_moisturePercentSd](slots/sockg_moisturePercentSd.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_moistureReleaseCurve](slots/sockg_moistureReleaseCurve.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_moistureSd_percent_volume](slots/sockg_moistureSd_percent_volume.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_molybdenum_g_ha](slots/sockg_molybdenum_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_molybdenumSd_g_ha](slots/sockg_molybdenumSd_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nearInfraredCarbon_gC_per_kg](slots/sockg_nearInfraredCarbon_gC_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nearInfraredCarbonSd_gC_per_kg](slots/sockg_nearInfraredCarbonSd_gC_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_neutralDetFiber_g_per_kg](slots/sockg_neutralDetFiber_g_per_kg.md) | No slot (predicate) description specified<br/>| 799 |
| [sockg_neutralDetFiberSd_g_per_kg](slots/sockg_neutralDetFiberSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrate_kg_ha](slots/sockg_nitrate_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrate_mg_L](slots/sockg_nitrate_mg_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrate_mg_l](slots/sockg_nitrate_mg_l.md) | No slot (predicate) description specified<br/>| 1479 |
| [sockg_nitrate_mgN_per_kg](slots/sockg_nitrate_mgN_per_kg.md) | No slot (predicate) description specified<br/>| 37066 |
| [sockg_nitrateNitrogen_kg_ha](slots/sockg_nitrateNitrogen_kg_ha.md) | No slot (predicate) description specified<br/>| 667 |
| [sockg_nitrateSd_kgN_ha](slots/sockg_nitrateSd_kgN_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrateSd_mg_L](slots/sockg_nitrateSd_mg_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrateSd_mgN_per_kg](slots/sockg_nitrateSd_mgN_per_kg.md) | No slot (predicate) description specified<br/>| 354 |
| [sockg_nitrites_mgN_per_kg](slots/sockg_nitrites_mgN_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitritesSd_mgN_per_kg](slots/sockg_nitritesSd_mgN_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrogen_kgN_per_ha](slots/sockg_nitrogen_kgN_per_ha.md) | No slot (predicate) description specified<br/>| 9110 |
| [sockg_nitrogenConcentration_g_per_kg](slots/sockg_nitrogenConcentration_g_per_kg.md) | No slot (predicate) description specified<br/>| 6723 |
| [sockg_nitrogenConcentrationSd_g_per_kg](slots/sockg_nitrogenConcentrationSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrogenGas_g_ha](slots/sockg_nitrogenGas_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrogenGasSd_g_ha](slots/sockg_nitrogenGasSd_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrogenMicrobialBiomass_mgN_per_kg](slots/sockg_nitrogenMicrobialBiomass_mgN_per_kg.md) | No slot (predicate) description specified<br/>| 2080 |
| [sockg_nitrogenMicrobialBiomassSd_mgN_per_kg](slots/sockg_nitrogenMicrobialBiomassSd_mgN_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrogenSd_kgN_per_ha](slots/sockg_nitrogenSd_kgN_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrogenTreatmentDescriptor](slots/sockg_nitrogenTreatmentDescriptor.md) | No slot (predicate) description specified<br/>| 750 |
| [sockg_nitrogenUseEfficiency_kg_ha](slots/sockg_nitrogenUseEfficiency_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrogenUseEfficiencyPct](slots/sockg_nitrogenUseEfficiencyPct.md) | No slot (predicate) description specified<br/>| 2791 |
| [sockg_nitrousOxide_g_ha](slots/sockg_nitrousOxide_g_ha.md) | No slot (predicate) description specified<br/>| 748 |
| [sockg_nitrousOxide_gN_per_ha_per_d](slots/sockg_nitrousOxide_gN_per_ha_per_d.md) | No slot (predicate) description specified<br/>| 107095 |
| [sockg_nitrousOxides_g_ha](slots/sockg_nitrousOxides_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrousOxideSd_g_ha](slots/sockg_nitrousOxideSd_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nitrousOxideSd_gN_per_ha_per_d](slots/sockg_nitrousOxideSd_gN_per_ha_per_d.md) | No slot (predicate) description specified<br/>| 101109 |
| [sockg_nitrousOxidesSd_g_ha](slots/sockg_nitrousOxidesSd_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nonFiberCarbs_g_per_kg](slots/sockg_nonFiberCarbs_g_per_kg.md) | No slot (predicate) description specified<br/>| 751 |
| [sockg_nonFiberCarbsSd_g_per_kg](slots/sockg_nonFiberCarbsSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nonHarvestedResidueCarbonContent_kgC_per_ha](slots/sockg_nonHarvestedResidueCarbonContent_kgC_per_ha.md) | No slot (predicate) description specified<br/>| 9217 |
| [sockg_nonHarvestedResidueCarbonContentSd_kgC_per_ha](slots/sockg_nonHarvestedResidueCarbonContentSd_kgC_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nonHarvestedResidueMass_kg_per_ha](slots/sockg_nonHarvestedResidueMass_kg_per_ha.md) | No slot (predicate) description specified<br/>| 10748 |
| [sockg_nonHarvestedResidueMassSd_kg_per_ha](slots/sockg_nonHarvestedResidueMassSd_kg_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nonHarvestedResidueMoisturePercent](slots/sockg_nonHarvestedResidueMoisturePercent.md) | No slot (predicate) description specified<br/>| 1372 |
| [sockg_nonHarvestedResidueMoisturePercentSd](slots/sockg_nonHarvestedResidueMoisturePercentSd.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_nonHarvestedResidueNitrogenContent_kgN_per_ha](slots/sockg_nonHarvestedResidueNitrogenContent_kgN_per_ha.md) | No slot (predicate) description specified<br/>| 10384 |
| [sockg_nonHarvestedResidueNitrogenContentSd_kgN_per_ha](slots/sockg_nonHarvestedResidueNitrogenContentSd_kgN_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_note](slots/sockg_note.md) | No slot (predicate) description specified<br/>| 11 |
| [sockg_nutrientEfficiencyRatio_kg_kg](slots/sockg_nutrientEfficiencyRatio_kg_kg.md) | No slot (predicate) description specified<br/>| 2569 |
| [sockg_openPanEvaporation_mm_per_d](slots/sockg_openPanEvaporation_mm_per_d.md) | No slot (predicate) description specified<br/>| 131522 |
| [sockg_organicCarbon_gC_per_kg](slots/sockg_organicCarbon_gC_per_kg.md) | No slot (predicate) description specified<br/>| 8192 |
| [sockg_organicCarbon_kg_ha](slots/sockg_organicCarbon_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_organicCarbonSd_gC_per_kg](slots/sockg_organicCarbonSd_gC_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_organicManagement](slots/sockg_organicManagement.md) | No slot (predicate) description specified<br/>| 769 |
| [sockg_organicMatter_kg_ha](slots/sockg_organicMatter_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_organicMatterSd_kg_ha](slots/sockg_organicMatterSd_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_organicPlantMaterial_gC_per_kg](slots/sockg_organicPlantMaterial_gC_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_organicPlantMaterialSd_gC_per_kg](slots/sockg_organicPlantMaterialSd_gC_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_organizationName](slots/sockg_organizationName.md) | No slot (predicate) description specified<br/>| 95 |
| [sockg_otherEvents](slots/sockg_otherEvents.md) | No slot (predicate) description specified<br/>| 4 |
| [sockg_particulateOrganicMatter_gC_per_kg](slots/sockg_particulateOrganicMatter_gC_per_kg.md) | No slot (predicate) description specified<br/>| 18222 |
| [sockg_particulateOrganicMatterSd_gC_per_kg](slots/sockg_particulateOrganicMatterSd_gC_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_perennialStandAge_years](slots/sockg_perennialStandAge_years.md) | No slot (predicate) description specified<br/>| 826 |
| [sockg_persons_UID](slots/sockg_persons_UID.md) | No slot (predicate) description specified<br/>| 98 |
| [sockg_pesticide_UID](slots/sockg_pesticide_UID.md) | No slot (predicate) description specified<br/>| 356 |
| [sockg_pesticideActiveIngredientType](slots/sockg_pesticideActiveIngredientType.md) | No slot (predicate) description specified<br/>| 353 |
| [sockg_pesticidePlacement](slots/sockg_pesticidePlacement.md) | No slot (predicate) description specified<br/>| 230 |
| [sockg_pesticideTarget](slots/sockg_pesticideTarget.md) | No slot (predicate) description specified<br/>| 247 |
| [sockg_ph](slots/sockg_ph.md) | No slot (predicate) description specified<br/>| 18189 |
| [sockg_phoneNumber](slots/sockg_phoneNumber.md) | No slot (predicate) description specified<br/>| 84 |
| [sockg_phospholipidFattyAcids](slots/sockg_phospholipidFattyAcids.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_phosphorus_kg_ha](slots/sockg_phosphorus_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_phosphorus_mgP_per_kg](slots/sockg_phosphorus_mgP_per_kg.md) | No slot (predicate) description specified<br/>| 13439 |
| [sockg_phosphorusConcentration_g_per_kg](slots/sockg_phosphorusConcentration_g_per_kg.md) | No slot (predicate) description specified<br/>| 6723 |
| [sockg_phosphorusConcentrationSd_g_per_kg](slots/sockg_phosphorusConcentrationSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_phosphorusSd_kg_ha](slots/sockg_phosphorusSd_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_phosphorusSd_mgP_per_kg](slots/sockg_phosphorusSd_mgP_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_phSd](slots/sockg_phSd.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_plantFraction](slots/sockg_plantFraction.md) | No slot (predicate) description specified<br/>| 21471 |
| [sockg_plantingAt](slots/sockg_plantingAt.md) | No slot (predicate) description specified<br/>| 23450 |
| [sockg_plantingDensity_kg_per_ha](slots/sockg_plantingDensity_kg_per_ha.md) | No slot (predicate) description specified<br/>| 22514 |
| [sockg_plantingMethod](slots/sockg_plantingMethod.md) | No slot (predicate) description specified<br/>| 22314 |
| [sockg_plantingRate_number_seeds_per_ha](slots/sockg_plantingRate_number_seeds_per_ha.md) | No slot (predicate) description specified<br/>| 17377 |
| [sockg_postalCodeNumber](slots/sockg_postalCodeNumber.md) | No slot (predicate) description specified<br/>| 60 |
| [sockg_potassium_kg_ha](slots/sockg_potassium_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_potassium_mgK_per_kg](slots/sockg_potassium_mgK_per_kg.md) | No slot (predicate) description specified<br/>| 10949 |
| [sockg_potassiumConcentration_g_per_kg](slots/sockg_potassiumConcentration_g_per_kg.md) | No slot (predicate) description specified<br/>| 6723 |
| [sockg_potassiumConcentrationSd_g_per_kg](slots/sockg_potassiumConcentrationSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_potassiumSd_kg_ha](slots/sockg_potassiumSd_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_potassiumSd_mgK_per_kg](slots/sockg_potassiumSd_mgK_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_precipitation_mm_per_d](slots/sockg_precipitation_mm_per_d.md) | No slot (predicate) description specified<br/>| 147232 |
| [sockg_profession](slots/sockg_profession.md) | No slot (predicate) description specified<br/>| 93 |
| [sockg_projectName](slots/sockg_projectName.md) | No slot (predicate) description specified<br/>| 64 |
| [sockg_projectScenario](slots/sockg_projectScenario.md) | No slot (predicate) description specified<br/>| 769 |
| [sockg_publicationDate](slots/sockg_publicationDate.md) | No slot (predicate) description specified<br/>| 162 |
| [sockg_publicationDescription](slots/sockg_publicationDescription.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_rate_number_seeds_per_ha](slots/sockg_rate_number_seeds_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_recordsWeatherForField](slots/sockg_recordsWeatherForField.md) | No slot (predicate) description specified<br/>| 14 |
| [sockg_recordsWeatherForSite](slots/sockg_recordsWeatherForSite.md) | No slot (predicate) description specified<br/>| 14 |
| [sockg_relativeHumidityPercent](slots/sockg_relativeHumidityPercent.md) | No slot (predicate) description specified<br/>| 138705 |
| [sockg_researchUnitDescription](slots/sockg_researchUnitDescription.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_residueCuttingHeight](slots/sockg_residueCuttingHeight.md) | No slot (predicate) description specified<br/>| 2952 |
| [sockg_residueMoisturePercent](slots/sockg_residueMoisturePercent.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_residueMoisturePercentSd](slots/sockg_residueMoisturePercentSd.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_residueNitrogen_kgN_per_ha](slots/sockg_residueNitrogen_kgN_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_residueNitrogenSd_kgN_per_ha](slots/sockg_residueNitrogenSd_kgN_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_residueRemoval](slots/sockg_residueRemoval.md) | No slot (predicate) description specified<br/>| 769 |
| [sockg_roleInStudy](slots/sockg_roleInStudy.md) | No slot (predicate) description specified<br/>| 93 |
| [sockg_rootCarbonContent_kgC_per_ha](slots/sockg_rootCarbonContent_kgC_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_rootCarbonContentSd_kgC_per_ha](slots/sockg_rootCarbonContentSd_kgC_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_rootDryMatter_kg_per_ha](slots/sockg_rootDryMatter_kg_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_rootDryMatterSd_kg_per_ha](slots/sockg_rootDryMatterSd_kg_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_rootMoisturePercent](slots/sockg_rootMoisturePercent.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_rootMoisturePercentSd](slots/sockg_rootMoisturePercentSd.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_rootNitrogenContent_kgN_per_ha](slots/sockg_rootNitrogenContent_kgN_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_rootNitrogenContentSd_kgN_per_ha](slots/sockg_rootNitrogenContentSd_kgN_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_rotationDescriptor](slots/sockg_rotationDescriptor.md) | No slot (predicate) description specified<br/>| 66 |
| [sockg_rowsHarvestedPercent](slots/sockg_rowsHarvestedPercent.md) | No slot (predicate) description specified<br/>| 3308 |
| [sockg_rowWidth_cm](slots/sockg_rowWidth_cm.md) | No slot (predicate) description specified<br/>| 23450 |
| [sockg_sampleDepth_cm](slots/sockg_sampleDepth_cm.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_samplingDate](slots/sockg_samplingDate.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_samplingDepth_cm](slots/sockg_samplingDepth_cm.md) | No slot (predicate) description specified<br/>| 1479 |
| [sockg_samplingDepthCm](slots/sockg_samplingDepthCm.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_samplingStartStopInterval](slots/sockg_samplingStartStopInterval.md) | No slot (predicate) description specified<br/>| 891 |
| [sockg_sandPercent](slots/sockg_sandPercent.md) | No slot (predicate) description specified<br/>| 27110 |
| [sockg_saturatedHydraulicConductivity_cm_per_sec](slots/sockg_saturatedHydraulicConductivity_cm_per_sec.md) | No slot (predicate) description specified<br/>| 33 |
| [sockg_saturatedHydraulicConductivitySd_cm_per_sec](slots/sockg_saturatedHydraulicConductivitySd_cm_per_sec.md) | No slot (predicate) description specified<br/>| 27 |
| [sockg_silicon_kg_ha](slots/sockg_silicon_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_siliconSd_kg_ha](slots/sockg_siliconSd_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_siltPercent](slots/sockg_siltPercent.md) | No slot (predicate) description specified<br/>| 27112 |
| [sockg_siteHistory](slots/sockg_siteHistory.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_siteId](slots/sockg_siteId.md) | No slot (predicate) description specified<br/>| 60 |
| [sockg_siteIdDescriptor](slots/sockg_siteIdDescriptor.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_siteMeanAnnualPrecipitation_mm](slots/sockg_siteMeanAnnualPrecipitation_mm.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_siteMeanAnnualTemperature_degC](slots/sockg_siteMeanAnnualTemperature_degC.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_siteNativeVegetation](slots/sockg_siteNativeVegetation.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_siteSpatialDescription](slots/sockg_siteSpatialDescription.md) | No slot (predicate) description specified<br/>| 60 |
| [sockg_size_m_squared](slots/sockg_size_m_squared.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_slopePercent](slots/sockg_slopePercent.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_snow_mm_per_d](slots/sockg_snow_mm_per_d.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_sodium_kg_ha](slots/sockg_sodium_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_sodiumConcentration_g_per_kg](slots/sockg_sodiumConcentration_g_per_kg.md) | No slot (predicate) description specified<br/>| 6415 |
| [sockg_sodiumConcentrationSd_g_per_kg](slots/sockg_sodiumConcentrationSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_sodiumSd_kg_ha](slots/sockg_sodiumSd_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_soil_t_ha](slots/sockg_soil_t_ha.md) | No slot (predicate) description specified<br/>| 15 |
| [sockg_soilCoverTimingDescriptor](slots/sockg_soilCoverTimingDescriptor.md) | No slot (predicate) description specified<br/>| 1034 |
| [sockg_soilDna](slots/sockg_soilDna.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_soilfluoresceinDiacetateHydrol_mg_per_kg_per_hr](slots/sockg_soilfluoresceinDiacetateHydrol_mg_per_kg_per_hr.md) | No slot (predicate) description specified<br/>| 40 |
| [sockg_soilMoisture_percent_volume](slots/sockg_soilMoisture_percent_volume.md) | No slot (predicate) description specified<br/>| 107000 |
| [sockg_soilMoistureDepth_cm](slots/sockg_soilMoistureDepth_cm.md) | No slot (predicate) description specified<br/>| 107354 |
| [sockg_soilMoistureSd_percent_volume](slots/sockg_soilMoistureSd_percent_volume.md) | No slot (predicate) description specified<br/>| 5038 |
| [sockg_soilOrganicCarbon_kgC_ha](slots/sockg_soilOrganicCarbon_kgC_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_soilOrganicCarbon_mgC_L](slots/sockg_soilOrganicCarbon_mgC_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_soilOrganicCarbonSd_kgC_ha](slots/sockg_soilOrganicCarbonSd_kgC_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_soilOrganicCarbonSd_mgC_L](slots/sockg_soilOrganicCarbonSd_mgC_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_soilOrganicMatter_mgSom_L](slots/sockg_soilOrganicMatter_mgSom_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_soilOrganicMatterSd_mgSom_L](slots/sockg_soilOrganicMatterSd_mgSom_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_soilSd_t_ha](slots/sockg_soilSd_t_ha.md) | No slot (predicate) description specified<br/>| 15 |
| [sockg_soilSeries](slots/sockg_soilSeries.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_soilTemp10cm_degC](slots/sockg_soilTemp10cm_degC.md) | No slot (predicate) description specified<br/>| 138926 |
| [sockg_soilTemp5cm_degC](slots/sockg_soilTemp5cm_degC.md) | No slot (predicate) description specified<br/>| 44409 |
| [sockg_soilTemperature_degC](slots/sockg_soilTemperature_degC.md) | No slot (predicate) description specified<br/>| 107352 |
| [sockg_soilTemperatureSd_degC](slots/sockg_soilTemperatureSd_degC.md) | No slot (predicate) description specified<br/>| 6403 |
| [sockg_soilWithResidueCoverPercent](slots/sockg_soilWithResidueCoverPercent.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_solarRadiationBareSoil_MJ_per_m_squared_per_d](slots/sockg_solarRadiationBareSoil_MJ_per_m_squared_per_d.md) | No slot (predicate) description specified<br/>| 38763 |
| [sockg_solarRadiationVegetatedGround_MJ_per_m_squared_per_d](slots/sockg_solarRadiationVegetatedGround_MJ_per_m_squared_per_d.md) | No slot (predicate) description specified<br/>| 119985 |
| [sockg_solubleOrganicCarbon_mgC_per_kg](slots/sockg_solubleOrganicCarbon_mgC_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_solubleOrganicCarbonSd_mgC_per_kg](slots/sockg_solubleOrganicCarbonSd_mgC_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_speciesMix](slots/sockg_speciesMix.md) | No slot (predicate) description specified<br/>| 6995 |
| [sockg_stageAtHarvest](slots/sockg_stageAtHarvest.md) | No slot (predicate) description specified<br/>| 1650 |
| [sockg_standingDeadDry_kg_per_ha](slots/sockg_standingDeadDry_kg_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_standingDeadDrySd_kg_per_ha](slots/sockg_standingDeadDrySd_kg_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_startDate](slots/sockg_startDate.md) | No slot (predicate) description specified<br/>| 93567 |
| [sockg_stateFIPS](slots/sockg_stateFIPS.md) | No slot (predicate) description specified<br/>| 18 |
| [sockg_stateProvince](slots/sockg_stateProvince.md) | No slot (predicate) description specified<br/>| 19 |
| [sockg_stockingRate_number_animals_per_ha](slots/sockg_stockingRate_number_animals_per_ha.md) | No slot (predicate) description specified<br/>| 1951 |
| [sockg_studiesSite](slots/sockg_studiesSite.md) | No slot (predicate) description specified<br/>| 123 |
| [sockg_suffix](slots/sockg_suffix.md) | No slot (predicate) description specified<br/>| 32 |
| [sockg_sulfur_kg_ha](slots/sockg_sulfur_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_sulfurConcentration_g_per_kg](slots/sockg_sulfurConcentration_g_per_kg.md) | No slot (predicate) description specified<br/>| 5074 |
| [sockg_sulfurConcentrationSd_g_per_kg](slots/sockg_sulfurConcentrationSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_sulfurSd_kg_ha](slots/sockg_sulfurSd_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_surfaceLitterDry_kg_per_ha](slots/sockg_surfaceLitterDry_kg_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_surfaceLitterDrySd_kg_per_ha](slots/sockg_surfaceLitterDrySd_kg_per_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_surfaceOrLeaching](slots/sockg_surfaceOrLeaching.md) | No slot (predicate) description specified<br/>| 2146 |
| [sockg_tempMax_degC](slots/sockg_tempMax_degC.md) | No slot (predicate) description specified<br/>| 144885 |
| [sockg_tempMin_degC](slots/sockg_tempMin_degC.md) | No slot (predicate) description specified<br/>| 144828 |
| [sockg_tileDrainage](slots/sockg_tileDrainage.md) | No slot (predicate) description specified<br/>| 438 |
| [sockg_tillageDescriptor](slots/sockg_tillageDescriptor.md) | No slot (predicate) description specified<br/>| 719 |
| [sockg_tillageEvent](slots/sockg_tillageEvent.md) | No slot (predicate) description specified<br/>| 27137 |
| [sockg_tillageEventDepth_cm](slots/sockg_tillageEventDepth_cm.md) | No slot (predicate) description specified<br/>| 26709 |
| [sockg_tillageEventMethod](slots/sockg_tillageEventMethod.md) | No slot (predicate) description specified<br/>| 24342 |
| [sockg_time](slots/sockg_time.md) | No slot (predicate) description specified<br/>| 5471 |
| [sockg_timingDescriptor](slots/sockg_timingDescriptor.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_title](slots/sockg_title.md) | No slot (predicate) description specified<br/>| 136 |
| [sockg_totalAmendmentAmount_kg_per_ha](slots/sockg_totalAmendmentAmount_kg_per_ha.md) | No slot (predicate) description specified<br/>| 17555 |
| [sockg_totalChloride_kg_ha](slots/sockg_totalChloride_kg_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalChlorideSd_kgCl_ha](slots/sockg_totalChlorideSd_kgCl_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalDissolvedNitrogen_kgN_ha](slots/sockg_totalDissolvedNitrogen_kgN_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalDissolvedNitrogen_mgN_L](slots/sockg_totalDissolvedNitrogen_mgN_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalDissolvedNitrogenSd_kgN_ha](slots/sockg_totalDissolvedNitrogenSd_kgN_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalDissolvedNitrogenSd_mgN_L](slots/sockg_totalDissolvedNitrogenSd_mgN_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalDissolvedPhosphorus_kgP_ha](slots/sockg_totalDissolvedPhosphorus_kgP_ha.md) | No slot (predicate) description specified<br/>| 667 |
| [sockg_totalDissolvedPhosphorus_mgP_L](slots/sockg_totalDissolvedPhosphorus_mgP_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalDissolvedPhosphorus_mgP_l](slots/sockg_totalDissolvedPhosphorus_mgP_l.md) | No slot (predicate) description specified<br/>| 667 |
| [sockg_totalDissolvedPhosphorusSd_jgP_ha](slots/sockg_totalDissolvedPhosphorusSd_jgP_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalDissolvedPhosphorusSd_mgP_L](slots/sockg_totalDissolvedPhosphorusSd_mgP_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalNitrogen_kg_ha](slots/sockg_totalNitrogen_kg_ha.md) | No slot (predicate) description specified<br/>| 667 |
| [sockg_totalNitrogen_mg_L](slots/sockg_totalNitrogen_mg_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalNitrogen_mg_l](slots/sockg_totalNitrogen_mg_l.md) | No slot (predicate) description specified<br/>| 667 |
| [sockg_totalNitrogenAmount_kgN_per_ha](slots/sockg_totalNitrogenAmount_kgN_per_ha.md) | No slot (predicate) description specified<br/>| 21967 |
| [sockg_totalNitrogenSd_kgN_ha](slots/sockg_totalNitrogenSd_kgN_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalNitrogenSd_mg_L](slots/sockg_totalNitrogenSd_mg_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalPesticideAmount_kg_per_ha](slots/sockg_totalPesticideAmount_kg_per_ha.md) | No slot (predicate) description specified<br/>| 353 |
| [sockg_totalPhosphoru_kg_ha](slots/sockg_totalPhosphoru_kg_ha.md) | No slot (predicate) description specified<br/>| 667 |
| [sockg_totalPhosphorus_mg_L](slots/sockg_totalPhosphorus_mg_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalPhosphorus_mg_l](slots/sockg_totalPhosphorus_mg_l.md) | No slot (predicate) description specified<br/>| 667 |
| [sockg_totalPhosphorusAmount_kgP_per_ha](slots/sockg_totalPhosphorusAmount_kgP_per_ha.md) | No slot (predicate) description specified<br/>| 8440 |
| [sockg_totalPhosphorusSd_kgP_ha](slots/sockg_totalPhosphorusSd_kgP_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalPhosphorusSd_mg_L](slots/sockg_totalPhosphorusSd_mg_L.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalPotassiumAmount_kgK_per_ha](slots/sockg_totalPotassiumAmount_kgK_per_ha.md) | No slot (predicate) description specified<br/>| 6151 |
| [sockg_totalSoilCarbon_gC_per_kg](slots/sockg_totalSoilCarbon_gC_per_kg.md) | No slot (predicate) description specified<br/>| 44073 |
| [sockg_totalSoilCarbonSd_gC_per_kg](slots/sockg_totalSoilCarbonSd_gC_per_kg.md) | No slot (predicate) description specified<br/>| 768 |
| [sockg_totalSoilNitrogen_gN_per_kg](slots/sockg_totalSoilNitrogen_gN_per_kg.md) | No slot (predicate) description specified<br/>| 46104 |
| [sockg_totalSoilNitrogenSd_gN_per_kg](slots/sockg_totalSoilNitrogenSd_gN_per_kg.md) | No slot (predicate) description specified<br/>| 720 |
| [sockg_totalSolarRadiation](slots/sockg_totalSolarRadiation.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_totalSolarRadiationBareSoil_MJ_per_m_squared_per_d](slots/sockg_totalSolarRadiationBareSoil_MJ_per_m_squared_per_d.md) | No slot (predicate) description specified<br/>| 8195 |
| [sockg_tracksGrowth](slots/sockg_tracksGrowth.md) | No slot (predicate) description specified<br/>| 4896 |
| [sockg_treatmentDescriptor](slots/sockg_treatmentDescriptor.md) | No slot (predicate) description specified<br/>| 769 |
| [sockg_treatmentId](slots/sockg_treatmentId.md) | No slot (predicate) description specified<br/>| 329500 |
| [sockg_type](slots/sockg_type.md) | No slot (predicate) description specified<br/>| 23230 |
| [sockg_unitGrainWeight_mg](slots/sockg_unitGrainWeight_mg.md) | No slot (predicate) description specified<br/>| 120 |
| [sockg_unitGrainWeightSd_mg](slots/sockg_unitGrainWeightSd_mg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_units](slots/sockg_units.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_upperDepth_cm](slots/sockg_upperDepth_cm.md) | No slot (predicate) description specified<br/>| 100137 |
| [sockg_url](slots/sockg_url.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_usedInExpUnit](slots/sockg_usedInExpUnit.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_value](slots/sockg_value.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_versionDate](slots/sockg_versionDate.md) | No slot (predicate) description specified<br/>| 1 |
| [sockg_volatileMatter_g_per_kg](slots/sockg_volatileMatter_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_volatileMatterSd_g_per_kg](slots/sockg_volatileMatterSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_wasNutrientDataAt](slots/sockg_wasNutrientDataAt.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_wasNutrientTreatment](slots/sockg_wasNutrientTreatment.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_water_mm](slots/sockg_water_mm.md) | No slot (predicate) description specified<br/>| 2146 |
| [sockg_waterQualityAreaDataAt](slots/sockg_waterQualityAreaDataAt.md) | No slot (predicate) description specified<br/>| 667 |
| [sockg_waterQualityAreaTreatment](slots/sockg_waterQualityAreaTreatment.md) | No slot (predicate) description specified<br/>| 667 |
| [sockg_waterQualityConcDataAt](slots/sockg_waterQualityConcDataAt.md) | No slot (predicate) description specified<br/>| 1479 |
| [sockg_waterQualityConcTreatment](slots/sockg_waterQualityConcTreatment.md) | No slot (predicate) description specified<br/>| 1479 |
| [sockg_waterSd_mm](slots/sockg_waterSd_mm.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_waterStableAggregatePercent](slots/sockg_waterStableAggregatePercent.md) | No slot (predicate) description specified<br/>| 42 |
| [sockg_waterStableAggregatesPercentSd](slots/sockg_waterStableAggregatesPercentSd.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_weatherAtField](slots/sockg_weatherAtField.md) | No slot (predicate) description specified<br/>| 147305 |
| [sockg_weatherBadValueFlag](slots/sockg_weatherBadValueFlag.md) | No slot (predicate) description specified<br/>| 1824 |
| [sockg_weatherDaily_UID](slots/sockg_weatherDaily_UID.md) | No slot (predicate) description specified<br/>| 147305 |
| [sockg_weatherRecordedAt](slots/sockg_weatherRecordedAt.md) | No slot (predicate) description specified<br/>| 149473 |
| [sockg_weatherRecordedBy](slots/sockg_weatherRecordedBy.md) | No slot (predicate) description specified<br/>| 39489 |
| [sockg_weatherStationId](slots/sockg_weatherStationId.md) | No slot (predicate) description specified<br/>| 38375 |
| [sockg_website](slots/sockg_website.md) | No slot (predicate) description specified<br/>| 29 |
| [sockg_wiltingPoint_percent_volume](slots/sockg_wiltingPoint_percent_volume.md) | No slot (predicate) description specified<br/>| 24 |
| [sockg_wiltingPointSd_percent_volume](slots/sockg_wiltingPointSd_percent_volume.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_windDirectionDegFromNorth](slots/sockg_windDirectionDegFromNorth.md) | No slot (predicate) description specified<br/>| 51210 |
| [sockg_windErosionDataAt](slots/sockg_windErosionDataAt.md) | No slot (predicate) description specified<br/>| 15 |
| [sockg_windErosionTreatment](slots/sockg_windErosionTreatment.md) | No slot (predicate) description specified<br/>| 15 |
| [sockg_windSpeed_m_per_s](slots/sockg_windSpeed_m_per_s.md) | No slot (predicate) description specified<br/>| 92684 |
| [sockg_worksAtDepartment](slots/sockg_worksAtDepartment.md) | No slot (predicate) description specified<br/>| 91 |
| [sockg_worksFor](slots/sockg_worksFor.md) | No slot (predicate) description specified<br/>| 35 |
| [sockg_worksIn](slots/sockg_worksIn.md) | No slot (predicate) description specified<br/>| 165 |
| [sockg_xylan_g_per_kg](slots/sockg_xylan_g_per_kg.md) | No slot (predicate) description specified<br/>| 1367 |
| [sockg_xylanSd_g_per_kg](slots/sockg_xylanSd_g_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_yearsBetweenBurns](slots/sockg_yearsBetweenBurns.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_yieldNutrUptakeDataAt](slots/sockg_yieldNutrUptakeDataAt.md) | No slot (predicate) description specified<br/>| 429 |
| [sockg_yieldNutrUptakeTreatment](slots/sockg_yieldNutrUptakeTreatment.md) | No slot (predicate) description specified<br/>| 409 |
| [sockg_zinc_g_ha](slots/sockg_zinc_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_zincConcentration_mg_per_kg](slots/sockg_zincConcentration_mg_per_kg.md) | No slot (predicate) description specified<br/>| 6723 |
| [sockg_zincConcentrationSd_mg_per_kg](slots/sockg_zincConcentrationSd_mg_per_kg.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [sockg_zincSd_g_ha](slots/sockg_zincSd_g_ha.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |






## Types

| Type | Description |
| --- | --- |
| [GeoWktLiteral](types/GeoWktLiteral.md) | No class (type) description specified |





## IRI prefixes

* dcgeoid: https://datacommons.org/browser/geoId/
* geo: http://www.opengis.net/ont/geosparql#
* kwgr: http://stko-kwg.geog.ucsb.edu/lod/resource/
* linkml: https://w3id.org/linkml/
* owl: http://www.w3.org/2002/07/owl#
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* sockg: https://idir.uta.edu/sockg-ontology/docs/
* xsd: http://www.w3.org/2001/XMLSchema#
