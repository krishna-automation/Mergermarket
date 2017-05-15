# Mergermarket
Mergermarket - Technical Test

This is a Cucumber JVM Maven project for the automation scenarios from Mergermarket
Project developed in Java covering a Page Object Model framework for the pages navigated. Used Eclipse as the IDE
As this is a Maven project , all the appropriate dependencies for Selenium,Java, Cucumber,Junit,TestNG are pulled in by the pom.xml

The project is tested on Chrome browser and Firefox browser( you should have the latest or any recent chromedriver.exe or  geckodriver.exe on your local machine to initialize the driver and run the tests )
Configure the tag @Chrome or @Firefox in the feature file and Testrunner file , to run on your selected browser appropriately

To run the project--
On your favourite IDE, import the Maven project   (choose existing Maven project)
(In case of Eclipse, you can follow the steps below)

1.	Open eclipse
2.	Click File > Import
3.	Type Maven in the search box under Select source of  “org.mergermarket.automation”
4.	Select Existing Maven Projects
5.	Click Next
6.	Click Browse and select the folder that is the root of the Maven project (probably contains the pom.xml file)
7.	Click OK
8.	Under Projects: click the checkbox next to the pom.xml file
9.	Click Finish


Now you got your “org.mergermarket.automation” in the IDE

Run the Cucumber JVM project

1.	You can normally run the Testrunner class as a Java Application Junit test ( in this case MergerMarketTestRunner.java )

(or)

2.	You can run as a Maven install / build.
Right click on pom.xml and Run as clean and install


