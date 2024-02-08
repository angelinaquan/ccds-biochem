# ccds-biochem
Charlotte Country Country Day School Physical Computational Biochemistry Research Code


Initial Setup: 
-	Install Rstudio in school store
-	Install the R language
-	Install Python in Microsoft store
-	Install most recent release of this github code
-	R session: setwd(“”) % use backslashes and not front lashes
-	type in command: source(“install-packages.r”)

Editing the configuration file
-	Open sample configuration in NOTEPAD
-	Rscript_path: location on computer where R script is (bin & rscript.exe)
-	Lib paths: two paths: .libPaths() in R and copy them in
-	Cores: always keep it in 0
-	Resid: rename to ASN
-	Output_dir “pdbs”
-	C- is CO
-	How the measurements are taken (2 by 2 or 3 by 3)
- Name of the bonds in your moecules

Run the program: 
-	Cd to the folder
-	Final command: python collect_data.py sample_configuration_Asn.json

Download files: 
-	Rcsb pdb
-	Search Asparagine
-	Tabular report -> pdf ids
- After clicking on download IDs, you have to click on the buttons that says 1-10000 and 10001-number. That will actually do the job of downloading
-	Go to R and do source(“install-files.r”)

Run histogram
-	CTRL + ALT + R to run
-	Editing the code to make it work
