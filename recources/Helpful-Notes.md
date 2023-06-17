# Helpful Notes
&emsp;**VCS** (version control systems) — helps to track the history of source code changes and to work comfortably in a team.\
**A repository** is a common name for a source code repository. The code in the repository is stored as commit histories—small changes to the source code.
Conventional file stores cannot show parallel change histories of the same file, but VCS can.\
&emsp;The **Git CLI** is a console interface to Git that runs in a terminal.

## Git

&emsp;**Bash** is an abbreviation for Bourne Again Shell, which we enable in the required project folder.

|        terminal       |        performance        |  |        terminal       |        performance        |
|-----------------------|---------------------------|--|-----------------------|---------------------------|
|       ``cd``          |  tilde (parent directory) |  | | |
|       ``pwd``         | present working directory |  | | |
|``mkdir <folder name>``|          new folder       |  | | |
|       ``ctrl+l``      |      clears the screen    |  | | |
|  ``cd <teka name>``   |       go to the folder    |  | | |
|         ``ls``        |      see its contents     |  | | |
|  <kbd>Ctrl + a</kbd>  | to beginning of the line  |  | | |
|  <kbd>Ctrl + e</kbd>  |         at its end        |  | | |
|  <kbd>Ctrl + C</kbd>  |   stop process as SIGINT  |  | | |

> Remember that every file in your working directory can be in one of two states: tracked or untracked.\
> Filling out the **.gitignore** file for a new repository before you start working is a great idea because it helps you avoid accidentally adding files that you don't want to include in your Git repository.

* ``git clone https://github.com/SKindij/<url.git>`` - _getting a copy of the existing Git repository on the working PC;_
  + ``git add <file name.vv>`` - _git starts tracking the file, and we make changes to the file;_
  + ``git add <file name.vv>`` - _we once again make a "snapshot" of the already working version of the file;_
    - ``git add .`` - _to add all existing files under version control;_
  + ``git commit -m "<comment about changes made>";``
    - ``git commit -a -m "<comments>"`` - _it automatically adds every tracked file, bypassing git add;_
  + ``git push `` - _to send changes to the remote repository;_
  + ``git status`` - _it shows the status of file synchronization;_
* ``cd /d D:\IT-KiSe\GIT-SKj-projects/my-project >> git init`` - _initialization of the project in the existing directory;_
  + ``git log`` - _to view history of commits;_
    - ``q`` = stop;
  + ``git log --stat`` - _shortened statistics;_    
    - ``--since='7 days ago';``
    - ``--patch`` - _difference (patch) introduced at each commit;_
  + ``git log --pretty=oneline`` - _prints each commit on a single line;_
    - ``--pretty=format:"%h - %an, %ar : %s" ``\
      > author ``%an`` refers to the person who originally did the work;\
      > committer ``%cn`` refers to the person who last applied the work;
* ``git commit --amend`` - _if you want to redo last commit, make additional changes to it (that you forgot about) and index them;_
  + ``git reset <file name.vv>`` - _it makes the file not indexed;_
* ``git remote -v `` - _it shows you the repo links that Git stores and uses;_
  + ``git remote add origin <link>`` - _
  + ``git remote rename <remote1> <remote2>``
  + ``git remote remove <remote1>`` - _removing the repository;_
* ``git fetch <link>`` - _it goes to remote project and retrieves all data that you don't have yet, which you can merge or review at any time;_
* ``git pull`` - _fetches data from the server and tries to merge it with the code you are currently working on;_

Git supports two types of tags: lightweight tags (_pointers to specific commit_) and annotated tags (_with description of tagged version_).

&emsp;**Lightweight tags:** These are simple pointers to specific commits. They are created using the command ``git tag <tag_name>``. Lightweight tags are created without any additional information or metadata, such as a description or tagger's name. They are commonly used for marking specific points in history but do not carry any extra information.

&emsp;**Annotated tags:** These tags include extra information, such as a tag message, tagger's name, email, and the date the tag was created. Annotated tags are created using the command ``git tag -a <tag_name> -m "tag message"``. The ``-a`` flag stands for "annotated," and the ``-m`` flag allows you to provide a message for the tag. Annotated tags are typically used for releases or important milestones, as they provide more context and information about the tagged version.

Both types of tags can be useful depending on the purpose and requirements of your project.













