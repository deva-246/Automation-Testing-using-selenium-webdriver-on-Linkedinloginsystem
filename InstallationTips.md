## Selenium web driver installation

1. Visit https://www.selenium.dev/downloads/

2. Search for java > download the stable version

3. Extract and store the files in a desired folder

4. Now go to eclipse ide > right click on your project > Properties > Java Build path

5. click module path > Add JARS > select all the files from the extracted folder > Apply and close

6. Now repeat the step 4 and 5 but this time select all the files from the extracted lib folder > apply and close

7. Now as a result of installation **Referenced Libraries** will be displayed in the project stack with various files in it.
   ![image](https://github.com/deva-246/Automation-Testing-using-selenium-webdriver-on-Linkedinloginsystem/assets/75877347/0f4bc963-5820-45b2-a390-b7acabd26386)



## Googlechrome driver installation

1. First identify your browser version by clicking ⋮ > Help > About Google chrome > Identify the  version.

   ![image](https://github.com/deva-246/Automation-Testing-using-selenium-webdriver-on-Linkedinloginsystem/assets/75877347/8af5307f-0511-43b4-9433-7e790cca15ea)

2. Now visit https://chromedriver.chromium.org/downloads and search for the desired web driver

3. Incase If you are using Chrome version 115 or newer, please consult the Chrome for Testing availability dashboard. This page provides convenient JSON endpoints for specific ChromeDriver version downloading > https://googlechromelabs.github.io/chrome-for-testing/ > download the stable version by,

   3.1 Copy pasting the url on another tab > automatic download begins

4. Now store the extracted files in a desire folder

5. In the script to enable the chromedriver use the code ,

         System.setProperty("webdriver.chrome.driver", "path of chromedriver.exe file in your system");

6. Once you run the script > chrome gets automatically called and performs the required testing functions. 
