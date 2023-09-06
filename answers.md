//Answer 1: 2.17.1


//Answer 2: user.name=GiveMeTheSun
            user.email=pascual.mmmmmm@gmail.com


//Answer 3: This command updates the index using the current content
       found in the working tree, to prepare the content staged
       for the next commit. It typically adds the current content
       of existing paths as a whole, but with some options it can
       also be used to add content with only part of the changes
       made to the working tree files applied, or remove paths
       that do not exist in the working tree anymore.

       The "index" holds a snapshot of the content of the working
       tree, and it is this snapshot that is taken as the
       contents of the next commit. Thus after making any changes
       to the working tree, and before running the commit
       command, you must use the add command to add any new or
       modified files to the index.

       This command can be performed multiple times before a
       commit. It only adds the content of the specified file(s)
       at the time the add command is run; if you want subsequent
       changes included in the next commit, then you must run git
       add again to add the new content to the index.

       The git status command can be used to obtain a summary of


 //answer 4:On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        README.md
        answers.md

nothing added to commit but untracked files present (use "git add"to track)


//answer 5: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        answers.md


//answer 6: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md
        new file:   answers.md


//answer 7: On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")


//answer 8: commit f47b13700c9363252e27bedc4c32ea1e1788dd26 (HEAD -> master)
Author: GiveMeTheSun <pascual.mmmmmm@gmail.com>
Date:   Wed Jan 25 18:50:48 2023 -0500

    Initial commit


//answer 9:On branch main
    Your branch is up to date with 'origin/main'.

    Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   answers.md

    no changes added to commit (use "git add" and/or "git commit -a")

    //answer 10: No


    //answer 11: To https://github.com/GiveMeTheSun/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/GiveMeTheSun/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

//answer 12: Yesssssss

//answer 13: .  ..  .git  .gitignore  README.md

//answer 14:
