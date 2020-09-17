# GitHubAction to Verify hms_deployment_manager.txt

A GitHub Action will be triggered as and when there is a modification in hms_deployment_manager.txt. 
This is created to ensure that the first three lines of the file are present in the file.
An action will be triggered for each push and pull request. The action will be triggered if and only if there is a change in hms_deployment_manager.txt
A workflow will invoke a shell script which validates the first three lines text as per CI requirement.

#GtiHubAction to Label

A PR will be marked with *URGENT* label if the title contains 'urgent' or 'emergency' in it.
