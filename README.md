## Description

This project was to create a reporting tool that would return information for 3 given questions. I did this by using python along with the module psycopg2 to be able to connect to database. Then I used postgreSQL queries to get the information wanted from the database which then can be displayed on the console as plaintext.


## Instructions

1. Download and install the following:
    Python 3.7.3
    VirtualBox 6.0.8
    Vagrant 2.2.5

2. Download the vagrant setup file provided by udacity and place into the directory where you want your program to run.

3. Download newsdata.sql and LogAnalysis.py files and place inside the same directory as the vagrant file.

4. Open a terminal in the directory and use vagrant up to start the virtual machine then use vagrant ssh to log into the virtual machine.

5. Once logged in cd to the vagrant directory and then run the command ```psql -d news -f newsdata.sql```.

6. In the terminal run ```python LogAnalysis.py``` and it should display the answers to the questions.