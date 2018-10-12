/**** TO RUN********/
On line 20 put the path to the file you would like to have read. Then compile and run

/**** Logic ********/
// I parsed the file by commas as CSV file is a comma separated values file
// # of records received, equals (number of rows) every data entry block, even the null data, divided by columns (10)
    -1,000 entry blocks/10 = 100 records received
// # of records successful, equals received-failed
// # of records failed, when there is a black empty spot in the data, wich would look like -> ,,  in the file
