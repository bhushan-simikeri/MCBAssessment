# MCBAssessment
This is a public repository for MCB Assessment for Bhushan Simikeri
Follow the below steps to set up the data model and generate the reports, reports generated during my assessment are placed in folder "Sample_Reports"
Step 1:Unzip 00Data_model_deploy,01Data_load_SQLLDR,02Gen_Report Folders
Step 2:From current folder Navigate to Data_model_deploy and execute OneClickModelDeploy.sql using oracle DBA user
	Eg: sqlplus system/admin @OneClickModelDeploy.sql
Step 3:From current folder Navigate to 01Data_load_SQLLDR and execute WDIData.sh and WDICountry.sh
	Eg: sh WDIData.sh
Step 4: From current folder Navigate to Data_model_deploy and execute OneClickReport_Gen.sql using "mcb" user
	Eg: sqlplus mcb/mcb123 @OneClickReport_Gen.sql
