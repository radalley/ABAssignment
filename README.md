# Deployment of a Python (Flask) web app to Azure App Service - Sample Application for Anheuser-Busch

This is the sample Python Flask application utilizing GitHubActions to deploy through Azure. Created for coding assessment for Anheuser-Busch Interview process 

Below are the instructions for the assessment:

Use GitHub Actions to create a CD process that can deploy an application to Azure.
- Use any language you desire. In this case, I chose Python with Flask
- Deploy to any resource in Azure (static web app, app service, AKS, etc). In this case, I chose App Service
- Use the Free subscription in Azure if you don’t have one already. Azure subscription set up for an account
- Store the code in GitHub and make the repository Public. Code has been stored and made public

Definition of Done: Requirement Checklist
- Sample App cloned and necessary files committed into the repository
- .Yaml file created for use by actions. On commit deploys to Azure
- Secrets created and Resource Groups made in Azure
- Commits in GitHub deploy directly to Azure
- App displays changes on https://dalleydevapp.azurewebsites.net/

Resources and Docs used:
Sample Python Flask app for deployment to Azure:        https://docs.microsoft.com/en-us/azure/app-service/quickstart-python
Use GitHub Actions to connect to Azure:  https://learn.microsoft.com/en-us/azure/developer/github/connect-from-azure?tabs=azure-portal%2Clinux
Docs for the Azure Web Apps Deploy action: https://github.com/Azure/webapps-deploy
More GitHub Actions for Azure: https://github.com/Azure/actions
More info on Python, GitHub Actions, and Azure App Service: https://aka.ms/python-webapps-actions
