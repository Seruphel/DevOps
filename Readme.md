#First Git Projet

Ici on met des infos : 


C:\Users\Aelion\Desktop\GitMe>git init
Initialized empty Git repository in C:/Users/Aelion/Desktop/GitMe/.git/

C:\Users\Aelion\Desktop\GitMe>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Readme.md

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\Aelion\Desktop\GitMe>git branch -M Main

C:\Users\Aelion\Desktop\GitMe>git status
On branch Main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Readme.md

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\Aelion\Desktop\GitMe>git add .\Readme.md

C:\Users\Aelion\Desktop\GitMe>git status
On branch Main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Readme.md


C:\Users\Aelion\Desktop\GitMe>git commit -m "First Commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Aelion@Aelion-LDLC-5.(none)')

C:\Users\Aelion\Desktop\GitMe>git config --global user.email "Slava-alviss@outlook.fr"

C:\Users\Aelion\Desktop\GitMe>git config --global user.name "Alviss"

C:\Users\Aelion\Desktop\GitMe>git commit -m "First Commit"
[Main (root-commit) e64bc9b] First Commit
 1 file changed, 2 insertions(+)
 create mode 100644 Readme.md

C:\Users\Aelion\Desktop\GitMe>git status
On branch Main
nothing to commit, working tree clean

C:\Users\Aelion\Desktop\GitMe>git log
commit e64bc9bbb9109fbd77ee84b31e6fb4ec3c9b5acf (HEAD -> Main)
Author: Alviss <Slava-alviss@outlook.fr>
Date:   Wed Apr 26 11:11:32 2023 +0100

    First Commit

C:\Users\Aelion\Desktop\GitMe>