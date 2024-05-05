Introduction
This project provides a simple example of how to connect to an SFTP server, download files, and handle file name conflicts.

Prerequisites
Before using this program, ensure that you have the following installed:

Java Development Kit (JDK) 8 or higher
JSch library (included in the project)
Usage
To use this program:

Clone or download this repository.
Compile the Java source files.
Create a CSV file named configdata.txt with the following format:
sql
Copy code
host,port,user,password,remoteFilePath,localFolderPath
host: The hostname or IP address of the SFTP server.
port: The port number of the SFTP server.
user: Your SFTP username.
password: Your SFTP password.
remoteFilePath: The path to the file on the SFTP server.
localFolderPath: The local directory where the file will be downloaded.
Run the SFTPExample class.
