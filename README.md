Q1- What does clone set the variable origin to represent?The clone command automatically sets the origin to represent the remote repositiory from which the directory was cloned (in this case gitHub).

Q2- What does the command git push --set-upstream origin master do?This command sets the url (of the remote repositiory) to which you want to make commits. What does remote tracking mean in this context? In this context, you are setting up the ability to commit to the remote repositiory (the beginning of remote tracking)# GitMergeRemoteAssign
This is an edit (I am person A)

Q3- Explain and illustrate what's happening in the commit tree when this command executes.
When this command is executed, the branch on which the command was made (max's branch) is merges the content of the master branch into max's branch without merging max's edits to the master. 
Q4- Are your commits overwritten by the remote master? No, ("a pull is a fetch and a merge")

Q5- Is this a merge or a rebase? This is an example of a merge. 

Q6- Person B: Checkout the local master branch- is it updated as well or still behind remote master?

