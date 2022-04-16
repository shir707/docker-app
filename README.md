# Node.js Weight Tracker

##General info <br />
*This is a CI/CD pipeline for deploying docker image of the application "Weight Tracker", and store it in azure container registry.<br />
*In the CI pipeline, I build the image docker for checking feature branch. When the merging into master is done, there is a build process and push into azure container registry that I've created by terraform (called: "shirRegistry) <br />
*In the CD pipeline, I log in into my azure container registry, pull the image from it and create the env file by the vars that I stored in the library dynamically.<br />
*Finally,I used ansible in order to run the image in all the servers

##Technologics <br />
Project is created with: <br />
*terraform code. git for the code: https://github.com/shir707/TF-Code <br />
*ansible code. git for the code: https://github.com/shir707/ansibleProject <br />
*an explanation for the app and requirments: https://github.com/shir707/bootcamp-app <br />

##In order to connect to the website application <br />
for prod enviorment: http://20.83.142.200:8080/list  <br />
for stage enviorment: http://20.118.16.14:8080/list


