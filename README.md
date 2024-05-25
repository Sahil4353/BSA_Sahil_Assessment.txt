# BSA_Sahil_Assessment.txt
Name : Sahil Kakadiya Student ID : 1000114910 Last Changes : 25th May 2024 6:50PM

Task 1
This script is designed to create user accounts based on input provided in a CSV file. 			
It parses the CSV file containing user details such as email, birthdate, groups, and 	
shared folder, and creates user accounts accordingly. Optionally, it can create shared 	
folders for users and add users to specific groups.


* Pre-requisites
  - Linux environment
  - Bash shell
  - sudo privileges
  - CSV file containing user details (email, birthdate, groups, shared folder)

* Ensure the script file has executable permissions. If not, run:

   chmod +x Sahil.sh
   
* Run the script with the CSV file as the argument:
	   
	   ./Sahil.sh Sahil.csv
Task 2
This script is designed to backup a specified directory, compress it into a tar.gz 	
archive, and upload it to a remote server using SCP.


* Pre-requisites
  - Linux environment
  - Bash shell
  - SSH access to the remote server
  - tar utility installed
  - Proper permissions to read/write files and directories
  
  
* Ensure the script file has executable permissions. If not, run:

	  chmod +x backup.sh



* Run the script with the directory to backup as the argument:

      ./backup.sh /home/Sahil/Documents

  - If no directory is provided as an argument, the script will prompt you to enter the 
    directory to backup.  
GitHub Link:
	https://github.com/Sahil4353/BSA_Self_Assessment.txt
