#GIT FLOW
cd ..1. Create a central repository on a server

	echo "# System-Designer" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin https://github.com/cyborg999/System-Designer.git
	git push -u origin master

2. Clone the new repositories
	
	git clone

3. Check Status
	
	git status

4. Add files
	
	git add <filename> or *

5. Commit Changes

	git commit  / git commit -m "message"

6. Send changes to central repo
	
	git push origin master

7. Get changes from other remote programmer
	
	git pull --rebase origin master

==================================


8. Create a new branch
	git checkout -b branch2 master

9. Check branches
	git branch //git branch branch2 to switch branch

10. Push changes from new branch to main branch
	git push -u origin branch2

	//git push first then git pull after this command
