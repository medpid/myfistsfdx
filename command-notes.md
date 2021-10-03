### sfdx force:project:create --projectname myfistsfdx  
: To create a project

### cd .\myfistsfdx\  
: To switch to the project directory

### sfdx force:org:list  
: To list the orgs, this will not give any results at this time. 

### sfdx force:auth:web:login --setdefaultdevhubusername --setalias vasutest  
: To set the developer org, this will prompt for login in the web. 

### sfdx force:config:set defaultdevhubusername=vasutest -g
: To set the alias as the global default.

## Creating a scratch ORG

### 