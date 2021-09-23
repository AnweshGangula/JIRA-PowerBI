# JIRA-PowerBI

Visualize JIRA data in PowerBI - [Jira API v3](https://developer.atlassian.com/cloud/jira/platform/rest/v3/intro/)

Table of Content:
1. [Create API Token](#1-Create-API-Token)
2. [Configure PowerBI Desktop](#2-Configure-PowerBI-Desktop)

![Sample Screenshot](Images\JIRA-PowerBI-Sample-Image.png)

## How to use

The JIRA content pack in Power BI relies on JIRA API. The Power BI team has originally shared the [JIRA content pack](./Original_Jira_PowerBI_ContentPack.pbit) in the [following blog post](https://powerbi.microsoft.com/en-us/blog/explore-your-jira-data-with-power-bi/) which was later removed.\
 Below are the steps to use the .pbit file
### 1. Create API Token
- Navigate to the API Token page in your Atlassian account settings (https://id.atlassian.com/manage/api-tokens)
    - Login to your atlassian account.
    - Navigate to `Account settings > Security` 
    - Under API Token, click on 'Create and manage API tokens'.
- Click the "Create API Token" button and enter any name of your choice like "PowerBI" and click Create
- Copy the token to clipboard using the "Copy" button\
  > Note: You will not be able to see the token again. Make sure to store the token somewhere safe

### 2. Configure PowerBI Desktop
- Download the [Original_Jira_PowerBI_ContentPack.pbit](./Original_Jira_PowerBI_ContentPack.pbit) PowerBI template and double click to open it.
- Once the file is open, it will ask to input the JIRA URL of your company. Eg:\
    `https://companyName.atlassian.net`
- Enter the URL and click **Load**
- After few seconds of processing, you will be asked to enter your credentials.
    - Choose "Basic" on the left sidebar
    - Type in your "**Email Address**" in the "User name" field and enter the "**API Token**" copied from [step 1](#1-Create-API-Token) in the "password" field
- Click connect or hit enter
- The dashboard will start populating the content in visuals in the ContentPack template.
