# db_class-hospital-database
hospital database composed of sql files

Prerequisites:
To run this database please have MySQL or any similar database server installed along with their clients

When cloning this repository your directory should look like this when you change into the repository directory:
-rw-r--r--@ 1 austinhome  staff  1158 Nov 22 14:55 Create_Tables_Script.sql
-rw-r--r--@ 1 austinhome  staff  2317 Nov 22 14:54 Insert_Courses_Script.sql
-rw-r--r--@ 1 austinhome  staff   543 Nov 22 14:54 Insert_Department_Script.sql
-rw-r--r--@ 1 austinhome  staff  1319 Nov 22 14:54 Insert_Enrollment_Script.sql
-rw-r--r--@ 1 austinhome  staff  2288 Nov 22 14:54 Insert_Professors_Script.sql
-rw-r--r--@ 1 austinhome  staff  7122 Nov 22 14:54 Insert_Students_Script.sql
-rw-r--r--@ 1 austinhome  staff   376 Nov 22 15:13 README.md

In order of how to load your sql files into the MySQL database or any other equivalant database:
1. Create_Tables_Script.sql
2. Insert_Students_Script.sql
3. Insert_Department_Script.sql
4. Insert_Professors_Script.sql
5. Insert_Courses_Script.sql
6. Insert_Enrollment_Script.sql  

To insert the sql file into your database:
on Unix/Unix-like systems (depending on your system you may or may not use sudo or have to use sudo or any previlege esclation):  sudo mysql -u root -p < Create_Tables_Script.sql
on Windows (Powershell): Get-Content Create_Tables_Script.sql | mysql -u root -p (if that does not work try running as Administrator)


