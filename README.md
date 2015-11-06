# WebSite1 (VB.net example of FusionCharts)


This is an example of using FusionCharts VB.net wrapper.

### Installing
Clone the entir folder in your local.
Open visual studio and open the site from File-->Open Web Site

### Main files description ==
* Default.aspx
	* The page where the chart will be displayed
* Default.aspx.vb
	* The code behind the Default.aspx page. In this file you will find the building of the JSON string for the chart

* /App_Code/DataConnection.vb
	* This is a class file holding the code to connect the program to access database file "App_Data/FactoryDB.mdb"

* /App_Code/FusionCharts.vb
	* This is the FusionCharts wrapper for VB.net. Basically it's a class file. 
