# Chapter 5 notes and practice
## Git version control 
- Can rollback code to a time when things worked if something stops working
- Good for reproducibility
- Tracks changes and makes it easy for others to access those changes
- Makes things available to others after people move on from projects

## Basic Git
- Telling git who you are: I've already done this. Is it possible to add a different email? I have used my personal email in the past rather than the ISU email
- My color ui is already set to true
- I made a respository on github (it was empty) and cloned it to hpc-class

### 'git status' shows you status of repository 
- I have an untracked file right now

### 'git add' adds that file if you specify the file name

I have a test file to be committed now (it's staged)

### The snapshot: git commit 
'git commit' -m "initial test import"' is how i committed this 
- git commit takes a snapshot, essentially

### 'git diff' shows you shows you differences in working directory vs what's been staged

### 'git log' shows your chain of commits
- This can get pretty long (as it did with Wade's work)
- In that case you may need to ctl-c out of it

### A couple other commands
1. 'git rm <filename>' removes files
2. 'git mv ' moves them and can be used to change extension

### '.gitignore' file tells you what to ignore
- I made a file "ignoreme.txt" in a "junk" folder and told git to ignore it
- Useful for ignoring big files, intermediate files, and temp files

### 'git reset' lets you undo things you've staged (removes them from staging)
- ex I added a line "messy addition" to my readme and then removed it

## At this point I pushed these to my [practice repository](https://github.com/ekmcmurchie/EEOB_546_McMurchie) (click link to view) and then switched on over to doing this exercise
