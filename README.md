# IND5003_PG01
In this analysis, to attempt to determine when maintenance is required for lifts in a building, we: 
1) utilize raw data collected by sensors,
2) preprocess the raw data preprocessing, and
3) apply analytical techniques. In this analysis, we utilize raw data obtained by the sensors, to attempt to determine when maintenance is required after data preprocessing and analytical techniques. 

## Instructions 
To process our data, run the Processing_Data notebook. 
(It will take about 30 mins to extract the files from the raw data, then about 3hrs 30 mins to generate out the parameters from the raw data)

The extracted files from the raw data is about 10 Gb, it will be uploaded onto teams.

From the Processing_Data notebook, you will end up with a Combined.csv file where you can rename it if necessary.
(For our dataset, ran the analysis using the combined_500Hz_21102023.csv file)

After processing the data, to analyse it, run the Analysis notebook. 

Do note to edit the file names in the notebooks as necessary. 


The file directory structure should look like: 

For_Submission
|__ Processing_Data.ipynb     	#first notebook to preprocess data
|__ Analysis.ipynb    	 	#second notebook for data analysis. this notebook uses combined_500Hz_21102023.csv     
|__ Other_Exploration.ipynb  	#third notebook with other data exploration methods (not in report)
|
|__ fig (folder)
|     |__ Butterworth.jpeg
|     |__ Jerk.jpeg
|     |__ RMSFormula.jpeg
|     |__ RMSTABLE.jpeg
|     |__ Wavelet.jpeg
|
|__ Raw_Data (folder)
|     |__ CL1
|     |         |__ 266 .tar files
|     |__ CL2
|     |         |__ 718 .tar files
|     |__ FL1
|     |         |__ 1643 .tar files
|     |__ FL2
|     |         |__ 2090 .tar files
|     |__ PL1
|     |         |__ 5610 .tar files
|     |__ PL2
|               |__ 4329 .tar files
|
|__ Extracted_Data (empty folder)
|__ Combined.csv    #file will be generated after running the "Processing_Data.ipynb" notebook, but file is here as the running process takes a long wait 
|__ test_compile_test.csv
|__ combined_500Hz_21102023.csv
| 
|__ test (folder)
|     |__ 003354   (folder with the trip's information)
|     |__ 234622   ( folder with the trip's information)
|     |__ 235056   (folder with the trip's information)
|
|__ Combine (folder)
      |__ test_compile_CL1
      |__ test_compile_CL2
      |__ test_compile_FL1
      |__ test_compile_FL2
      |__ test_compile_PL1
      |__ test_compile_PL2
