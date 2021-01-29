## Setting up lab enviroment

- Login to your azure enviroment (ensure the account you use has at a minimum has Contributor role privilege)
- Open cloud shell (it would create the shell enviroment if it is the first time being accessed)
- Go to the storage account linked to the the cloud shell environment
- In the storage account click on "File shares" tab on the left side menu
- Click on the fileshare name that is displayed on the right hand pane (only one should have been created by default)
- Once inside the file share, click on "Add directory" on the top and name it "openhack"
- Click on newly created "openhack" directory and then click on "Upload" button on top. Upload files "deploy.sh" and "azuredeploy.json" available in "deploy" folder of this guide
- Create another directory called "jenkins" inside "openhack" directory and upload "default-user.groovy" & "Dockerfile" available in "deploy/jenkins" of this guide
- Now in the cloud shell command line type -

 `cd clouddrive/openhack`

 `bash deploy.sh -l uksouth`



Notes:
- please refer to deploy/deployment.md if you need more details on the deployment

- original repo - https://github.com/microsoft/OpenHack/blob/main/byos/devops-2.0/deployment.md
