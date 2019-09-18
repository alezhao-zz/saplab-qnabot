### **Create a QnA Bot with Azure Bot Service**

Create a QnA chat bot from the **Publish** page for an existing knowledge base. This bot uses the Bot Framework SDK v4. You do not need to write any code to build the bot, all the code is provided for you.

![](https://iothubstorageaccts.blob.core.windows.net/botpic/overview.png)



## **System requirements**

You must have the following to complete this lab:

- Azure Subscription
- Windows 10

## **Exercises**

This Hands-on lab includes the following exercises:

1. ###### Create a knowledge base by FAQ URL

   https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/tutorials/create-publish-query-in-portal

2. ###### Create a QnA Bot with Azure Bot Service

   https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/tutorials/create-qna-bot

3. ###### Create a knowledge base by Excel FAQ

   - Open QnA maker portal <https://www.qnamaker.ai/>, click Create a knowledge base at upper tab.

   - Under section **Step 2**, select **Microsoft** in **Microsoft Azure Directory ID** section, choose lab provided `Azure Subscription` in **Azure subscription name** section, select **QnA maker Service Name** which created by pervious step in **Azure QnA service** section.

     ![](https://iothubstorageaccts.blob.core.windows.net/botpic/23.png)

   - Under section **Step 3**, entry your `Knowledge Base Name` in **Name your KB** section.

   - Under section **Step 4**, click c, select **[qnamaker.xlsx](https://alebotstorage.blob.core.windows.net/botprepare/qnamaker.xlsx)** to upload

     ![](https://iothubstorageaccts.blob.core.windows.net/botpic/24.png)

   - Click **Create your KB** at the bottom. 

   - Under your created QnA Maker App, click **Save and train** at upper of right-hand corner.

     ![](https://iothubstorageaccts.blob.core.windows.net/botpic/25.png)

   - After train completed, select **PUBLISH** at upper panel, click **Publish**

     ![](https://iothubstorageaccts.blob.core.windows.net/botpic/26.png)

     

   - Do **Exercise 2** again to create a new bot service

Estimated time to complete this lab:  **30** **minutes**.
