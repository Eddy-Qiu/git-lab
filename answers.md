#Answer1
git version 2.17.1

#Answer2
user.name=Eddy Qiu
user.email=eq296919@ohio.edu

#Answer3 
When you enter git --help, the terminal brings up a list of common Git command.

#Answer4
The terminal outputs two untracked files, namely README.md and answers.md.

#Answer5
The terminal outputs a file that needs to be committed, namely README.md, and one untracked file, namely answers.md
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md


#Answer6
The terminal outputs two files in green color indicating that they need to be committed.
[master (root-commit) 949d53d] Initial commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 answers.md
eqiu@odd37:~/2400/git-lab$ git status
On branch master
nothing to commit, working tree clean


#Answer7
[master (root-commit) 949d53d] Initial commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 answers.md
eqiu@odd37:~/2400/git-lab$ git status
On branch master
nothing to commit, working tree clean


#Answer8
commit 949d53d50865a61356452ab4129b012b346b1458 (HEAD -> master)
Author: Eddy Qiu <eq296919@ohio.edu>
Date:   Fri Sep 6 16:37:02 2019 -0400

#Answer9
On branch master
Your branch is up to date with 'origin/master'.

#Answer10
No.
#Answer11
To https://github.com/Eddy-Qiu/git-lab.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/Eddy-Qiu/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

#Answer12
<<<<<<< HEAD
Full name: Eddy Qiu
GitHub user name: Eddy-Qiu
Email: eq296919@ohio.edu
Answers are recoded in answers.md
=======
Ohio University CS 2400, Section 107.
>>>>>>> 345879677f308466427d1316cc19ad8e7250eafb

#Answer13
.  ..  git-lab	git-lab-2  Labs
