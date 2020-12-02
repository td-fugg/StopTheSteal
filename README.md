## StopTheSteal :ballot_box_with_check: 
*Highlighting abnormal voting patterns of the 2020 Presidential Election*

[Home](https://github.com/td-fugg/StopTheSteal) | [Georgia](https://github.com/td-fugg/StopTheSteal/tree/master/Georgia) | [Florida](https://github.com/td-fugg/StopTheSteal/tree/master/Florida) | [Michigan](https://github.com/td-fugg/StopTheSteal/tree/master/Michigan) | [Pennsylvania](https://github.com/td-fugg/StopTheSteal/tree/master/Pennsylvania) | [Wisconsin](https://github.com/td-fugg/StopTheSteal/tree/master/Wisconsin)


All of the precinct data, and aggregated voter roll and census data is available in the postgresl data.

#### Notes: ####    
Michigan's voter data: 5 records failed the ETL load out of ~7.9m  
Wisconsin's voter roll data: Between 40-50 records kicked out of the ETL from the original source. The tab-delimted file had some missing line endings.  The data contained information for numerous elections. I only filtered the results of the "2020 Presidential Election".   

The sql used to come up with the metrics at in the state folder's "ad-hoc" folder. The

### Michigan ###
The precinct data for Michigan includes census data and voter roll information. Links to the sources are below :

2019 Census Data  Estimates:  [Census.gov](https://www2.census.gov/programs-surveys/popest/tables/2010-2019/counties/totals/co-est2019-annres.xlsx)

Michigan Voter Roll as of 2020-10 [Michiganvoter.info](http://69.64.83.144/~mi/download/20201012/)

### Wisconsin ###
Wisconsin voter roll data from the 5758_DataRequest.zip [here](https://gofile.io/d/XwcWGo)