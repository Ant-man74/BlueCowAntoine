# BlueCowAntoine
Algorythm used to solve a case of the Traveling sellsman problem with additionnal constraint

To get it to work add the database file (in the folder blueCow\App_Data), this will allow you to use a working database
 - Distance.mdf
 - Distance_log.ldf
 - Distance_vs2015.mdf
 - Distance_vs2015_log.mdf

or regenarate the database 
 - Create a database file with the name you desire
 - Execute the sql command that are in the project
 - the project should be working after you change the path name in appconfig but this method do not always work

change the path to these files in AppConfig

To use the project:
1) enter your variables in the first windows of the application
2) generate new bids
3) get distance matrix
4) fix missing CC
5) Change the parameter of your algorythm
5) Init pop quick (this may take some time)
6) after completion you will have a tour that may have some violation
7) Add to report / show values
8) You can now select an optimisation method and a replacement method before hitting optimize fitness
Depending on the chosen parameter the algorythm may take long, don not click multiple time as it will crash otherwise
9) during the optimisation you can click on Add to report / show values at any moment
10) you can repeat the step 8 and 9 as may time as you want as lo ng as you let them finish
11) click on generate PDF
