# FirstRepository
Created First Repository on Github to explore

=> GIT Commands I used
	- git init
	- git remote add origin "Path of Repository from Github"
	- git pull origin master
	- git status
	- git add -A(For all files)/<FileName>
	- git commit -a -m <"Message">
	- git commit -m <"Message"> after git add -Add
	


=> Steps Followed to work with Git Repository
	- Created an account on https://github.com
	- Created a new repository (say FirstRepository)
	- Installed Git on local machine
	- Created a folder for Project; Right click and click Git Bash Here from inside the folder
	- git init command on Git Bash to create local repository
	- git remote add origin "Path of FirstRepository from Github" command to link remote/centralized repository to local repository
	- git pull origin master command to get the latest files from remote/centralized repository to local repository
	- git status command to check status of the file in the current branch
	- git add -A(For all files)/<FileName> command to add to staging/index after adding/modifying the file
	- git commit -a(For all files) -m <"Message"> command to commit to local repository for all files in staging/index
	- Added new text file.
	- git commit -a -m <"Commit all but one new file not staged/indexed"> command commits all the modified files (at least staged once) but does not commit the untracked file. However no error is thrown.
	- git commit -m <"Message"> command works when all the files are staged after modification by command - git add -A
	- 

=> ProjAddtoSourceControlWithCreate
	- Create New Git Repository option not displayed; Displayed Add to Source Control instead; On projectcreation displayed VSS login (May be because VSS was installed)

=> ProjFromDirectVS
	- Created Local Git Repository via Add to Source Control on right bottom after creating new project
	- Team Explorer -> Manage Connections -> Sync -> Provided empty repository and Github credentials to push all commits to github
