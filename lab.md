## AI Powered Call Center Intelligence Solution Accelerator

![](/images/img001.png)

## Getting started

1. Once the VM is provisioned, open the **Visual Studio Code**.

1. Click on the **File** and select **Open Folder**, select the file from the **C:\Users\Demouser\Program1.cs** and click on **Open**.

1. Once the file is opened, select the **Terminal** and enter the below command and verify the output.

   `````
   dotnet run
   `````
   
   ![](/images/img007.png)

1. Click on the **File** and select **Open Folder**, select the **C:\AllFiles\AI-Powered-Call-Center-Intelligence-Solution-Accelerator-main** and click on **Open**.

1. Navigate to the **azure-speech-streaming-reactjs\speechexpressbackend\.env** and replace the value **TEXTANALYTICS_ENDPOINT** with the text analytics endpoint and save the file.

1. Now click on the **Speechexpressbackend** and select open in **Integrated Terminal**.

1. Run the Commands to start the **Speechexpressbackend**

   `````
   npm install -all
   
   npm start
   
   `````
   
1. Once it gets started, you will get the URLs.

1. You can try accessing below URLs from browser to verify that the backend component is working as expected.

   ``````
   http://localhost:8080/api/sayhello
   http://localhost:8080/api/get-speech-token
   ``````
  
 1. Now click on the **Speechreactfrontend** and select open in **Integrated Terminal**.
 
 1. Run the Commands to start the **Speechreactfrontend**.
 
    `````
    npm install -all
   
    npm start
   
    `````
   
 1. Once it gets started, you will get the URLs.
 
 1. Open a browser and go to **http://localhost:3000** to access the app. Click on the microphone icon on the web page and start talking. You should see transcription displayed on the web page in real-time.


>Note : If you are getting error, run the below command and perform the step 10-13.

 ````
 npm audit fix --force
 ````
 
 ## Accessing the Power BI Report
 
 1. On the LabVM, Double click on the SpeechInsights.pbit on the desktop to open the **PowerBI** Files.
 
 1. After Power BI Desktop has finished loading, it will prompt you to enter SQL server and database information. You can also be found in the Overview page of the SQL Database in your Azure Portal.
 
 1. On the Power BI file provide the values of **SQL Server Name** and **Database Name**. Click on **Load**.
 
    ![](/images/img006.png)
    
    ![](/images/img002.png)


1. After a few seconds, another window will appear and prompt you to enter in credentials to access your SQL database. Select Database as the credential type, and enter the user name and password. Then click on **Connect**.

   ![](/images/img003.png)

   > Note : You can find the details for the username and password under **Environment Details** tab.

1. You should now be looking at the Cover page of the Power BI report template you opened.
 
   ![](/images/img004.png)
   
 ## Congratulations!! You have completed the lab Successfully

