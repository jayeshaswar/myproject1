Project Name : FoodInspection

 ------------------------------------------------------------------- OPERATING SYSTEM SETUP ------------------------------------------------------------------------
 
Install Operating System Ubuntu 16.04 (64-bits)

Use Python version  Python 2.7

IDE :  Pycharm

--------------------------------------------------------------------PROJECT DATA & DEPENDENCIES SETUP ------------------------------------------------------------------------------

Install python-pip     // apt-get install python-pip                                                                                          
Install verious requirements of python packages for project.                    // pip install -r requirements.txt                                                                                                                                                     
Install remaining packages using source files (tar.gz )                         // python setup.py install


--------------------------------------------------------------------DATABASE SETUP ------------------------------------------
----------------------------------------------------------

Install Mysql database server in ubuntu  // sudo apt-get install mysql-server-5.6

Install mysqlclient for python           // pip install mysqlclient

Install some dependencies                // sudo apt-get install python-pip python-dev libmysqlclient-dev 
                                        // pip install MySQL-python

Install Mysql Workbench for GUI purpose  // sudo apt install mysql-workbench

Set the Root user for mysql workbench    // user : root , password : xbyte

Make Database 'foodinspection' & Table 'data1' with column name " Id, F_name, Facility_address, 

Number_of_Critical_violations, Number_of_Non_critical_violations, Violation_Link" 


-------------------------------------------------Scrapy Code -----------------------------------------------------------------------------------------------------------------


Start project in scrapy            //scrapy startproject Foodinspection

set up pipelines.py's name into settings.py

In directory named spiders : Add new python file : foodspider.py

Set up Database info in settings.py

Write your code into foodspider.py

Write your code into pipelines.py

Write your code into items.py

Run your project                   //scrapy crawl foodspider

