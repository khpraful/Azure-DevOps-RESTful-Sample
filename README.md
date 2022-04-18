# Azure-DevOps-RESTful-Sample
In the config.py file, add the assignee (person or group) in the user field and personal access token (generated through Azure DevOps) in the token field
In the approve_deployments.py file, replace organization with Azure DevOps organization name and project with the name of project under that organizaiton in the urls
Execute approve_deployments.py
It will display list of all pending approvals for the configured user along with useful details such as release pipeline name, environment, approval type, etc in order to make informed decision
It will also display the list of approval ids
Enter the approval ids you would like to approve in comma-separated fashion. The list of approval ids is available as output in above step in case you want to copy-paste and approve the entire list in one go. Please make sure to provide only comma-separated list without any column brackets ([ ]) at beginning and end
It will ask for confirmation. To confirm, enter “y” or “Y”, else enter “n” or “N”
Enter approval comments
If valid approval ids are provided, the approvals will take place and confirmation messages will be displayed
