ANS:1 git version 2.26.2.windows.1
ANS:2 user.name=Ali Abbas
user.email=fa295519@ohio.edu
ANS:3 hese are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout

examine the history and state (see also: git help revisions)
   bisect            Use binary search to find the commit that introduced a bug
   diff              Show changes between commits, commit and working tree, etc
   grep              Print lines matching a pattern
   log               Show commit logs
   show              Show various types of objects
   status            Show the working tree status

grow, mark and tweak your common history
   branch            List, create, or delete branches
   commit            Record changes to the repository
   merge             Join two or more development histories together
   rebase            Reapply commits on top of another base tip
   reset             Reset current HEAD to the specified state
   switch            Switch branches
   tag               Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch             Download objects and refs from another repository
   pull              Fetch from and integrate with another repository or a local branch
   push              Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
ANS:4 No commits yet

nothing to commit
ANS:5 
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
  ANS:6 
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md
        ANS:7  2 files changed, 2 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md
 ANS:8 commit 97377ed32972357faf4c44f3d95da175d6c43ffc (HEAD -> master)                                                        Author: Ali Abbas <fa295519@ohio.edu>                                                                                   Date:   Sat May 16 03:05:40 2020 -0400 
 ANS:9 Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 275 bytes | 275.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/aliabbas95/git-lab.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
PS C:\Users\aliab\onedrive\Desktop\cs2400\git-lab>   
ANS:10 NO CHANGES
ANS:11 rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/aliabbas95/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
ANS:12  YES I GOT THE CHANGES . CS 2400, Section 107
HELLO GIT now shows in my local directory , and this change i have made online.
ANS:13Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----        5/16/2020   3:41 AM                git-lab-2
-a----        5/16/2020   3:29 AM           4055 answers.md
-a----        5/16/2020   3:26 AM             83 README.md
