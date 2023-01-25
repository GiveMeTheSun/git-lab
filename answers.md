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
