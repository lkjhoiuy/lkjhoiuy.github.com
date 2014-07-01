lkjhoiuy.github.com
===================

Remove every file from Git's index.

`$ git rm --cached -r .`

Rewrite the Git index to pick up all the new line endings.

`$ git reset --hard`

Add all your changed files back, and prepare them for a commit.

`$ git add .`

Commit.

`$ git config core.autocrlf false` (true par défaut)