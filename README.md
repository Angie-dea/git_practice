# git_practiceslaveski@DESKTOP-1I5U2JC MINGW64 ~
$ mkdir git_practice
mkdir: cannot create directory ‘git_practice’: File exists

slaveski@DESKTOP-1I5U2JC MINGW64 ~
$ cd git_practice

slaveski@DESKTOP-1I5U2JC MINGW64 ~/git_practice (master)
$ git init
Reinitialized existing Git repository in C:/Users/slaveski/git_practice/.git/

slaveski@DESKTOP-1I5U2JC MINGW64 ~/git_practice (master)
$ echo "Hello Git and GitHub" >> README.txt

slaveski@DESKTOP-1I5U2JC MINGW64 ~/git_practice (master)
$ git add README.txt
warning: LF will be replaced by CRLF in README.txt.
The file will have its original line endings in your working directory

slaveski@DESKTOP-1I5U2JC MINGW64 ~/git_practice (master)
$ git commit -m "First commit"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'slaveski@DESKTOP-1I5U2JC.(none)')

slaveski@DESKTOP-1I5U2JC MINGW64 ~/git_practice (master)
$ git config user.email "a.slaveski@hotmail.com"

slaveski@DESKTOP-1I5U2JC MINGW64 ~/git_practice (master)
$ git config user.name "Angie-dea"

slaveski@DESKTOP-1I5U2JC MINGW64 ~/git_practice (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.txt

