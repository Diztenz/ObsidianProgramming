Git is in a class of it's own.  Git is a repository that stores files, data, etc. 
Git repositories are pulled through the terminal.
* Popular commands include
	* git clone
	* git pull
	* git add . = adds all the files
	* git add (file name.extension) adds just that file
	* git commit = use git commit -m "Title of commit"
	* git push -u origin master(or main)
	* git remote -v = shows you the linked git repository url
	* git restore plus file name (I learned that if the file has spaces you can use " "  or ' ' to include the whole file example file "Capture the Flag.md")


**

NEED HELP?

  

On command line = git <verb> --help or git help <verb> 

<verb> being what you need help on like, add, config, etc etc etc

  

INITIALIZE A REPOSITORY FROM EXISTING CODE

  

go to directory/file location and type git init to initialize a directory

  

To remove a git directory just go to directory and enter: rm -rf .git

  

BEFORE FIRST COMMIT

 git status 

  

 run a touch .gitignore file 

  

ADD FILES TO THE STAGING AREA

  

 git add -A adds all or git add .

 git add filename adds individual files.

 git reset to remove everything from the staging area.

 git status 

  

OUR FIRST COMMIT

 git add .

  
  
  

 git log = will give us the commits we just made, commit author, commit time, commit message

  

CLONING A REMOTE REPO

 git clone <url> <where to clone> if u use a “.” on the where to clone it’ll clone to current dir

  

VIEWING INFORMATION ABOUT THE REMOTE REPOSITORY

 git remote -v 

 git branch -a will list all local and remote branches of the repository

  
  
  
  
  

Terminal commands:

  

ls - lists all of the folders 

ls -la - lists all of the files 
	
cd .. - returns one dir back 

cd - enters a directory

. - just install in the current directory 

 On initial install:

 git --version - checks the version of the installed locally git

  

git config --global [user.name](https://www.youtube.com/redirect?event=comments&redir_token=QUFFLUhqbFJrNWRfSXhnMWprbExpUk9jSmwtZkkwSEw2Z3xBQ3Jtc0tsdTl6QnlMSUY1RDh6XzZfUExSOGNTbl9NU3VyNlpWSjl2N1RuQVUyVi1JelpVTkt1RU5SbThtakIxTU43NEpJeWVpMUFyazAzQnBJMklQTDJuX1BldzB6YTRHZ0pVeC1hemRsWFZKeU1oM1BGc3JnTQ&q=http%3A%2F%2Fuser.name%2F&stzid=Ugw8-6oD_KS5Qp7wOQ14AaABAg) "Your Name" - sets up the name of the user 

  

git config --global [user.email](https://www.youtube.com/redirect?event=comments&redir_token=QUFFLUhqbU1UQXZhbE9OUm16TWlyMm9aQzNoSjZNVlk3QXxBQ3Jtc0ttLUVJMmx5SzYxWGE5TUt5NVlydEFuS2EwaDRlSm9BQVpLbmZiZlJRYmVJZE5WTlZQQzk1ek51OGpMWjFzXzNTWDFtdnFzenFoRzQ5VHQwQ1F4SGhUSld5NXJWaUhJOEhpUU53czJkUVBsS1NVTjk3QQ&q=http%3A%2F%2Fuser.email%2F&stzid=Ugw8-6oD_KS5Qp7wOQ14AaABAg) "yourname@[somemail.eu](https://www.youtube.com/redirect?event=comments&redir_token=QUFFLUhqbUo3Qmc1c292VExjTnN4bnZHLW1hYTkyYlVLUXxBQ3Jtc0ttTW1vd3Y3aHltMENMOTJjTnNnWUFqWUpTc0V0UzdUbUttRzBTUlI4QUU0eTV0VE1EVlVYanhSREVZdS01bGZfdUdZaDZjcGNKME9najg4UzFPVWhJTFNvSElHbEtjdlJyeWtkYURiTGRadVRuYWhuUQ&q=http%3A%2F%2Fsomemail.eu%2F&stzid=Ugw8-6oD_KS5Qp7wOQ14AaABAg)" - sets up the mail of the user

  

git config --list - lists all the git configurations

  

  

For help on commands:

  

git help <verb> (e.g. git help config) OR 

  

git <verb> --help 

  

  

For initializing the project:

  

git init - initializes the git repo in the current folder

  

touch .gitignore - creates a git ignore file

  

git status - check working tree - both on the git and on local 

  
  
  

Add files:

  

git add -A - adds all of the files for commiting

  

remember - git status - to check the state of the repo 

  

  

Remove files: 

  

git reset - removes files to be committed 

  

git reset somefile.js - removes somefile.js from the commit preparation

  

  

Committing:

  

git commit -m "This is the commit message" - -m is used to add message

  

  

Check log:

  

git log - renders commit ids, authors, dates

  

  

Clone a remote repo:

  

git clone <url> <where to clone>

  
  
  

View info about the repo:

  

git remote -v - lists info about the repo

  

git branch -a - lists all of the branches

  
  
  

View changes:

  

git diff - shows the difference made in the files

  

  

Pull before push ALWAYS:

  

git pull origin master

  

  

THEN PUSH:

  

git push origin master - <origin> name of remote repo <master> the branch that we push to 

  

  

First time push of the branch:

  

git push -u origin <name of the branch> - -u coordinates the two branches (local and on server)

  

  

Create a branch:

  

git branch <name of the branch>

  
  
  

Checkout a branch: in other words change to a branch

  

git checkout <name of the branch>

  
  
  

Merge a branch:

  

git checkout master

  

git pull origin master

  

git branch --merged - see which branches are merged 

  

git merge <name of the branch you want to merge>

  

git push origin master 

  
  
  

Delete a branch:

  

git branch -d <name of the branch> - this deletes it locally!!!

  

git branch -a - check the repo branches 

  

git push origin --delete <name of the branch> - this deletes it from the repo!

  
**