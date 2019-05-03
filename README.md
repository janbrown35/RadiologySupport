RADIOLOGY SUPPORT UNITE: Course project for Fundamentals of Mobile Web Application Development
---------------------------------------------
CONTENTS OF THIS FILE

*Introduction

*Requirements

*Recommend modules

*Installation

*Configuration

*Usage

*Contributors

*Troubleshooting

*License




INTRODUCTION
--------------
This file contains the folders of code for the development of a mobile web application.  It begins with the making of a first homepage in Module1 to an almost fully developed website called “Radiology Support” in mod5. The Radiology Support Unite project, modules 2 through 5, contain the code as the website built for Radiology Support professionals who support Radiology software, hardware, and networking.  The website contains pages for tips and forums on what Radiology Support professionals to use on the job. It also contains information on upcoming events for Radiology Support professionals as well as how to obtain continuing education.  A student page is included for students looking to pursue a career in Radiology Support. Here is a link to these modules: http://janmountain.centralus.cloudapp.azure.com/

REQUIREMENTS
-----------------
This project requires:

* An Azure virtual server

* phpMyadmin to connect to server

* Atom or some other HTML editor: https://atom.io/

* Filezilla to transfer files: https://filezilla-project.org/download.php?type=server

* A browser to display the different modules

* DevTools or similar developer tools to make changes and test any changes

* The following modules and their files of code:


Module 1:Configure a Development Environment
http://janmountain.centralus.cloudapp.azure.com/module1/
  
Module 2:Design Your First Home Page
http://janmountain.centralus.cloudapp.azure.com/Mod2/
 
Module 3:Adding New Pages and Database
http://janmountain.centralus.cloudapp.azure.com/mod3/
 
Module 4:Adding Navigation
http://janmountain.centralus.cloudapp.azure.com/mod4/
 
Module 5: Testing and Developing
http://janmountain.centralus.cloudapp.azure.com/mod5/
 
INSTALLATION
-------------------
* Create an account in Azure and then create a storage account.

* Create and configure a LAMP virtual server.

* Connect to the virtual server with SSH such as Putty.

* Create a user account using phpMyAdmin with root and password from the VM server logs.

* Create any new tables using phpMyAdmin or Atom software

* Download Atom software: https://atom.io/

* Download Filezilla: https://filezilla-project.org/download.php?type=server

CONFIGURATION
----------------
* Configure user permission on the Azure server
  -Use phpMyAdmin to create user
  -Use phpMyAdmin to create database and tables 
 * Connect database to website using php file: sample code change to fit server created and user created
<?php
            $servername = "localhost";
            $username = "janedoe";
            $password = "12345";
            $dbname = "mysampledb";

            // Create connection
            $conn = new mysqli($servername, $username, $password, $dbname);
            // Check connection
            if ($conn->connect_error) {
                die("Connection failed: " . $conn->connect_error);
            }
 ?>
* Configure putty to connect to server
* Configure Filezilla to connect to server to transfer files

USAGE
-------
Once you have done the installation you will be able to display the website.  Radiology Support professionals can connect and 
use the website.

CONTRIBUTORS
-------------
* none


TROUBLESHOOTING
------------------------------------------------
* If database not connecting double check code
* If website not displaying correctly use DevTools to test and modify elements and CSS stylesheet

LICENSE
--------
* Not Applicable





