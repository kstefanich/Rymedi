# Dashboard

- Rapidtest Dashboard is a powerful tool that enables you to review the collected testing data with multiple charts and KPI´s. Optionally you can also use 
  external reporting tools like Tableau to analyse the testing data. 

- The data can be further filtered by Testing Group, sub organizations and the time frame for more in depth data analysis.

- In the Dashboard Screen you can check the following charts:
	
    - **Patient Registration per Day**: That’s the number of patients that are being registered every day. It counts the new users that have completed the 
      registration form, have received a Unique QR-Codes and are ready to be tested.

   	 {% hint style="info" %} Check this chart to control any anomalies during the registration process. If the registration flow doesn’t meet your expectations 
   	 maybe some of your target users haven’t received the invitation link. {% endhint %}

    - **Patient Testing per Day**: This is the number of patients that are being tested each day. It is an indicator of how many tests are being initiated every 
      day, and whether they are still awaiting results or have been completed.

    - **Test Results**: This is a comparative chart between the positive and negative results. An increase of the positive results could mean that there is a cluster of infection in your Testing Group. 
    
    - {% hint style="info" %} Antibody Test Results are updated every day at UTC 0. Antiviral Test Charts are updated every 7 days at UTC 0. {% endhint %}
    
    - **Test Kit Status**: This chart shows you the number of total Initiated, Completed Tests and those awaiting CLIA Audit (if that feature is enabled) at the time. 
    
    - {% hint style="info" %} It is important that Initiated, Completed and CLIA Audit tests stay in equilibrium. For example, more Initiated Tests than 
  	  Completed Tests could be an indicator that there is a bottleneck in the diagnostic laboratories. {% endhint %}

    - **Patient Gender**: This chart shows you how many users of each gender have been registered on the platform.

    - You can Download the Dashboard reports as a PDF file.
    
    - **Registered**: Total Sum of all registered Patients.

    - **Tested Patients**: Total Sum of all tested Patients.
    
    - **Reported**: Total Sum of all Patients that received at least one test result.
    
    - **Processing**: Total Sum of all Patients that are awaiting a Result.
    
    - **Total Patient Tests**: Total Sum of all unique Patients tested.
    
    - **Test Kits**: Total Sum of all created Test Kit Labels.
    
   	 {% hint style="info" %} The total number of tested patients and Test Kits can be different because one patient may have been tested multiple 
   	 times. {% endhint %}
    
    - **Sample Initiated**: Total Sum of all Initiated Tests samples.
    
    - **CLIA Review**: Total Sum of all Test Kits that need to be CLIA reviewed.
    
    - **CLIA Reject**: Total Sum of all Test Kits that have been rejected in the CLIA review.
    
    - **Completed**: Total Sum of all completed Tests.
    
    - **Expired**: Total Sum of all Test Kits that have been initiated and not completed after a few weeks. They are marked as expired.
    
    - **Negative**: Total Sum of all Test Kits with a negative, or not detected, test result.
    
    - **Positive**: Total Sum of all Test Kits with a positive, or detected, test result.
    
    - **Inconclusive**: Total Sum of all Test Kits with a inconclusive test result.
    
    - **Invalid**: Total Sum of all Test Kits with an invalid test result.

- Tap on Dashboard (1) in the side menu to open the Dashboard.

![](https://user-images.githubusercontent.com/105650529/170533701-e5334202-ad60-4e4b-9415-961826f4258d.jpg)

- You can Download Testing Reports (2).

- Select an specific Sub Organization or Testing Group (3) to see its data.

- Select the Time Zone and the data from a range of two dates(4). 

![](https://user-images.githubusercontent.com/105650529/170533713-d2d0426b-a0eb-49a6-8c08-01a706db3eaa.jpg)

- Check the global progress of the test results using the data visualization tools (5).

![](https://user-images.githubusercontent.com/105650529/170533728-dfd70eed-76ab-440b-acc5-91beccee27b9.jpg)



