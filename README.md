# Python CRUD + MySQL

Python-based program created for data management needs CRUD (Create Read Update Delete). 
<br>Integrated with MySQL as data storage

# Application Needed 
1. Xampp (Apache & MySQL Server)
<br>Download : https://www.apachefriends.org/xampp-files/7.3.29/xampp-windows-x64-7.3.29-0-VC15-installer.exe
2. Python
<br>Download : https://www.python.org/ftp/python/3.7.4/python-3.7.4-amd64.exe
4. Pip
<br>Installation Guide : https://degananda.com/cara-install-python-pip-package-installer-pada-windows/

# Install MySQL Connector
- Open CMD
- Enter on CMD : pip install mysql-connector 
- Wait until finish

# Activate Apache & MySQL Server on Xampp
![image](https://user-images.githubusercontent.com/25089714/126472803-5a5d8c54-cfd2-4ce0-bded-01dd53fa090d.png)
<br><br>**Make sure Apache & MySQL server is active (See Screenshoot) !**

# Create Script Function
- Connection Function to Database (with mysql-connector)
<br>See Script Here : https://github.com/faishalcode/Python-CRUD-MySQL/blob/main/Source%20Code/connect.py

- Create Database Function
<br>See Script Here : https://github.com/faishalcode/Python-CRUD-MySQL/blob/main/Source%20Code/create_db.py

- Create Table Function
<br>See Script Here : https://github.com/faishalcode/Python-CRUD-MySQL/blob/main/Source%20Code/create_table.py

- Insert Data Function
<br>See Script Here : https://github.com/faishalcode/Python-CRUD-MySQL/blob/main/Source%20Code/insert.py

- Update Data Function
<br>See Script Here : https://github.com/faishalcode/Python-CRUD-MySQL/blob/main/Source%20Code/update.py

- Show All Data Function
<br>See Script Here : https://github.com/faishalcode/Python-CRUD-MySQL/blob/main/Source%20Code/view_all.py

- Show One Data Function
<br>See Script Here : https://github.com/faishalcode/Python-CRUD-MySQL/blob/main/Source%20Code/view_one.py

- Show Many Data Function 
<br>See Script Here : https://github.com/faishalcode/Python-CRUD-MySQL/blob/main/Source%20Code/view_many.py

- Delete Data Function 
<br>See Script Here : https://github.com/faishalcode/Python-CRUD-MySQL/blob/main/Source%20Code/delete.py

# All In One Function (All Function in 1 Application) 
![image](https://user-images.githubusercontent.com/25089714/126481865-2c0497dc-da7a-444e-814c-0e997b0735a5.png)
<br><br>See Script Here : https://github.com/faishalcode/Python-CRUD-MySQL/blob/main/Complete%20Application/app_crud.py

# Little Problem 
I have some little problem while make a code 
- Error Code : 
<br> Traceback (most recent call last):
<Br>File "<frozen importlib._bootstrap>", line 1518, in _find_and_load_unlocked
<br>AttributeError: 'module' object has no attribute '__path__'
**<br>Solve with this solution : https://forums.mysql.com/read.php?50,584171,584729#msg-584729**
  
- Error Code : 
<br>.ps1 cannot be loaded because the execution of scripts is disabled on this system [duplicate]
**<br>Solve with this solution : https://stackoverflow.com/questions/16460163/ps1-cannot-be-loaded-because-the-execution-of-scripts-is-disabled-on-this-syste?lq=1**

# Reference   
1. https://www.petanikode.com/python-mysql/
2. https://stackoverflow.com/
  
<br>Have some script or code request? 
<br>Find me on : https://faishalcode.github.io

<br>Thanks for visiting my little code, Hope can help your problems :)
