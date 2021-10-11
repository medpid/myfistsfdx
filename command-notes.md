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

### sfdx force:org:create -f config\project-scratch-def.json --setalias myfistsfdx --durationdays 30 --setdefaultusername --json --loglevel fatal
: Create a scratch ORG

### Open Default Org
: To open the scractch org that was created.

### sfdx force:user:password:generate
: To generate password for the scratch org

### sfdx force:user:display -u myfistsfdx // alias used
: To get the userinfo and password anytime

### sfdx force:org:delete
: To delete the default ORG.
