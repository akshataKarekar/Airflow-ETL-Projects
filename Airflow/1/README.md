web-server-access-log.txt contains below:

a. timestamp - TIMESTAMP
b. latitude - float
c. longitude - float
d. visitorid - char(37)
e. accessed_from_mobile - boolean
f. browser_code - int

Task 1: Add a command in the shell script to extract the fields timestamp and visitorid from the web-server-access-log.txt and write to a file extracted.txt

Task 2: Update the shell script to add a command to capitalize the visitorid and write to a new file capitalized.txt.

Task 3: Update the shell script to add a command to compress the transformed file capitalized.txt into a new file log.tar.gz.

Task 2: Create the imports block.

Task 3: Create the DAG Arguments block. You can use the default settings

Task 4: Create the DAG definition block. The DAG should run daily.

Task 5: Create the task extract_transform_and_load to call the shell script.

Task 6: Create the task pipeline block.

Task 7: Submit the DAG.

Task 8: Submit the shell script to dags folder.

Task 9: Change the permission to read shell script.

Task 10. Verify if the DAG is submitted
