In this scenario, I have been assigned to a project that aims to de-congest the national highways by analyzing the road traffic data from different toll plazas. Each highway is operated by a different toll operator with a different IT setup that uses different file formats. My job is to collect data available in different formats and consolidate it into a single file.

Filelist:

vehicle-data.csv
tollplaza-data.tsv
payment-data.txt

vehicle-data.csv:

vehicle-data.csv is a comma-separated values file.
It has the below 6 fields

Rowid  - This uniquely identifies each row. This is consistent across all the three files.
Timestamp - What time did the vehicle pass through the toll gate.
Anonymized Vehicle number - Anonymized registration number of the vehicle 
Vehicle type - Type of the vehicle
Number of axles - Number of axles of the vehicle
Vehicle code - Category of the vehicle as per the toll plaza.


tollplaza-data.tsv:

tollplaza-data.tsv is a tab-separated values file.
It has the below 7 fields

Rowid  - This uniquely identifies each row. This is consistent across all the three files.
Timestamp - What time did the vehicle pass through the toll gate.
Anonymized Vehicle number - Anonymized registration number of the vehicle 
Vehicle type - Type of the vehicle
Number of axles - Number of axles of the vehicle
Tollplaza id - Id of the toll plaza
Tollplaza code - Tollplaza accounting code.

payment-data.txt:

payment-data.txt is a fixed width file. Each field occupies a fixed number of characters.

It has the below 7 fields

Rowid  - This uniquely identifies each row. This is consistent across all the three files.
Timestamp - What time did the vehicle pass through the toll gate.
Anonymized Vehicle number - Anonymized registration number of the vehicle 
Tollplaza id - Id of the toll plaza
Tollplaza code - Tollplaza accounting code.
Type of Payment code - Code to indicate the type of payment. Example : Prepaid, Cash.
Vehicle Code -  Category of the vehicle as per the toll plaza.
