

# Class: ScalesCriminalCase




This class occurs 2368748 times.


URI: [scales:CriminalCase](http://schemas.scales-okn.org/rdf/scales#CriminalCase)






```mermaid
 classDiagram
    class ScalesCriminalCase
    click ScalesCriminalCase href "../ScalesCriminalCase"
      ScalesCriminalCase : jxdm72_CaseCharge
        
          
    
    
    ScalesCriminalCase --> "0..1" Jxdm72Charge : jxdm72_CaseCharge
    click Jxdm72Charge href "../Jxdm72Charge"

        
      ScalesCriminalCase : jxdm72_CaseCourt
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : jxdm72_CaseCourt
    click Any href "../Any"

        
      ScalesCriminalCase : jxdm72_CaseDefendantParty
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : jxdm72_CaseDefendantParty
    click Any href "../Any"

        
      ScalesCriminalCase : jxdm72_CaseInitiatingParty
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : jxdm72_CaseInitiatingParty
    click Any href "../Any"

        
      ScalesCriminalCase : jxdm72_CaseJudge
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : jxdm72_CaseJudge
    click Any href "../Any"

        
      ScalesCriminalCase : niem50_CaseDocketID
        
          
    
    
    ScalesCriminalCase --> "0..1" String : niem50_CaseDocketID
    click String href "../String"

        
      ScalesCriminalCase : niem50_CaseGeneralCategoryText
        
          
    
    
    ScalesCriminalCase --> "0..1" String : niem50_CaseGeneralCategoryText
    click String href "../String"

        
      ScalesCriminalCase : niem50_EndDate
        
          
    
    
    ScalesCriminalCase --> "0..1" Date : niem50_EndDate
    click Date href "../Date"

        
      ScalesCriminalCase : niem50_JurisdictionText
        
          
    
    
    ScalesCriminalCase --> "0..1" String : niem50_JurisdictionText
    click String href "../String"

        
      ScalesCriminalCase : niem50_StartDate
        
          
    
    
    ScalesCriminalCase --> "0..1" Date : niem50_StartDate
    click Date href "../Date"

        
      ScalesCriminalCase : niem50_StatusDescriptionText
        
          
    
    
    ScalesCriminalCase --> "0..1" String : niem50_StatusDescriptionText
    click String href "../String"

        
      ScalesCriminalCase : scales_DocketTable
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_DocketTable
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbAppcd
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbAppcd
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbAppdate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbAppdate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbCaslgky
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbCaslgky
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbCircuit
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCircuit
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCounty
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCounty
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtdef
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtdef
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtfil
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtfil
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtfilr
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtfilr
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtfiltrn
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtfiltrn
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtfilwor
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtfilwor
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtpn
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtpn
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtpnwof
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtpnwof
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCttr
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCttr
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCttrr
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCttrr
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCttrtrn
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCttrtrn
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCttrwor
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCttrwor
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2foffcd1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2foffcd1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2foffcd2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2foffcd2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2foffcd3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2foffcd3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2foffcd4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2foffcd4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2foffcd5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2foffcd5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2toffcd1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2toffcd1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2toffcd2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2toffcd2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2toffcd3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2toffcd3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2toffcd4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2toffcd4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2toffcd5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2toffcd5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDeflgky
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbDeflgky
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbDefno
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbDefno
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDisp1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbDisp1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDisp2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbDisp2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDisp3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbDisp3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDisp4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbDisp4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDisp5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbDisp5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDispdate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbDispdate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbDistrict
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbDistrict
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbDocket
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbDocket
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFcounsel
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFcounsel
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFgenddate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFgenddate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFgstrtdate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFgstrtdate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFiledate
        
          
    
    
    ScalesCriminalCase --> "0..1" Datetime : scales_hasIdbFiledate
    click Datetime href "../Datetime"

        
      ScalesCriminalCase : scales_hasIdbFineamt1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFineamt1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFineamt2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFineamt2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFineamt3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFineamt3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFineamt4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFineamt4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFineamt5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFineamt5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFinetot
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFinetot
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFiscalyr
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFiscalyr
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFoffcd1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFoffcd1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFoffcd2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFoffcd2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFoffcd3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFoffcd3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFoffcd4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFoffcd4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFoffcd5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFoffcd5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFofflvl1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFofflvl1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFofflvl2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFofflvl2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFofflvl3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFofflvl3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFofflvl4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFofflvl4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFofflvl5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFofflvl5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFsev1
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFsev1
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFsev2
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFsev2
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFsev3
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFsev3
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFsev4
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbFsev4
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbFsev5
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbFsev5
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbFtitle1
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFtitle1
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFtitle2
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFtitle2
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFtitle3
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFtitle3
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFtitle4
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFtitle4
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFtitle5
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFtitle5
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFugstat
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFugstat
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbInt1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbInt1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbInt2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbInt2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbInt3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbInt3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbIs_stub
        
          
    
    
    ScalesCriminalCase --> "0..1" Boolean : scales_hasIdbIs_stub
    click Boolean href "../Boolean"

        
      ScalesCriminalCase : scales_hasIdbLoaddate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbLoaddate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbMagdef
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbMagdef
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbMagdock
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbMagdock
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbOffice
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbOffice
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbPriscd1
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbPriscd1
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbPriscd2
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbPriscd2
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbPriscd3
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbPriscd3
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbPriscd4
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbPriscd4
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbPriscd5
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbPriscd5
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbPristim1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbPristim1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbPristim2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbPristim2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbPristim3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbPristim3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbPristim4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbPristim4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbPristim5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbPristim5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbPristot
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbPristot
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProbcd1
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbProbcd1
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbProbcd2
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbProbcd2
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbProbcd3
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbProbcd3
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbProbcd4
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbProbcd4
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbProbcd5
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbProbcd5
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbProbmon1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProbmon1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProbmon2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProbmon2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProbmon3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProbmon3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProbmon4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProbmon4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProbmon5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProbmon5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProbtot
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProbtot
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProccd
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProccd
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProcdate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbProcdate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbReopseq
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbReopseq
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbSentdate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbSentdate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbStatuscd
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbStatuscd
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbSupvrel1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbSupvrel1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbSupvrel2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbSupvrel2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbSupvrel3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbSupvrel3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbSupvrel4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbSupvrel4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbSupvrel5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbSupvrel5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTapeyear
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTapeyear
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTcounsel
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTcounsel
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTermdate
        
          
    
    
    ScalesCriminalCase --> "0..1" Datetime : scales_hasIdbTermdate
    click Datetime href "../Datetime"

        
      ScalesCriminalCase : scales_hasIdbTermoff
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTermoff
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbToffcd1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbToffcd1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbToffcd2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbToffcd2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbToffcd3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbToffcd3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbToffcd4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbToffcd4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbToffcd5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbToffcd5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTofflvl1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTofflvl1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTofflvl2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTofflvl2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTofflvl3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTofflvl3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTofflvl4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTofflvl4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTofflvl5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTofflvl5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTrandef
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTrandef
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTrandist
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTrandist
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbTrandock
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTrandock
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTranoff
        
          
    
    
    ScalesCriminalCase --> "0..1" Integer : scales_hasIdbTranoff
    click Integer href "../Integer"

        
      ScalesCriminalCase : scales_hasIdbTsev1
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTsev1
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTsev2
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTsev2
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbTsev3
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTsev3
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbTsev4
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTsev4
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbTsev5
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTsev5
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbTtitle1
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTtitle1
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTtitle2
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTtitle2
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTtitle3
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTtitle3
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTtitle4
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTtitle4
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTtitle5
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTtitle5
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbTypemag
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTypemag
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTypereg
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTypereg
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTypetrn
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTypetrn
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbUpdate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbUpdate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbVer
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbVer
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasMemberCase
        
          
    
    
    ScalesCriminalCase --> "0..1" ScalesCivilCase : scales_hasMemberCase
    click ScalesCivilCase href "../ScalesCivilCase"

        
      ScalesCriminalCase : scales_hasRelatedCase
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasRelatedCase
    click Any href "../Any"

        
      ScalesCriminalCase : scales_Party
        
          
    
    
    ScalesCriminalCase --> "0..1" ScalesParty : scales_Party
    click ScalesParty href "../ScalesParty"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [scales_hasIdbFtitle4](../slots/scales_hasIdbFtitle4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbCaslgky](../slots/scales_hasIdbCaslgky.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbFofflvl1](../slots/scales_hasIdbFofflvl1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFinetot](../slots/scales_hasIdbFinetot.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbPriscd5](../slots/scales_hasIdbPriscd5.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbCircuit](../slots/scales_hasIdbCircuit.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFofflvl3](../slots/scales_hasIdbFofflvl3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFofflvl4](../slots/scales_hasIdbFofflvl4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbCtfil](../slots/scales_hasIdbCtfil.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFtitle5](../slots/scales_hasIdbFtitle5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbReopseq](../slots/scales_hasIdbReopseq.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFsev5](../slots/scales_hasIdbFsev5.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbProcdate](../slots/scales_hasIdbProcdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbTermdate](../slots/scales_hasIdbTermdate.md) | 0..1 <br/> [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime) |  <br/>  | direct | 50408 |
| [scales_hasIdbFoffcd3](../slots/scales_hasIdbFoffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTermoff](../slots/scales_hasIdbTermoff.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbProbmon5](../slots/scales_hasIdbProbmon5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFineamt1](../slots/scales_hasIdbFineamt1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbPriscd3](../slots/scales_hasIdbPriscd3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbInt3](../slots/scales_hasIdbInt3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFofflvl2](../slots/scales_hasIdbFofflvl2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbDisp2](../slots/scales_hasIdbDisp2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTtitle3](../slots/scales_hasIdbTtitle3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbStatuscd](../slots/scales_hasIdbStatuscd.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbCtpn](../slots/scales_hasIdbCtpn.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbSupvrel1](../slots/scales_hasIdbSupvrel1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbOffice](../slots/scales_hasIdbOffice.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbSupvrel3](../slots/scales_hasIdbSupvrel3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbD2foffcd2](../slots/scales_hasIdbD2foffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTsev4](../slots/scales_hasIdbTsev4.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbProccd](../slots/scales_hasIdbProccd.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbPriscd1](../slots/scales_hasIdbPriscd1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbCounty](../slots/scales_hasIdbCounty.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFineamt3](../slots/scales_hasIdbFineamt3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbPristim3](../slots/scales_hasIdbPristim3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbProbcd2](../slots/scales_hasIdbProbcd2.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [jxdm72_CaseCourt](../slots/jxdm72_CaseCourt.md) | 0..1 <br/> [Jxdm72Court](../classes/Jxdm72Court.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 2368748 |
| [scales_hasIdbMagdock](../slots/scales_hasIdbMagdock.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFsev4](../slots/scales_hasIdbFsev4.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbMagdef](../slots/scales_hasIdbMagdef.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTrandef](../slots/scales_hasIdbTrandef.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTapeyear](../slots/scales_hasIdbTapeyear.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTypemag](../slots/scales_hasIdbTypemag.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbFoffcd1](../slots/scales_hasIdbFoffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbProbcd3](../slots/scales_hasIdbProbcd3.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbCtfilr](../slots/scales_hasIdbCtfilr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFcounsel](../slots/scales_hasIdbFcounsel.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFiscalyr](../slots/scales_hasIdbFiscalyr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTsev1](../slots/scales_hasIdbTsev1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbSupvrel2](../slots/scales_hasIdbSupvrel2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbToffcd1](../slots/scales_hasIdbToffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbDisp1](../slots/scales_hasIdbDisp1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [jxdm72_CaseCharge](../slots/jxdm72_CaseCharge.md) | 0..1 <br/> [Jxdm72Charge](../classes/Jxdm72Charge.md) |  <br/>  | direct | 607725 |
| [scales_hasIdbTofflvl4](../slots/scales_hasIdbTofflvl4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbD2foffcd3](../slots/scales_hasIdbD2foffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbPristim4](../slots/scales_hasIdbPristim4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbCttrwor](../slots/scales_hasIdbCttrwor.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [jxdm72_CaseInitiatingParty](../slots/jxdm72_CaseInitiatingParty.md) | 0..1 <br/> [Jxdm72CaseInitiatingParty](../classes/Jxdm72CaseInitiatingParty.md)&nbsp;or&nbsp;<br />[ScalesParty](../classes/ScalesParty.md) |  <br/>  | direct | 2212899 |
| [scales_hasIdbTypetrn](../slots/scales_hasIdbTypetrn.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_DocketTable](../slots/scales_DocketTable.md) | 0..1 <br/> [Jxdm72RegisterOfActions](../classes/Jxdm72RegisterOfActions.md)&nbsp;or&nbsp;<br />[Jxdm72RegisterAction](../classes/Jxdm72RegisterAction.md) |  <br/>  | direct | 2511005 |
| [scales_hasIdbFgstrtdate](../slots/scales_hasIdbFgstrtdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbPristot](../slots/scales_hasIdbPristot.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbDisp4](../slots/scales_hasIdbDisp4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbProbmon4](../slots/scales_hasIdbProbmon4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbD2toffcd2](../slots/scales_hasIdbD2toffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbVer](../slots/scales_hasIdbVer.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbCtfilwor](../slots/scales_hasIdbCtfilwor.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbPristim1](../slots/scales_hasIdbPristim1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbProbcd4](../slots/scales_hasIdbProbcd4.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbFtitle2](../slots/scales_hasIdbFtitle2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbProbtot](../slots/scales_hasIdbProbtot.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbAppcd](../slots/scales_hasIdbAppcd.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbD2foffcd4](../slots/scales_hasIdbD2foffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFoffcd2](../slots/scales_hasIdbFoffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTtitle4](../slots/scales_hasIdbTtitle4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | 0..1 <br/> [ScalesCivilCase](../classes/ScalesCivilCase.md)&nbsp;or&nbsp;<br />[ScalesCriminalCase](../classes/ScalesCriminalCase.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) |  <br/>  | direct | 3540 |
| [niem50_CaseDocketID](../slots/niem50_CaseDocketID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 2368748 |
| [scales_hasIdbSupvrel5](../slots/scales_hasIdbSupvrel5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbCtfiltrn](../slots/scales_hasIdbCtfiltrn.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTtitle1](../slots/scales_hasIdbTtitle1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbProbmon3](../slots/scales_hasIdbProbmon3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTsev2](../slots/scales_hasIdbTsev2.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbD2toffcd5](../slots/scales_hasIdbD2toffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbDocket](../slots/scales_hasIdbDocket.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbFtitle3](../slots/scales_hasIdbFtitle3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbPristim5](../slots/scales_hasIdbPristim5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTofflvl1](../slots/scales_hasIdbTofflvl1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbDistrict](../slots/scales_hasIdbDistrict.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbToffcd2](../slots/scales_hasIdbToffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFsev2](../slots/scales_hasIdbFsev2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbTranoff](../slots/scales_hasIdbTranoff.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) |  <br/>  | direct | 121785 |
| [scales_hasIdbTcounsel](../slots/scales_hasIdbTcounsel.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbD2foffcd1](../slots/scales_hasIdbD2foffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbDispdate](../slots/scales_hasIdbDispdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbFtitle1](../slots/scales_hasIdbFtitle1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbToffcd3](../slots/scales_hasIdbToffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFoffcd4](../slots/scales_hasIdbFoffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbAppdate](../slots/scales_hasIdbAppdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbProbcd5](../slots/scales_hasIdbProbcd5.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbTypereg](../slots/scales_hasIdbTypereg.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [niem50_EndDate](../slots/niem50_EndDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 2204518 |
| [scales_hasIdbTrandist](../slots/scales_hasIdbTrandist.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbTsev5](../slots/scales_hasIdbTsev5.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbTtitle5](../slots/scales_hasIdbTtitle5.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbInt1](../slots/scales_hasIdbInt1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [niem50_CaseGeneralCategoryText](../slots/niem50_CaseGeneralCategoryText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 2277147 |
| [scales_hasIdbDeflgky](../slots/scales_hasIdbDeflgky.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbTsev3](../slots/scales_hasIdbTsev3.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbCttrtrn](../slots/scales_hasIdbCttrtrn.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbDisp3](../slots/scales_hasIdbDisp3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFineamt5](../slots/scales_hasIdbFineamt5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFoffcd5](../slots/scales_hasIdbFoffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbProbcd1](../slots/scales_hasIdbProbcd1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbD2foffcd5](../slots/scales_hasIdbD2foffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbCtpnwof](../slots/scales_hasIdbCtpnwof.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFugstat](../slots/scales_hasIdbFugstat.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [niem50_StatusDescriptionText](../slots/niem50_StatusDescriptionText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 2277147 |
| [scales_hasIdbTofflvl2](../slots/scales_hasIdbTofflvl2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTofflvl5](../slots/scales_hasIdbTofflvl5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbDefno](../slots/scales_hasIdbDefno.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [niem50_JurisdictionText](../slots/niem50_JurisdictionText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 2131217 |
| [scales_hasIdbCttrr](../slots/scales_hasIdbCttrr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbProbmon1](../slots/scales_hasIdbProbmon1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTofflvl3](../slots/scales_hasIdbTofflvl3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbPriscd2](../slots/scales_hasIdbPriscd2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [niem50_StartDate](../slots/niem50_StartDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 2277147 |
| [scales_hasIdbSupvrel4](../slots/scales_hasIdbSupvrel4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasMemberCase](../slots/scales_hasMemberCase.md) | 0..1 <br/> [ScalesCivilCase](../classes/ScalesCivilCase.md) |  <br/>  | direct | 1 |
| [scales_hasIdbFsev1](../slots/scales_hasIdbFsev1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbInt2](../slots/scales_hasIdbInt2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbPriscd4](../slots/scales_hasIdbPriscd4.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbIs_stub](../slots/scales_hasIdbIs_stub.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) |  <br/>  | direct | 121785 |
| [scales_hasIdbFiledate](../slots/scales_hasIdbFiledate.md) | 0..1 <br/> [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime) |  <br/>  | direct | 121785 |
| [scales_hasIdbToffcd5](../slots/scales_hasIdbToffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbFineamt4](../slots/scales_hasIdbFineamt4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbDisp5](../slots/scales_hasIdbDisp5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbD2toffcd4](../slots/scales_hasIdbD2toffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbTrandock](../slots/scales_hasIdbTrandock.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbCttr](../slots/scales_hasIdbCttr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbUpdate](../slots/scales_hasIdbUpdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [jxdm72_CaseJudge](../slots/jxdm72_CaseJudge.md) | 0..1 <br/> [Jxdm72CaseJudge](../classes/Jxdm72CaseJudge.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) |  <br/>  | direct | 2363117 |
| [scales_hasIdbFofflvl5](../slots/scales_hasIdbFofflvl5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbLoaddate](../slots/scales_hasIdbLoaddate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbD2toffcd3](../slots/scales_hasIdbD2toffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_Party](../slots/scales_Party.md) | 0..1 <br/> [ScalesParty](../classes/ScalesParty.md) |  <br/>  | direct | 19710 |
| [scales_hasIdbFgenddate](../slots/scales_hasIdbFgenddate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbTtitle2](../slots/scales_hasIdbTtitle2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbFineamt2](../slots/scales_hasIdbFineamt2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbPristim2](../slots/scales_hasIdbPristim2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbCtdef](../slots/scales_hasIdbCtdef.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [jxdm72_CaseDefendantParty](../slots/jxdm72_CaseDefendantParty.md) | 0..1 <br/> [Jxdm72CaseDefendantParty](../classes/Jxdm72CaseDefendantParty.md)&nbsp;or&nbsp;<br />[ScalesParty](../classes/ScalesParty.md) |  <br/>  | direct | 2562309 |
| [scales_hasIdbToffcd4](../slots/scales_hasIdbToffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbProbmon2](../slots/scales_hasIdbProbmon2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |
| [scales_hasIdbSentdate](../slots/scales_hasIdbSentdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbFsev3](../slots/scales_hasIdbFsev3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 121785 |
| [scales_hasIdbD2toffcd1](../slots/scales_hasIdbD2toffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) |  <br/>  | direct | 121785 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Jxdm72Booking](../classes/Jxdm72Booking.md) | [scales_BookingCase](../slots/scales_BookingCase.md) | range | [ScalesCriminalCase](../classes/ScalesCriminalCase.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | any_of[range] | [ScalesCriminalCase](../classes/ScalesCriminalCase.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | any_of[range] | [ScalesCriminalCase](../classes/ScalesCriminalCase.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: scales_CriminalCase
from_schema: okns:scales-kg
rank: 1000
slots:
- scales_hasIdbFtitle4
- scales_hasIdbCaslgky
- scales_hasIdbFofflvl1
- scales_hasIdbFinetot
- scales_hasIdbPriscd5
- scales_hasIdbCircuit
- scales_hasIdbFofflvl3
- scales_hasIdbFofflvl4
- scales_hasIdbCtfil
- scales_hasIdbFtitle5
- scales_hasIdbReopseq
- scales_hasIdbFsev5
- scales_hasIdbProcdate
- scales_hasIdbTermdate
- scales_hasIdbFoffcd3
- scales_hasIdbTermoff
- scales_hasIdbProbmon5
- scales_hasIdbFineamt1
- scales_hasIdbPriscd3
- scales_hasIdbInt3
- scales_hasIdbFofflvl2
- scales_hasIdbDisp2
- scales_hasIdbTtitle3
- scales_hasIdbStatuscd
- scales_hasIdbCtpn
- scales_hasIdbSupvrel1
- scales_hasIdbOffice
- scales_hasIdbSupvrel3
- scales_hasIdbD2foffcd2
- scales_hasIdbTsev4
- scales_hasIdbProccd
- scales_hasIdbPriscd1
- scales_hasIdbCounty
- scales_hasIdbFineamt3
- scales_hasIdbPristim3
- scales_hasIdbProbcd2
- jxdm72_CaseCourt
- scales_hasIdbMagdock
- scales_hasIdbFsev4
- scales_hasIdbMagdef
- scales_hasIdbTrandef
- scales_hasIdbTapeyear
- scales_hasIdbTypemag
- scales_hasIdbFoffcd1
- scales_hasIdbProbcd3
- scales_hasIdbCtfilr
- scales_hasIdbFcounsel
- scales_hasIdbFiscalyr
- scales_hasIdbTsev1
- scales_hasIdbSupvrel2
- scales_hasIdbToffcd1
- scales_hasIdbDisp1
- jxdm72_CaseCharge
- scales_hasIdbTofflvl4
- scales_hasIdbD2foffcd3
- scales_hasIdbPristim4
- scales_hasIdbCttrwor
- jxdm72_CaseInitiatingParty
- scales_hasIdbTypetrn
- scales_DocketTable
- scales_hasIdbFgstrtdate
- scales_hasIdbPristot
- scales_hasIdbDisp4
- scales_hasIdbProbmon4
- scales_hasIdbD2toffcd2
- scales_hasIdbVer
- scales_hasIdbCtfilwor
- scales_hasIdbPristim1
- scales_hasIdbProbcd4
- scales_hasIdbFtitle2
- scales_hasIdbProbtot
- scales_hasIdbAppcd
- scales_hasIdbD2foffcd4
- scales_hasIdbFoffcd2
- scales_hasIdbTtitle4
- scales_hasRelatedCase
- niem50_CaseDocketID
- scales_hasIdbSupvrel5
- scales_hasIdbCtfiltrn
- scales_hasIdbTtitle1
- scales_hasIdbProbmon3
- scales_hasIdbTsev2
- scales_hasIdbD2toffcd5
- scales_hasIdbDocket
- scales_hasIdbFtitle3
- scales_hasIdbPristim5
- scales_hasIdbTofflvl1
- scales_hasIdbDistrict
- scales_hasIdbToffcd2
- scales_hasIdbFsev2
- scales_hasIdbTranoff
- scales_hasIdbTcounsel
- scales_hasIdbD2foffcd1
- scales_hasIdbDispdate
- scales_hasIdbFtitle1
- scales_hasIdbToffcd3
- scales_hasIdbFoffcd4
- scales_hasIdbAppdate
- scales_hasIdbProbcd5
- scales_hasIdbTypereg
- niem50_EndDate
- scales_hasIdbTrandist
- scales_hasIdbTsev5
- scales_hasIdbTtitle5
- scales_hasIdbInt1
- niem50_CaseGeneralCategoryText
- scales_hasIdbDeflgky
- scales_hasIdbTsev3
- scales_hasIdbCttrtrn
- scales_hasIdbDisp3
- scales_hasIdbFineamt5
- scales_hasIdbFoffcd5
- scales_hasIdbProbcd1
- scales_hasIdbD2foffcd5
- scales_hasIdbCtpnwof
- scales_hasIdbFugstat
- niem50_StatusDescriptionText
- scales_hasIdbTofflvl2
- scales_hasIdbTofflvl5
- scales_hasIdbDefno
- niem50_JurisdictionText
- scales_hasIdbCttrr
- scales_hasIdbProbmon1
- scales_hasIdbTofflvl3
- scales_hasIdbPriscd2
- niem50_StartDate
- scales_hasIdbSupvrel4
- scales_hasMemberCase
- scales_hasIdbFsev1
- scales_hasIdbInt2
- scales_hasIdbPriscd4
- scales_hasIdbIs_stub
- scales_hasIdbFiledate
- scales_hasIdbToffcd5
- scales_hasIdbFineamt4
- scales_hasIdbDisp5
- scales_hasIdbD2toffcd4
- scales_hasIdbTrandock
- scales_hasIdbCttr
- scales_hasIdbUpdate
- jxdm72_CaseJudge
- scales_hasIdbFofflvl5
- scales_hasIdbLoaddate
- scales_hasIdbD2toffcd3
- scales_Party
- scales_hasIdbFgenddate
- scales_hasIdbTtitle2
- scales_hasIdbFineamt2
- scales_hasIdbPristim2
- scales_hasIdbCtdef
- jxdm72_CaseDefendantParty
- scales_hasIdbToffcd4
- scales_hasIdbProbmon2
- scales_hasIdbSentdate
- scales_hasIdbFsev3
- scales_hasIdbD2toffcd1
class_uri: scales:CriminalCase

```
</details>

### Induced

<details>

```yaml
name: scales_CriminalCase
from_schema: okns:scales-kg
rank: 1000
attributes:
  scales_hasIdbFtitle4:
    name: scales_hasIdbFtitle4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle4
    alias: scales_hasIdbFtitle4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbCaslgky:
    name: scales_hasIdbCaslgky
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCaslgky
    alias: scales_hasIdbCaslgky
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbFofflvl1:
    name: scales_hasIdbFofflvl1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl1
    alias: scales_hasIdbFofflvl1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFinetot:
    name: scales_hasIdbFinetot
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFinetot
    alias: scales_hasIdbFinetot
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbPriscd5:
    name: scales_hasIdbPriscd5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd5
    alias: scales_hasIdbPriscd5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbCircuit:
    name: scales_hasIdbCircuit
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCircuit
    alias: scales_hasIdbCircuit
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: double
  scales_hasIdbFofflvl3:
    name: scales_hasIdbFofflvl3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl3
    alias: scales_hasIdbFofflvl3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFofflvl4:
    name: scales_hasIdbFofflvl4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl4
    alias: scales_hasIdbFofflvl4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbCtfil:
    name: scales_hasIdbCtfil
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfil
    alias: scales_hasIdbCtfil
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFtitle5:
    name: scales_hasIdbFtitle5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle5
    alias: scales_hasIdbFtitle5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbReopseq:
    name: scales_hasIdbReopseq
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbReopseq
    alias: scales_hasIdbReopseq
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFsev5:
    name: scales_hasIdbFsev5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev5
    alias: scales_hasIdbFsev5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbProcdate:
    name: scales_hasIdbProcdate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProcdate
    alias: scales_hasIdbProcdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbTermdate:
    name: scales_hasIdbTermdate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTermdate
    alias: scales_hasIdbTermdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: datetime
  scales_hasIdbFoffcd3:
    name: scales_hasIdbFoffcd3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd3
    alias: scales_hasIdbFoffcd3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTermoff:
    name: scales_hasIdbTermoff
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTermoff
    alias: scales_hasIdbTermoff
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbProbmon5:
    name: scales_hasIdbProbmon5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon5
    alias: scales_hasIdbProbmon5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFineamt1:
    name: scales_hasIdbFineamt1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt1
    alias: scales_hasIdbFineamt1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbPriscd3:
    name: scales_hasIdbPriscd3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd3
    alias: scales_hasIdbPriscd3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbInt3:
    name: scales_hasIdbInt3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbInt3
    alias: scales_hasIdbInt3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFofflvl2:
    name: scales_hasIdbFofflvl2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl2
    alias: scales_hasIdbFofflvl2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDisp2:
    name: scales_hasIdbDisp2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp2
    alias: scales_hasIdbDisp2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTtitle3:
    name: scales_hasIdbTtitle3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle3
    alias: scales_hasIdbTtitle3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbStatuscd:
    name: scales_hasIdbStatuscd
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbStatuscd
    alias: scales_hasIdbStatuscd
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbCtpn:
    name: scales_hasIdbCtpn
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtpn
    alias: scales_hasIdbCtpn
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbSupvrel1:
    name: scales_hasIdbSupvrel1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel1
    alias: scales_hasIdbSupvrel1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbOffice:
    name: scales_hasIdbOffice
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbOffice
    alias: scales_hasIdbOffice
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbSupvrel3:
    name: scales_hasIdbSupvrel3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel3
    alias: scales_hasIdbSupvrel3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbD2foffcd2:
    name: scales_hasIdbD2foffcd2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd2
    alias: scales_hasIdbD2foffcd2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTsev4:
    name: scales_hasIdbTsev4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev4
    alias: scales_hasIdbTsev4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbProccd:
    name: scales_hasIdbProccd
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProccd
    alias: scales_hasIdbProccd
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbPriscd1:
    name: scales_hasIdbPriscd1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd1
    alias: scales_hasIdbPriscd1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbCounty:
    name: scales_hasIdbCounty
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCounty
    alias: scales_hasIdbCounty
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: double
  scales_hasIdbFineamt3:
    name: scales_hasIdbFineamt3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt3
    alias: scales_hasIdbFineamt3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbPristim3:
    name: scales_hasIdbPristim3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim3
    alias: scales_hasIdbPristim3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbcd2:
    name: scales_hasIdbProbcd2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd2
    alias: scales_hasIdbProbcd2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  jxdm72_CaseCourt:
    name: jxdm72_CaseCourt
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: jxdm72:CaseCourt
    alias: jxdm72_CaseCourt
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: Any
    any_of:
    - range: jxdm72_Court
    - range: string
  scales_hasIdbMagdock:
    name: scales_hasIdbMagdock
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbMagdock
    alias: scales_hasIdbMagdock
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFsev4:
    name: scales_hasIdbFsev4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev4
    alias: scales_hasIdbFsev4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbMagdef:
    name: scales_hasIdbMagdef
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbMagdef
    alias: scales_hasIdbMagdef
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTrandef:
    name: scales_hasIdbTrandef
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrandef
    alias: scales_hasIdbTrandef
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTapeyear:
    name: scales_hasIdbTapeyear
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTapeyear
    alias: scales_hasIdbTapeyear
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: double
  scales_hasIdbTypemag:
    name: scales_hasIdbTypemag
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTypemag
    alias: scales_hasIdbTypemag
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbFoffcd1:
    name: scales_hasIdbFoffcd1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd1
    alias: scales_hasIdbFoffcd1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbcd3:
    name: scales_hasIdbProbcd3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd3
    alias: scales_hasIdbProbcd3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbCtfilr:
    name: scales_hasIdbCtfilr
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfilr
    alias: scales_hasIdbCtfilr
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFcounsel:
    name: scales_hasIdbFcounsel
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFcounsel
    alias: scales_hasIdbFcounsel
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFiscalyr:
    name: scales_hasIdbFiscalyr
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFiscalyr
    alias: scales_hasIdbFiscalyr
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTsev1:
    name: scales_hasIdbTsev1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev1
    alias: scales_hasIdbTsev1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbSupvrel2:
    name: scales_hasIdbSupvrel2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel2
    alias: scales_hasIdbSupvrel2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbToffcd1:
    name: scales_hasIdbToffcd1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd1
    alias: scales_hasIdbToffcd1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDisp1:
    name: scales_hasIdbDisp1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp1
    alias: scales_hasIdbDisp1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  jxdm72_CaseCharge:
    name: jxdm72_CaseCharge
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: jxdm72:CaseCharge
    alias: jxdm72_CaseCharge
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: jxdm72_Charge
  scales_hasIdbTofflvl4:
    name: scales_hasIdbTofflvl4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl4
    alias: scales_hasIdbTofflvl4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbD2foffcd3:
    name: scales_hasIdbD2foffcd3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd3
    alias: scales_hasIdbD2foffcd3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbPristim4:
    name: scales_hasIdbPristim4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim4
    alias: scales_hasIdbPristim4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbCttrwor:
    name: scales_hasIdbCttrwor
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttrwor
    alias: scales_hasIdbCttrwor
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  jxdm72_CaseInitiatingParty:
    name: jxdm72_CaseInitiatingParty
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: jxdm72:CaseInitiatingParty
    alias: jxdm72_CaseInitiatingParty
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: Any
    any_of:
    - range: jxdm72_CaseInitiatingParty
    - range: scales_Party
  scales_hasIdbTypetrn:
    name: scales_hasIdbTypetrn
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTypetrn
    alias: scales_hasIdbTypetrn
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_DocketTable:
    name: scales_DocketTable
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:DocketTable
    alias: scales_DocketTable
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: Any
    any_of:
    - range: jxdm72_RegisterOfActions
    - range: jxdm72_RegisterAction
  scales_hasIdbFgstrtdate:
    name: scales_hasIdbFgstrtdate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFgstrtdate
    alias: scales_hasIdbFgstrtdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbPristot:
    name: scales_hasIdbPristot
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristot
    alias: scales_hasIdbPristot
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDisp4:
    name: scales_hasIdbDisp4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp4
    alias: scales_hasIdbDisp4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbmon4:
    name: scales_hasIdbProbmon4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon4
    alias: scales_hasIdbProbmon4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbD2toffcd2:
    name: scales_hasIdbD2toffcd2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd2
    alias: scales_hasIdbD2toffcd2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbVer:
    name: scales_hasIdbVer
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbVer
    alias: scales_hasIdbVer
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbCtfilwor:
    name: scales_hasIdbCtfilwor
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfilwor
    alias: scales_hasIdbCtfilwor
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbPristim1:
    name: scales_hasIdbPristim1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim1
    alias: scales_hasIdbPristim1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbcd4:
    name: scales_hasIdbProbcd4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd4
    alias: scales_hasIdbProbcd4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbFtitle2:
    name: scales_hasIdbFtitle2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle2
    alias: scales_hasIdbFtitle2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbProbtot:
    name: scales_hasIdbProbtot
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbtot
    alias: scales_hasIdbProbtot
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbAppcd:
    name: scales_hasIdbAppcd
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbAppcd
    alias: scales_hasIdbAppcd
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbD2foffcd4:
    name: scales_hasIdbD2foffcd4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd4
    alias: scales_hasIdbD2foffcd4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFoffcd2:
    name: scales_hasIdbFoffcd2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd2
    alias: scales_hasIdbFoffcd2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTtitle4:
    name: scales_hasIdbTtitle4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle4
    alias: scales_hasIdbTtitle4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasRelatedCase:
    name: scales_hasRelatedCase
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasRelatedCase
    alias: scales_hasRelatedCase
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: Any
    any_of:
    - range: scales_CivilCase
    - range: scales_CriminalCase
    - range: uri
  niem50_CaseDocketID:
    name: niem50_CaseDocketID
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: niem50:CaseDocketID
    alias: niem50_CaseDocketID
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbSupvrel5:
    name: scales_hasIdbSupvrel5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel5
    alias: scales_hasIdbSupvrel5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbCtfiltrn:
    name: scales_hasIdbCtfiltrn
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfiltrn
    alias: scales_hasIdbCtfiltrn
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTtitle1:
    name: scales_hasIdbTtitle1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle1
    alias: scales_hasIdbTtitle1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbProbmon3:
    name: scales_hasIdbProbmon3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon3
    alias: scales_hasIdbProbmon3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTsev2:
    name: scales_hasIdbTsev2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev2
    alias: scales_hasIdbTsev2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbD2toffcd5:
    name: scales_hasIdbD2toffcd5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd5
    alias: scales_hasIdbD2toffcd5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDocket:
    name: scales_hasIdbDocket
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDocket
    alias: scales_hasIdbDocket
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbFtitle3:
    name: scales_hasIdbFtitle3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle3
    alias: scales_hasIdbFtitle3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbPristim5:
    name: scales_hasIdbPristim5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim5
    alias: scales_hasIdbPristim5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTofflvl1:
    name: scales_hasIdbTofflvl1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl1
    alias: scales_hasIdbTofflvl1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDistrict:
    name: scales_hasIdbDistrict
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDistrict
    alias: scales_hasIdbDistrict
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbToffcd2:
    name: scales_hasIdbToffcd2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd2
    alias: scales_hasIdbToffcd2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFsev2:
    name: scales_hasIdbFsev2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev2
    alias: scales_hasIdbFsev2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbTranoff:
    name: scales_hasIdbTranoff
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTranoff
    alias: scales_hasIdbTranoff
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: integer
  scales_hasIdbTcounsel:
    name: scales_hasIdbTcounsel
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTcounsel
    alias: scales_hasIdbTcounsel
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbD2foffcd1:
    name: scales_hasIdbD2foffcd1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd1
    alias: scales_hasIdbD2foffcd1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDispdate:
    name: scales_hasIdbDispdate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDispdate
    alias: scales_hasIdbDispdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbFtitle1:
    name: scales_hasIdbFtitle1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle1
    alias: scales_hasIdbFtitle1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbToffcd3:
    name: scales_hasIdbToffcd3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd3
    alias: scales_hasIdbToffcd3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFoffcd4:
    name: scales_hasIdbFoffcd4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd4
    alias: scales_hasIdbFoffcd4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbAppdate:
    name: scales_hasIdbAppdate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbAppdate
    alias: scales_hasIdbAppdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbProbcd5:
    name: scales_hasIdbProbcd5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd5
    alias: scales_hasIdbProbcd5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbTypereg:
    name: scales_hasIdbTypereg
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTypereg
    alias: scales_hasIdbTypereg
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  niem50_EndDate:
    name: niem50_EndDate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: niem50:EndDate
    alias: niem50_EndDate
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: date
  scales_hasIdbTrandist:
    name: scales_hasIdbTrandist
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrandist
    alias: scales_hasIdbTrandist
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbTsev5:
    name: scales_hasIdbTsev5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev5
    alias: scales_hasIdbTsev5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbTtitle5:
    name: scales_hasIdbTtitle5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle5
    alias: scales_hasIdbTtitle5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbInt1:
    name: scales_hasIdbInt1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbInt1
    alias: scales_hasIdbInt1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  niem50_CaseGeneralCategoryText:
    name: niem50_CaseGeneralCategoryText
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: niem50:CaseGeneralCategoryText
    alias: niem50_CaseGeneralCategoryText
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbDeflgky:
    name: scales_hasIdbDeflgky
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDeflgky
    alias: scales_hasIdbDeflgky
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbTsev3:
    name: scales_hasIdbTsev3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev3
    alias: scales_hasIdbTsev3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbCttrtrn:
    name: scales_hasIdbCttrtrn
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttrtrn
    alias: scales_hasIdbCttrtrn
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDisp3:
    name: scales_hasIdbDisp3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp3
    alias: scales_hasIdbDisp3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFineamt5:
    name: scales_hasIdbFineamt5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt5
    alias: scales_hasIdbFineamt5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFoffcd5:
    name: scales_hasIdbFoffcd5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd5
    alias: scales_hasIdbFoffcd5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbcd1:
    name: scales_hasIdbProbcd1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd1
    alias: scales_hasIdbProbcd1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbD2foffcd5:
    name: scales_hasIdbD2foffcd5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd5
    alias: scales_hasIdbD2foffcd5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbCtpnwof:
    name: scales_hasIdbCtpnwof
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtpnwof
    alias: scales_hasIdbCtpnwof
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFugstat:
    name: scales_hasIdbFugstat
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFugstat
    alias: scales_hasIdbFugstat
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  niem50_StatusDescriptionText:
    name: niem50_StatusDescriptionText
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: niem50:StatusDescriptionText
    alias: niem50_StatusDescriptionText
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbTofflvl2:
    name: scales_hasIdbTofflvl2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl2
    alias: scales_hasIdbTofflvl2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTofflvl5:
    name: scales_hasIdbTofflvl5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl5
    alias: scales_hasIdbTofflvl5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDefno:
    name: scales_hasIdbDefno
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDefno
    alias: scales_hasIdbDefno
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  niem50_JurisdictionText:
    name: niem50_JurisdictionText
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: niem50:JurisdictionText
    alias: niem50_JurisdictionText
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbCttrr:
    name: scales_hasIdbCttrr
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttrr
    alias: scales_hasIdbCttrr
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbmon1:
    name: scales_hasIdbProbmon1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon1
    alias: scales_hasIdbProbmon1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTofflvl3:
    name: scales_hasIdbTofflvl3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl3
    alias: scales_hasIdbTofflvl3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbPriscd2:
    name: scales_hasIdbPriscd2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd2
    alias: scales_hasIdbPriscd2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  niem50_StartDate:
    name: niem50_StartDate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: niem50:StartDate
    alias: niem50_StartDate
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: date
  scales_hasIdbSupvrel4:
    name: scales_hasIdbSupvrel4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel4
    alias: scales_hasIdbSupvrel4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasMemberCase:
    name: scales_hasMemberCase
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasMemberCase
    alias: scales_hasMemberCase
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: scales_CivilCase
  scales_hasIdbFsev1:
    name: scales_hasIdbFsev1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev1
    alias: scales_hasIdbFsev1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbInt2:
    name: scales_hasIdbInt2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbInt2
    alias: scales_hasIdbInt2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbPriscd4:
    name: scales_hasIdbPriscd4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd4
    alias: scales_hasIdbPriscd4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbIs_stub:
    name: scales_hasIdbIs_stub
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbIs_stub
    alias: scales_hasIdbIs_stub
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: boolean
  scales_hasIdbFiledate:
    name: scales_hasIdbFiledate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFiledate
    alias: scales_hasIdbFiledate
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: datetime
  scales_hasIdbToffcd5:
    name: scales_hasIdbToffcd5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd5
    alias: scales_hasIdbToffcd5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFineamt4:
    name: scales_hasIdbFineamt4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt4
    alias: scales_hasIdbFineamt4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDisp5:
    name: scales_hasIdbDisp5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp5
    alias: scales_hasIdbDisp5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbD2toffcd4:
    name: scales_hasIdbD2toffcd4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd4
    alias: scales_hasIdbD2toffcd4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTrandock:
    name: scales_hasIdbTrandock
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrandock
    alias: scales_hasIdbTrandock
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbCttr:
    name: scales_hasIdbCttr
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttr
    alias: scales_hasIdbCttr
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbUpdate:
    name: scales_hasIdbUpdate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbUpdate
    alias: scales_hasIdbUpdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  jxdm72_CaseJudge:
    name: jxdm72_CaseJudge
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: jxdm72:CaseJudge
    alias: jxdm72_CaseJudge
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: Any
    any_of:
    - range: jxdm72_CaseJudge
    - range: uri
  scales_hasIdbFofflvl5:
    name: scales_hasIdbFofflvl5
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl5
    alias: scales_hasIdbFofflvl5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbLoaddate:
    name: scales_hasIdbLoaddate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbLoaddate
    alias: scales_hasIdbLoaddate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbD2toffcd3:
    name: scales_hasIdbD2toffcd3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd3
    alias: scales_hasIdbD2toffcd3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_Party:
    name: scales_Party
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:Party
    alias: scales_Party
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: scales_Party
  scales_hasIdbFgenddate:
    name: scales_hasIdbFgenddate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFgenddate
    alias: scales_hasIdbFgenddate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbTtitle2:
    name: scales_hasIdbTtitle2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle2
    alias: scales_hasIdbTtitle2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbFineamt2:
    name: scales_hasIdbFineamt2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt2
    alias: scales_hasIdbFineamt2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbPristim2:
    name: scales_hasIdbPristim2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim2
    alias: scales_hasIdbPristim2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbCtdef:
    name: scales_hasIdbCtdef
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtdef
    alias: scales_hasIdbCtdef
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  jxdm72_CaseDefendantParty:
    name: jxdm72_CaseDefendantParty
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: jxdm72:CaseDefendantParty
    alias: jxdm72_CaseDefendantParty
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: Any
    any_of:
    - range: jxdm72_CaseDefendantParty
    - range: scales_Party
  scales_hasIdbToffcd4:
    name: scales_hasIdbToffcd4
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd4
    alias: scales_hasIdbToffcd4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbmon2:
    name: scales_hasIdbProbmon2
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon2
    alias: scales_hasIdbProbmon2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbSentdate:
    name: scales_hasIdbSentdate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSentdate
    alias: scales_hasIdbSentdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbFsev3:
    name: scales_hasIdbFsev3
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev3
    alias: scales_hasIdbFsev3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbD2toffcd1:
    name: scales_hasIdbD2toffcd1
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd1
    alias: scales_hasIdbD2toffcd1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
class_uri: scales:CriminalCase

```
</details>