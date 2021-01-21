# GitHubActions to Validate Deployment Manager File

A GitHub Action will be triggered as and when there is a modification in hms_deployment_manager.txt.   
This is created to ensure that the first three lines of the file are present in the file.  
An action will be triggered for each push and pull request. The action will be triggered if and only if there is a change in hms_deployment_manager.txt  
A workflow will invoke a shell script which validates the first three lines text as per CI requirement.  
The shell script checks for the empty lines as well.  

# Sample GitHubActions to Label baed on the configuration file.

Adding labels based on the modification done to file inside a specific folder.

# GitHubActions to Label a PR

A PR will be marked with *URGENT* label if the title contains 'urgent' or 'emergency' in it.

# GitHubActions to Label post PR review

A PR will be marked with *PR Reviewied* label after the PR is approved.


