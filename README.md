lkjhoiuy.github.com
===================

1/ Removing all history

- Remove every file from Git's index:
$ git rm --cached -r .

- Rewrite the Git index to pick up all the new line endings:
$ git reset --hard

- Add all your changed files back, and prepare them for a commit:
$ git add .

- Commit: (or core.autocrlf ? No)
$ git config core.autocrlf false (true by default)

2/ Creating a new branch as an orphan

- Create a new branch with no parents (<branchname> = gh-pages):
git checkout --orphan <branchname>

- Clear the working directory with:
git rm --cached -r .