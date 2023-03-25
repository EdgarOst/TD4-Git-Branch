Git interactive rebase
Many times, when working with Git, you may want to revise your local commit history. One of the great things about Git is that it allows you to make decisions at the last possible moment. You can decide what files go into which commits right before you commit with the staging area, you can decide that you didn’t mean to be working on something yet with git stash, and you can rewrite commits that already happened so they look like they happened in a different way.
Second paragraph  
 To modify a commit that is farther back in your history, you must move to more complex tools. Git doesn’t have a modify-history tool, but you can use the rebase tool to rebase a series of commits onto the HEAD that they were originally based on instead of moving them to another one. With the interactive rebase tool, you can then stop after each commit you want to modify and change the message, add files, or do whatever you wish. 
You must indicate how far back you want to rewrite commits by telling the command which commit to rebase onto.


Changing Multiple Commit Messages

Changing Multiple Commit Messages
To modify a commit that is farther back in your history, you must move to more complex tools.
With the interactive rebase tool, you can then stop after each commit you want to modify and change the message, add files, or do whatever you wish.
You can run rebase interactively by adding the -i option to git rebase.
You must indicate how far back you want to rewrite commits by telling the command which commit to rebase onto.
Changing Multiple Commit Messages
Created by Edgar
