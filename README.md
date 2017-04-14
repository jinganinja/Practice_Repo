#Practice_Repo
Oh hey there! This here is a practice repo with some code!

I will be writing the code in python, so you can play with the code as well as 
the repository. 

##How to clone the Repo
1. Click the clone or download button on the top right of this page 
2. Click the copy to clipboard icon
3. Move into your terminal
4. Navigate to the folder you would like to be in
5. Use the following command

    git clone <paste from your clipboard> 
    
Now all the files from the repository are in the folder you were in when you
completed the command above. 

##What to try Next
There are tons of things you can try next, so feel free to fiddle with it as 
much as you would like! The following are a few things just to get you started 
trying things out.

1. Open the Start.To.Python.py file. 
2. Read through the code/comments and try to make sense of it.
3. Write down somewhere what you think it is doing. 
4. Jump to the Start to Python section of this readme and see if you were right!
5. Move into your terminal. 
6. Move to the folder that this practice repo is in using the `cd` command
7. Use the git commands to create a new branch of whatever name you think is 
appropriate. 
8. Create a new virtual environment with the commands in the git doc. 

Note: A virtual environment name usually is the name of the repository you are 
using or some variant. 
9. Modify the turns to be 5. 
10. Go into your terminal and run `python Start.To.Python.py`
11. Test it, see if you broke it and if so, fix it.
12. Once you are happy with that, move to the 'Once you are Happy with that Code'
section.
13. Modify the board to be 10x10.
14. Test it, see if you broke it and if so, fix it.
15. Once you are happy with that, move to the 'Once you are Happy with that Code'
section.
16. Fiddle with it until you are satisfied that you understand it.
17. Test it out! Try to make it break, see if you can.
18. Once you are happy with that, move to the 'Once you are Happy with that Code'
section.

###Once you are Happy with that Code
Once you are happy with the code changes you have made move into your console. 
Once you are there navigate to the folder that your repo is in. Then use the 
`git status` command. Any file names in red are unstaged changes. Any file names
in green are staged changes. To stage a change you use the `git add <file name>`
command. Try it! Stage the changes to the file you changed. 

Once they are staged you can try the `git status` command again. If you completed
the staging properly, the filename will be green. To unstage the changes, use 
`git reset HEAD <filename>`. Try it! Unstage the changes you made. 

As you may remember a commit, the next step, should only have one change.
So what do you do if you have multiple changes in a file and you haven't committed?
I am so glad you asked!

    git add -p <filename>

This command will parse the changes into clumps. You can further break down the
clumps by typing `s` and hitting enter. You guessed it! Try it out. 

Once you have tried it enough times for you to get it, try the next step: Make a
commit! 

    git commit -m 'a commit message describing your changes'
This commits your changes and is more challenging to undo that an add is. So,
always make sure you want to commit what you are committing prior to completing
it. Once you are confident you want to commit your changes, do it!

Now onto pushing to the remote version of the repository: git hub. 

    git push origin <branchname> 
This will push all your current *commits* to git hub NOT your staged changes.

Now go to github in your browser and create a pull request. When you open the
repository there will be a green button that says something about creating a pull
request. Click it, fill in the information needed and such. Now you have a pull 
request! Congrats! 