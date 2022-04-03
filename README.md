# necbdc.org.in
North East Cane and Bamboo Development Council


To Set up the environment:

Step 1: Clone the repo 
	Commnad: git clone <repo-name>
	Example: git clone https://github.com/dhirajinchalkaranji/codefellas.git

Step 2: Create your own branch
	Command: git branch <branch-name>
		 git checkout <branch-name>
	Example: git branch huzaifa_branch
		 git checkout huzaifa_branch

Step 3: Check git url 
	Command:  git remote -v
	
	Origin  should be your repo
	Upstream should be main repo (master) 
	if not then follow the commands:
	
	Commnad: git remote add origin <your-repo-url>
		 git remote add upstream <main-repo-url>

	Example: git remote add origin https://github.com/mdhuzaifapatel/codefellas.git
	         git remote add upstream https://github.com/dhirajinchalkaranji/codefellas.git

	Visit GitHub and raise Pull request

---------------------------------------------------------------------------------------------------------------------------------

If you make any changes to the files in your system, then you have to push:

Step 3: Check status of your changes
	Command: git status

Step 4: Add your changes to commit
	Command: git add . 

Step 5: Commit your changes [with commit-message (optional)]
	Command: git commit 
		 git commit -m "<your-message>"
	Example: git commit -m "huzaifa's commit" 

Step 6: Push your changes 
	Command: git push origin
-
--------------------------------------------------------------------------------------------------------------------------------
To pull the changes made by other contributors:

1. Switch to master
	Command: git checkout master
2. Pull the changes
	Commnad: git pull upstream



 
