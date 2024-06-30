# Parsing_Log_Files

Script Pseudocode:

● Is named "show-attackers.sh".

● Requires that a file is provided as an argument. If a file is not provided, or it cannot be read,
then the script will display an error message and exit with a status of 1.

● Counts the number of failed login attempts by IP address. If there are any IP addresses with
more than 10 failed login attempts, the number of attempts made, the IP address from which
those attempts were made, and the location of the IP address will be displayed.

● Produces output in CSV (comma-separated values) format with a header of
"Count,IP,Location".
