# Git_Info
all about Git
## First usage
* set username and email
* ```git config --global user.name "Name"```
* ```git config --global user.email "email"```
## Clone Code From Git
* ```git clone https://locationofurlrepository/repositoryname.git``` change this like according your repository url
## Using Git for Existing Project but not yet tracked by local git also
* ```cd existing-project```
* ```git init```
* ```git add --all```
* ```git commit -m "Initial Commit"```
* ```git remote add origin https://locationofurlrepository/repositoryname.git``` change this like according your repository url
* ```git push -u origin master```
## Using Git for Existing Project and code tracked by local git
* ```cd existing-project```
* ```git remote set-url origin https://locationofurlrepository/repositoryname.git```
* ```git push -u origin --all```
* ```git push origin --tags```
