
| COMMANDS | DETAILS |
| -------------- | ---------- |
| `~/` | navigate you to your home directory |
| `ls` | list out everything (Helps to find out where you R)|
| `ls -la` | lists out everything in detail |

`mkdir`			creates new folders
`cd`			navigate into <name of the directory>
`touch`			creates a new file
`rm -rf`	<name> 	it deletes anything hahaha
`git status`  check the status of git
`git add`     add item for git to start tracking or monitoring for changes (pass in the name of the files that you want to add) `git add <name of file>` or `git add *`
`git commit -m "add all files"` most important line because this is when git is actually adding the files or changes you have made.

`git add .` removes files from git

`git push -u origin master` this pushes the changes to designated branch. in this case "master" is the branch that is designated.

`git push` this command will run whatever was run before. if you have pushed to "-u origin master" then this command will push code to that place. otherwise it might ask you to tell it where to push the code to.

`git pull` this command will pull code or get code that exists on the origin which is essentially the browser (GitHub). make sure you have told git which branch to get the code from. see the notes below;

`git branch` use this command to find out what branch you are looking at. it will print out the name of the branch you are looking at. it will have a * on it.

`git checkout <name of branch>` use this command to check out branch.

status > add > commit > push 
