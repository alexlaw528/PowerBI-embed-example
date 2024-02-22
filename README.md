# Embed PowerBI into React

https://learn.microsoft.com/en-us/javascript/api/overview/powerbi/powerbi-client-react

## Embed Procedure

- Requires
  - Embed URL
    - Report cannot be in "myworkspace". Create a new workspace and move or generate report inside of it
    - Retrieve embed URL by making a GET request to `https://api.powerbi.com/v1.0/myorg/groups/{groupId}/reports/{reportId}`
    - Or, from your report web browser navigate to File > Embed Report
  - Access token
    - Access token can be retrieved within web dev tools (chrome)
    - From your published report run `copy(powerBIAccessToken)` to retrieve access token
  - Report ID
    - Can be found in the URL of your report
