# Jira & PowerBI - using JIRA Filter

## Steps:
> **Note**: Use the steps in [Main ReadMe](../README.md#how-to-use) file to get API token and Configure PowerBI

This is a Power BI Template that extracts the JIRA issues from 
1. Account specified by the URL parameter
2. AND the filter with the filterId parameter

Create a custom filter in your JIRA account and pass the filterId as the parameter. Usually, the filters are all stored in the following url 
> `https://companyName.atlassian.net/jira/filters`

and the filterd can be identified from the URL of the filter:
> `https://companyName.atlassian.net/issues/?filter=13014`