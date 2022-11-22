# my-first-repository
Practice account for learning Git

Local vs Remote 

mkdir my-repo-name
cd my-repo-name
git init
git remote # gives blank as it is just local repo

cd .. 

goto already created repo (or get repo url from alrady created repo from git)
cd my-first-repo

git remote -v #gives the remote url it's linked to
origin  https://github.com/codemdshahbazali/my-first-repository.git (fetch)
origin  https://github.com/codemdshahbazali/my-first-repository.git (push)

now copy this remote url and move to the first repo

cd ..
cd my-repo-name
git remote add origin https://github.com/codemdshahbazali/my-first-repository.git
git pull # to pull all the changes from remote server

What I'm going to do next is use the Git pull command which will connect with the GIT hub server, and pull down all the changes from the repository. So on my local I now have all the changes, but when I check the directory it's blank. The reason for this is that I haven't set up a branch that matches with what I have on the server repository. Fortunately I can change that by performing the command. Git check out main. Which will set up a branch main on my local that tracks the branch main from the remote. And now when I check my folder using the LS command, it confirms that I have the read me test and test two files available on my local.

ls # returns blank The reason for this is that I haven't set up a branch that matches with what I have on the server repository
git checkout main # Git check out main. Which will set up a branch main on my local that tracks the branch main from the remote

ls #will give all the files
