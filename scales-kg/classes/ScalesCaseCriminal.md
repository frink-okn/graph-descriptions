

# Class: TODO -- what's a good name for this class (type)? (scales_CaseCriminal)


_No type description provided_





URI: [scales:CaseCriminal](http://schemas.scales-okn.org/rdf/scales#CaseCriminal)






```mermaid
 classDiagram
    class ScalesCaseCriminal
    click ScalesCaseCriminal href "../ScalesCaseCriminal"
      ScalesCaseCriminal : scales_hasAgent
        
          
    
    
    ScalesCaseCriminal --> "0..1" ScalesAgent : scales_hasAgent
    click ScalesAgent href "../ScalesAgent"

        
      ScalesCaseCriminal : scales_hasCharge
        
          
    
    
    ScalesCaseCriminal --> "0..1" ScalesCharge : scales_hasCharge
    click ScalesCharge href "../ScalesCharge"

        
      ScalesCaseCriminal : scales_hasDocketTable
        
          
    
    
    ScalesCaseCriminal --> "0..1" ScalesDocketTable : scales_hasDocketTable
    click ScalesDocketTable href "../ScalesDocketTable"

        
      ScalesCaseCriminal : scales_hasFilingDate
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasFilingDate
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbAppcd
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbAppcd
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbAppdate
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbAppdate
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbCaslgky
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbCaslgky
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbCircuit
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbCircuit
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbCounty
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbCounty
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbCtdef
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbCtdef
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbCtfil
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbCtfil
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbCtfilr
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbCtfilr
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbCtfiltrn
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbCtfiltrn
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbCtfilwor
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbCtfilwor
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbCtpn
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbCtpn
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbCtpnwof
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbCtpnwof
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbCttr
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbCttr
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbCttrr
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbCttrr
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbCttrtrn
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbCttrtrn
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbCttrwor
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbCttrwor
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbD2foffcd1
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbD2foffcd1
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbD2foffcd2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbD2foffcd2
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbD2foffcd3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbD2foffcd3
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbD2foffcd4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbD2foffcd4
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbD2foffcd5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbD2foffcd5
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbD2toffcd1
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbD2toffcd1
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbD2toffcd2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbD2toffcd2
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbD2toffcd3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbD2toffcd3
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbD2toffcd4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbD2toffcd4
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbD2toffcd5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbD2toffcd5
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbDeflgky
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbDeflgky
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbDefno
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbDefno
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbDisp1
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbDisp1
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbDisp2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbDisp2
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbDisp3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbDisp3
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbDisp4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbDisp4
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbDisp5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbDisp5
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbDispdate
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbDispdate
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbDistrict
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbDistrict
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbDocket
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbDocket
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbFcounsel
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFcounsel
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFgenddate
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbFgenddate
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbFgstrtdate
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbFgstrtdate
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbFiledate
        
          
    
    
    ScalesCaseCriminal --> "0..1" Datetime : scales_hasIdbFiledate
    click Datetime href "../Datetime"

        
      ScalesCaseCriminal : scales_hasIdbFineamt1
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFineamt1
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFineamt2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFineamt2
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFineamt3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFineamt3
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFineamt4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFineamt4
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFineamt5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFineamt5
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFinetot
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFinetot
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFiscalyr
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFiscalyr
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFoffcd1
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFoffcd1
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFoffcd2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFoffcd2
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFoffcd3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFoffcd3
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFoffcd4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFoffcd4
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFoffcd5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFoffcd5
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFofflvl1
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFofflvl1
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFofflvl2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFofflvl2
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFofflvl3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFofflvl3
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFofflvl4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFofflvl4
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFofflvl5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbFofflvl5
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbFsev1
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbFsev1
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbFsev2
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbFsev2
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbFsev3
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbFsev3
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbFsev4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbFsev4
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbFsev5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbFsev5
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbFtitle1
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbFtitle1
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbFtitle2
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbFtitle2
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbFtitle3
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbFtitle3
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbFtitle4
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbFtitle4
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbFtitle5
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbFtitle5
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbFugstat
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbFugstat
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbInt1
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbInt1
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbInt2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbInt2
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbInt3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbInt3
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbIs_stub
        
          
    
    
    ScalesCaseCriminal --> "0..1" Boolean : scales_hasIdbIs_stub
    click Boolean href "../Boolean"

        
      ScalesCaseCriminal : scales_hasIdbLoaddate
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbLoaddate
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbMagdef
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbMagdef
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbMagdock
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbMagdock
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbOffice
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbOffice
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbPriscd1
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbPriscd1
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbPriscd2
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbPriscd2
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbPriscd3
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbPriscd3
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbPriscd4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbPriscd4
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbPriscd5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbPriscd5
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbPristim1
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbPristim1
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbPristim2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbPristim2
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbPristim3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbPristim3
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbPristim4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbPristim4
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbPristim5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbPristim5
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbPristot
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbPristot
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbProbcd1
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbProbcd1
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbProbcd2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbProbcd2
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbProbcd3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbProbcd3
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbProbcd4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbProbcd4
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbProbcd5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbProbcd5
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbProbmon1
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbProbmon1
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbProbmon2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbProbmon2
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbProbmon3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbProbmon3
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbProbmon4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbProbmon4
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbProbmon5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbProbmon5
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbProbtot
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbProbtot
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbProccd
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbProccd
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbProcdate
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbProcdate
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbReopseq
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbReopseq
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbSentdate
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbSentdate
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbStatuscd
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbStatuscd
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbSupvrel1
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbSupvrel1
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbSupvrel2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbSupvrel2
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbSupvrel3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbSupvrel3
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbSupvrel4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbSupvrel4
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbSupvrel5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbSupvrel5
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbTapeyear
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbTapeyear
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbTcounsel
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbTcounsel
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbTermdate
        
          
    
    
    ScalesCaseCriminal --> "0..1" Datetime : scales_hasIdbTermdate
    click Datetime href "../Datetime"

        
      ScalesCaseCriminal : scales_hasIdbTermoff
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbTermoff
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbToffcd1
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbToffcd1
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbToffcd2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbToffcd2
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbToffcd3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbToffcd3
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbToffcd4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbToffcd4
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbToffcd5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbToffcd5
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbTofflvl1
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbTofflvl1
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbTofflvl2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbTofflvl2
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbTofflvl3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbTofflvl3
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbTofflvl4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbTofflvl4
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbTofflvl5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbTofflvl5
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbTrandef
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbTrandef
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbTrandist
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbTrandist
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbTrandock
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbTrandock
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasIdbTranoff
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbTranoff
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbTsev1
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbTsev1
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbTsev2
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbTsev2
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbTsev3
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbTsev3
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbTsev4
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbTsev4
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbTsev5
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbTsev5
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbTtitle1
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbTtitle1
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbTtitle2
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbTtitle2
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbTtitle3
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbTtitle3
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbTtitle4
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbTtitle4
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbTtitle5
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbTtitle5
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbTypemag
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbTypemag
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbTypereg
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbTypereg
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbTypetrn
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasIdbTypetrn
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasIdbUpdate
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasIdbUpdate
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasIdbVer
        
          
    
    
    ScalesCaseCriminal --> "0..1" Double : scales_hasIdbVer
    click Double href "../Double"

        
      ScalesCaseCriminal : scales_hasJurisdiction
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasJurisdiction
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasMemberCase
        
          
    
    
    ScalesCaseCriminal --> "0..1" ScalesCaseCivil : scales_hasMemberCase
    click ScalesCaseCivil href "../ScalesCaseCivil"

        
      ScalesCaseCriminal : scales_hasPacerID
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasPacerID
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasRelatedCase
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasRelatedCase
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_hasStatus
        
          
    
    
    ScalesCaseCriminal --> "0..1" String : scales_hasStatus
    click String href "../String"

        
      ScalesCaseCriminal : scales_hasTerminatingDate
        
          
    
    
    ScalesCaseCriminal --> "0..1" Any : scales_hasTerminatingDate
    click Any href "../Any"

        
      ScalesCaseCriminal : scales_isInCourt
        
          
    
    
    ScalesCaseCriminal --> "0..1" ScalesCourt : scales_isInCourt
    click ScalesCourt href "../ScalesCourt"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [scales_hasIdbProbtot](../slots/scales_hasIdbProbtot.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFofflvl2](../slots/scales_hasIdbFofflvl2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbDisp1](../slots/scales_hasIdbDisp1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFtitle3](../slots/scales_hasIdbFtitle3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbDisp4](../slots/scales_hasIdbDisp4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTapeyear](../slots/scales_hasIdbTapeyear.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbDisp2](../slots/scales_hasIdbDisp2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbProbmon2](../slots/scales_hasIdbProbmon2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbVer](../slots/scales_hasIdbVer.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[ScalesCaseCivil](../classes/ScalesCaseCivil.md)&nbsp;or&nbsp;<br />[ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | No slot description provided | direct |
| [scales_hasIdbCtfilwor](../slots/scales_hasIdbCtfilwor.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTsev2](../slots/scales_hasIdbTsev2.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFcounsel](../slots/scales_hasIdbFcounsel.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbMagdock](../slots/scales_hasIdbMagdock.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbSupvrel2](../slots/scales_hasIdbSupvrel2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbDeflgky](../slots/scales_hasIdbDeflgky.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbCttrr](../slots/scales_hasIdbCttrr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbDispdate](../slots/scales_hasIdbDispdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbCtdef](../slots/scales_hasIdbCtdef.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFoffcd3](../slots/scales_hasIdbFoffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbDocket](../slots/scales_hasIdbDocket.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbPristim4](../slots/scales_hasIdbPristim4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbProbmon3](../slots/scales_hasIdbProbmon3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFineamt2](../slots/scales_hasIdbFineamt2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFgenddate](../slots/scales_hasIdbFgenddate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFgstrtdate](../slots/scales_hasIdbFgstrtdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFineamt1](../slots/scales_hasIdbFineamt1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbD2foffcd1](../slots/scales_hasIdbD2foffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTsev1](../slots/scales_hasIdbTsev1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbTypemag](../slots/scales_hasIdbTypemag.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbTtitle5](../slots/scales_hasIdbTtitle5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbCttrtrn](../slots/scales_hasIdbCttrtrn.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbD2toffcd2](../slots/scales_hasIdbD2toffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTrandef](../slots/scales_hasIdbTrandef.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbCttrwor](../slots/scales_hasIdbCttrwor.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbPriscd5](../slots/scales_hasIdbPriscd5.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbD2foffcd4](../slots/scales_hasIdbD2foffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbToffcd2](../slots/scales_hasIdbToffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbCtfilr](../slots/scales_hasIdbCtfilr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFsev1](../slots/scales_hasIdbFsev1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFofflvl1](../slots/scales_hasIdbFofflvl1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbAppcd](../slots/scales_hasIdbAppcd.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFiscalyr](../slots/scales_hasIdbFiscalyr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTtitle2](../slots/scales_hasIdbTtitle2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbSentdate](../slots/scales_hasIdbSentdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbInt1](../slots/scales_hasIdbInt1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTtitle3](../slots/scales_hasIdbTtitle3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasStatus](../slots/scales_hasStatus.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbIs_stub](../slots/scales_hasIdbIs_stub.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) | No slot description provided | direct |
| [scales_hasIdbFsev5](../slots/scales_hasIdbFsev5.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasMemberCase](../slots/scales_hasMemberCase.md) | 0..1 <br/> [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | No slot description provided | direct |
| [scales_hasIdbTypereg](../slots/scales_hasIdbTypereg.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbProbcd2](../slots/scales_hasIdbProbcd2.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbInt2](../slots/scales_hasIdbInt2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbProbcd5](../slots/scales_hasIdbProbcd5.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbCttr](../slots/scales_hasIdbCttr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbToffcd4](../slots/scales_hasIdbToffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFiledate](../slots/scales_hasIdbFiledate.md) | 0..1 <br/> [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime) | No slot description provided | direct |
| [scales_hasIdbMagdef](../slots/scales_hasIdbMagdef.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbPriscd4](../slots/scales_hasIdbPriscd4.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbTofflvl4](../slots/scales_hasIdbTofflvl4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTypetrn](../slots/scales_hasIdbTypetrn.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbCounty](../slots/scales_hasIdbCounty.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbD2toffcd1](../slots/scales_hasIdbD2toffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasCharge](../slots/scales_hasCharge.md) | 0..1 <br/> [ScalesCharge](../classes/ScalesCharge.md) | No slot description provided | direct |
| [scales_hasIdbFtitle5](../slots/scales_hasIdbFtitle5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasDocketTable](../slots/scales_hasDocketTable.md) | 0..1 <br/> [ScalesDocketTable](../classes/ScalesDocketTable.md) | No slot description provided | direct |
| [scales_hasIdbInt3](../slots/scales_hasIdbInt3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbDisp3](../slots/scales_hasIdbDisp3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFsev4](../slots/scales_hasIdbFsev4.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbTermdate](../slots/scales_hasIdbTermdate.md) | 0..1 <br/> [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime) | No slot description provided | direct |
| [scales_hasFilingDate](../slots/scales_hasFilingDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFinetot](../slots/scales_hasIdbFinetot.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbPristim5](../slots/scales_hasIdbPristim5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFineamt4](../slots/scales_hasIdbFineamt4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbProbcd1](../slots/scales_hasIdbProbcd1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbTofflvl1](../slots/scales_hasIdbTofflvl1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbPristim1](../slots/scales_hasIdbPristim1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasPacerID](../slots/scales_hasPacerID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbTcounsel](../slots/scales_hasIdbTcounsel.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbD2toffcd4](../slots/scales_hasIdbD2toffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbCtpnwof](../slots/scales_hasIdbCtpnwof.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbProccd](../slots/scales_hasIdbProccd.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFoffcd2](../slots/scales_hasIdbFoffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTrandist](../slots/scales_hasIdbTrandist.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFoffcd4](../slots/scales_hasIdbFoffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbCaslgky](../slots/scales_hasIdbCaslgky.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbSupvrel5](../slots/scales_hasIdbSupvrel5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasAgent](../slots/scales_hasAgent.md) | 0..1 <br/> [ScalesAgent](../classes/ScalesAgent.md) | No slot description provided | direct |
| [scales_hasIdbToffcd5](../slots/scales_hasIdbToffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTsev5](../slots/scales_hasIdbTsev5.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbDefno](../slots/scales_hasIdbDefno.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFsev2](../slots/scales_hasIdbFsev2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbProbcd3](../slots/scales_hasIdbProbcd3.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbD2foffcd3](../slots/scales_hasIdbD2foffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbPristim3](../slots/scales_hasIdbPristim3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFtitle2](../slots/scales_hasIdbFtitle2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFoffcd1](../slots/scales_hasIdbFoffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbProbcd4](../slots/scales_hasIdbProbcd4.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbReopseq](../slots/scales_hasIdbReopseq.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTofflvl3](../slots/scales_hasIdbTofflvl3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTtitle1](../slots/scales_hasIdbTtitle1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbD2foffcd2](../slots/scales_hasIdbD2foffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbStatuscd](../slots/scales_hasIdbStatuscd.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbAppdate](../slots/scales_hasIdbAppdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbToffcd3](../slots/scales_hasIdbToffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbProbmon4](../slots/scales_hasIdbProbmon4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbProcdate](../slots/scales_hasIdbProcdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFineamt5](../slots/scales_hasIdbFineamt5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTsev4](../slots/scales_hasIdbTsev4.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbPriscd3](../slots/scales_hasIdbPriscd3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFsev3](../slots/scales_hasIdbFsev3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbToffcd1](../slots/scales_hasIdbToffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTsev3](../slots/scales_hasIdbTsev3.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbD2toffcd5](../slots/scales_hasIdbD2toffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbPristim2](../slots/scales_hasIdbPristim2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbSupvrel4](../slots/scales_hasIdbSupvrel4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_isInCourt](../slots/scales_isInCourt.md) | 0..1 <br/> [ScalesCourt](../classes/ScalesCourt.md) | No slot description provided | direct |
| [scales_hasIdbTrandock](../slots/scales_hasIdbTrandock.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbProbmon1](../slots/scales_hasIdbProbmon1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFtitle1](../slots/scales_hasIdbFtitle1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbCtfiltrn](../slots/scales_hasIdbCtfiltrn.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTermoff](../slots/scales_hasIdbTermoff.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFofflvl4](../slots/scales_hasIdbFofflvl4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbPriscd1](../slots/scales_hasIdbPriscd1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFtitle4](../slots/scales_hasIdbFtitle4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFoffcd5](../slots/scales_hasIdbFoffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbLoaddate](../slots/scales_hasIdbLoaddate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbTofflvl5](../slots/scales_hasIdbTofflvl5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbOffice](../slots/scales_hasIdbOffice.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbTtitle4](../slots/scales_hasIdbTtitle4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbDistrict](../slots/scales_hasIdbDistrict.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbSupvrel1](../slots/scales_hasIdbSupvrel1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTranoff](../slots/scales_hasIdbTranoff.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbCtpn](../slots/scales_hasIdbCtpn.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbProbmon5](../slots/scales_hasIdbProbmon5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasTerminatingDate](../slots/scales_hasTerminatingDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbD2toffcd3](../slots/scales_hasIdbD2toffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbUpdate](../slots/scales_hasIdbUpdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFugstat](../slots/scales_hasIdbFugstat.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbCircuit](../slots/scales_hasIdbCircuit.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasJurisdiction](../slots/scales_hasJurisdiction.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbPriscd2](../slots/scales_hasIdbPriscd2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [scales_hasIdbFineamt3](../slots/scales_hasIdbFineamt3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFofflvl5](../slots/scales_hasIdbFofflvl5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbTofflvl2](../slots/scales_hasIdbTofflvl2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbD2foffcd5](../slots/scales_hasIdbD2foffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbSupvrel3](../slots/scales_hasIdbSupvrel3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbDisp5](../slots/scales_hasIdbDisp5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbCtfil](../slots/scales_hasIdbCtfil.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbFofflvl3](../slots/scales_hasIdbFofflvl3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |
| [scales_hasIdbPristot](../slots/scales_hasIdbPristot.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot description provided | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | any_of[range] | [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | any_of[range] | [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) |






## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:CaseCriminal |
| native | scales-kg/:ScalesCaseCriminal |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: scales_CaseCriminal
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 127619 occurences.
from_schema: scales-kg
rank: 1000
slots:
- scales_hasIdbProbtot
- scales_hasIdbFofflvl2
- scales_hasIdbDisp1
- scales_hasIdbFtitle3
- scales_hasIdbDisp4
- scales_hasIdbTapeyear
- scales_hasIdbDisp2
- scales_hasIdbProbmon2
- scales_hasIdbVer
- scales_hasRelatedCase
- scales_hasIdbCtfilwor
- scales_hasIdbTsev2
- scales_hasIdbFcounsel
- scales_hasIdbMagdock
- scales_hasIdbSupvrel2
- scales_hasIdbDeflgky
- scales_hasIdbCttrr
- scales_hasIdbDispdate
- scales_hasIdbCtdef
- scales_hasIdbFoffcd3
- scales_hasIdbDocket
- scales_hasIdbPristim4
- scales_hasIdbProbmon3
- scales_hasIdbFineamt2
- scales_hasIdbFgenddate
- scales_hasIdbFgstrtdate
- scales_hasIdbFineamt1
- scales_hasIdbD2foffcd1
- scales_hasIdbTsev1
- scales_hasIdbTypemag
- scales_hasIdbTtitle5
- scales_hasIdbCttrtrn
- scales_hasIdbD2toffcd2
- scales_hasIdbTrandef
- scales_hasIdbCttrwor
- scales_hasIdbPriscd5
- scales_hasIdbD2foffcd4
- scales_hasIdbToffcd2
- scales_hasIdbCtfilr
- scales_hasIdbFsev1
- scales_hasIdbFofflvl1
- scales_hasIdbAppcd
- scales_hasIdbFiscalyr
- scales_hasIdbTtitle2
- scales_hasIdbSentdate
- scales_hasIdbInt1
- scales_hasIdbTtitle3
- scales_hasStatus
- scales_hasIdbIs_stub
- scales_hasIdbFsev5
- scales_hasMemberCase
- scales_hasIdbTypereg
- scales_hasIdbProbcd2
- scales_hasIdbInt2
- scales_hasIdbProbcd5
- scales_hasIdbCttr
- scales_hasIdbToffcd4
- scales_hasIdbFiledate
- scales_hasIdbMagdef
- scales_hasIdbPriscd4
- scales_hasIdbTofflvl4
- scales_hasIdbTypetrn
- scales_hasIdbCounty
- scales_hasIdbD2toffcd1
- scales_hasCharge
- scales_hasIdbFtitle5
- scales_hasDocketTable
- scales_hasIdbInt3
- scales_hasIdbDisp3
- scales_hasIdbFsev4
- scales_hasIdbTermdate
- scales_hasFilingDate
- scales_hasIdbFinetot
- scales_hasIdbPristim5
- scales_hasIdbFineamt4
- scales_hasIdbProbcd1
- scales_hasIdbTofflvl1
- scales_hasIdbPristim1
- scales_hasPacerID
- scales_hasIdbTcounsel
- scales_hasIdbD2toffcd4
- scales_hasIdbCtpnwof
- scales_hasIdbProccd
- scales_hasIdbFoffcd2
- scales_hasIdbTrandist
- scales_hasIdbFoffcd4
- scales_hasIdbCaslgky
- scales_hasIdbSupvrel5
- scales_hasAgent
- scales_hasIdbToffcd5
- scales_hasIdbTsev5
- scales_hasIdbDefno
- scales_hasIdbFsev2
- scales_hasIdbProbcd3
- scales_hasIdbD2foffcd3
- scales_hasIdbPristim3
- scales_hasIdbFtitle2
- scales_hasIdbFoffcd1
- scales_hasIdbProbcd4
- scales_hasIdbReopseq
- scales_hasIdbTofflvl3
- scales_hasIdbTtitle1
- scales_hasIdbD2foffcd2
- scales_hasIdbStatuscd
- scales_hasIdbAppdate
- scales_hasIdbToffcd3
- scales_hasIdbProbmon4
- scales_hasIdbProcdate
- scales_hasIdbFineamt5
- scales_hasIdbTsev4
- scales_hasIdbPriscd3
- scales_hasIdbFsev3
- scales_hasIdbToffcd1
- scales_hasIdbTsev3
- scales_hasIdbD2toffcd5
- scales_hasIdbPristim2
- scales_hasIdbSupvrel4
- scales_isInCourt
- scales_hasIdbTrandock
- scales_hasIdbProbmon1
- scales_hasIdbFtitle1
- scales_hasIdbCtfiltrn
- scales_hasIdbTermoff
- scales_hasIdbFofflvl4
- scales_hasIdbPriscd1
- scales_hasIdbFtitle4
- scales_hasIdbFoffcd5
- scales_hasIdbLoaddate
- scales_hasIdbTofflvl5
- scales_hasIdbOffice
- scales_hasIdbTtitle4
- scales_hasIdbDistrict
- scales_hasIdbSupvrel1
- scales_hasIdbTranoff
- scales_hasIdbCtpn
- scales_hasIdbProbmon5
- scales_hasTerminatingDate
- scales_hasIdbD2toffcd3
- scales_hasIdbUpdate
- scales_hasIdbFugstat
- scales_hasIdbCircuit
- scales_hasJurisdiction
- scales_hasIdbPriscd2
- scales_hasIdbFineamt3
- scales_hasIdbFofflvl5
- scales_hasIdbTofflvl2
- scales_hasIdbD2foffcd5
- scales_hasIdbSupvrel3
- scales_hasIdbDisp5
- scales_hasIdbCtfil
- scales_hasIdbFofflvl3
- scales_hasIdbPristot
class_uri: scales:CaseCriminal

```
</details>

### Induced

<details>
```yaml
name: scales_CaseCriminal
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 127619 occurences.
from_schema: scales-kg
rank: 1000
attributes:
  scales_hasIdbProbtot:
    name: scales_hasIdbProbtot
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProbtot -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbtot
    alias: scales_hasIdbProbtot
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFofflvl2:
    name: scales_hasIdbFofflvl2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFofflvl2 4.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl2
    alias: scales_hasIdbFofflvl2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbDisp1:
    name: scales_hasIdbDisp1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDisp1 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp1
    alias: scales_hasIdbDisp1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFtitle3:
    name: scales_hasIdbFtitle3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFtitle3 18:922G.F
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle3
    alias: scales_hasIdbFtitle3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbDisp4:
    name: scales_hasIdbDisp4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDisp4 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp4
    alias: scales_hasIdbDisp4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTapeyear:
    name: scales_hasIdbTapeyear
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 551088 occurrences with subject type scales_CaseCivil and object type double.
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbTapeyear 2019.0
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTapeyear 2099.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTapeyear
    alias: scales_hasIdbTapeyear
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: double
  scales_hasIdbDisp2:
    name: scales_hasIdbDisp2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDisp2 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp2
    alias: scales_hasIdbDisp2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbProbmon2:
    name: scales_hasIdbProbmon2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProbmon2 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon2
    alias: scales_hasIdbProbmon2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbVer:
    name: scales_hasIdbVer
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbVer 1.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbVer
    alias: scales_hasIdbVer
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasRelatedCase:
    name: scales_hasRelatedCase
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 64461 occurrences with subject type scales_CaseCivil and object type scales_CaseCivil.
    - 54514 occurrences with subject type scales_CaseCivil and object type uri.
    - 1 occurrences with subject type scales_CaseCivil and object type scales_CaseCriminal.
    - 3203 occurrences with subject type scales_CaseCriminal and object type uri.
    - 337 occurrences with subject type scales_CaseCriminal and object type scales_CaseCivil.
    examples:
    - value: scales:CaseCivil/wyd;;2:17-cv-00025 scales:hasRelatedCase scales:CaseCivil/wyd;;1:16-cv-00148
    - value: scales:CaseCivil/akd;;3:16-cv-00293 scales:hasRelatedCase scales:CaseCivil/akd;;3:18-cv-00303
    - value: scales:CaseCivil/iand;;1:17-cv-00106 scales:hasRelatedCase scales:CaseCriminal/iand;;1:17-cr-00012
    - value: scales:CaseCriminal/alsd;;1:16-cr-00008 scales:hasRelatedCase scales:CaseCivil/alsd;;1:18-cv-00296
    - value: scales:CaseCriminal/wvnd;;3:16-cr-00010 scales:hasRelatedCase scales:CaseCivil/wvnd;;3:17-cv-00111
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasRelatedCase
    alias: scales_hasRelatedCase
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: uri
    - range: scales_CaseCivil
    - range: scales_CaseCriminal
  scales_hasIdbCtfilwor:
    name: scales_hasIdbCtfilwor
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCtfilwor 1.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfilwor
    alias: scales_hasIdbCtfilwor
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTsev2:
    name: scales_hasIdbTsev2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 104516 occurrences with subject type scales_CaseCriminal and object type string.
    - 7066 occurrences with subject type scales_CaseCriminal and object type integer.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTsev2 -8
    - value: scales:CaseCriminal/txsd;;2:17-cr-00501 scales:hasIdbTsev2 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev2
    alias: scales_hasIdbTsev2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbFcounsel:
    name: scales_hasIdbFcounsel
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFcounsel 6.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFcounsel
    alias: scales_hasIdbFcounsel
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbMagdock:
    name: scales_hasIdbMagdock
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbMagdock -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbMagdock
    alias: scales_hasIdbMagdock
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbSupvrel2:
    name: scales_hasIdbSupvrel2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbSupvrel2 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel2
    alias: scales_hasIdbSupvrel2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbDeflgky:
    name: scales_hasIdbDeflgky
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDeflgky 086211700012CR0010
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDeflgky
    alias: scales_hasIdbDeflgky
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbCttrr:
    name: scales_hasIdbCttrr
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCttrr 0.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttrr
    alias: scales_hasIdbCttrr
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbDispdate:
    name: scales_hasIdbDispdate
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDispdate 01/01/1900
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDispdate
    alias: scales_hasIdbDispdate
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbCtdef:
    name: scales_hasIdbCtdef
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCtdef 1.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtdef
    alias: scales_hasIdbCtdef
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFoffcd3:
    name: scales_hasIdbFoffcd3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFoffcd3 7830.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd3
    alias: scales_hasIdbFoffcd3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbDocket:
    name: scales_hasIdbDocket
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 551088 occurrences with subject type scales_CaseCivil and object type string.
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbDocket 1600009
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDocket 1700012
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDocket
    alias: scales_hasIdbDocket
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: string
  scales_hasIdbPristim4:
    name: scales_hasIdbPristim4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbPristim4 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim4
    alias: scales_hasIdbPristim4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbProbmon3:
    name: scales_hasIdbProbmon3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProbmon3 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon3
    alias: scales_hasIdbProbmon3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFineamt2:
    name: scales_hasIdbFineamt2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFineamt2 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt2
    alias: scales_hasIdbFineamt2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFgenddate:
    name: scales_hasIdbFgenddate
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFgenddate 01/01/1900
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFgenddate
    alias: scales_hasIdbFgenddate
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbFgstrtdate:
    name: scales_hasIdbFgstrtdate
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFgstrtdate 01/01/1900
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFgstrtdate
    alias: scales_hasIdbFgstrtdate
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbFineamt1:
    name: scales_hasIdbFineamt1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFineamt1 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt1
    alias: scales_hasIdbFineamt1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbD2foffcd1:
    name: scales_hasIdbD2foffcd1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbD2foffcd1 6801.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd1
    alias: scales_hasIdbD2foffcd1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTsev1:
    name: scales_hasIdbTsev1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTsev1 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev1
    alias: scales_hasIdbTsev1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbTypemag:
    name: scales_hasIdbTypemag
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTypemag -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTypemag
    alias: scales_hasIdbTypemag
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbTtitle5:
    name: scales_hasIdbTtitle5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTtitle5 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle5
    alias: scales_hasIdbTtitle5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbCttrtrn:
    name: scales_hasIdbCttrtrn
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCttrtrn 0.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttrtrn
    alias: scales_hasIdbCttrtrn
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbD2toffcd2:
    name: scales_hasIdbD2toffcd2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbD2toffcd2 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd2
    alias: scales_hasIdbD2toffcd2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTrandef:
    name: scales_hasIdbTrandef
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTrandef -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrandef
    alias: scales_hasIdbTrandef
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbCttrwor:
    name: scales_hasIdbCttrwor
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCttrwor 0.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttrwor
    alias: scales_hasIdbCttrwor
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbPriscd5:
    name: scales_hasIdbPriscd5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 53626 occurrences with subject type scales_CaseCriminal and object type integer.
    - 57956 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbPriscd5 -8
    - value: scales:CaseCriminal/akd;;1:17-cr-00001 scales:hasIdbPriscd5 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd5
    alias: scales_hasIdbPriscd5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbD2foffcd4:
    name: scales_hasIdbD2foffcd4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbD2foffcd4 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd4
    alias: scales_hasIdbD2foffcd4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbToffcd2:
    name: scales_hasIdbToffcd2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbToffcd2 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd2
    alias: scales_hasIdbToffcd2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbCtfilr:
    name: scales_hasIdbCtfilr
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCtfilr 0.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfilr
    alias: scales_hasIdbCtfilr
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFsev1:
    name: scales_hasIdbFsev1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFsev1 839
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev1
    alias: scales_hasIdbFsev1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbFofflvl1:
    name: scales_hasIdbFofflvl1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFofflvl1 4.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl1
    alias: scales_hasIdbFofflvl1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbAppcd:
    name: scales_hasIdbAppcd
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbAppcd -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbAppcd
    alias: scales_hasIdbAppcd
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbFiscalyr:
    name: scales_hasIdbFiscalyr
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFiscalyr 2017.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFiscalyr
    alias: scales_hasIdbFiscalyr
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTtitle2:
    name: scales_hasIdbTtitle2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTtitle2 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle2
    alias: scales_hasIdbTtitle2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbSentdate:
    name: scales_hasIdbSentdate
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbSentdate 01/01/1900
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSentdate
    alias: scales_hasIdbSentdate
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbInt1:
    name: scales_hasIdbInt1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbInt1 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbInt1
    alias: scales_hasIdbInt1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTtitle3:
    name: scales_hasIdbTtitle3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTtitle3 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle3
    alias: scales_hasIdbTtitle3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasStatus:
    name: scales_hasStatus
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 561182 occurrences with subject type scales_CaseCivil and object type string.
    - 127619 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasStatus closed
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasStatus closed
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasStatus
    alias: scales_hasStatus
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: string
  scales_hasIdbIs_stub:
    name: scales_hasIdbIs_stub
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 551088 occurrences with subject type scales_CaseCivil and object type boolean.
    - 111582 occurrences with subject type scales_CaseCriminal and object type boolean.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbIs_stub false
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbIs_stub false
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbIs_stub
    alias: scales_hasIdbIs_stub
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: boolean
  scales_hasIdbFsev5:
    name: scales_hasIdbFsev5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 108070 occurrences with subject type scales_CaseCriminal and object type string.
    - 3512 occurrences with subject type scales_CaseCriminal and object type integer.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFsev5 -8
    - value: scales:CaseCriminal/txsd;;4:16-cr-00241 scales:hasIdbFsev5 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev5
    alias: scales_hasIdbFsev5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasMemberCase:
    name: scales_hasMemberCase
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 72187 occurrences with untyped subjects and object type http://schemas.scales-okn.org/rdf/scales#CaseCivil.
    - 3609 occurrences with subject type scales_CaseCivil and object type scales_CaseCivil.
    - 1 occurrences with subject type scales_CaseCriminal and object type scales_CaseCivil.
    examples:
    - value: scales:CaseOther/wvsd;;2:13-md-02440 scales:hasMemberCase scales:CaseCivil/wvsd;;2:16-cv-10447
    - value: scales:CaseCivil/wyd;;2:17-cv-00014 scales:hasMemberCase scales:CaseCivil/wyd;;2:17-cv-00023
    - value: scales:CaseCriminal/ohsd;;1:16-cr-00004 scales:hasMemberCase scales:CaseCivil/ohsd;;1:16-cv-00014
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasMemberCase
    alias: scales_hasMemberCase
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: scales_CaseCivil
  scales_hasIdbTypereg:
    name: scales_hasIdbTypereg
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTypereg CR
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTypereg
    alias: scales_hasIdbTypereg
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbProbcd2:
    name: scales_hasIdbProbcd2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 104617 occurrences with subject type scales_CaseCriminal and object type string.
    - 6965 occurrences with subject type scales_CaseCriminal and object type integer.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProbcd2 -8
    - value: scales:CaseCriminal/casd;;3:17-cr-00163 scales:hasIdbProbcd2 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd2
    alias: scales_hasIdbProbcd2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbInt2:
    name: scales_hasIdbInt2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbInt2 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbInt2
    alias: scales_hasIdbInt2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbProbcd5:
    name: scales_hasIdbProbcd5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 102604 occurrences with subject type scales_CaseCriminal and object type integer.
    - 8978 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProbcd5 -8
    - value: scales:CaseCriminal/akd;;1:17-cr-00015 scales:hasIdbProbcd5 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd5
    alias: scales_hasIdbProbcd5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbCttr:
    name: scales_hasIdbCttr
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCttr 0.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttr
    alias: scales_hasIdbCttr
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbToffcd4:
    name: scales_hasIdbToffcd4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbToffcd4 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd4
    alias: scales_hasIdbToffcd4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFiledate:
    name: scales_hasIdbFiledate
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 551088 occurrences with subject type scales_CaseCivil and object type datetime.
    - 111582 occurrences with subject type scales_CaseCriminal and object type datetime.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbFiledate 2016-04-15T00:00:00
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFiledate 2017-03-02T00:00:00
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFiledate
    alias: scales_hasIdbFiledate
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: datetime
  scales_hasIdbMagdef:
    name: scales_hasIdbMagdef
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbMagdef -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbMagdef
    alias: scales_hasIdbMagdef
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbPriscd4:
    name: scales_hasIdbPriscd4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 95754 occurrences with subject type scales_CaseCriminal and object type string.
    - 15828 occurrences with subject type scales_CaseCriminal and object type integer.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbPriscd4 -8
    - value: scales:CaseCriminal/azd;;4:16-cr-01355 scales:hasIdbPriscd4 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd4
    alias: scales_hasIdbPriscd4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbTofflvl4:
    name: scales_hasIdbTofflvl4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTofflvl4 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl4
    alias: scales_hasIdbTofflvl4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTypetrn:
    name: scales_hasIdbTypetrn
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 81005 occurrences with subject type scales_CaseCriminal and object type string.
    - 30577 occurrences with subject type scales_CaseCriminal and object type integer.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTypetrn -8
    - value: scales:CaseCriminal/almd;;1:16-cr-00441 scales:hasIdbTypetrn -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTypetrn
    alias: scales_hasIdbTypetrn
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbCounty:
    name: scales_hasIdbCounty
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 551088 occurrences with subject type scales_CaseCivil and object type double.
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbCounty 2110.0
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCounty 19113.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCounty
    alias: scales_hasIdbCounty
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: double
  scales_hasIdbD2toffcd1:
    name: scales_hasIdbD2toffcd1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbD2toffcd1 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd1
    alias: scales_hasIdbD2toffcd1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasCharge:
    name: scales_hasCharge
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 340575 occurrences with subject type scales_Agent and object type scales_Charge.
    - 262292 occurrences with subject type scales_CaseCriminal and object type scales_Charge.
    examples:
    - value: scales:Agent/wyd;;6:17-cr-00033_a0 scales:hasCharge scales:Charge/wyd;;6:17-cr-00033_c1
    - value: scales:CaseCriminal/wyd;;6:17-cr-00033 scales:hasCharge scales:Charge/wyd;;6:17-cr-00033_c1
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasCharge
    alias: scales_hasCharge
    owner: scales_CaseCriminal
    domain_of:
    - scales_Agent
    - scales_CaseCriminal
    range: scales_Charge
  scales_hasIdbFtitle5:
    name: scales_hasIdbFtitle5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFtitle5 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle5
    alias: scales_hasIdbFtitle5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasDocketTable:
    name: scales_hasDocketTable
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 561182 occurrences with subject type scales_CaseCivil and object type scales_DocketTable.
    - 127619 occurrences with subject type scales_CaseCriminal and object type scales_DocketTable.
    examples:
    - value: scales:CaseOther/txsd;;3:16-mc-00016 scales:hasDocketTable scales:DocketTable/txsd;;3:16-mc-00016
    - value: scales:CaseCriminal/wyd;;6:17-cr-00033 scales:hasDocketTable scales:DocketTable/wyd;;6:17-cr-00033
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasDocketTable
    alias: scales_hasDocketTable
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: scales_DocketTable
  scales_hasIdbInt3:
    name: scales_hasIdbInt3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbInt3 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbInt3
    alias: scales_hasIdbInt3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbDisp3:
    name: scales_hasIdbDisp3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDisp3 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp3
    alias: scales_hasIdbDisp3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFsev4:
    name: scales_hasIdbFsev4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 110056 occurrences with subject type scales_CaseCriminal and object type string.
    - 1526 occurrences with subject type scales_CaseCriminal and object type integer.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFsev4 -8
    - value: scales:CaseCriminal/txsd;;7:16-cr-01164 scales:hasIdbFsev4 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev4
    alias: scales_hasIdbFsev4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbTermdate:
    name: scales_hasIdbTermdate
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 517964 occurrences with subject type scales_CaseCivil and object type datetime.
    - 48652 occurrences with subject type scales_CaseCriminal and object type datetime.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbTermdate 2019-01-15T00:00:00
    - value: scales:CaseCriminal/akd;;1:16-cr-00001 scales:hasIdbTermdate 2016-08-01T00:00:00
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTermdate
    alias: scales_hasIdbTermdate
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: datetime
  scales_hasFilingDate:
    name: scales_hasFilingDate
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 550105 occurrences with subject type scales_CaseCivil and object type date.
    - 11077 occurrences with subject type scales_CaseCivil and object type string.
    - 126369 occurrences with subject type scales_CaseCriminal and object type date.
    - 23203350 occurrences with subject type scales_DocketEntry and object type date.
    - 457921 occurrences with subject type scales_DocketEntry and object type string.
    - 1250 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasFilingDate 2016-04-15
    - value: scales:CaseCivil/ctd;;3:15-cv-01889 scales:hasFilingDate 12/31/2015
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasFilingDate 2017-03-02
    - value: scales:DocketEntry/akd;;1:16-cr-00001_de0 scales:hasFilingDate 2016-02-03
    - value: scales:DocketEntry/akd;;3:15-cv-00265_de0 scales:hasFilingDate 12/31/2015
    - value: scales:CaseCriminal/casd;;3:12-cr-03082 scales:hasFilingDate 07/26/2012
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasFilingDate
    alias: scales_hasFilingDate
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    - scales_DocketEntry
    range: Any
    any_of:
    - range: date
    - range: string
  scales_hasIdbFinetot:
    name: scales_hasIdbFinetot
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFinetot 0.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFinetot
    alias: scales_hasIdbFinetot
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbPristim5:
    name: scales_hasIdbPristim5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbPristim5 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim5
    alias: scales_hasIdbPristim5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFineamt4:
    name: scales_hasIdbFineamt4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFineamt4 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt4
    alias: scales_hasIdbFineamt4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbProbcd1:
    name: scales_hasIdbProbcd1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProbcd1 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd1
    alias: scales_hasIdbProbcd1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbTofflvl1:
    name: scales_hasIdbTofflvl1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTofflvl1 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl1
    alias: scales_hasIdbTofflvl1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbPristim1:
    name: scales_hasIdbPristim1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbPristim1 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim1
    alias: scales_hasIdbPristim1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasPacerID:
    name: scales_hasPacerID
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 561182 occurrences with subject type scales_CaseCivil and object type string.
    - 127619 occurrences with subject type scales_CaseCriminal and object type string.
    - 262292 occurrences with subject type scales_Charge and object type string.
    - 23661271 occurrences with subject type scales_DocketEntry and object type string.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasPacerID 1:16-cv-00009
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasPacerID 1:17-cr-00012
    - value: scales:Charge/akd;;1:16-cr-00001_c1-3 scales:hasPacerID 1-3
    - value: scales:DocketEntry/akd;;1:16-cr-00001_de0 scales:hasPacerID 1
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasPacerID
    alias: scales_hasPacerID
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    - scales_Charge
    - scales_DocketEntry
    range: string
  scales_hasIdbTcounsel:
    name: scales_hasIdbTcounsel
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTcounsel -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTcounsel
    alias: scales_hasIdbTcounsel
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbD2toffcd4:
    name: scales_hasIdbD2toffcd4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbD2toffcd4 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd4
    alias: scales_hasIdbD2toffcd4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbCtpnwof:
    name: scales_hasIdbCtpnwof
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCtpnwof 1.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtpnwof
    alias: scales_hasIdbCtpnwof
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbProccd:
    name: scales_hasIdbProccd
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProccd 1.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProccd
    alias: scales_hasIdbProccd
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFoffcd2:
    name: scales_hasIdbFoffcd2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFoffcd2 6801.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd2
    alias: scales_hasIdbFoffcd2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTrandist:
    name: scales_hasIdbTrandist
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 92764 occurrences with subject type scales_CaseCriminal and object type integer.
    - 18818 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTrandist -8
    - value: scales:CaseCriminal/akd;;1:16-cr-00001 scales:hasIdbTrandist -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrandist
    alias: scales_hasIdbTrandist
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbFoffcd4:
    name: scales_hasIdbFoffcd4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFoffcd4 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd4
    alias: scales_hasIdbFoffcd4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbCaslgky:
    name: scales_hasIdbCaslgky
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCaslgky 086211700012CR0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCaslgky
    alias: scales_hasIdbCaslgky
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbSupvrel5:
    name: scales_hasIdbSupvrel5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbSupvrel5 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel5
    alias: scales_hasIdbSupvrel5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasAgent:
    name: scales_hasAgent
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 9582250 occurrences with subject type scales_CaseCivil and object type scales_Agent.
    - 1437899 occurrences with subject type scales_CaseCriminal and object type scales_Agent.
    examples:
    - value: scales:CaseCivil/wyd;;2:17-cv-00211 scales:hasAgent scales:Agent/wyd;;2:17-cv-00211_a9
    - value: scales:CaseCriminal/wyd;;6:17-cr-00033 scales:hasAgent scales:Agent/wyd;;6:17-cr-00033_a5
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasAgent
    alias: scales_hasAgent
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: scales_Agent
  scales_hasIdbToffcd5:
    name: scales_hasIdbToffcd5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbToffcd5 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd5
    alias: scales_hasIdbToffcd5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTsev5:
    name: scales_hasIdbTsev5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 93149 occurrences with subject type scales_CaseCriminal and object type string.
    - 18433 occurrences with subject type scales_CaseCriminal and object type integer.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTsev5 -8
    - value: scales:CaseCriminal/ared;;4:16-cr-00001 scales:hasIdbTsev5 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev5
    alias: scales_hasIdbTsev5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbDefno:
    name: scales_hasIdbDefno
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDefno 1.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDefno
    alias: scales_hasIdbDefno
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFsev2:
    name: scales_hasIdbFsev2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFsev2 839
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev2
    alias: scales_hasIdbFsev2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbProbcd3:
    name: scales_hasIdbProbcd3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 47013 occurrences with subject type scales_CaseCriminal and object type integer.
    - 64569 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProbcd3 -8
    - value: scales:CaseCriminal/akd;;1:16-cr-00001 scales:hasIdbProbcd3 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd3
    alias: scales_hasIdbProbcd3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbD2foffcd3:
    name: scales_hasIdbD2foffcd3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbD2foffcd3 7820.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd3
    alias: scales_hasIdbD2foffcd3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbPristim3:
    name: scales_hasIdbPristim3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbPristim3 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim3
    alias: scales_hasIdbPristim3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFtitle2:
    name: scales_hasIdbFtitle2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFtitle2 21:841A=CD.F
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle2
    alias: scales_hasIdbFtitle2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbFoffcd1:
    name: scales_hasIdbFoffcd1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFoffcd1 6801.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd1
    alias: scales_hasIdbFoffcd1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbProbcd4:
    name: scales_hasIdbProbcd4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 64463 occurrences with subject type scales_CaseCriminal and object type integer.
    - 47119 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProbcd4 -8
    - value: scales:CaseCriminal/akd;;1:16-cr-00001 scales:hasIdbProbcd4 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd4
    alias: scales_hasIdbProbcd4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbReopseq:
    name: scales_hasIdbReopseq
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbReopseq 0.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbReopseq
    alias: scales_hasIdbReopseq
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTofflvl3:
    name: scales_hasIdbTofflvl3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTofflvl3 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl3
    alias: scales_hasIdbTofflvl3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTtitle1:
    name: scales_hasIdbTtitle1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTtitle1 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle1
    alias: scales_hasIdbTtitle1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbD2foffcd2:
    name: scales_hasIdbD2foffcd2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbD2foffcd2 6801.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd2
    alias: scales_hasIdbD2foffcd2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbStatuscd:
    name: scales_hasIdbStatuscd
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 551088 occurrences with subject type scales_CaseCivil and object type string.
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbStatuscd L
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbStatuscd E
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbStatuscd
    alias: scales_hasIdbStatuscd
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: string
  scales_hasIdbAppdate:
    name: scales_hasIdbAppdate
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbAppdate 01/01/1900
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbAppdate
    alias: scales_hasIdbAppdate
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbToffcd3:
    name: scales_hasIdbToffcd3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbToffcd3 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd3
    alias: scales_hasIdbToffcd3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbProbmon4:
    name: scales_hasIdbProbmon4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProbmon4 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon4
    alias: scales_hasIdbProbmon4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbProcdate:
    name: scales_hasIdbProcdate
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProcdate 03/02/2017
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProcdate
    alias: scales_hasIdbProcdate
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbFineamt5:
    name: scales_hasIdbFineamt5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFineamt5 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt5
    alias: scales_hasIdbFineamt5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTsev4:
    name: scales_hasIdbTsev4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 99020 occurrences with subject type scales_CaseCriminal and object type string.
    - 12562 occurrences with subject type scales_CaseCriminal and object type integer.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTsev4 -8
    - value: scales:CaseCriminal/ared;;4:16-cr-00001 scales:hasIdbTsev4 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev4
    alias: scales_hasIdbTsev4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbPriscd3:
    name: scales_hasIdbPriscd3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbPriscd3 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd3
    alias: scales_hasIdbPriscd3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbFsev3:
    name: scales_hasIdbFsev3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFsev3 409
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev3
    alias: scales_hasIdbFsev3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbToffcd1:
    name: scales_hasIdbToffcd1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbToffcd1 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd1
    alias: scales_hasIdbToffcd1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTsev3:
    name: scales_hasIdbTsev3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 100285 occurrences with subject type scales_CaseCriminal and object type string.
    - 11297 occurrences with subject type scales_CaseCriminal and object type integer.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTsev3 -8
    - value: scales:CaseCriminal/ared;;4:16-cr-00001 scales:hasIdbTsev3 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev3
    alias: scales_hasIdbTsev3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbD2toffcd5:
    name: scales_hasIdbD2toffcd5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbD2toffcd5 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd5
    alias: scales_hasIdbD2toffcd5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbPristim2:
    name: scales_hasIdbPristim2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbPristim2 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim2
    alias: scales_hasIdbPristim2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbSupvrel4:
    name: scales_hasIdbSupvrel4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbSupvrel4 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel4
    alias: scales_hasIdbSupvrel4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_isInCourt:
    name: scales_isInCourt
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 561182 occurrences with subject type scales_CaseCivil and object type scales_Court.
    - 127619 occurrences with subject type scales_CaseCriminal and object type scales_Court.
    examples:
    - value: scales:CaseOther/txsd;;3:16-mc-00016 scales:isInCourt scales:Court/txsd
    - value: scales:CaseCriminal/wyd;;6:17-cr-00033 scales:isInCourt scales:Court/wyd
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:isInCourt
    alias: scales_isInCourt
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: scales_Court
  scales_hasIdbTrandock:
    name: scales_hasIdbTrandock
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTrandock -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrandock
    alias: scales_hasIdbTrandock
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbProbmon1:
    name: scales_hasIdbProbmon1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProbmon1 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon1
    alias: scales_hasIdbProbmon1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFtitle1:
    name: scales_hasIdbFtitle1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFtitle1 21:841A=CD.F
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle1
    alias: scales_hasIdbFtitle1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbCtfiltrn:
    name: scales_hasIdbCtfiltrn
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCtfiltrn 1.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfiltrn
    alias: scales_hasIdbCtfiltrn
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTermoff:
    name: scales_hasIdbTermoff
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 103076 occurrences with subject type scales_CaseCriminal and object type integer.
    - 8506 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTermoff -8
    - value: scales:CaseCriminal/cand;;1:16-cr-00325 scales:hasIdbTermoff 1
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTermoff
    alias: scales_hasIdbTermoff
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: string
  scales_hasIdbFofflvl4:
    name: scales_hasIdbFofflvl4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFofflvl4 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl4
    alias: scales_hasIdbFofflvl4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbPriscd1:
    name: scales_hasIdbPriscd1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbPriscd1 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd1
    alias: scales_hasIdbPriscd1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbFtitle4:
    name: scales_hasIdbFtitle4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFtitle4 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle4
    alias: scales_hasIdbFtitle4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbFoffcd5:
    name: scales_hasIdbFoffcd5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFoffcd5 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd5
    alias: scales_hasIdbFoffcd5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbLoaddate:
    name: scales_hasIdbLoaddate
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbLoaddate 05/02/2017
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbLoaddate
    alias: scales_hasIdbLoaddate
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbTofflvl5:
    name: scales_hasIdbTofflvl5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTofflvl5 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl5
    alias: scales_hasIdbTofflvl5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbOffice:
    name: scales_hasIdbOffice
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 551088 occurrences with subject type scales_CaseCivil and object type string.
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbOffice 1
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbOffice 1
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbOffice
    alias: scales_hasIdbOffice
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: string
  scales_hasIdbTtitle4:
    name: scales_hasIdbTtitle4
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTtitle4 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle4
    alias: scales_hasIdbTtitle4
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbDistrict:
    name: scales_hasIdbDistrict
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 551088 occurrences with subject type scales_CaseCivil and object type string.
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbDistrict akd
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDistrict iand
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDistrict
    alias: scales_hasIdbDistrict
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: string
  scales_hasIdbSupvrel1:
    name: scales_hasIdbSupvrel1
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbSupvrel1 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel1
    alias: scales_hasIdbSupvrel1
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTranoff:
    name: scales_hasIdbTranoff
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 110543 occurrences with subject type scales_CaseCriminal and object type double.
    - 1039 occurrences with subject type scales_CaseCriminal and object type integer.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTranoff -8.0
    - value: scales:CaseCriminal/casd;;3:12-cr-03082 scales:hasIdbTranoff -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTranoff
    alias: scales_hasIdbTranoff
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: integer
    - range: double
  scales_hasIdbCtpn:
    name: scales_hasIdbCtpn
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCtpn 1.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtpn
    alias: scales_hasIdbCtpn
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbProbmon5:
    name: scales_hasIdbProbmon5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProbmon5 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon5
    alias: scales_hasIdbProbmon5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasTerminatingDate:
    name: scales_hasTerminatingDate
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 512691 occurrences with subject type scales_CaseCivil and object type date.
    - 10827 occurrences with subject type scales_CaseCivil and object type string.
    - 121860 occurrences with subject type scales_CaseCriminal and object type date.
    - 1198 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasTerminatingDate 2019-01-15
    - value: scales:CaseCivil/ctd;;3:15-cv-01889 scales:hasTerminatingDate 02/17/2016
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasTerminatingDate 2019-03-01
    - value: scales:CaseCriminal/casd;;3:12-cr-03082 scales:hasTerminatingDate 09/18/2012
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasTerminatingDate
    alias: scales_hasTerminatingDate
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: Any
    any_of:
    - range: date
    - range: string
  scales_hasIdbD2toffcd3:
    name: scales_hasIdbD2toffcd3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbD2toffcd3 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd3
    alias: scales_hasIdbD2toffcd3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbUpdate:
    name: scales_hasIdbUpdate
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbUpdate 01/01/1900
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbUpdate
    alias: scales_hasIdbUpdate
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbFugstat:
    name: scales_hasIdbFugstat
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFugstat N
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFugstat
    alias: scales_hasIdbFugstat
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbCircuit:
    name: scales_hasIdbCircuit
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 551088 occurrences with subject type scales_CaseCivil and object type double.
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbCircuit 9.0
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCircuit 8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCircuit
    alias: scales_hasIdbCircuit
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: double
  scales_hasJurisdiction:
    name: scales_hasJurisdiction
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 561174 occurrences with subject type scales_CaseCivil and object type string.
    - 31 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasJurisdiction U.S. Government
        Defendant
    - value: scales:CaseCriminal/txed;;4:17-cr-00092 scales:hasJurisdiction Ct. 1s
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasJurisdiction
    alias: scales_hasJurisdiction
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCivil
    - scales_CaseCriminal
    range: string
  scales_hasIdbPriscd2:
    name: scales_hasIdbPriscd2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type string.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbPriscd2 -8
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd2
    alias: scales_hasIdbPriscd2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: string
  scales_hasIdbFineamt3:
    name: scales_hasIdbFineamt3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFineamt3 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt3
    alias: scales_hasIdbFineamt3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFofflvl5:
    name: scales_hasIdbFofflvl5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFofflvl5 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl5
    alias: scales_hasIdbFofflvl5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbTofflvl2:
    name: scales_hasIdbTofflvl2
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTofflvl2 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl2
    alias: scales_hasIdbTofflvl2
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbD2foffcd5:
    name: scales_hasIdbD2foffcd5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbD2foffcd5 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd5
    alias: scales_hasIdbD2foffcd5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbSupvrel3:
    name: scales_hasIdbSupvrel3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbSupvrel3 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel3
    alias: scales_hasIdbSupvrel3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbDisp5:
    name: scales_hasIdbDisp5
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDisp5 -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp5
    alias: scales_hasIdbDisp5
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbCtfil:
    name: scales_hasIdbCtfil
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbCtfil 1.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfil
    alias: scales_hasIdbCtfil
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbFofflvl3:
    name: scales_hasIdbFofflvl3
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFofflvl3 4.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl3
    alias: scales_hasIdbFofflvl3
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
  scales_hasIdbPristot:
    name: scales_hasIdbPristot
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 111582 occurrences with subject type scales_CaseCriminal and object type double.
    examples:
    - value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbPristot -8.0
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristot
    alias: scales_hasIdbPristot
    owner: scales_CaseCriminal
    domain_of:
    - scales_CaseCriminal
    range: double
class_uri: scales:CaseCriminal

```
</details>