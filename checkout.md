\# Git Checkout (Old vs New)



\## Old command: git checkout

`git checkout` was used for:

\- switching branches

\- creating a new branch

\- restoring files



\### Examples

git checkout main

git checkout -b feature-branch

git checkout -- file.txt



\## New commands



\### git switch

Used only for switching branches.



Examples:

git switch main

git switch -c feature-branch



\### git restore

Used for restoring files.



Example:

git restore file.txt



\## Why Git changed this

Git split `checkout` into `switch` and `restore` to make commands clearer and easier to use.

