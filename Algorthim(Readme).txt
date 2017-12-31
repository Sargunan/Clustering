IDE USED : Anaconda Spyder
Environment : Python 3.6 + Additional SciLearn Pacakages

STEP 1 : Import the Dataset
STEP 2: Data Preprocessing
	2a. Fill empty values
	2b. Create new column 'Payementused' in product to identify what kind of payment used : CASH or Digital Money
	2c. Update exisiting column in product dataframe , as male = 0 and other = 1
        2d. Drop uncessary columns
        2e. check for uniquness
STPE3 : Calculation of Number of cluster : Number of Store * Gender type(2) * PayementType used (2)
STEP 4: Using K means cluster with above values
STEP 5: Write into results into file.