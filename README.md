<body>
<font face = "Times New Roman" size = "10">

**Please read the content very carefully and follow the steps as mentioned to make the Python code works perfectly** 

A description of the script is mentioned in the paper. Please read it carefully to function the code properly
If any queries please email me at gbbgohain@gmail.com
<b>WEATHER_CONVERTER:</b> -
Please follow the steps to set up the folder and the code
After the WEATHER_CONVERTER.zip file has been downloaded from 
<b>https://github.com/gbgohain26/WEATHER_CONVERTER/</b>
Extract the WEATHER_CONVERTER.zip file and unzip the file in C:\ Drive. After extraction, inside the folder and the python code with different subfolders. Inside folder WEATHER_CONVERTER we have 2 subfolders as mentioned below

<b>a.IMD_DAILY_GRIDDED</b>
	<b>Sub Folder</b>
	<b>a. DAILY_DATA_LIST</b>
		Inside the folder, we have LIST-DATA.xls, we have to fill the F_NAME (Filename ), JDAY (Julian Day), and JDAY_MERGE (merge last two digits of the year and Julian day) eg. If the file name for maximum temperature is max12062020.grd the F_NAME will be 12062020, so for every file, we have to assign only the date of data captured and the sheet name should be the year
	<b>b. DAILY_GRID_DATA</b>
		This folder contains the daily data downloaded from <b>http://www.imdpune.gov.in/Seasons/Temperature/temp.html</b>

		it has three subfolders
		<b>1. MAXIMUM</b>-for storing maximum gridded data
		<b>2. MINIMUM</b>-for storing minimum gridded data
		<b>3. RAINFALL</b>-for storing Rainfall gridded data

		If you already have the data you can place it here else use the DOWNLOAD_DAILY_GRID_DATA.pyc file to download the data. It will store automatically in the folder assigned.

	<b>c. DATA_CROP_MODEL</b>
		This folder saves the DSSAT weather files

	<b>d. STATION_LIST</b>
		We have to prepare an excel sheet for each state. The state may contain different grids
		Eg:- A sample file is mentioned below

		<b>STATION:-</b> is the Weather station or GRID name

		<b>WCODE:-</b> is the weather station code that will be assigned to the weather file ( it will be a specific grid or specific location or weather station)

		<b>LATITUDE:–</b> Assign the latitude for the location

		<b>LONGITUDE:–</b> Assign the longitude for the location

		<b>ELEVATION:–</b> It’s the above sea level 
		<b>Script</b>
		<b>• DAILY_WEATHER:- </b>it will convert the gridded data to the DSSAT model format
		File
		<b>• LIST.txt:- </b> we have to assign which states or which location has to run  and the location excel sheet name should be same as mentioned in the LIST.txt
<b>b. IMD_GRIDDED_1980_2015</b>
	<b>Sub folder</b>
	<b>a. DSSAT_WEATHER</b>
		This folder saves the DSSAT weather files

	<b>b. GRID_DATA</b>
	This folder contains the yearly data downloaded which can be downloaded from 
		<b>http://www.imdpune.gov.in/Clim_Pred_LRF_New/Grided_Data_Download.html</b>
		The rainfall data is available at 0.250X 0.250 from 1901 to 2019
		The temperature data is available at 10X 10 from 1901 to 2019, if you want data at 0.50X 0.50, we have to put a request to IMD, Pune
		it has three subfolders
			1. MaxT-for storing maximum gridded data
			2. MinT-for storing minimum gridded data
			3. Rainfall-for storing Rainfall gridded data

	<b>c. STATION_LIST</b>
		We have to prepare an excel sheet for each state. The state may contain different grids

		<b>STATION:-</b> is the Weather station or GRID name
		<b>WCODE:-</b> is the weather station code that will be assigned to the weather file ( it will be a specific grid or specific location or weather station)
		<b>LATITUDE:–</b> Assign the latitude for the location
		<b>LONGITUDE:–</b> Assign the longitude for the location
		<b>ELEVATION:–</b> It’s the above sea level 
	
	<b>ScriptM</b>
		<b>• DAILY_WEATHER:-</b> it will convert the gridded data to the DSSAT model format
	<b>File</b>
		<b>• LIST.txt:-</b> we have to assign which states or which location has to run  and the location excel sheet name should be same as mentioned in the LIST.txt

	DSSAT soil at 10km can be downloaded from
	<b>https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/1PEEY0/CIMWRJ&version=2.6 </b>

	0.250 X 0.250 shapefile is included in the github , with State name, District name, DSSAT soil ID, unique Weather code, Latitude and Longitude, altitude and Nitrogen amount
	</font><br />
	</body>
