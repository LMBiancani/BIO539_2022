Version Control with Git - Example

This assignment assumes you know how to use git on your computer locally
- Go to http://github.com and sign up for an account
- Create a new github repository using the + in the upper righthand corner
- Select a name (it doesn't matter for the assignment, but usually you will pick something informative)
- In your Terminal (Mac / Linux) or git-bash (Windows) go to your local repository If your git names your default branch "master" switch this to "main"
	git branch -m master main
- Connect your repository to your "remote" github repository (conventionally termed origin)
	git remote add origin https://github.com/rachelss/curly-enigma.git
- Check that "origin" indicates the remote repo
	git remote -v
- Push your local "main" repository to github (i.e. duplicate the entire repository including all the commit history to your remote "origin" site)
	git push origin main
- Make a change to your repository, save it, and commit the change

Work in pairs for the rest of the assignment
- Assign one partner to be person #1 and one as #2
(1) in your github repository click the settings button and add #2 as a collaborator
