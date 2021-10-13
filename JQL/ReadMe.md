# Jira & PowerBI - using JQL

Reference: https://community.powerbi.com/t5/Desktop/Jira-and-Power-BI/m-p/801779/highlight/true#M385759

## Steps:
> **Note**: Use the steps in [Main ReadMe](../README.md#how-to-use) file to get API token and Configure PowerBI

1. Once you open the [Jira PowerBI JQL.pbit](./Jira_PowerBI-JQL.pbit) file, it will ask for 2 inputs
    1. URL:\
    input your company url which looks like - `https://companyName.atlassian.net`
    2. JQL (Optional): This is an optional field.\
    If you're familiar with JQL in Jira and would like to filter the data accordingly, copy the JQL query from your JIRA web app and paste it here.\
        > **Note**: all data will be loaded if you leave this blank
2. Hit enter and the default visuals will be loaded.

## Tip:

The **Jira PowerBI JQL.pbit** file contains a function called `JQL to List` which can be invoked in a table with 
- a column containing multiple Jira URL and 
- an optional column with respective JQL for each URL. 

This will help in saving time to extract data from multiple URL's, but extracting them all at once.
