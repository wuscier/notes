# see hidden files like .git in windows command line
cmd
attrib -h .git

# create a .txt file 
cmd
notepad todo.txt

# git reset --hard
to give up untracked changes[will remove newly added files!!!] and go back to last commit status

# git commit -am "add comments"    [one line commit]
-a/--all  to automatically stage files that have been modified and deleted, but new files you have not told Git about are not affected
-m <msg>  use the given <msg> as the commit message.
  
  # git diff e690 a8w3
  compare two commits
  
  # summary
  ![git add commit](https://github.com/wuscier/notes/blob/master/imgs/add_commit.png)

