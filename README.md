# Science-For-Kids-BSc-dissertation
Bsc Final Year Project, Java Application to teach kids science

MUST HAVE
Working computer with windows
Eclipse - can be dowloaded from https://www.eclipse.org/downloads/
It cannot be asured that this project will work in other development environments

This Project contains
24 Java classes and 1 CSS sheet.
A MySQL database called ScienceForKids with 10 tables.

HOW TO SETUP THE DATABASE FOR THE SCIENCEFORKIDS PROGRAM

Pre-requirements
Have MySQL Server Installed
Have MySQL Workbench Installed
From the MySQL Installer have Connector/ODBC & Connector/J installed

1. Open up MySQL Workbench.
2. Create new connection, connection name localhost
2.1. username MUST be 'root' as the connection username within the code is 'root'
2.2. password MUST be 'root1' as the connection password within the code is 'root1'
3. After logging into the server, on the left hand side in the 'navigator' panel click 'data import'
4. Click 'Import from self contained file' and browse to find the file on the disk called 'ScienceForKidsDatabaseDump'
5. Click start import in the bottom right hand corner of the Workbench
6. If you click the refresh button in the navigator panel next to the word SCHEMAS, the ScienceForKids Schema should appear.
7. The program should now have access to the database and all its data 

HOW TO ACCESS THE WORKING CODE WITHIN ECLIPSE

1. Open up your Eclipse IDE and create a new workspace.
2. Click File -> Import -> General -> Existing Projects Into Workspace
3. Then in selecting root directory browse for the ScienceForKids folder on this disk.
4. Press the radio button 'copy projects into workspace' if you wish for a faster experience.
5. Click Finish, the project should then be loaded into your workspace and be able to run, this also contains the JUnit test cases.
6. The project will only fully run from your eclipse IDE if the database has been setup.

USING THE PROGRAM
See User Manual PDF for how to use the program.
Only year 4 physics and year 7 physics have working datasets.
Year 4 & year 7 biology also have working datasets but they are minimal.
