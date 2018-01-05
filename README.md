# EcommerceProject
##Technologies Used HTML 5

CSS3

JavaScript

Bootstrap 

Maven 

Spring 

Hibernate 

Apache Tomcat 9.0

Java Development Kit version 8 Steps to Install Eclipse- •	Download the Eclipse Installer windows 64bit (Recommended) or Windows 32bit, from https://eclipse.org/downloads/index.php

•	Start the Eclipse Installer executable For Windows users, after the Eclipse Installer executable has finished downloading it should be available in your download directory. Start the Eclipse Installer executable. You may get a security warning to run this file. If the Eclipse Foundation is the Publisher, you are good to select Run.

•	Select Eclipse IDE for JAVA EE Developers(Mars/Neon/oxygen).

•	Select your installation folder, Specify the folder where you want Eclipse to be installed. The default folder will be in your User directory. Select the ‘Install’ button to begin the installation.

•	Launch Eclipse, Once the installation is complete you can now launch Eclipse.

Installation Video: https://www.youtube.com/watch?v=35NUuhmQuB4 ###Maven Installation-

Maven is a Java tool, so you must have Java installed in order to proceed. Apache Maven 3.5.2  is the latest release and recommended version for all users. Which can be downloaded from http://maven.apache.org/download.cgi.

Another way to install Maven plug-in for Eclipse:

•	Open Eclipse

•	Go to Help -> Eclipse Marketplace

•	Search by Maven

•	Click "Install" button at "Maven Integration for Eclipse" section

Configuration

###Configuring Maven into Eclipse

•	First download maven from here(http://maven.apache.org/download.cgi) in your system

•	set Maven environment variables

M2_HOME: ....\apache-maven-3.5.2 \ maven installed path M2_Repo: D:\maven_repo \If change maven repo location M2: %M2_HOME%\bin

•	Open Eclipse

click on Windows -> Preferences

Choose Maven from left panel, and select installations.

Click on Maven -> "User Settings" option form left panel, to check local repository location.

###Configuring Tomcat9 server into Eclipse

•	Download Tomcat 8 from https://tomcat.apache.org/download and place it within any local folder.

•	Start Eclipse and click on “Servers” tab in the workbench. Go ahead and try adding a new server. You would find option for Tomcat 9 available for selection as shown below.

•	After clicking Finish, you would see a new server added with the name as “Tomcat v9.0 Server at localhost”. Start the server.

•	Check http://localhost:8080 (provided you installed Tomcat 8 and set Http port as 8080)
