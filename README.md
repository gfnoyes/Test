1.	Q: How do you see the files changed within each commit from git log? 
A: Each commit has what is called an 'identifier', which consists of 40 hexadecimal characters. The commits are listed in order starting with the most recent commit. The information also includes an Author, which shows the name and email address of the 'committer' and the Date, which shows the date and time of the commit message
The git log also provides a summary, which is a short run view of the history, called 'git log --oneline' The git log --stat will show the files in each commit and also the additions and subtractions

2.	Q: How do you see the contents of what changed within each file from the git log?
A: git log --patch, the items are color coded: the added items are in green and the subtracted items are in red

3.	Q: What does HEAD refer to in the context of git? 
A: The HEAD compares the working tree to the HEAD commit and it refers to the head that is currently active. It is also case sensitive ('head' in lowercase will refer to any named heads in the repository, as opposed to one that is currently active)
