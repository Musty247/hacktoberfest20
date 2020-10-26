# hacktoberfest20
hacktoberfest2020

This project aims to simplify and guide the way to first contribution. If you are looking to make your first contribution, follow the steps below.\

If you don't have git on your machine install it or use command prompt.

## Fork the repository
Create a Fork
Simply click on the “fork” button  at the top of the repository page on GitHub.

## Clone your Fork
Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon or copy the link.


Open a terminal and run the following git command:
git clone "url you just copied"

For example:
git clone https://github.com/username/hacktoberfest20.git

## Create a branch
Change to the repository directory on your computer (if you are not already there):

cd hacktoberfest20

Now create a branch using the "git checkout" command:

git checkout -b your-new-branch-name

For example:
git checkout -b your-name

## Modify the Code
Now open Contributors.md file , add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

If you go to the project directory and execute the command 
"git status", you'll see there are changes.

Add those changes to the branch you just created using the "git add "command:

git add Contributors.md
In your local clone, modify the code and commit them to your local clone using the git commit command.

## Push your Changes
In your workspace, use the "git push" command to upload your changes to your remote fork on GitHub.

For Example
git push -u origin "your-branch-name"

## Create a Pull Request
On the GitHub page of your remote fork, click the “Compare & pull request” button. 


Now submit the pull request.


Soon I'll be merging all your changes into the master branch of this project.

Congratulations on your first pull request!
