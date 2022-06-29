# thefork_challenge
Automation Framework to automate tests with selenium


*NOTE* - 
- I have written @BeforeMethod and @AfterMethod in the Test classes because we have 2 different URLs for each test(thefork and pokemonAPI). In real scenario both this methods would be in TestBase class.

- Please click on the checkbox manually to verify Robot recaptcha as it is not possible via automation(according to my knowledge). I have put thread.sleep just before this step so that we have some time to manually do it.

- WebDriverManger has been used to initialize and get browser drivers 

- It's a Maven project, Dependencies have been managed in pom.xml. You may have to install testng plugin 

- Added the test report emailable-report.html to the repo after running the tests locally, just for reference

- I could not understand the 2nd part of pokemon i.e "pokemon that are normal type or that one of their types is normal type". So I did not do it. The first part is done and have stored the urls in the list.


*STEPS* - 
Right click on POM.xml and -
- Clean and Build the project with Maven 
- Install the project with Maven Install option
If there is any error, please check if the Java compiler that you are using is 1.8 or higher.
Goto the project and right click --> Properties --> Java compiler


*EXECUTE* - Right click on testng.xml and Run As TestNG suite

 

