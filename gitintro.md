Version control control is a tool that helps you track different versions of your files.
You can see all the modifications and who made the modifications.

Centralized version control helps many people work on one files and make changes from different places whilst the admin sees it.


To prevent this type of catastrophic loss, a Distributed Version Control allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.


Git is a DVCS that stores data in a filesystem made from snapshots. Snapshots are basically data that shows each version and the comments that came along with it.

Git uses depends on local files/folders to do the operations in a expediated timeframe.

Tracking changes. Git always tracks any changes in files and therefore is able to find any changes or loss of data.

Committed = data stored in local database
modified = has been modified but waiting for the next snapshot
staged = flagged a file's version to be committed in the next  snapshot



### You can download git on windows, macos and linux

### Git can be used in a GUI version.

After installing git, you should set the email + pass.

git config --global user.name "Jane Smith"

git config --global user.email "example@email.com"

### Git comes with the defaul text edictor visual studio code, however you can change the editor in the git:

$ git config --global core.editor emacs

### Checking the settings:

### To check settings, use the git config --list command.

To get help:

git help command
 
command is what you need to do ie clone.

###  To make the changes, we use the command:

git add .        OR   you can use git add filename



###  To get a clone from github for a repo:
git clone https://github.com/test



### Local get has three structured:

### Working Directory: The actual files reside here.
Index: The area used for staging
Head: Points to the most recent commit

### git status:

this shows the state of the files.
for example if it's modified, committed or else.

git clones automatically are given the name origin, therefore we use git push origin main, where origin is the default name given by git.

git remote add shortname url
this command will change the name.

you can rename by using 
$ git remote rename filename-BEFORE filename-AFTER


$ git remote rm filename
to remove


$ git commit --amend
to undo action

to undo a commit:
$ git revert HEAD



$ git checkout test
checkout command is used as switching branches

