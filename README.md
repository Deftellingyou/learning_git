# learning_git
This repo is for learning tutorials about git from Amigos code. 
Key takeaways: 
To start , open your git bash/ terminal 
configure your git with your email address and username using : 
git config --global user.email "example@example.com"
git config --global user.name "yourusername"

- once that's set up, create a local repo/folder which you'd store your project in. you can do this via the CLI using: mkdir folder-name
- initialise the relevant folder to become a git folder in order to use git commands by : git init . 
- create files in folder using : touch filename
- add files to stage using : git add filename or use "." for all files in the folder and sub-folders
- save files by using : git commit filename or use "." for all files in the folder and sub-folders of use "-A" if your in a child folder and want to include files in parent folder
- connect to a remote server e.g github by ssh and push all your changes to the server using : git push . 
for initial push use : git push -u main

