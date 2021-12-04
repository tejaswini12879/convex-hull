INSTRUCTIONS TO RUN :

There are 3 codes going to be submitted :

1. QUICKHULL - main code :
	a. Run all the cells in ‘quickhull. ipynb’ file with paths corrected, currently, the
	paths are for collab and all the test datasets used were submitted in the folder test
	so, put the paths to the read input function wherever it is called.
	
2. Analysis - analysis code :
	a. It contains both quickhull and random incremental algorithms. To run quickhull,
	uncomment lines 11 to 18 and comment the line 19 and use restart and run all. To
	run incremental algorithm comment lines 11 to 18 and uncomment line 19 and use
	restart and run all. The tests here are implemented randomly through NumPy so
	no need for a test data set for this.

3. Test-Quick hull :
	a. Datasets like teacup set points etc., are used in this code. Since there are highly
	complex 3-d pictures,(in rotated form) the input output bound increases. We tried
	to test this for 20 different datasets but were successful only for 10 tests because
	of RAM issues in the colab. So it’s better to collapse other cells and open and run
	only 1 cell at a time to avoid system hang issues.

Directory Structure :

Src : have all the 3 codes

Test outputs : the images that are saved (convex hulls of 10-different data sets)

Obj_files : datasets used for testing

Report : Report which has theory, results and analysis parts.
