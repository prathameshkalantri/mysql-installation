# mysql-installationHow to install mysql in linux mint:
use following steps:
1:before installing , check if there are any mysql files or refference . if yes ,those needs to  be cleard.       
use following command in terminal:
sudo apt-get remove --purge mysql*  
sudo apt-get purge mysql*  
sudo apt-get autoremove  
sudo apt-get autoclean  
sudo apt-get remove dbconfig-mysql

2:now download mysql from following link
https://dev.mysql.com/downloads/repo/apt/ or download from mysql official website,

3:install downloaded deb file using package installer or using following command
sudo dpkg -i mysql-apt-config_0.8.10-1_all.deb

4: check for any update using sudo apt-get update
then run sudo apt-get install mysql-server
during this proccess you will be prompt to set password

5: check if you can login to mysql using mysql -u root -p

6:now install mysql workbench using following comand sudo apt-get install mysql-workbench

how to uninstall mysql completely in linux mint:
use following command , it will completely remove mysql from your linux machin
sudo apt-get remove --purge mysql*  
sudo apt-get purge mysql*  
sudo apt-get autoremove  
sudo apt-get autoclean  
sudo apt-get remove dbconfig-mysql



How to install intellij in linux mint :
1: go to the official website of intellij idea and download it.

2: read all the instruction of installation from "install-linux-tar.txt" and follow the step

3: to create desktop entry of intellij, go to tool>create desktop entry.

How to uninstall intellij :
1: delete all the packages , derectories and files from the machine.


How to connect machine code to the local database:

it depends on which database are you using, in my case in using mysql database.
to connect my sql database :
there are two ways :
1:a: download mysql connecter.jar file
  b: open your intellij project and go to project structure > libraries > "+" on the left upper corner > java and give the path of mysql connecter.jar file in the searchbox. and apply.

2:go to intellij project and go to project structure > libraries > "+" on the left upper corner > from meven put this "mysql:mysql-connector-java:5.1.40" link in the searchbox and apply. 




