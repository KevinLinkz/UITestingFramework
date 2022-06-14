# UITestingFramework
This is my experiment UI Automation Testing Framework.

This framework uses the Singleton Pattern. 
For the report it uses Extent Report,
For frameworks test, it uses testNG,
For UI Testing, it uses page load with WebDriverManager.
For Screenshot, it uses shutterbug.

It uses Thread for testng.xml, it will run together with stably.
The thread will use for run the test and data-provider too.

Steps:
1. Create folder by ddMMMyyyyhhmm every it runs.
2. Run testng.xml
3. Web Driver Manager will setup for init the browser.
4. Test will run the test case.
5. The data it uses Data Provider.
6. Assert will verify the expected.
7. Shutterbug will screenshot every page on the browser and put to ExtentTest.
8. Last, ExtentTest will flush to the ExtentReport.

Dependencies :
1. TestNG
2. WebDriverManager
3. Seleniumhq
4. ExtentReports

Actually data provider can use Excel for dynamic data. 
But if you want performance testing, I think, NPOI it's not good choice.

Improvements would be needed:
1. Actually, I didn't make log. I think it's enough to use ExtentReport for logs.
2. I don't know about uses singleton pattern, it's good or no. 
   because so many config and trouble for the thread access same variable. 

I hope my experiment can give you an idea.
Thank You.


