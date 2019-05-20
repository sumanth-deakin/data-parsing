SEER 1973-2015 Research Data in ASCII Text Format              April 16, 2018

The following is a description of the contents of the SEER_1973_2015_TEXTDATA
directory for the 1973-2015 Research Data.  The data in this directory are
stored in ASCII text format and must be analyzed with your own
statistical/analytical software.

Additional information regarding the SEER 1973-2015 Research Data is located
on the SEER Web site at:
     http://seer.cancer.gov/data

This TEXTDATA directory contains the following:

     - SEER Cancer Incidence Research Database for patients diagnosed
       1973-2015
     - County level population estimates for the SEER registries by 19 age
       groups and single ages from the Census Bureau for 1973-2015
     - Data dictionaries for the SEER and population data

Similar in nature to the previous 1973-2014 version with the 
July - December 2005 Louisiana diagnoses being distributed as a supplement 
to the SEER Research Data.  Hurricane Katrina had a large impact on Louisiana's 
population for this six month time period so these diagnoses are not analyzed in 
most SEER reporting.  Consequently, the populations include one decimal place.

Use of or citation of the data in a published document should
contain the following reference.
     Surveillance, Epidemiology, and End Results (SEER) Program
     (www.seer.cancer.gov) Research Data (1973-2015), National Cancer
     Institute, DCCPS, Surveillance Research Program,
     released April 2018, based on the November 2017 submission.

To reference an electronic copy of the most recent and previous versions of the
SEER Cancer Statistics Review (CSR) and other materials, please visit the SEER
Web site at:
     http://seer.cancer.gov

Some documentation contained with this data is in Portable Document Format (PDF).
The PDF files can be viewed and printed with the Adobe Acrobat Reader public
domain software provided at the Adobe Web site:
     http://www.adobe.com

The following paragraphs describe the general directory structure of the data.

  \INCIDENCE
     TEXTDATA.FILEDESCRIPTION.PDF - Data dictionary for the SEER incidence 
     data files.
     Additional documentation is located on the SEER Web site:
       http://seer.cancer.gov/data
       
     READ.SEER.RESEARCH.NOV2017.SAS - SAS code with input statement only.
     Setup to read SEER 9 only, other files have same format.

     Sub-directories with the SEER November 2017 Research Data files.  The
     SEER November 2017 data within each sub-directory have been broken out
     into nine site group files.  The split into site files was made using the 
     Site recode ICD-O-3/WHO 2008.  These files are stored as ASCII text files.

     BREAST.TXT    -  Breast
     COLRECT.TXT   -  Colon and Rectum
     DIGOTHR.TXT   -  Other Digestive
     FEMGEN.TXT    -  Female Genital
     LYMYLEUK.TXT  -  Lymphoma of All Sites and Leukemia
     MALEGEN.TXT   -  Male Genital
     RESPIR.TXT    -  Respiratory
     URINARY.TXT   -  Urinary
     OTHER.TXT     -  All Other Sites

     YR1973_2015.SEER9
        This directory contains the SEER November 2017 Research Data files
        from nine SEER registries for 1973-2015.  The SEER 9 registries are
        Atlanta, Connecticut, Detroit, Hawaii, Iowa,  New Mexico, San
        Francisco-Oakland, Seattle-Puget Sound, and Utah.  Data are available
        for cases diagnosed from 1973 and later for these registries with the
        exception of Seattle-Puget Sound and Atlanta. The Seattle-Puget Sound
        and Atlanta registries joined the SEER program in 1974 and 1975,
        respectively.

     YR1992_2015.SJ_LA_RG_AK
        This directory contains the SEER November 2017 Research Data files
        from the San Jose-Monterey, Los Angeles, Rural Georgia and Alaska
        Natives SEER registries for 1992-2015.

     YR2000_2015.CA_KY_LO_NJ_GA
        This directory contains the SEER November 2017 Research Data files
        from the Greater California, Kentucky, Louisiana, New Jersey, and
        Greater Georgia SEER registries for 2000-2015.  For the year 2005, 
        only January - June diagnoses are included for Louisiana.  Hurricane 
        Katrina had a large impact on Louisiana's population for the 
        July - December 2005 time period.  For most SEER reporting, Louisiana 
        cases diagnosed in the latter half of 2005 are not analyzed.

     YR2005.LO_2ND_HALF
        This directory contains the July - December 2005 diagnoses for
        Louisiana from their November 2017 SEER submission.  Hurricane Katrina
        had a large impact on Louisiana's population for this six month time
        period.  For most SEER reporting, Louisiana cases diagnosed during this
        six month period are not analyzed.  These data are considered a
        supplement to the SEER Research Data.

   \POPULATIONS
     POPDIC.HTML - Data dictionary for the population data files
     Additional documentation is located on the SEER Web site:
       http://seer.cancer.gov/popdata

     Sub-directories with population files (19AGEGROUPS.TXT and SINGLEAGES.TXT)
     with estimates to match the registry/year coverage of the SEER Research
     Incidence Data for 1973-2015.  These files are stored as ASCII text files.
     
     WHITE_BLACK_OTHER\YR1973_2015.SEER9
        This directory contains population files for the SEER 9 registries for
        the appropriate years.  These populations contain estimates for the
        races of White, Black, and Other (American Indian/Asian Pacific
        Islander).  To be consistent with the SEER Research Incidence Data,
        the Seattle-Puget Sound and Atlanta registry population estimates are
        for 1974-2015 and 1975-2015, respectively.

     EXPANDED.RACE.BY.HISPANIC\YR1992_2015.SEER9.PLUS.SJ_LA_RG_AK
        This directory contains population files for the SEER 9 registries plus
        San Jose-Monterey, Los Angeles, Rural Georgia and Alaska Natives for
        1992-2015.  The populations are for the eight combinations of race and
        Hispanic origin.  The races are White, Black, American Indian/Alaskan
        Native, and Asian or Pacific Islander.  Hispanic origin has values of
        Hispanic and non-Hispanic.  To be consistent with the SEER Research
        Incidence Data, the populations for the Alaska Native Tumor Registry
        only include the estimates for American Indian/Alaskan Native.
     
     EXPANDED.RACE.BY.HISPANIC\YR2000_2015.CA_KY_LO_NJ_GA
        This directory contains population files for the Greater California,
        Kentucky, Louisiana, New Jersey, and Greater Georgia SEER registries 
        for 2000-2015.  For the year 2005, the Louisiana populations here are 
        meant to only be used with the January - June diagnoses.  The populations 
        are for the eight combinations of race and Hispanic origin.  The races 
        are White, Black, American Indian/Alaskan Native, and Asian or Pacific 
        Islander.  Hispanic origin has values of Hispanic and non-Hispanic.

     EXPANDED.RACE.BY.HISPANIC\YR2005.LO_2ND_HALF
        This directory contains population files to be utilized with the
        July - December 2005 Louisiana diagnoses.  The populations are for the
        eight combinations of race and Hispanic origin.  The races are White,
        Black, American Indian/Alaskan Native, and Asian or Pacific Islander.
        Hispanic origin has values of Hispanic and non-Hispanic.

----------------
REVISION HISTORY
----------------
4/16/2018 - Initial Release

