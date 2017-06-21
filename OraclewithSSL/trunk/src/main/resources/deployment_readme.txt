Things which should be renamed in template before using it.
----------------------------------------------------------
1. Project Name
2. Mule configuration file names
3. Properties file names (except logging-metadata,json file because this is mandatory files whose name shouldn’t be changed).
4. Secure property key value (in the template it is given as dummy just for demo)
5. Mule flow names which should be as application requirement.
6. Munit flow names which should be as application requirement.

Consider the below details before sending a mail for deployment.
---------------------------------------------------------------
1. CR Number:- 
2. Application Name :- 
3. SVN Location :- 
4. Properties for application
   (a) env=dev
   (b) key=icoe!123
5. Deployment Details (Cloudhub)
   (a) Worker Size = .1vCores
   (b) Workers = 1
   (c) Mule Runtime = 3.8.3
6. For On Premise deployment
   (a) Consider only above 1-4 options
   (b) Make sure http component shouldn't as source in mule flow in the application.