# Alma SRU Search

Uses the Alma SRU to lookup ISBNs and retrieve print and e-holdings.

## Setup and Use

### You Will Need

* Your Alma code for the campus_code variable
* Your Network Zone Alma code for the network_code variable
* A UTF-8 CSV file with a column headed with ISBN and an ISBN in each row 
* Put the name of the input file as the input_file variable

### Output

* The processed file will add two new columns showing any retrieved IZ and NZ availability
* The file will save as output.csv

## Credit

This is largely based on https://github.com/MrJeremyHobbs/SRU-searcher
