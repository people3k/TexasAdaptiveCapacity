# ethno-demography
This supporting document should allow one to recreate the analysis performed as part of “The optimal species richness environments for human populations, ” By Freeman et al.  2018 Submitted to PNAS July 2018.  The annotated scripts in this directory (RichnessSIScripts.pdf) contain code to replicate the analysis, as well as  code  for  additional  analyses  not  included  in  the  main  paper  or  supplemental  information.   To replicate the analysis, one can either analyze the data files provided or build their own data set.  As discussed in the main body of the text, we built three data sets following the procedures outlined by Tallavaara et al. (2017) for linking species richness values, net primary productivity and pathogen stress  to  each  ethnographic  case.   We  do  not  replicate  the  scripts  provided  by  Tallavaara  et  al.(2017) as these are available, clear and should be cited when used.To  replicate  our  analysis,  one  needs  to  set  their  working  directory  in  R  to  the  file  location that contains the data files.  There are 11 files that follow the naming convention “name.csv.” The 11 files are “MainFinal.csv”.  “AGPOP3Eco.csv”, “HGFEM4R.csv”, “AGPOPClass.csv”, “CountryMeansEco2.csv”, “AGPOP3EcoH.csv”, “AGPOP3EcoL.csv”, “HiHG.csv”, “LowHG,csv”, “CountryMeansEco2H.csv”,  and  “CountryMeansEco2L.csv”.   The  first  five  files  are  the  main  files,  the second six files are divided into high and low species richness environments by economy type for convenience.  In each file, the variables are defined as follows:
1.  Group/Country–name of the ethnographic society of country
2.  Latitude–the latitude at the geographic center of a group’s territory or a country’s territory.
3.  Longitude–the longitude at the geographic center of a group’s territory or a country’s territory.
4.  Class–an ordinal ranking of wealth and status differentiation among the hunter-gatherer and agriculturalists societies (see main text for more details)
5.  Class2–an binary ranking of wealth and status differentiation among the hunter-gatherer and agriculturalists societies (see main text for more details).
6.  ECI–The average economic complexity index since 1973 as measured among modern countries.
7.  DENSITY–Population density in people per square kilometer. This is a point in time estimatefor hunter-gatherer and agricultural groups and an average density since 1973 among nation states.
8.  LnDENSITY–The natural log of population density
9.  npp–net primary productivity estimated at the center of each group’s territory
10.  npp2-Net primary productivity squared
11.  biodiv–Standardized estimate of species richness at the center of each group’s range.
12.  biodiv2–Species richness *100 ad squared.
13.  pathos–Index of pathogen stress at the center of a group’s territory.
14.  DivDiff–The absolute value of species richness-the species richness value of peak population density (values identified in Fig.  2 of the main manuscript).1
5.  ID–A nominal variable that denotes economy type.  HG=hunter-gatherer,  AG=subsistence agriculturalist, IND=modern nation state

Tallavaara, M., J. T. Eronen, and M. Luoto2017. Supporting   data   and   script   for   ”productivity,   biodiversity,   and   pathogens   influence   the   global   hunter-gatherer   population   density”   (Tallavaara   et   al.   pnas   2018).https://doi.org/10.5281/zenodo.1167852
